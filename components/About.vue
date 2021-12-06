<template>
	<div
		class="
			flex flex-col
			items-center
			justify-center
			rounded-2xl
			p-10
			flex
			items-center
			justify-center
			red-bg-2
			border border-opacity-25 border-white
			red-bg-2
			space-y-8
		"
	>
		<Header :data="'About'"/>
		<div class="text-lg text-center font-medium mx-10">
			Mario is a blockchain game running on Binance Smart Chain. Collect Ultra-Rare digital moonsters, play with them, experience an adventure, trade
			and earn.
		</div>
		<YellowButton v-bind:data="'Launch App'" />
	</div>
</template>

<style scoped>
.red-bg-2 {
	background-color: #c93535;
}
</style>