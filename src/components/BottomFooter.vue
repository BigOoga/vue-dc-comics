<template>
  <div id="bottom-footer">
    <div class="d-flex justify-content-around align-items-center h-100">
      <div class="btn-signup text-uppercase">Sign up now!</div>
      <div class="links">
        <ul>
          <li><a class="fs-2" href="">Follow us</a></li>
          <li>
            <a href=""><img src="@/assets/img/footer-facebook.png" alt=""/></a>
          </li>
          <li>
            <a href=""><img src="@/assets/img/footer-twitter.png" alt=""/></a>
          </li>
          <li>
            <a href=""><img src="@/assets/img/footer-youtube.png" alt=""/></a>
          </li>
          <li>
            <a href=""><img src="@/assets/img/footer-pinterest.png" alt=""/></a>
          </li>
          <li>
            <a href=""><img src="@/assets/img/footer-periscope.png" alt=""/></a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BottomFooter",
};
</script>

<style lang="scss">
@import "@/assets/scss/_bottom-footer.scss";
</style>
