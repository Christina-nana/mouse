<script setup lang="ts">
import {ref} from 'vue'
import useMouse from './composiable/mouse'

let {x:mouseX,y} = useMouse()
</script>

<template>
<h1>{{mouseX}}:{{y}}</h1>
</template>

<style>

</style>
