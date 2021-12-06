<template>
	<div
		class="
			flex flex-col
			hover:shadow-2xl
			flex-grow
			sm:h-100
			border border-opacity-25 border-white
			red-bg-1
			rounded-2xl
			items-center
			justify-start
			p-4
			sm:p-6
			sm:space-y-4
			space-y-0
		"
	>
		<img :src="data.image" alt="" class="sm:h-36 sm:w-36 w-28 h-28 p-4" />
		<div class="sm:text-xl font-bold">{{ data.title }}</div>
		<div class="sm:text-base text-sm text-center opacity-60 flex items-start flex-1">{{ data.description }}</div>
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
@media (min-width: 640px) {
	.sm\:h-100 {
		height: 22rem;
	}
}
</style>