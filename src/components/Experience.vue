<template>
    <div class="mb-20 mx-6 sm:mx-16 lg:mx-32 xl:mx-48">
        <div class="flex justify-between items-center mt-20 ">
            <h2 class="text-3xl font-bold" > {{ title }} </h2>
            <button @click="showHide" class="bg-gray-300 hover:bg-gray-400 text-gray-800 text-sm py-1 px-2 rounded items-center ml-2 mb-1">Show/Hide</button>
        </div>
        <div v-if="showExperience" class="mt-4 border-2 rounded-lg p-5">
            <slot></slot>
        </div>
    </div>
</template>
<script>
    export default {
        data() {
            return {
                showExperience: true,
            }
        },
        props: ['title'],
        methods: {
            showHide() {
                this.showExperience = !this.showExperience;
            },
        },
        }
</script>
<style></style>
