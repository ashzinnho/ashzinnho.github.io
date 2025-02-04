<script>
    let i= $state(0);
</script>

<p>Sua idade:</p>
<input type="number" bind:value={i} />
<br />

{#if i <=12 }
    <p> Desconto de 50%!</p>
{:else if i<=17 }
    <p>Desconto de 30%!</p>
    {:else if i >= 60 }
    <p>Desconto de 40%!</p>
    {:else}
    <p>Sem desconto!</p>
{/if}