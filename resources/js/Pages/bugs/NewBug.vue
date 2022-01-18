<template>
    <form>
        <div class="form-group">
            <label for="title">Title</label>
            <input type="text" class="form-control" id="title" v-model="title">
        </div>
        <div class="form-group">
            <label for="description">Description</label>
            <textarea class="form-control" id="description" v-model="description"></textarea>
        </div>
        <div class="form-group">
            <button>Cadastrar</button>
        </div>
    </form>
</template>

<script>
export default {
    name: "NewBug",
    data() {
        return {
            title: "",
            description: ""
        }
    },
}
</script>

<style scoped>

</style>
