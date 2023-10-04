<script>
export default {
   name: 'Main',
   props: ['message']
}
</script>

<template>
   <h1>{{message}}</h1>
</template>

<style scoped>
h1 {
   font-family: sans-serif;
   font-size: 44px;
   font-weight: 500;
   color: white;
}
</style>