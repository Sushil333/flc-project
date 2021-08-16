<template>
  <div>
    <Navbar />

    <div class="container_full">
      <div class="col-md-5 top_space">
        <div class="top_left_section">
          <Hidd
            stake-power="xxx"
            asset-stake="xxx"
            claimable-reward="xxx"
            time-to-reward="hh:mm:ss"
          />
          <Waxx claimed-balance="xxx" hdd-to-waxx="xxx" />
        </div>

        <div class="roylity_top">
          <h1>Royalty Cards</h1>

          <div class="roylity_top_in res-grid">
            <div class="image_box">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="image_box">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="image_box">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-7 right_sec">
        <div class="right_section">
          <h1>My Assets</h1>

          <div class="right_section_in_full">
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
            <div class="right_section_in">
              <VCard qty="xxxx" hdd="xxxx" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hidd from "./components/Hidd.vue";
import Waxx from "./components/Waxx.vue";
import VCard from "./components/VCard.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Hidd,
    Waxx,
    VCard,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}
</style>
