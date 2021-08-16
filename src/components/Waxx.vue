<template>
  <div class="left_section left_section_in">
    <div class="left_section_in first_left_section_in">
      <h1>Total Claimed Balance</h1>
      <span> : {{ claimedBalance }} HIDD</span>
    </div>

    <div class="left_section_in">
      <h1>Convert HIDD to Wax</h1>
      <span> : {{ hddToWaxx }} </span>
    </div>

    <a href="#" class="button_blue"> Claim WAX</a>
  </div>
</template>

<script>
export default {
    name: 'Waxx',
    props: {
        hddToWaxx: String,
        claimedBalance: String
    }
};
</script>

<style>
  
</style>
