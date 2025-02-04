<script>
    let fibonacciNumbers = [0, 1];
    let month = 0; // Valor do mês
    
    function updateFibonacciForMonth() {
        // Garante que fibonacciNumbers seja longo o suficiente para o mês atual
        while (fibonacciNumbers.length <= month) {
            let last = fibonacciNumbers[fibonacciNumbers.length - 1];
            let secondlast = fibonacciNumbers[fibonacciNumbers.length - 2];
            fibonacciNumbers.push(last + secondlast);
        }
    }

    function increaseMonth() {
        month++;
        updateFibonacciForMonth();
    }

    function decreaseMonth() {
        if (month > 0) {
            month--;
            updateFibonacciForMonth();
        }
    }

    function updateMonthFromInput(event) {
        month = parseInt(event.target.value);
        updateFibonacciForMonth();
    }
</script>

<h1>Os coelhos de Fibonacci</h1>
<p>
    Mês: <input type="number" min="0" bind:value={month} on:input={updateMonthFromInput} />
    <button on:click={increaseMonth}>Próximo mês</button>
    <button on:click={decreaseMonth}>Mês anterior</button>
</p>
<p>Após {month} meses, haverá {fibonacciNumbers[month]} ninhadas de coelhos</p>