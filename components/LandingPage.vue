<template>
	<div class="flex items-center">
		<div class="left w-1/2 space-y-12">
			<div class="uppercase text-xl font-semibold">Super Mario Metaverse</div>
			<div class="text-8xl font-bold w-100">Collect and Play Mario</div>
			<div class="text-xl w-100">Team up for a paws-itively adorable adventure and Unique NFT Collectibles Game for Mario lovers!</div>
			<div class="space-x-2 flex">
				<YellowButton v-bind:data="'Learn More'" />
				<button class="uppercase py-2 px-6 rounded-md yellow-font">How It Works</button>
			</div>
		</div>
		<div class="right w-1/2 relative">
			<img class="z-1" src="/images/mario1.png" alt="" />
			<div class="absolute bottom-0 right-0 p-6 my-16 border border-opacity-25 border-white rounded-lg shadow-2xl red-bg-1 w-96 space-y-8">
				<div class="flex justify-between items-center">
					<div>
						<div class="text-base opacity-70">#511</div>
						<div class="text-2xl font-bold">Super Mario</div>
					</div>
					<div class="p-2 w-14 h-14 rounded-full flex items-center justify-center red-bg-2 border border-opacity-25 border-white">
						<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"
							/>
						</svg>
					</div>
				</div>
				<div class="flex space-x-2 text-xl font-semibold">
					<div class="px-6 py-3 space-x-2 flex items-center rounded-full flex items-center justify-center red-bg-2 border border-opacity-25 border-white">
						<div>
							<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									stroke-width="2"
									d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
								/>
							</svg>
						</div>
						<div>525K USD</div>
					</div>
					<div class="px-6 py-2 space-x-2 flex items-center rounded-full flex items-center justify-center red-bg-2 border border-opacity-25 border-white">
						<div>
							<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									stroke-width="2"
									d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4m0 5c0 2.21-3.582 4-8 4s-8-1.79-8-4"
								/>
							</svg>
						</div>
						<div>845K</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
.yellow {
	background-color: #ffb400;
}
.yellow-font {
	color: #ffb400;
}
.w-100 {
	width: 32rem;
}
.red-bg-1 {
	background-color: #e75353;
}
.red-bg-2 {
	background-color: #c93535;
}
</style>