<template>
	<div class="flex flex-col items-center space-y-8">
		<Header :data="'Super Mario'"></Header>
		<div>
			<ul class="flex space-x-4">
				<li class="py-2 px-6 border border-white border-opacity-50 rounded-full">All</li>
				<li class="py-2 px-6 border border-white border-opacity-50 rounded-full">Generic</li>
				<li class="py-2 px-6 border border-white border-opacity-50 rounded-full">Common</li>
				<li class="py-2 px-6 border border-white border-opacity-50 rounded-full text-blue-400">Uncommon</li>
				<li class="py-2 px-6 border border-white border-opacity-50 rounded-full text-blue-400">Rare</li>
				<li class="py-2 px-6 border border-white border-opacity-50 rounded-full text-yellow-300">Legendary</li>
			</ul>
		</div>
		<div class="container">
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
import "@egjs/vue-flicking/dist/flicking.css";
import "@egjs/flicking-plugins/dist/arrow.css";
import "@egjs/flicking-plugins/dist/pagination.css";

export default {
	components: {
		Flicking: Flicking,
	},
	data() {
		return {
			plugins: [new Fade(), new Arrow(), new Pagination({ type: "scroll"})],
		};
	},
};
</script>

<style scoped>
.container {
	max-width: 70rem;
}
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
</style>