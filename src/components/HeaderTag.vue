<template>
  <header>
      <h1>{{title}}</h1>
      <ButtonTag text= 'Add Task'  color= 'green'/>
  </header>
</template>

<script>
import ButtonTag from './ButtonTag.vue'

export default {
    name: 'HeaderTag ',
    props : {
        title: String,
    },
    components: {
        ButtonTag,
    }
}
</script>

<style scoped>
    header {
        display:flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 30px;
    }
</style>