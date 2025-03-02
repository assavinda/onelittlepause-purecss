<template>
    <section class="containerx">
        <!-- holder -->
        <div>
            <img src="/images/home/home-bg.png" class="holder">
        </div>
        
        <slot></slot>
    </section>
</template>

<script setup>

</script>

<style scoped>
.containerx {
    position: relative;
    width: fit-content;
    height: fit-content;
    overflow: hidden;
    background-color: white;
}
.holder {
    opacity: 0.5;
    max-width: 100vw;
    max-height: 100vh;
}
</style>