<template>
	<div class="red-bg">
		<div class="container mx-auto flex p-4 sm:py-12 sm:flex-row flex-col space-y-4 sm:space-y-0">
			<div class="flex flex-col justify-center items-center space-y-3 sm:items-start sm:space-y-6">
				<div class="text-4xl uppercase font-bold">Mario</div>
				<div class="w-80 text-center sm:text-left sm:text-base text-sm">Team up for a paws-itively adorable adventure and Unique NFT Collectibles Game for Mario lovers!</div>
				<div>
					<ul class="flex space-x-4">
						<li>
							<img
								src="icons/wfacebook.png"
								class="w-10 h-10 rounded-lg border border-opacity-25 border-white red-bg-1 p-2"
								alt="facebook"
							/>
						</li>
						<li>
							<img
								src="icons/wtwitter.png"
								class="w-10 h-10 rounded-lg border border-opacity-25 border-white red-bg-1 p-2"
								alt="twitter"
							/>
						</li>
						<li>
							<img
								src="icons/wtelegram.png"
								class="w-10 h-10 rounded-lg border border-opacity-25 border-white red-bg-1 p-2"
								alt="telegram"
							/>
						</li>
						<li>
							<img
								src="icons/wyoutube.png"
								class="w-10 h-10 rounded-lg border border-opacity-25 border-white red-bg-1 p-2"
								alt="youtube"
							/>
						</li>
					</ul>
				</div>
			</div>
			<div class="w-96"></div>
			<div class="w-full flex">
				<div class="w-1/3 sm:space-y-4 space-y-4">
					<div class="font-bold sm:text-xl">Navigation</div>
					<ul class="sm:space-y-2 space-y-1 sm:text-base text-xs">
						<li class="opacity-60">Home</li>
                        <li class="opacity-60">Features</li>
                        <li class="opacity-60">Ecosystem</li>
					</ul>
				</div>
                <div class="w-1/3 space-y-4">
					<div class="font-bold sm:text-xl">Invest</div>
					<ul class="space-y-2 sm:text-base text-xs">
						<li class="opacity-60">Token Presale</li>
                        <li class="opacity-60">Get NFT</li>
					</ul>
				</div>
                <div class="w-1/3 space-y-4">
					<div class="font-bold sm:text-xl">Docs</div>
					<ul class="space-y-2 sm:text-base text-xs">
						<li class="opacity-60">Smart Observer Audit</li>
                        <li class="opacity-60">Whitepaper</li>
					</ul>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style scoped>
.red-bg {
	background-color: #b22727;
}
.red-bg-1 {
	background-color: #c93535;
}
.container {
	max-width: 70rem;
}
</style>