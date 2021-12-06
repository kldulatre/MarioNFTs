<template>
	<div class="flex flex-col justify-center items-center space-y-8">
		<Header :data="'Features'" />
		<div class="flex space-x-4">
			<div class="w-1/3" v-for="item in data" :key="item.title">
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