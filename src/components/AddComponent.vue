<template>
<button v-on:click="$emit('incCount')">+1</button>
</template>

<script>
    export default{
        name:'AddComponent'
    }
</script>