<template>
  <div class="left_section">
    <div class="left_section_in first_left_section_in">
      <h1>My Stake Power (per day)</h1>
      <span> : {{ stakePower }} HIDD</span>
    </div>

    <div class="left_section_in">
      <h1>My Asset Staked</h1>
      <span> : {{ assetStake }} </span>
    </div>

    <div class="left_section_in ">
      <h1>Time To Reward</h1>
      <span>: {{ timeToReward }}</span>
    </div>

    <div class="left_section_in">
      <h1>Claimable Reward</h1>
      <span> : {{ claimableReward}} </span>
    </div>
    <a href="#" class="button_blue"> Claim HIDD</a>
  </div>
</template>

<script>
    export default { 
        name: 'Hidd',
        props: {
            claimableReward: String,
            timeToReward: String,
            assetStake: String,
            stakePower: String
        }
    };
</script>

<style></style>
