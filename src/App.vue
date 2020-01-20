<template>
  <div>
    <h1>Home</h1>
    <h2>{{ count }}</h2>
    <button @click="onClickAdd">Click !</button>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      count: 0
    };
  },
  methods: {
    onClickAdd() {
      this.count = this.count + 1;
    }
  }
};
</script>

<style>
h1 {
  background: orange;
}
h2 {
  background: blueviolet;
}
</style>
