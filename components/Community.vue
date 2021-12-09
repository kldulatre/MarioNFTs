<template>
	<div>
		<div class="hidden sm:block relative mt-40">
			<div class="hidden sm:block z-1 w-full background"></div>
			<div class="hidden sm:block z-10 absolute bottom-0 w-full">
				<div class="container mx-auto m-12">
					<div class="flex items-end">
						<img class="w-1/2 object-contain h-96" src="images/community.png" alt="community" />
						<div class="w-1/2 flex-1 m-8 space-y-6">
							<Header :data="'Join Our Community'" />
							<SubBody :data="'Be part of our data amazing community and stay tuned for the news.'" />
							<YellowButton :data="'Join us'" />
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="sm:hidden background2 flex flex-col items-center space-y-4 py-8 px-8 mt-16">
			<Header class="text-center" :data="'Join Our Community'" />
			<img class="object-contain h-60" src="images/community.png" alt="community" />
			<SubBody class="text-center" :data="'Be part of our data amazing community and stay tuned for the news.'" />
			<YellowButton :data="'Join us'" />
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
	max-width: 70rem;
}
.background {
	height: 23rem;
	background-color: #c93535;
}
.background2 {
	background-color: #c93535;
}
</style>