<template>
    <p>Burger for Component</p>
    <div class="imput-container">
        <label for="nome">Nome do cliente:</label>
        <input type="text" id="nome" name="nome" v-model="nome" placeholder="Digite o seu nome">
    </div>
    <div class="imput-container">
        <label for="pao">Escolha o pão:</label>
        <select name="pao" id="pao" v-model="pao">
            <option value="">Selecione o seu pão</option>
            <option value="Integral">Integral</option>
        </select>
    </div>
</template>

<script>
export default{
    name:'BurgerForm'
}
</script>

<style scopes>

</style>