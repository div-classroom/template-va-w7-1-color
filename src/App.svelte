<script>
	import StockLineChart from "./components/StockLineChart.svelte"
	import PopulationMap from "./components/PopulationMap.svelte"	
</script>
	
<div id="container">
	<StockLineChart />
	<PopulationMap />
</div>
	
<style>
	#container {
		display: flex;
	}
</style>