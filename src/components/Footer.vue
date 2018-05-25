<template>
  <footer>
        <div class="wrap center">
    <div class="about-us">
            <div class="name"> Jello </div>
            <div class="license">Released under MIT License</div>
    </div>

    <div class="links">
        <a href="https://twitter.com/_getKre" target="_blank"> <ion-icon name="logo-twitter"></ion-icon></a>
        <a href="https://github.com/KreeCorp/Jello"  target="_blank"><ion-icon name="logo-github"></ion-icon></a>
    </div>


    <div class="copyright">
    Copyright   <span>  © </span>  {{ new Date().getFullYear() }}
    </div>
    </div>
  </footer>
</template>


<script>
export default {
  name: "Footer"
};
</script>
