<script>
export let data

</script>

<p class="font-bold text-center"> {data.content} </p>

<script lang="ts">
    export let data;
</script>

<div>
  {#each data.cart as { id, quantity } (id)}
    <div>{id} - {quantity}</div>
  {/each}
</div>