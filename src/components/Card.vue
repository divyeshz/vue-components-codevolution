<template>
    <div class="container">
        <div class="card mb-3">
            <div class="card-body">
                <slot>
                    
                </slot>
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