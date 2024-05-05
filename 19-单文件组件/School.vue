<template>
    <div class="demo">
        <h2>学校名称：{{ name }}</h2>
        <h2>学校地址：{{ address }}</h2>
        <button @click="showName">点我提示学校名</button>
    </div>
</template>

<script>
    export default {
        name: 'School',
        data() {
            return {
                name: '家里蹲',
                address: 'home'
            }
        },
        methods: {
            showName() {
                console.log(this.name)
            }
        },
    }
</script>

<style>
    .demo {
        background-color: orange
    }
</style>