<template>
  <section>
    <div class="container">
      <h1>Latest Articles</h1>
      <div class="cards">
        <div class="card">
          <img src="../assets/image-currency.jpg" alt="">
          <div class="text-container">
            <p class="author">By Claire Robinson</p>
            <h4>Receive money in any<br>
            currency with no fees</h4>
            <p class="description">The world is getting smaller and<br>
            we're becoming more mobile. So<br>
            why should you be forced to only<br>
            receive money in a single...</p>
          </div>
        </div>
        <div class="card">
          <img src="../assets/image-restaurant.jpg" alt="">
          <div class="text-container">
            <p class="author">By Wilson Hutton</p>
            <h4>Treat yourself without<br>
            worrying about money</h4>
            <p class="description">Our simple budgeting feature<br>
            allows you to separate out your<br>
            spending and set realistic limits<br>
            each month. That means you...</p>
          </div>
        </div>
        <div class="card">
          <img src="../assets/image-plane.jpg" alt="">
          <div class="text-container">
            <p class="author">By Wilson Hutton</p>
            <h4>Take your Easybank card<br>
            wherever you go</h4>
            <p class="description">We want you to enjoy your travels.<br>
            This is why we don't charge any<br>
            fees on purchases while you're<br>
            abroad. We'll even show you...</p>
          </div>
        </div>
        <div class="card">
          <img src="../assets/image-confetti.jpg" alt="">
          <div class="text-container">
            <p class="author">By Claire Robinson</p>
            <h4>Our invite-only Beta<br>
            accounts are now live!</h4>
            <p class="description">After a lot of hard work by the<br>
            whole team, we're excited to launch<br>
            our closed beta. It's easy to request<br>
            an invite through the site...</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Articles'
}
</script>

<style scoped>
section {
  overflow: auto;
  height: 40rem;
  background-color: hsl(0, 0%, 98%);
}

h1 {
  margin-top: 5rem;
  font-size: 2.1rem;
}

.card {
  margin-top: 3rem;
  display: block;
  width: 14rem;
}

.cards {
  display: flex;
  justify-content: space-between;
}

.text-container {
  margin: 0;
  padding: 10px;
  background-color: hsl(0, 0%, 100%);
}

.author {
  margin: 0;
  font-size: 12px;
}

.description {
  font-size: 12px;
}

.card > img {
  margin: 0;
  width: 100%;
  display: block;
}

@media only screen and (max-width: 560px) {
  section {
    height: auto;
    text-align: center;
  }
  .cards {
    flex-direction: column;
  }
  .card {
    margin: 0 auto;
    margin-bottom: 1rem;
  }
}

</style>