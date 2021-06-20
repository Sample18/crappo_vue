<template>
  <div class="menu" @click="popUp">

    <div class="menu__button">+</div>
    <div class="menu__content">
      <div class="menu__title">
        <a class="vert-line" href="">Login</a>
        <a class="register" href="">Register</a>
      </div>

      <ul class="menu__content__list">
        <li>Products</li>
        <li>Features</li>
        <li>About</li>
        <li>Contact</li>
        <li class="close-menu">Close</li>
      </ul>
    </div>

  </div>
</template>

<script>
export default {
  name: "popUp",
  methods: {
    popUp () {
      let menu = document.querySelector(".menu");
      menu.classList.toggle('open');
    }
  },
}
</script>

<style scoped>
.menu {
  display: none;
  position: relative;
  margin-right: 2vw;
  width: 54px;
  height: 54px;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  white-space: nowrap;
  color: rgba(255, 255, 255, 1);
  overflow: hidden;
  background-color: rgba(54, 113, 233, 1);
  border-radius: 50%;
  box-shadow: 0 3px 10px -2px rgba(0, 0, 0, 0.25);
  transition: 0.2s;
}

.menu.open {
  border: 1px solid rgb(13, 13, 43);
  width: 210px;
  height: 100%;
  border-radius: 2px;
}

.menu.open .menu__button {
  display: none;
  color: #999;
  transform: rotate(45deg);
}

.menu.open .menu__content {
  opacity: 1;
  visibility: visible;
}

.menu__button {
  border: 0;
  position: absolute;
  left: 20%;
  font-size: 34px;
  padding: 7px;
  transition: 0.2s;
  user-select: none;
}

.menu__title {
  display: flex;
  min-height: 100%;
}

.menu__content {
  opacity: 0;
  visibility: hidden;
  transition: 0.2s;
}

.menu__content__list { list-style: none; }

.menu__content__list li {
  text-align: center;
  line-height: 54px;
  margin: 0;
  transition: 0.2s;
  transition-delay: 0.08s;
}

.menu__content__list li:hover {
  background-color: rgb(13, 13, 43);
}

@media (max-width: 530px) {
  .menu {
    display: inline-block;
  }
  .vert-line {
    min-height: 54px;
    text-align: center;
    line-height: 54px;
    padding: 0 0 0 40px;
  }
  .vert-line:hover {
    background-color: rgb(13, 13, 43);
  }
  .register {
    min-height: 54px;
    text-align: center;
    line-height: 54px;
    border-radius: 0;
    padding: 0 21px 0 20px;
  }
  .register:hover {
    background-color: rgb(13, 13, 43);
  }
}
</style>