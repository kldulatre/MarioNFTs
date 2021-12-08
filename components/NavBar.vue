<template>
	<div>
		<div class="flex flex-row justify-between py-8 items-end hidden sm:flex">
			<div class="font-bold text-4xl">MARIO</div>
			<div>
				<ul class="flex flex-row space-x-8 uppercase">
					<li>Home</li>
					<li>Alpha</li>
					<li>Market</li>
					<li>Create</li>
					<li>About</li>
				</ul>
			</div>
			<YellowButton v-bind:data="'Open App'" />
		</div>
		<div class="flex flex-col items-center space-y-3 py-4 shadow-md border-b border-opacity-10 sm:hidden">
			<div class="font-bold text-4xl">MARIO</div>
			<div>
				<ul class="flex flex-row uppercase space-x-4 text-xs">
					<li>Home</li>
					<li>Alpha</li>
					<li>Market</li>
					<li>Create</li>
					<li>About</li>
					<li>Sign-Up</li>
				</ul>
			</div>
		</div>
	</div>
</template>

<style scoped>
.yellow {
	background-color: #ffb400;
}
</style>