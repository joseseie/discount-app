<template>
  <q-page class="flex flex-center">

    <div class="text-center q-gutter-lg q-pa-lg">

      <!--Espaço da foto-->
      <div class="">

        <img
            src="https://avatars.githubusercontent.com/u/18400142?v=4"
            alt="José Seie"
            style="border-radius: 100%;width: 100px;height: 100px"
        >
        
      </div>

      <!--Espaço com o texto-->
      <div class="">

        <div class="text-h6" style="font-size: 20pt">
          Oi, José
        </div>
        <div class="text-grey-5">
          Nossa calculadora online oferece descontos com base no numero de cursos da Explicador que frequentou
        </div>
      </div>

      <!--Espaço do botão-->
      <div class="q-pa-lg">

        <q-btn
          label="Calcular"
          unelevated
          color="blue-8"
          class="full-width"
        />

      </div>

      <!--Força que os elementos subam-->

      <div style="height: 9vh;"></div>

    </div>

  </q-page>
</template>

<script>

export default {
  name: 'PageIndex'
}
</script>
