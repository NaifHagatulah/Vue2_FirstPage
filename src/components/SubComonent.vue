<template>
<button v-on:click="$emit('SubCount')">-1</button>
</template>

<script>
export default{
    name:'SubComponent'
}
</script>