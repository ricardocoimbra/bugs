<template>
    <div>
        <h1>Bugs</h1>
        <button @click="addBug()">Add Bug</button>
    </div>

</template>

<script>
export default {
    name: "Bugs.vue",
    methods: {
        addBug() {
            this.$router.push({ name: "bugs.create" });
        }
    }
}
</script>

<style scoped>

</style>
