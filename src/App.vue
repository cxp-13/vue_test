<template lang="">
    <div id="root">
        <school ></school>
        <student ></student>
    </div>
</template>
<script>
    import school from './components/SchoolName.vue'
    import student from './components/StudentName.vue'

    export default {
        name: 'App',
		
        components: {
            school,
            student
        }
    }
</script>
<style lang="">

</style>