<template>
    <div>
        <h2>This is Popup</h2>
        <input type="text" v-model="name" name="" id="">
        <button @click="$emit('close', name)">Close Popup</button>
    </div>
</template>

<script>
export default {
    name: 'PopupComponent',
    emits: {
        close: (name) => {
            if (!name) {
                return false
            } else {
                return true
            }
        }
    },
    data() {
        return {
            name: ''
        }
    }
}
</script>

<style scoped></style>