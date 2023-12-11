<template>
    <div class="mb-20 mx-6 sm:mx-16 lg:mx-32 xl:mx-48">
        <h2 class="text-3xl font-bold mt-20" > {{ title }} </h2>
        <div class="mt-4 border-2 rounded-lg p-5">
            <slot></slot>
        </div>
    </div>
</template>
<script>
    export default {
        props: ['title'],
        }
</script>
<style></style>
