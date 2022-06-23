<template>
    <!-- test -->
    <div class="root">
        <h1>学校名称：{{ name }}</h1>
        <h1>学校地址：{{ address }}</h1>
        <button @click="showName">点我提示学校名</button>

    </div>
</template>


    <script>
export default {
    name: 'SchoolName',
    data() {
        return {

            name: '尚硅谷',
            address: '北京'
        }
    },
    methods: {
        showName() {
            alert(this.name)
        }
    },
}
</script>

    <style>
    /* test */
    .root {
        background-color: aqua;
    }
    </style>
