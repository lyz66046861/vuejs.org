<template>
  <p>{{ greeting }} World!</p>
</template>

<script>
export default {
  data: function() {
    return {
      greeting: "Hello"
    };
  },
  methods:{
    show: function(props) {
      console.log(props)
    }
  }
};
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>