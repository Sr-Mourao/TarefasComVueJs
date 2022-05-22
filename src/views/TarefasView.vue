<template>
  <div>
     <v-list
      flat
      subheader
    >
      <v-subheader>General</v-subheader>

      <v-list-item-group
        v-model="settings"
        multiple
        active-class=""
      >
      <Tarefa />
      <Tarefa />
      <Tarefa />
      <Tarefa />

      </v-list-item-group>
    </v-list>
  </div>
</template>

<script>
import Tarefa from '../components/tarefas/TarefaComp.vue'

  export default {
    name: 'HomeView',

    components: {
      Tarefa
    },
  }
</script>

