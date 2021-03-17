<template>
    <header>
        <h2> {{msg}} </h2>
        <button style = "color: green" class="btn btn-success">Add task</button>
    </header>
</template>

<script>
export default {
    props: {
        msg : String
    }
}
</script>

<style scoped>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
</style>