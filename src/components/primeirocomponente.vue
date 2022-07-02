<template>
    <div>
        <h1>Olá vue</h1>
        <p>Meu nome é {{ nome }} e sou {{ profissão }}</p>
    </div>
</template>

<script>
    
    export default{
        name: 'primeirocomponente', 
        data(){
            return {
                nome: 'Matheus',
                profissão: 'programador'
            }
        }
    }
</script>