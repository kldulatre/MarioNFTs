<template>
	<div class="flex flex-col justify-center items-center sm:space-y-8 space-y-6">
		<Header :data="'Features'" />
		<div class="flex sm:space-x-4 justify-center sm:justify-start flex-wrap sm:flex-nowrap space-y-4 sm:space-y-0">
			<div class="sm:w-1/3 w-4/5" v-for="item in data" :key="item.title">
				<Card class="" :data="item" />
			</div>
		</div>
	</div>
</template>

<script>
export default {
	data() {
		return {
			data: [
				{
					title: "True Ownership",
					description: "Every item or character you own in the game is 100% yours and stored on the blockchain.",
                    image: "images/trueOwnership.png"
				},
				{
					title: "Marketplace",
					description: "You will be able to trade on any marketplace that support NFT's.",
                    image: "images/marketplace.png"
				},
                {
					title: "Leaderboard",
					description: "Grow your beasties and move up in the player rankings.",
                    image: "images/leaderboard.png"
				},
			],
		};
	},
};
</script>

<style lang="scss" scoped>
</style>