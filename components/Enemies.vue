<template>
	<div class="flex sm:flex-row flex-col sm:border sm:border-opacity-25 sm:border-white sm:rounded-2xl sm:p-12 p-8 sm:px-16 background">
		<div class="hidden sm:inline-block sm:w-1/2 space-y-8 flex flex-col justify-center">
			<Header :data="'Enemies and obstacles'" class="w-96"></Header>
			<SubBody :data="description" />
			<YellowButton :data="'Check Enemies'" />
		</div>
		<div class="hidden sm:inline-block sm:w-1/2 flex w-full justify-end">
			<img src="images/enemies.png" class="h-96" alt="enemies" />
		</div>
		<div class="sm:hidden flex flex-col items-center space-y-6">
			<Header :data="'Enemies and obstacles'" class="sm:w-96 text-center"></Header>
			<img src="images/enemies.png" class="sm:h-96 h-60" alt="enemies" />
			<SubBody class="text-center" :data="description" />
			<YellowButton :data="'Check Enemies'" />
		</div>
	</div>
</template>

<script>
export default {
	data() {
		return {
			description:
				"Each enemies has their own power, choose the good Mario while sending them to dungeons, some Mario can perform better than others based on dungeon rules",
		};
	},
};
</script>

<style scoped>
.background{
    background-color: #c93535;
}
</style>