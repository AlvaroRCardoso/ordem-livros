<script>
  import series from "../constants/series";
  import ItemSerie from "../components/serie/ItemSerie.svelte";
</script>

<div class="flex flex-col gap-5">
  {#each series as serie}
    <ItemSerie {serie} />
  {/each}
</div>
