<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Esta es mi primer aplicacion con vue.js, El siguiente enlace es de mi github<br>
      <a href="https://github.com/josman32" target="_blank" rel="noopener">Github</a>.
    </p>
    <h3>Redes Sociales</h3>
    <ul>
      <li><a href="https://www.facebook.com/1997manuel" target="_blank" rel="noopener">Facebook</a></li>
      <li><a href="https://api.whatsapp.com/send?phone=75618771&text=Enseguida%20te%20responderemos" target="_blank" rel="noopener">Whatsapp</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Presentacion',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
