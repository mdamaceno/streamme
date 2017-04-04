<template lang="pug">
.outra
    h1 {{ msg }}
    router-link(to="/") Hello
</template>

<script>
export default {
  name: 'outra-pagina',
  data () {
    return {
      msg: 'Outra Página'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
