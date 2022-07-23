<template>
  <section>
    <div class="heading">
      <h1>Why Choose Easybank?</h1>
      <p>We leverage Open Banking to turn your bank into your financial hub.<br>
      Control your finances like never before.</p>
    </div>
    <div class="squares">
      <div class="container flex">
        <div class="square">
          <img src="../assets/icon-online.svg" alt="">
          <h3>Online Banking</h3>
          <p>Our modern web and mobile<br>
          applications allow you to keep<br>
          track of your finances wherever you<br>
          are in the world.</p>
        </div>
        <div class="square">
          <img src="../assets/icon-budgeting.svg" alt="">
          <h3>Simple Budgeting</h3>
          <p>See exactly where your money<br>
          goes each month. Receive<br>
          notifications when you're close to<br>
          hitting your limits.</p>
        </div>
        <div class="square">
          <img src="../assets/icon-onboarding.svg" alt="">
          <h3>Fast Onboarding</h3>
          <p>We don't do branches. Open you<br>
          account in minutes online and start<br>
          taking control of your finances<br>
          right away.</p>
        </div>
        <div class="square">
          <img src="../assets/icon-api.svg" alt="">
          <h3>Open API</h3>
          <p>Manage your savings, investments,<br>
          pension, and much more from one<br>
          account. Tracking your money has<br>
          never been easier.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'InfoSection'
}
</script>

<style scoped>
section {
  position: relative;
  overflow: auto;
  z-index: 8;
  height: 36rem;
  background-color: hsl(220, 16%, 96%);
}
h1 {
  font-size: 2.1rem;
  margin: 0;
}
.heading {
  margin-top: 80px;
  margin-left: 170px;
}
.squares {
  margin-top: 60px;
}
.flex {
  display: flex;
  justify-content: space-between;
}

@media only screen and (max-width: 560px) {
  section {
    height: auto;
    text-align: center;
  }
  h1 {
    width: 60%;
    margin: 0 auto;
  }
  .heading {
    margin-top: 2rem;
    margin-left: 0;
  }
  .heading > p {
    width: 80%;
    margin: 0 auto;
  }
  .flex {
    flex-direction: column;
  }
}

</style>