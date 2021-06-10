<template>
  <div class="home"></div>
</template>

<script>
export default {
  mounted() {
    this.axios.get("/js/seller.json").then((res) => {
      console.log(res.data);
    });
  },
};
</script>
