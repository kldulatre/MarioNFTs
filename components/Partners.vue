<template>
	<div class="flex flex-col items-center sm:space-y-8 space-y-4">
		<Header :data="'Our Partners'"></Header>
		<div class="text-xl">Everyone is in love with Mario</div>
		<div class="grid grid-cols-3 sm:gap-12 gap-4 sm:pt-4 p-2">
			<div class="flex justify-center items-center justify-center opacity-50 hover:opacity-100"><img src="logos/xbox.png" alt=""></div>
            <div class="flex justify-center items-center justify-center opacity-50 hover:opacity-100"><img src="logos/nintendo.png" alt=""></div>
            <div class="flex justify-center items-center justify-center opacity-50 hover:opacity-100"><img src="logos/steam.png" alt=""></div>
            <div class="flex justify-center items-center justify-center opacity-50 hover:opacity-100"><img src="logos/tesla.png" alt=""></div>
            <div class="flex justify-center items-center justify-center opacity-50 hover:opacity-100"><img src="logos/adidas.png" alt=""></div>
            <div class="flex justify-center items-center justify-center opacity-50 hover:opacity-100"><img src="logos/facebook.png" alt=""></div>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
</style>