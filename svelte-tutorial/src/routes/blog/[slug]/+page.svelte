<script lang="ts">
    export let data;
</script>

<div>
  {#each data.names as { name }}
    <div class="font-bold">{name}</div>
  {/each}
</div>
