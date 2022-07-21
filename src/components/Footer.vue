<template>
  <section>
    <div class="container ht">
      <div class="content">
        <div class="social">
          <div class="logo">
            <img class="easybank" src="../assets/footer-logo.svg" alt="">
          </div>
          <div class="social-icons">
            <img src="../assets/icon-facebook.svg" alt="">
            <img src="../assets/icon-youtube.svg" alt="">
            <img src="../assets/icon-twitter.svg" alt="">
            <img src="../assets/icon-pinterest.svg" alt="">
            <img src="../assets/icon-instagram.svg" alt="">
          </div>
        </div>
        <div class="menu">
          <a href="">About Us</a>
          <a href="">Contact</a>
          <a href="">Blog</a>
          <a href="">Careers</a>
          <a href="">Support</a>
          <a href="">Privacy Policy</a>
        </div>
        <div class="button">
          <button class="btn">Request Invite</button>
          <p>&copy; Easybank. All Rights Reserved</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped>
section {
  overflow: auto;
  height: 10rem;
  background-color: hsl(233, 26%, 24%);
}

.ht {
  height: 100%;
}

.content {
  height: 100%;
  margin-top: 2.6rem;
  display: flex;
  align-content: space-between;
}

.button {
  margin-left: auto;
  text-align: right;
}

.social {
  height: 100%;
  align-items: space-between;
}

.social-icons {
  display: flex;
  justify-content: space-between;
  margin-top: 2rem;
}

.menu {
  display: flex;
  height: 5rem;
  margin-left: 6rem;
  flex-direction: column;
  flex-wrap: wrap;
  column-gap: 2rem;
  font-size: 12px;
}

a:not(:last-child) {
  margin-bottom: 8px;
}

a {
  color: hsl(0, 0%, 100%);
  text-decoration: none;
}

p {
  font-size: 12px;
  color: gray;
}


</style>