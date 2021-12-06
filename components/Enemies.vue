<template>
	<div class="flex border border-opacity-25 border-white rounded-2xl p-12 px-16 background">
		<div class="w-1/2 space-y-8 flex flex-col justify-center">
			<Header :data="'Enemies and obstacles'" class="w-96"></Header>
			<SubBody :data="description" />
			<YellowButton :data="'Check Enemies'" />
		</div>
		<div class="w-1/2 flex w-full justify-end">
			<img src="images/enemies.png" class="h-96" alt="enemies" />
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