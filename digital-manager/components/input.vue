<template>
  <div class="my-4 flex flex-col">
    <label class="text-h4">{{label}}</label>
    <input :placeholder="placeholder" class="w-full p-2 border rounded-lg"/>
    </div>
</template>

<script lang="ts" setup>
const props = defineProps({
    label: {
        type: String,
    },
    placeholder: {
        type: String,
    },
    type: {
        type: String,
    }

})
</script>

<style>

</style>