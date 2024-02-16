<template>
    <div>
        <h2>This is Popup</h2>
        <button @click="$emit('close','Divyesh')">Close Popup</button>
    </div>
</template>

<script>
export default {
    name: 'PopupComponent',
    emits: ['close']
}
</script>

<style scoped></style>