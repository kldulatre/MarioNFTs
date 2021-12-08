<template>
	<div
		class="
			flex flex-col
			items-center
			justify-center
			sm:rounded-2xl
			sm:p-10 p-4 p-8
			flex
			items-center
			justify-center
			red-bg-2
			sm:border sm:border-opacity-25 sm:border-white
			red-bg-2
			sm:space-y-8 space-y-4
		"
	>
		<Header :data="'About'"/>
		<div class="sm:text-lg text-base text-center sm:font-medium sm:mx-10 mx-2">
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