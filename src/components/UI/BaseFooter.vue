<template>
  <q-footer>
    <div class="row contact flex flex-center">
      <div class="shadow-5 card q-pa-xl rounded col-lg-8">
        <div class="row flex flex-center align-center">
          <div class="col-lg-4"><h2>Interesse of vragen?</h2></div>
          <div class="col-lg-4">
            <p>
              Geintresseerd in een samenwerking of een gesprek?<br />
              Neem gerust contact op.
            </p>
          </div>
          <div class="col-lg-4 contact-btn">
            <a class="btn btn-light" href="mailto:hichamsahla91@gmail.com">Neem contact op</a>
          </div>
        </div>
      </div>
    </div>
    <q-toolbar class="footer">
      <q-toolbar-title align="center">
        <a
          target="_blank"
          href="https://www.linkedin.com/in/hicham-sahla-5a5520154/"
        >
          <q-avatar size="54px" class="social-media">
            <img src="../../assets/linkedin.png" />
          </q-avatar>
        </a>
        <a target="_blank" href="https://github.com/hicham-sahla">
          <q-avatar size="54px" class="social-media">
            <img src="../../assets/github.png" />
          </q-avatar>
        </a>
        <a target="_blank" href="mailto:hichamsahla91@gmail.com">
          <q-avatar size="54px" class="social-media">
            <img src="../../assets/email.png" />
          </q-avatar>
        </a>
        <br />
        <small class="q-mt-sm"
          >Created by me © Hicham Sahla {{ new Date().getFullYear() }}</small
        >
      </q-toolbar-title>
    </q-toolbar>
  </q-footer>
</template>

<script>
export default {
  name: "BaseFooter",
};
</script>
