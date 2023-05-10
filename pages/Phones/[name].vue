<template>
    <h1>{{ name }}</h1>
    <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</template>

<script setup>
    const route = useRoute()

    const name = computed(()=>{
        return route.params.name.replaceAll("-"," ");
    })
</script>