<template>
  <div id="block">click me</div>
</template>
<script>
export default {
  props: ["delay"],
};
</script>
<style scoped>
#block {
  width: 400px;
  border-radius: 20px;
  background: #0faf87;
  color: white;
  text-align: center;
  padding: 100px 0px;
  margin: 40px auto;
}
</style>
