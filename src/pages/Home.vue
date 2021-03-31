<template>
    <main>
        <h1>Pacientes</h1>
            <table id="tabelaPacientes" style="width:500px;text-align:center;">
                <thead>
                    <tr>
                        <th>Paciente:</th>
                        
                    </tr>
                    <tr>
                        <th>Idade:</th>
                        
                    </tr>
                    <tr>
                        <th>resultado:</th>
                    </tr>
                </thead>
            </table>
    </main>
</template>

<script>
export default {
    setup() {
        
    },
}
</script>

<style scoped>

    main{
        background-color: var(--color-background-home);
        justify-content: center;
        align-items: center;
    }

    .text-top{
        color: var(--color-text-ligth);
        font-size: 22px;
        margin-bottom: 20px;

    }

    #subcribe{
        width: 340px;
    }
    
    .text-bottom{
        color: var(--color-text-light);
        font-size: 18px;
        margin-top: 20px;
    }

    @media (min-width:700px){
        #subscribe{
            width: 370px;
        }
    }

</style>