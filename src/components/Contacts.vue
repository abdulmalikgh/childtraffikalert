<template>
  <section id="contacts">
    <h2 class="h1-responsive font-weight-bold text-center mb-5 pt-5">Contact us</h2>
    <p
      class="text-center w-responsive mx-auto mb-5"
    >If you need further information or feedback you can conctact us or fill the form below</p>
    <div class="row">
      <div class="col-md-9 mb-md-0 mb-5">
        <form class="ml-5 mr-5 mb-3">
          <div class="row">
            <div class="col-md-6">
              <mdb-input label="Your Name" type="text" />
            </div>
            <div class="col-md-6">
              <mdb-input label="Your Email" type="email" />
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <mdb-input label="Subject" type="text" />
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <mdb-input
                wrapperClass="active-pink-textarea"
                type="textarea"
                label="Your message"
                rows="3"
              />
            </div>
          </div>
          <div class="text-center text-md-left">
            <mdb-btn color="primary" class="btn-md">Send</mdb-btn>
          </div>
        </form>
      </div>
      <div class="col-md-3 text-center">
        <ul class="list-unstyled mb-0">
          <li>
            <i class="fas fa-map-marker-alt fa-2x blue-text"></i>
            <p>Achimota, Mile 7, Ghana</p>
          </li>
          <li>
            <i class="fas fa-phone fa-2x mt-4 blue-text"></i>
            <p>+ 223 249809695</p>
          </li>
          <li>
            <i class="fas fa-envelope fa-2x mt-4 blue-text"></i>
            <p class="mb-4">contact@example.com</p>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>
<script>
import { mdbInput, mdbBtn } from "mdbvue";

export default {
  name: "ReportAbuse",
  components: {
    mdbInput,
    mdbBtn
  }
};
</script>
<style>
#contacts {
  background-color: #eee;
}
</style>