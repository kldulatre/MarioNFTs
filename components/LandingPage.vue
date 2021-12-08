<template>
	<div class="flex items-center flex-col-reverse sm:flex-row">
		<div class="sm:w-1/2 sm:space-y-12 space-y-6 w-full sm:flex-none flex flex-col items-center sm:items-start">
			<div class="uppercase text-xl sm:font-semibold">Super Mario Metaverse</div>
			<div class="sm:text-8xl sm:font-bold sm:w-100 text-6xl font-bold text-center sm:text-left">Collect and Play Mario</div>
			<div class="sm:text-xl sm:w-100 inline-block text-center sm:text-left text-base w-4/5">
				<span>Team up for a paws-itively adorable adventure and Unique NFT Collectibles Game for Mario lovers!</span>
			</div>
			<div class="space-x-2 flex">
				<YellowButton v-bind:data="'Learn More'" />
				<button class="uppercase sm:py-2 py-1 sm:px-6 px-2 rounded-md yellow-font sm:text-base text-sm">How It Works</button>
			</div>
		</div>
		<div class="sm:right sm:w-1/2 relative w-11/12">
			<img class="z-1" src="/images/mario1.png" alt="" />
			<div
				class="
					sm:inline-block sm:absolute sm:bottom-0 sm:absolute sm:bottom-0 sm:right-0 sm:p-6 sm:my-16 sm:w-96 sm:space-y-8
					absolute
					bottom-14
					right-0
					mr-4
					p-4
					border border-opacity-25 border-white
					rounded-lg
					sm:shadow-2xl
					red-bg-1
					w-3/5
					space-y-2
					shadow-2xl
				"
			>
				<div class="flex justify-between items-center">
					<div>
						<div class="sm:text-base opacity-70 text-xs">#511</div>
						<div class="sm:text-2xl font-bold text-lg">Super Mario</div>
					</div>
					<div
						class="
							sm:p-2 sm:w-14 sm:h-14
							w-8
							h-8
							p-1
							rounded-full
							flex
							items-center
							justify-center
							red-bg-2
							border border-opacity-25 border-white
						"
					>
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
				<div class="flex sm:space-x-2 sm:text-xl sm:font-semibold">
					<div
						class="
							sm:px-6 sm:py-3 sm:space-x-2
							px-2
							py-1
							space-x-1
							flex
							items-center
							rounded-full
							flex
							items-center
							justify-center
							red-bg-2
							border border-opacity-25 border-white
						"
					>
						<div>
							<svg xmlns="http://www.w3.org/2000/svg" class="sm:h-6 sm:w-6 h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									stroke-width="2"
									d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
								/>
							</svg>
						</div>
						<div class="text-xs">525K USD</div>
					</div>
					<div
						class="
							sm:px-6 sm:py-2 sm:space-x-2
							px-2
							py-1
							space-x-1
							flex
							items-center
							rounded-full
							flex
							items-center
							justify-center
							red-bg-2
							border border-opacity-25 border-white
						"
					>
						<div>
							<svg xmlns="http://www.w3.org/2000/svg" class="sm:h-6 sm:w-6 h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									stroke-width="2"
									d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4m0 5c0 2.21-3.582 4-8 4s-8-1.79-8-4"
								/>
							</svg>
						</div>
						<div class="text-xs">845K</div>
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
@media (min-width: 640px) {
	.sm\:w-100 {
		width: 32rem;
	}
}
.red-bg-1 {
	background-color: #e75353;
}
.red-bg-2 {
	background-color: #c93535;
}
.h-100 {
	height: 35rem;
}
</style>