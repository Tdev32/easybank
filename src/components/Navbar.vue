<template>
  <header>
    <div class="container flex">
      <div class="logo">
        <img src="../assets/logo.svg" alt="">
      </div>
      <nav class="flex">
        <a href="">Home</a>
        <a href="">About</a>
        <a href="">Contact</a>
        <a href="">Blog</a>
        <a href="">Careers</a>
      </nav>
      <button class="btn">Request Invite</button>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped>
header {
  background-color: white;
  font-family: 'Public Sans';
  height: 3.5rem;
  position: relative;
  z-index: 1000;
}

.logo > img {
  transform: translateY(10%);
}

.flex {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

nav {
  width: 20rem;
}

a {
  font-size: 0.9rem;
  color: gray;
  text-decoration: none;
}

</style>