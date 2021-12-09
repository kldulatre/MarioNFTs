<template>
	<div class="flex flex-col items-center sm:space-y-8 space-y-4">
		<Header :data="'Super Mario'"></Header>
		<div>
			<ul class="flex space-x-1 sm:space-x-4 flex-wrap justify-center px-8">
				<li class="sm:py-2 py-1 sm:px-6 px-4 mb-2 sm:text-base text-sm border border-white border-opacity-50 rounded-full">All</li>
				<li class="sm:py-2 py-1 sm:px-6 px-4 mb-2 sm:text-base text-sm border border-white border-opacity-50 rounded-full">Generic</li>
				<li class="sm:py-2 py-1 sm:px-6 px-4 mb-2 sm:text-base text-sm border border-white border-opacity-50 rounded-full">Common</li>
				<li class="sm:py-2 py-1 sm:px-6 px-4 mb-2 sm:text-base text-sm border border-white border-opacity-50 rounded-full text-blue-400">
					Uncommon
				</li>
				<li class="sm:py-2 py-1 sm:px-6 px-4 mb-2 sm:text-base text-sm border border-white border-opacity-50 rounded-full text-blue-400">Rare</li>
				<li class="sm:py-2 py-1 sm:px-6 px-4 mb-2 sm:text-base text-sm border border-white border-opacity-50 rounded-full text-yellow-300">
					Legendary
				</li>
			</ul>
		</div>
		<div class="w-full sm:container">
			<Flicking :options="{ align: 'center', circular: true }" :plugins="plugins">
				<NFTCard />
				<NFTCard />
				<NFTCard />
				<NFTCard />
				<NFTCard />
				<NFTCard />
				<NFTCard />
				<NFTCard />
				<NFTCard />
				<NFTCard />
				<NFTCard />
				<NFTCard />
				<span slot="viewport" class="flicking-arrow-next is-circle"></span>
				<span slot="viewport" class="flicking-arrow-prev is-circle"></span>
				<div slot="viewport" class="flicking-pagination bottomest"></div>
			</Flicking>
		</div>
	</div>
</template>

<script>
import { Flicking } from "@egjs/vue-flicking";
import { Fade, Arrow, Pagination } from "@egjs/flicking-plugins";
// import "@egjs/vue-flicking/dist/flicking.css";
// import "@egjs/flicking-plugins/dist/arrow.css";
// import "@egjs/flicking-plugins/dist/pagination.css";

export default {
	head: {
		link: [
			{
				rel: "stylesheet",
				href: "https://cdnjs.cloudflare.com/ajax/libs/egjs-flicking/4.4.1/flicking.css",
			},
			{
				rel: "stylesheet",
				href: "https://naver.github.io/egjs-flicking-plugins/release/latest/dist/flicking-plugins.css",
			},
		],
	},
	components: {
		Flicking: Flicking,
	},
	data() {
		return {
			plugins: [new Fade(), new Arrow(), new Pagination({ type: "scroll" })],
		};
	},
};
</script>

<style scoped>
.bottomest {
	bottom: 0px;
	z-index: 100;
}
.flicking-pagination-bullet {
	display: inline-block;
	width: 12px;
	height: 12px;
	margin: 0 4px;
	border-radius: 50%;
	background-color: rgb(10 10 10 / 10%);
	cursor: pointer;
	font-size: 10rem;
}
@media (min-width: 640px) {
	.sm\:container {
		max-width: 70rem;
	}
}
</style>