/* eslint-disable */
<template>

    <div  :key="task.id" v-for="task in tasks">

         <h3> {{tasks.text}}</h3>

    </div>
</template>

<script>
export default {
    name : 'TaskTag',
    props : {
        task:Object
    },

}
</script>

<style scoped>

.task{

}

</style>