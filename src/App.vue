<template>
  <div>
    <Navbar />

    <div class="col-md-5 top_space">
      <div class="top_left_section">
        
        <Hidd stakePower="xxx" assetStake="xxx" timeToReward="hh:mm:ss" claimableReward="xxx"/>
        <Waxx claimedBalance="xxxx" hddToWaxx="xxx" />
      </div>

      <div class="roylity_top">
        <h1>Royalty Cards</h1>

        <div class="roylity_top_in res-grid">
          <div class="image_box">
            <VCard qty="xxxx" hdd="xxx" />
          </div>

          <div class="image_box">
            <VCard qty="xxxx" hdd="xxx" />
          </div>

          <div class="image_box last_child">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
        </div>
      </div>
    </div>

    <div class="col-md-7 right_sec">
      <div class="right_section">
        <h1>My Assets</h1>

        <div class="right_section_in_full">
          <div class="right_section_in">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
          <div class="right_section_in">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
          <div class="right_section_in">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
          <div class="right_section_in last_child">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
        </div>

        <div class="right_section_in_full top_space_right">
          <div class="right_section_in">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
          <div class="right_section_in">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
          <div class="right_section_in">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
          <div class="right_section_in last_child">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
        </div>

        <div class="right_section_in_full top_space_right">
          <div class="right_section_in">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
          <div class="right_section_in">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
          <div class="right_section_in">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
          <div class="right_section_in last_child">
            <VCard qty="xxxx" hdd="xxx" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import VCard from "./components/VCard.vue";
import Hidd from "./components/Hidd.vue";
import Waxx from "./components/Waxx.vue";

export default {
  name: "App",
  components: {
    Navbar,
    VCard,
    Hidd,
    Waxx,
  },
};
</script>

<style></style>
