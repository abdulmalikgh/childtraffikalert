<template>
  <section id="education" class="text-center">
    <h2 class="mb-3 font-weight-bold text-center">Education</h2>
    <mdb-row class="row row d-flex justify-content-center mb-4">
      <mdb-col class="col-md-8">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi
          voluptate hic provident nulla repellat facere esse molestiae
          ipsa labore porro minima quam quaerat rem, natus repudiandae
          debitis est sit pariatur.
        </p>
      </mdb-col>
    </mdb-row>
    <mdb-row>
      <mdb-col class="col-md-6 mb-1">
        <i class="fas fa-camera-retro fa-4x orange-text"></i>
        <h4 class="my-4">Background</h4>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          Reprehenderit maiores nam, aperiam minima assumenda deleniti
          hic.
        </p>
      </mdb-col>
      <mdb-col class="col-md-6 mb-1">
        <i class="fas fa-camera-retro fa-4x orange-text"></i>
        <h4 class="my-4">Background</h4>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          Reprehenderit maiores nam, aperiam minima assumenda deleniti
          hic.
        </p>
      </mdb-col>
    </mdb-row>
  </section>
</template>
<script>
import { mdbCol, mdbRow } from "mdbvue";
export default {
  name: "Eduaction",
  components: {
    mdbRow,
    mdbCol
  }
};
</script>