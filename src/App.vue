<template>
  <div id="app">
    <sidebar/>
    <navbar/>
    <paymentbar/>
    <performance/>
    <absent/>
  </div>
</template>

<script>
import sidebar from '@/components/sidebar.vue';
import navbar from '@/components/navbar.vue';
import paymentbar from '@/components/paymentbar.vue';
import performance from '@/components/performance.vue';
import absent from '@/components/absent.vue';

export default {
  name: 'app',
  components: {
    sidebar,
    navbar,
    paymentbar,
    performance,
    absent
  }
}
</script>

<style>
body{
  background: #F8F8F8;
  font-family: 'Khula', sans-serif;
}
</style>
