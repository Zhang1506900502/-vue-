<template>
  <div class="home">1111</div>
</template>

<script>
export default {
  name: "Home",
  components: {},
  mounted() {
    function sum(x) {
      return function (y) {
        return x + y;
      };
    }
    var sum1 = sum(1);
    var sum10 = sum(10);

    console.log(sum1(2));
    console.log(sum10(5));
  },
};
</script>
