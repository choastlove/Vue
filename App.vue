// App.vue
<template>
    <div class="box" v-text="note"></div>
</template>

<script>
export default {
    data () {
        return {
            note: '这是一个组件的html模板！'
        }
    }
}
</script>

<style scoped>
.box {
    color: #000;
}
</style>