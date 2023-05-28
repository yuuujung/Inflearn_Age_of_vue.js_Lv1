<template>
  <header>
    <h1>{{ propsdata }}</h1>
    <button v-on:click="pass">send</button>
  </header>
</template>

<script>
export default {
    name: 'AppHeader',
    props: ['propsdata'],
    methods: {
        pass() {
            this.$emit('renew')
        }
    }
}
</script>

<style>

</style>