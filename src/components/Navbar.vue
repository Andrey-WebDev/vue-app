<template>
  <div class="navbar">
    <div class="navbar-logo" @click="$router.push('/')">Logo</div>
    <div class="navbar__btns">
      <my-button @click="$router.push('/posts')">Посты</my-button>
      <my-button style="margin-left: 20px" @click="$router.push('/about')">О сайте</my-button>
      <!-- <my-button style="margin-left: 20px" @click="$router.push('/store')">store</my-button> -->
      <!-- <my-button style="margin-left: 20px" @click="$router.push('/composition')">Composition</my-button> -->
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.navbar {
  height: 50px;
  background-color: lightgray;
  box-shadow: 2px 2px 4px gray;
  display: flex;
  align-items: center;
  padding: 0 15px;
}
.navbar__btns {
  margin-left: auto;
}
.navbar-logo {
  cursor: pointer;
  font-weight: 600;
  color: lightseagreen;
}
</style>
