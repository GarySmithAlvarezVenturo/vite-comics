<script></script>

<template>
  <header>
    <nav>
      <img src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="" />
      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </nav>
  </header>
  <div class="jumbotron"></div>
</template>

<!-- STYLE HEADER -->

<style lang="scss" scoped>
@use "./../assets/styles/partials/variables.scss" as *;

header {
  background-color: rgb(255, 255, 255);

  nav {
    display: flex;
    justify-content: space-between;
    margin: auto;
    height: 120px;
    max-width: 1200px;

    .logo {
      margin-top: 1rem;
      height: 80px;
    }

    ul {
      list-style: none;
      align-items: center;
      gap: 1rem;
      display: flex;
      color: rgb(0, 0, 0);

      li {
        font-size: 0.7rem;
        font-weight: bold;
        padding-inline: 0.5rem;
      }
    }
  }
}

.jumbotron {
  background-image: url(../assets/vue-dc-comics-1/img/jumbotron.jpg);
  height: 25rem;
}
</style>
