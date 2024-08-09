<template>
    <div>
        <h1>Componentes de Dados</h1>
        <p>Nome: {{nomeProduto}} = {{codigoProduto}}</p>
    </div>
</template>
<style scoped>
div{
    text-align: center;
    border: 2px solid rgb(10,69,4);
    background-color: #050d04;
    border-radius: 15px;
    margin: 30px;
    padding: 10px;
}
p{
    font-size: 1.5rem;
}
</style>
<!-- <script> Forma nao muito utilizada 
//Exemplo
//Option api
// export default {
//     data:function(){
//         return{
//             nomeProduto:"Caderno",
//             codigoProduto:"#123"
//         }
//     }
// }

//Composition api
export default { //Nao é a forma mais comun
    setup:function(){
        const nomeProduto = "Lapis"
        const codigoProduto = "#789"
        return{
            nomeProduto,
            codigoProduto
        }
    }
}

</script> -->
<script setup>
const nomeProduto = "Apontador"
const codigoProduto = "#987"
</script>