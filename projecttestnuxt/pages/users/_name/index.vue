<template>
  <h1>Welcome : {{$route.params.name}}</h1>
</template>

<script>
export default {
    validate(data){
      return /^\d+$/.test(data.params.name)
    }
}
</script>

<style>

</style>
