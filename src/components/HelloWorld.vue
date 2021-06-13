<template>
  <div class="hello">
    <Button content="testew few f ew">
      <template v-slot:header> this is header </template>
      <template v-slot:footer> this is footer </template>
    </Button>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  components: {
    Button: () => import("./Button"),
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
