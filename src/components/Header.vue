<template>
    <header>
        <h2> {{msg}} </h2>
        <Button/>
    </header>
</template>

<script>
import Button from "./Button.vue"
export default {
    name: "Header",
    components: {
        Button,
    },
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