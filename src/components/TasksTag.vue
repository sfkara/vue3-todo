<template>
  <div  :key="task.id" v-for="task in tasks">
      <task-tag :task='task' />
  </div>
</template>

<script>

import TaskTag from './TaskTag.vue'
export default {
    name : 'TasksTag',
    props : {
        tasks : Array
    },
    components :{
        
        TaskTag
    }
    
}
</script>

<style>

</style>