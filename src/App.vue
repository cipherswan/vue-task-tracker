<template>
  <div id="app">
    <div class="header">
      <h1>{{title}}</h1>
      <h6>{{desc}}</h6>
    </div>

    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      title: 'Task Tracker',
      desc: 'An application to track your everyday tasks.',
    };
  },
};
</script>

<style>

</style>
