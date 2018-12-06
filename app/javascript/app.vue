<template>
  <div id="app">
    <p>{{ message }}</p>
  </div>
</template>

<script>
    export default {
        data: function () {
            return {
                message: "I wanto use vuejs in rails"

            }
        }
    }
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
