<template>
     <div :class="[type]">{{content}}</div>
</template>

<script>
    export default {
        props: {
            content: {
                type: String,
                default: 'comfirm'
            },
            type:{
                type: String,
                default: 'info'
            }
        }
    }
</script>

<style lang="scss" scoped>
div {
    background-color:green;
    color:#fff;
    padding: 5px 10px;
    border-radius: 10px;
    opacity: 0.6;
    transition: 1s;
    display: inline-block;
    cursor: pointer;
    &:hover{
        opacity: 1;
    }
    &.info{
        background-color: #ddd;
    }
    &.success{
        background-color: greenyellow;
    }
}
</style>