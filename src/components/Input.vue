<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <input class="form-control" type="text" :value="modelValue"
                        @input="$emit('update:modelValue', $event.target.value)">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'InputComponent',
    props: {
        modelValue: String
    }
}
</script>

<style scoped></style>