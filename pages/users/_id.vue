<template>
  <div>
    <h1>{{ message }}</h1>
    <p>id: {{ this.$route.params.id }}</p>
  </div>
</template>

<script>
export default {
  name: "_id",
  data: function(){
    return {
      message: '/users/_id.vueを表示中'
    }
  }
}
</script>

<style scoped>

</style>
