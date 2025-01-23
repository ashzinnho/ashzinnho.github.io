<script>
   let np, nt, ns;
   let nf = $state(0);

   function calcularnota() {
       nf =(np*5 + nt*2 + ns*3)/10
   }
</script>

<h1>Boletim Escolar</h1>

Nota da prova:
<input type="number" bind:value={np} min="0" max="10" />
<br />

Nota do trabalho:
<input type="number" bind:value={nt} min="0" max="10" />
<br />

Nota do seminário:
<input type="number" bind:value={ns} min="0" max="10" />
<br />

<button onclick={calcularnota}> Calcular a nota final!</button>

<p>Tua nota final é: {nf}</p>

{#if nf >= 8.5}
    <p>Conceito A, aprovado 😁</p>
{:else if nf >= 7}
    <p>Conceito B, aprovado 😎</p>
{:else if nf >= 5}
    <p>Conceito C, recuperação 😅</p>
{:else if nf >= 2.5}
    <p>Conceito D, recuperação 😣</p>
{:else if nf}
    <p>Conceito E, reprovado 😱</p>
{/if}