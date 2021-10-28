<template>
  <section>
    <o-field label="Name">
      <o-input v-model="name" placeholder="What is your name?"></o-input>
    </o-field>
    <o-button @click="clickMe">Clear Name</o-button>
  </section>
</template>

<script>
export default {
  data() {
      return {
        name: ''
      }
    },
  methods: {
      clickMe() {
        this.name = ''
      }
    }
  }
</script>

<style>
body {
  margin-top: 200px;
  margin-left: auto;
  margin-right: auto;
  width: 500px;
}
</style>