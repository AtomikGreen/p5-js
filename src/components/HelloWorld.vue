<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Liens: </h2>

    <ul>
      <li>
        <a
          href="http://localhost:8080/#/p5Pong"
          target="_blank"
        >
          Pong-game
        </a>
      </li>
    </ul>
    <ul/>
      <li>
        <a
          href="http://localhost:8080/#/p5Pong2"
          target="_blank"
        >
          Pong-game(2)
        </a>
      </li>
      <li>
        <a
          href="http://localhost:8080/#/backgroundtest"
          target="_blank"
        >
          backgroundtest
        </a>
      </li>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'P5 PONG'
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
  color: #0000FF;
}
#HelloWorld{
    backgroud-color: white    
}
</style>
