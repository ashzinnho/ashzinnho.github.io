<script>
  let { children } = $props();
</script>

<style>

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

 
  nav {
    background-color: #333;
    display: flex;
    justify-content: space-around;
    padding: 15px;
  }

  nav a {
    color: white;
    text-align: center;
    padding: 14px 20px;
    text-decoration: none;
  }

  nav a:hover {
    background-color: #ddd;
    color: black;
  }
</style>

<nav>
  <a href="/">Início</a>
  <a href="/filmes">Conhecimento</a>
  <a href="/energia">Energia</a>
  <a href="/morte">Morte</a>
  <a href="/sangue">Sangue</a>
</nav>

{@render children()}
