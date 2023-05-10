<template>
  <div class="hello">
    <h1>Juhyun Lim</h1>
    <p>
      Hello, I'm working.<br/>
      Please feel free to contact me if you have any questions.<br/><br/>
      <b>You are being redirected to my LinkedIn page.</b>
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  created(){
    setTimeout( () => { window.location = "https://www.linkedin.com/in/juhyun-lim-1022/"}, 5000);
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
