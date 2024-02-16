<template>
    <h2>
        Hello {{ name }} {{ heroName }}
    </h2>
</template>

<script>
export default {
    name: 'GreetComponent',
    props: ['name', 'heroName']
}
</script>

<style scoped></style>