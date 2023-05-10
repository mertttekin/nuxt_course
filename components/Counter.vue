<template>
    <h1>Counter</h1>
    <section>
        <p>This page will be displayed at the /about route.</p>
        <button @click="increment">increment</button>
        <p>{{ count }}</p>
        <button class="rounded-full " @click="decrement">decrement</button>
        
    </section>

</template>

<script setup>

    const count = ref(0);

    function increment() {
        count.value++;
     }
    function decrement() { 
        count.value--;
    }

</script>