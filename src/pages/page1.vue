<template>
        <h1>Page1</h1>
              
        <div style="width: 50%;" class="q-mx-auto text-center ">
    <q-card
      class="my-card bg-cyan-8"
     
    >
      <q-card-section>
        <div class="text-h6">Nom de la personne  </div>
        <div class="text-subtitle2 text-orange-8">Description</div>
      </q-card-section>
      
      <q-card-section class="q-pt-none">
        Alphonse Marie Louis de Prat de Lamartine, né à Mâcon le 21 octobre 1790 et mort à Paris le 28 février 1869, est un poète, un écrivain, un historien et un homme politique français. Il appartient au mouvement romantique (sa poésie lyrique incarne une idéalisation de la nature).
      </q-card-section>
      </q-card>
</div>

</template>

<script>
import { defineComponent,ref  } from 'vue';

import  mydata  from "src/data/mydata"

export default defineComponent({
    name : 'page1',
   
    setup () {
    return {
      slide: ref('first')
    }
  },
    data (){
         return {mydata}
    }

    
})

</script>