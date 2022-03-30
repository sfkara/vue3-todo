/* eslint-disable */
<template>

    <div class="task">

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

<style>

</style>