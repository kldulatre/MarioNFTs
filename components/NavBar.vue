<template>
	<div class="flex justify-between py-8 items-end">
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
</template>

<style scoped>
.yellow {
    background-color: #ffb400;
}
</style>