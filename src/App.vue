<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'VUE HELLO',
      image: 'https://picsum.photos/id/1005/600/200'
    }
  }
}

</script>

<template>
  <div>
    <h1>{{ message }}</h1>
    <img :src="image" style="width:100%;" alt="">
  </div>
</template>

<style></style>
