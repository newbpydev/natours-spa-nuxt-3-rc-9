<template>
  <!-- * Footer -->
  <footer class="footer">
    <!-- @ logo box -->
    <div class="footer__logo-box">
      <img
        src="@/assets/img/logo-green-2x.png"
        alt="Full logo"
        class="footer__logo"
      />
    </div>

    <!-- @ row -->
    <div class="row">
      <!-- # Navigation -->
      <div class="col-1-of-2">
        <div class="footer__navigation">
          <ul class="footer__list">
            <li class="footer__item">
              <a href="#" class="footer__link">Company</a>
            </li>
            <li class="footer__item">
              <a href="#" class="footer__link">Contact us</a>
            </li>
            <li class="footer__item">
              <a href="#" class="footer__link">Careers</a>
            </li>
            <li class="footer__item">
              <a href="#" class="footer__link">Privacy Policy</a>
            </li>
            <li class="footer__item">
              <a href="#" class="footer__link">Terms</a>
            </li>
          </ul>
        </div>
      </div>

      <!-- # Copyright -->
      <div class="col-1-of-2">
        <p class="footer__copyright">
          Built by <a href="#" class="footer__link">Jonas Schmedtmann</a> for
          his online course
          <a href="#" class="footer__link">Advanced CSS and Sass</a>. Copyright
          &copy; by Jonas Schmedtmann. You are 100% allowed to use this webpage
          for both personal and commercial use, but NOT to claim it as your own
          design. A credit to the origianl author, Jonas Schmedtmann, is of
          course hightly appreciated!
        </p>
      </div>
    </div>
  </footer>
</template>

<script setup lang="ts"></script>

<style scoped></style>
