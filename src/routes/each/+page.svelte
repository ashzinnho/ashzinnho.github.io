<script>
    let lista = ['uva','cereja','morango','pera'];
</script>

<h2>Minhas frutas favs</h2>
<ul>
    {#each lista as fruta}
    <li>{fruta}</li>
    {/each}
</ul>