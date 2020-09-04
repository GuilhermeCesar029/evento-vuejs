<template>
    <div id="evento-1">
        <button v-on:click="cont++">Adiciona 1</button>
        <p>Quantas vezes o botão foi clicado: {{cont}}</p>
    </div>
</template>

<script>
    export default {
        data: function() {
            return {
                cont: 0
            }
        }
    }
</script>