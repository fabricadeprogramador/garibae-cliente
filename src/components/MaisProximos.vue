<template>
    <div class="card-lava-jato">
        <v-row>
            <v-avatar>
                <img
                    src="http://www.guiafeurosa.com.br/files/guia/21/lava-jato-do-zue-em-feu-rosa-serra-es.jpg"
                    alt="Logo do Lava-jato"
                >
            </v-avatar>
            <div>
                <p alt="Nome do lava-jato">Nome do Lava-jato</p>
                <p alt="Status do lava-jato">Aberto</p>
                <p alt="Distância">2,2 km</p>
                <p alt="Preço do serviço mais barato">R$ 25,00</p>
            </div>
        </v-row>

    </div>
</template>

<script>
    export default {
        name: "MaisProximos",
        data: () => ({})
    };
</script>

<style>
    .card-lava-jato {
         background-color: white;
         padding: 10px 20px;
         margin: 15px;
         border-radius: 10px;
     }

    .card-lava-jato p {
        margin-bottom: 0px !important;
        font-size: 13px;
    }
    .v-avatar {
        margin: 0 15px !important;
    }

    .v-avatar img{
        heigth: 70px;
        width: 70px;
    }
</style>
