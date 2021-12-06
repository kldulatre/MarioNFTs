<template>
	<div
		class="
			flex flex-col
			hover:shadow-2xl
			flex-grow
			h-100
			border border-opacity-25 border-white
			red-bg-1
			rounded-2xl
			items-center
			justify-start
			p-6
			space-y-4
		"
	>
		<img :src="data.image" alt="" class="h-40 w-40 p-4" />
		<div class="text-xl font-bold">{{ data.title }}</div>
		<div class="text-center opacity-60 flex items-start flex-1">{{ data.description }}</div>
	</div>
</template>

<script>
export default {
	props: ["data"],
};
</script>

<style scoped>
.red-bg-1 {
	background-color: #e75353;
}
.h-100 {
	height: 22rem;
}
</style>