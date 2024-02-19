<template>
    <div>
        <h3 v-for="name in names" :key="name.firstName">
            <slot :firstName="name.firstName" :lastName="name.lastName"></slot>
        </h3>
    </div>
</template>

<script>
export default {
    name: 'NameListComponent',
    data() {
        return {
            names: [
                {
                    firstName: 'Neel',
                    lastName: 'Joshi',
                },
                {
                    firstName: 'Divyesh',
                    lastName: 'Mepal',
                },
                {
                    firstName: 'Divyesh',
                    lastName: 'Patel',
                }
            ],
        }
    },
}
</script>

<style scoped></style>