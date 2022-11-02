<script>
  let name = "world"
  let src = './src/football.gif'
</script>

<h4>This is dynamic data</h4>
<h1>hello {name}</h1>
<h2>hello {name.toUpperCase()}</h2> <hr>

<h4>Dynamic atributes</h4>
<img src={src} alt="a football"> <br> <br>

<img {src} alt="a football">

<style>
  img{
    width: 200px;
  }
</style>
