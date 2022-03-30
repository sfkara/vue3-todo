<template>
    <button  @click="onClick()" :style="{background: color}" class="btn">
        {{text}}
    </button>
   
</template>

<script>
export default {
    name:'ButtonTag',
    props : {
        text : String,
        color : String
    },
    methods : {
        onClick() {
            console.log('firat')
        }
    }
}
</script>

<style>

</style>