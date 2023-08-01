<script lang="ts">
  import BarChartRace from "./components/BarChartRace.svelte";

  const datasetUrl = "/data/frontend-libraries-frameworks.csv";
  const maxBars = 6;
</script>

<main>
  <BarChartRace {datasetUrl} {maxBars} />
</main>

<style>
  main {
    font-family: "Helvetica";
    display: flex;
    justify-content: center;
  }
</style>
