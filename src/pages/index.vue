<template>
  <Layout>
    <div>
      Welcome to your static site!
    </div>
  </Layout>
</template>

<script>
import Layout from "../components/Layout";

export default {
  name: "Home",
  components: {
    Layout,
  },
  head() {
    return {
      title: "Home"
    };
  }
};
</script>

<style>
</style>
