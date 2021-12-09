<template>
	<div class="card-panel border border-white border-opacity-50 p-4 mx-2 mb-10 rounded-2xl relative background sm:h-30 h-96 overflow-hidden">
		<div class="rounded-full border border-white flex-0 absolute top-0 left-0 m-4 sm:py-2 py-1 sm:px-3 px-2 sm:text-sm text-xs highlight">Legendary</div>
		<img class="sm:w-96 w-60 sm:h-96 h-60 contain" src="marios/Dr_Mario_DMW.png" alt="" />
		<div class="w-full absolute bottom-0 left-0 highlight p-4 space-y-4">
			<div class="flex justify-between">
				<div>
					<div class="text-sm opacity-60">#101</div>
					<div class="font-bold">Get Mario</div>
				</div>
				<div class="flex flex-col items-end">
					<div class="text-sm opacity-60">Supply</div>
					<div class="font-bold">20</div>
				</div>
			</div>
			<div class="flex justify-between">
				<div class="flex space-x-2">
					<div
						class="
							sm:px-4
							sm:py-1
							sm:space-x-2
							px-2
							py-1
							space-x-1
							background
							flex
							items-center
							rounded-full
							flex
							items-center
							justify-center
							border border-opacity-25 border-white
							text-sm
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
						<div>525K USD</div>
					</div>
					<div
						class="
							sm:px-4
							sm:py-1
							sm:space-x-2
							px-2
							py-1
							space-x-1
							background
							flex
							items-center
							rounded-full
							flex
							items-center
							justify-center
							border border-opacity-25 border-white
							text-sm
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
						<div class="text-sm">845K</div>
					</div>
				</div>
				<div>
					<div class="sm:p-2 sm:w-10 sm:h-10 h-8 w-8 rounded-full flex items-center justify-center background border border-opacity-25 border-white">
						<svg xmlns="http://www.w3.org/2000/svg" class="sm:h-6 sm:w-6 h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"
							/>
						</svg>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style scoped>
.cardwidth {
	width: 50rem;
}
.background {
	background-color: #e75353;
}
.highlight {
	background-color: #c93535;
}
@media (min-width: 640px) {
	.sm\:h-30 {
		height: 30rem;
	}
}
</style>