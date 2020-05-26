<template>
  <div id="app">
    <Hero />
    <main class="mt-5">
      <mdb-container>
        <AboutUs />
        <ReportAbuse />
        <hr class="my-5" />
        <Education />
        <hr class="my-5" />
        <Contacts />
      </mdb-container>
    </main>
    <FooterBar />
  </div>
</template>

<script>
import Hero from "./components/Hero";
import AboutUs from "./components/AboutUs";
import ReportAbuse from "./components/ReportAbuse";
import FooterBar from "./components/FooterBar";
import Education from "./components/Education";
import Contacts from "./components/Contacts";

import { mdbContainer } from "mdbvue";

export default {
  name: "App",
  components: {
    Hero,
    FooterBar,
    ReportAbuse,
    mdbContainer,
    Education,
    Contacts,
    AboutUs
  }
};
</script>

<style lang="scss">
$image-path: "~@/../mdb/mdbvue/img";
@import "~@/../mdb/mdbvue/scss/mdb-free.scss";

@import url("https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap");

html,
body,
header {
  height: 100%;
}
</style>
