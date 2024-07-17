<script>
export default {
    name: 'EquipeView',
    data() {
        return {
            equipe: [
                {
                    nome: 'Claudio',
                    
                },
                {
                    nome: 'Gustavo',
                 
                },
                {
                    nome: 'Manuela',
                },
                {
                    nome: 'Max',
                },
                {
                    nome: 'Vinicius',
                },
                {
                    nome: 'Yohana'
                }
            ]
        }
    }
}
</script>

<template>
    <div>
        <h1>Equipe</h1>
        <ul>
            <li v-for="membro in equipe" :key="membro.nome">
                <h2>{{ membro.nome }}</h2>
            </li>
        </ul>
    </div>
</template>

<style scoped>
/* Your component-specific styles go here */
</style>