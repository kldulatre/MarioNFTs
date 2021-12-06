<template>
	<div class="relative mt-40">
		<div class="z-1 w-full bg-green-100 background"></div>
		<div class="z-10 absolute bottom-0 w-full">
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
</template>

<script>
export default {};
</script>

<style scoped>
.container {
	max-width: 70rem;
}
.background{
	height: 23rem;
	background-color: #c93535;
}
</style>