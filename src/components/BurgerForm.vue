<template>
    <p>Burger for Component</p>
    <div>
        <form id="burger-form">
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
            <div class="imput-container">
                <label for="carne">Escolha a carne do seu Burger:</label>
                <select name="carne" id="carne" v-model="carne">
                    <option value="">Selecione o tipo de carne</option>
                    <option value="Maminha">Maminha</option>
                </select>
            </div>
            <div class="imput-container">
                <label for="opcionais">Selecione os opcionais:</label>
                <div class="checkbox-container">
                    <input type="checkbox" name="opcionais" v-model="opcionais" value="salame">
                    <span>Salame</span>
                </div>
            </div>
            <div class="imput-container">
                <input type="submit" class="submit-btn" value="Criar meu Burger!">
            </div>
        </form>
    </div>
</template>

<script>
export default{
    name:'BurgerForm'
}
</script>

<style scopes>
    #burger-form{
        max-width: 400px;
        margin: 0 auto;
    }

    
</style>