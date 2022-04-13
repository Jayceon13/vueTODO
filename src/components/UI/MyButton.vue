<template>
    <button class="btn">
        <slot></slot>
    </button>
</template>

<script>
export default {
    name: 'my-button'
}
</script>

<style scoped>
.btn {
    align-self: flex-end;
    padding: 10px 15px;
    background: yellow;
    color: teal;
    border: 1px solid teal;
}
</style>