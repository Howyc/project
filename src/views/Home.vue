<template>
  <div class="home">
    我是主页
  </div>
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
