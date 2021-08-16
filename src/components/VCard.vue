<template>
  <div class="mb-3 mb-md-5">
    <img src="@/assets/images/box.png" />
    <h1>Qty: xxxx <span>HIDD:xxxx </span></h1>
  </div>
</template>

<script>
export default {
    name: 'VCard',
    props: {
        qty: String,
        hidd: String
    }
};
</script>

<style></style>
