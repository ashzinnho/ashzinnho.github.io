<script>
    let i= $state(0);
</script>

Sua idade:
<input type="number" bind:value={i} />
<br />
 

 
<p>Você é</p>

{#if i <16 }
    <p> Não eleitor </p>
{:else if i<=17 }
    <p>Eleitor facultativo</p>
    {:else if i >= 70 }
    <p>Eleitor facultativo</p>
    {:else}
    <p>Eleitor obrigatorio</p>
{/if}