<script>
    import CovidStat from "../components/CovidStat.svelte";
    import CovidChart from "../components/CovidChart.svelte";
    import TableContainer from "../components/TableContainer.svelte";
</script>

<svelte:head>
    <title>COVID 19 - US</title>
</svelte:head>

<div class="section header">
    <div class="container">
        <h1>COVID 19 - US</h1>
    </div>
</div>

<CovidStat />
<CovidChart />
<TableContainer />