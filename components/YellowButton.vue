<template>
	<div>
		<button class="uppercase yellow py-3 px-8 rounded-xl font-semibold text-lg shadow">{{ data }}</button>
	</div>
</template>


<script>
export default {
	props: ["data"],
};
</script>

<style scoped>
.yellow {
	background-color: #ffb400;
}
</style>