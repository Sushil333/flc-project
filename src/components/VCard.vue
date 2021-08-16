<template>
  <div class="">
    <img src="@/assets/images/box.png" />
    <h1>Qty: xxxx <span>HIDD:xxxx </span></h1>
  </div>
</template>

<script>
export default {
    name: 'VCard',
    props: {
        qty: Number,
        hidd: String
    }
};
</script>

<style></style>
