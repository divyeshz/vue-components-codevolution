<template>
    <div class="container">
        <div class="card mb-3">
            <div id="card-header" class="card-header">
                <slot name="header"></slot>
            </div>
            <div id="card-body" class="card-body">
                <slot></slot>
            </div>
            <div id="card-footer" class="card-footer text-body-secondary">
                <slot name="footer"></slot>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CardComponent',
    props: ['content']
}
</script>

<style scoped></style>