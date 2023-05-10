<template>
    <a href="#" @click="$event=>view('welcome')">Show Welcome</a>
    <a href="#" @click="$event=>view('counter')">Show Counter</a>

    <Counter v-if="page =='counter'"/>
    <Welcome v-if="page =='welcome'"/>
</template>

<script setup>

const page = ref("welcome")

function view(name){
    page.value = name;
}

</script>

<style>
    a {
        margin-right: 10px;
    }
</style>