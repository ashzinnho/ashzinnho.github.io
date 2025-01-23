<script>
    let corrida, flexao, abdominal;
    let nf = $state(0);
 
    function calcularnota() {
        nf =(corrida*4 + flexao*3 + abdominal*3)/10
    }
 </script>
 
 <h1>MÉDIA PONDERADA</h1>
 
 Corrida de 100 metros:
 <input type="number" bind:value={corrida} min="0" max="10" />
 <br />
 
 Flexões:
 <input type="number" bind:value={flexao} min="0" max="10" />
 <br />
 
 Abdominais:
 <input type="number" bind:value={abdominal} min="0" max="10" />
 <br />
 
 <button onclick={calcularnota}> Calcular a média ponderada!</button>
 
 <p>Tua nota final é: {nf}</p>
 
 {#if nf >= 8.5}
     <p>A, Excelente 💪</p>
 {:else if nf >= 7}
     <p>B, Muito bom 🙂</p>
 {:else if nf >= 5}
     <p>C, Satisfatório 😐</p>
 {:else if nf >= 2.5}
     <p>D, Abaixo da média 😟</p>
 {:else if nf}
     <p>E, Insuficiente 😞</p>
 {/if}
 