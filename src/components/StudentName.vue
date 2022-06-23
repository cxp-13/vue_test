<template>
	<!-- test -->
	<div class="root">
		<h1>学生名称：{{ name }}</h1>
		<h1>学生年龄：{{ age }}</h1>
		<!-- <button @click="showName">点我提示学校名</button> -->
	</div>
</template>

<script>
export default {
	name: 'StudentName',
	data() {
		return {
			name: '尚硅谷',
			age: 12
		};
	}
};
</script>
