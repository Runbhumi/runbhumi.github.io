<template>
  <!-- Site footer -->
  <footer class="site-footer">
    <div class="container">
      <div class="row">
        <div class="col-sm-12 col-md-3">
          <h6
            style="color: #2DADC2; font-style: italic; font-weight: bold;font-size: 32px;"
          >
            Runbhumi
          </h6>
          <ul class="social-icons">
            <li>
              <a class="mail" href="#"
                ><img src="../assets/icons/feather_mail.svg"
              /></a>
            </li>
            <li>
              <a
                class="instagram"
                href="https://www.instagram.com/runbhumi_official/"
                ><img src="../assets/icons/feather_instagram.svg"
              /></a>
            </li>
            <li>
              <a class="linkedin" href="#"
                ><img src="../assets/icons/linkedin.svg"
              /></a>
            </li>
            <li>
              <a class="twitter" href="#"
                ><img src="../assets/icons/twitter.svg"
              /></a>
            </li>
          </ul>
        </div>

        <div class="col-xs-6 col-md-3">
          <h6>About</h6>
          <ul class="footer-links">
            <li><a href="#">Features</a></li>
            <li>
              <a href="#">Meet the team</a>
            </li>
          </ul>
        </div>

        <div class="col-xs-6 col-md-3">
          <h6>Legal</h6>
          <ul class="footer-links">
            <li>
              <router-link to="/privacy-policy">Privacy Policy</router-link>
            </li>
            <li>
              <router-link to="/terms-and-conditions"
                >Terms & Conditions</router-link
              >
            </li>
          </ul>
        </div>
        <div class="col-xs-6 col-md-3">
          <h6>Enter the waitlist</h6>
          <div class="column">
            <a href="https://play.google.com/store/apps"
              ><img src="../assets/download app.svg" alt="download" width="80%"
            /></a>
          </div>
        </div>
      </div>
    </div>
    <div class="container d-flex justify-content-center mt-3">
      <div>
        <p style="margin:0;">
          Made with 💙 in India
        </p>
        <p style="margin:0;">
          © 2020-2021 Runbhumi
        </p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style lang="scss" scoped>
.site-footer {
  background-color: #ffffff;
  padding: 45px 0 20px;
  font-size: 15px;
  line-height: 24px;
}
.site-footer hr {
  opacity: 0.5;
}
.site-footer hr.small {
  margin: 20px 0;
}
.site-footer h6 {
  color: #000000;
  font-size: 24px;
  font-weight: 600;
  margin-top: 5px;
}
.site-footer a {
  text-decoration: none;
}
.site-footer a:hover {
  color: #2dadc2;
  text-decoration: none;
}
.footer-links {
  padding-left: 0;
  list-style: none;
}
.footer-links li {
  display: block;
  font-size: 22px;
}
.footer-links a {
  color: #000000;
}
.footer-links a:active,
.footer-links a:focus,
.footer-links a:hover {
  color: #2dadc2;
  text-decoration: none;
}
.footer-links.inline li {
  display: inline-block;
}
.site-footer .social-icons a {
  width: 40px;
  height: 40px;
  line-height: 40px;
  margin-left: 6px;
  margin-right: 0;
}
@media (max-width: 991px) {
  .site-footer [class^="col-"] {
    margin-bottom: 30px;
  }
}
@media (max-width: 767px) {
  .site-footer {
    padding-bottom: 0;
  }
  .site-footer .copyright-text,
  .site-footer .social-icons {
    text-align: center;
  }
}
.social-icons {
  padding-left: 0;
  margin-bottom: 0;
  list-style: none;
}
.social-icons li {
  display: inline-block;
  margin-bottom: 4px;
}
.social-icons li.title {
  margin-right: 15px;
  text-transform: uppercase;
  font-weight: 700;
  font-size: 13px;
}
.social-icons a {
  font-size: 16px;
  display: inline-block;
  line-height: 44px;
  width: 44px;
  height: 44px;
  text-align: center;
  margin-right: 8px;
  border-radius: 100%;
}
.social-icons.size-sm a {
  line-height: 34px;
  height: 34px;
  width: 34px;
  font-size: 14px;
}
@media (max-width: 767px) {
  .social-icons li.title {
    display: block;
    margin-right: 0;
    font-weight: 600;
  }
}
</style>
