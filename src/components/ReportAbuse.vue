<template>
  <secton id="report-abuse">
    <h2 class="font-weight-bold text-center">Report Abuse</h2>
    <mdb-row>
      <mdb-col class="col-lg-12 col-md-12">
        <form action>
          <div class="orange-text">
            <mdb-input label="Name (Optional)" icon="user" type="text" />
            <mdb-input label="Email (Optional)" icon="envelope" type="email" />
            <mdb-input label="Phone Number (Optional)" icon="phone" type="number" />
            <mdb-input label="Location (optional)" icon="location-arrow" type="text" />
            <mdb-input
              icon="pencil-alt"
              wrapperClass="active-pink-textarea"
              type="textarea"
              label="Description"
              rows="4"
            />
            <mdb-input type="file" />
          </div>
          <div class="text-center">
            <mdb-btn color="primary">
              Send
              <mdb-icon far icon="paper-plane" class="ml-1" />
            </mdb-btn>
          </div>
        </form>
      </mdb-col>
    </mdb-row>
  </secton>
</template>
<script>
import { mdbRow, mdbCol, mdbBtn, mdbInput, mdbIcon } from "mdbvue";

export default {
  name: "ReportAbuse",
  components: {
    mdbRow,
    mdbCol,
    mdbInput,
    mdbBtn,
    mdbIcon
  }
};
</script>