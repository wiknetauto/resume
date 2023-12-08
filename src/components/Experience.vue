<script>
    export default {
        props: ['header1', 'header2'],
        data() {
            return {
            }
        },
    }
</script>

<template>
    <div class="mb-20 mx-6 sm:mx-16 lg:mx-32 xl:mx-48">
        <h2 class="text-3xl font-bold mt-20" > {{ header1 }} </h2>
        <div class="mt-4 border-2 rounded-lg p-5">
            <slot name="employment"></slot>
        </div>
        <h2 class="text-3xl font-bold mt-20" > {{ header2 }} </h2>
        <div class="mt-4 border-2 rounded-lg p-5">
            <slot name="education"></slot>
        </div>
    </div>
</template>

<style></style>
