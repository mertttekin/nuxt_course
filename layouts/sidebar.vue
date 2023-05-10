<template>
    <section>
        <article class="sidebar bg-gray-500">
            <p>Dashboard</p>
            <p>Settings</p>
        </article>
        <slot></slot>
    </section>
</template> 

<style>
    .sidebar{
        display: flex;
        flex-direction: column;
        height: 100vh;
        width: 20%;
        margin: 0;
        align-items: left;
        padding: 10px;
        font-weight: 600;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    section {
        display: flex;
        justify-content: space-between;
        margin: 0;
    }
    template{
        margin: 0;
    }
</style>