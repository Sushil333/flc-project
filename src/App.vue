<template>
  <div>
    <Navbar />
    <div class="container-fluid">
      <div class="mainOuter">
        <div class="row">
          <div class="col-md-5">
            <div class="row">
              <div class="col-lg-12">
                <div class="right_section ">
                  <h1>&nbsp;</h1>
                </div>
              </div>
            </div> 
            <div class="top_left_section">        
              <Hidd stakePower="xxx" assetStake="xxx" timeToReward="hh:mm:ss" claimableReward="xxx"/>
              <Waxx claimedBalance="xxxx" hddToWaxx="xxx" />
            </div>
            <div class="roylity_top">
              <h1>Royalty Cards</h1>
              <div class="row">
                <div class="col-sm-12 col-md-12 col-lg-4 image_box">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-12 col-md-12 col-lg-4 image_box">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-12 col-md-12 col-lg-4 image_box last_child">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-7">
            <div class="right_section">    
              <div class="row">
                <div class="col-lg-12">
                  <h1>My Assets</h1>
                </div>
              </div>      
              <div class="row g-xl-4 g-xxl-5 borderCol">
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in last_child">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in last_child">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
                <div class="col-sm-6 col-md-6 col-lg-3 right_section_in last_child">
                  <VCard qty="xxxx" hdd="xxx" />
                </div>
              </div>
            </div>
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
