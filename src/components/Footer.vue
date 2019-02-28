<template>
  <footer>
      <p> {{ copyright }} </p>
  </footer>
</template>

<script>
export default {
 
  data () {
      return {
        copyright: 'Made by Max 2019'
      }
  }
}
</script>

<style scoped>

footer {
    background:  #222;
    padding: 6px;
    bottom: 10px;
}
p {
    color: rgb(204, 214, 204);
    text-align: center;
}

</style>