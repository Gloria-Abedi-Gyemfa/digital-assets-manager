<template>
    <div>
        <button class="w-full bg-[#2563EB] text-[#ffffff] p-1.5 rounded-lg">{{text}}</button>
    </div>
</template>
<script>
const props = defineProps({
    text: {
        type: String,
    }
})
</script>