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
      <img class="shapes" src="../assets/bg-intro-desktop.svg" alt="">
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

.shapes {
  position: absolute;
  top: -35%;
  right: -35%;
}

.phones {
  position: relative;
  z-index: 10;
  top: -22%;
  right: -22%;
}

.info {
  transform: translateY(16%);
  margin-left: 170px;
  text-align: left;
}
</style>