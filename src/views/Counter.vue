<template>
<div id="counter">
<h1>Counter</h1>
<p>{{count}}</p>
<AddComponent v-on:incCount="increment"/>
<SubComonent v-on:SubCount="Subtrackt"/>
</div>
</template>

<script>

import AddComponent from '@/components/AddComponent.vue'
import SubComonent from '@/components/SubComonent.vue'

export default {
  name: 'CounterPoop',
  components: {
    AddComponent,
    SubComonent
},
 data(){
    return{
        count:0,
    }
    
 },
 methods:{
    increment: function(){
        this.count++;
    },
    Subtrackt: function(){
        this.count--;
    }
 }

}
</script>
