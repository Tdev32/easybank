<template>
  <div class="showcase">
    <div class="info">
      <h1>Next generation<br>digital banking</h1>
      <p>Take your financial life online. Your Easybank account<br>
      will be a one-stop-shop for spending, saving,<br>
      budgeting, investing, and much more.</p>
      <button class="btn">Request Invite</button>
    </div>
    <div class="stuff">
      <img class="desktop-shapes" src="../assets/bg-intro-desktop.svg" alt="">
      <img class="mobile-shapes" src="../assets/bg-intro-mobile.svg" alt="">
      <img class="phones" src="../assets/image-mockups.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Showcase'
}
</script>

<style scoped>
.showcase {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  height: 75vh;
  background-color: hsl(0, 0%, 98%);
}
.container {
  width: 1100px;
  margin: 0 auto;
}

h1 {
  font-size: 2.2rem;
  font-weight: 500;
}

.mobile-shapes {
  display: none;
}

.desktop-shapes {
  position: absolute;
  width: 84%;
  top: -25%;
  right: -28%;
}

.phones {
  position: relative;
  width: 100%;
  z-index: 10;
  top: -13%;
  right: -14%;
}

.info {
  transform: translateY(16%);
  margin-left: 170px;
  text-align: left;
}

@media only screen and (max-width: 560px) {
  .showcase {
    grid-template-columns: 1fr;
    width: 100%;
    height: 42rem;
  }
  .desktop-shapes {
    display: none;
  }
  .mobile-shapes {
    position: absolute;
    display: block;
    width: 100%;
    top: -3%;
    right: 0%;
  }
  .phones {
    position: absolute;
    width: 90%;
    top: -13%;
    right: 5%;
  }
  .info {
    transform: translateY(80%);
    margin: 0;
    text-align: center;
  }
}
</style>