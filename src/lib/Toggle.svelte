<script lang="ts">
  import { onMount } from "svelte";

  import Fa from "svelte-fa";
  import {
    faSun,
    faMoon
  } from "@fortawesome/free-solid-svg-icons";

  import { themeChange } from "theme-change";

  let mode = "synthwave";

  onMount(() => {
    themeChange(false);
  });
</script>

<button 
  data-toggle-theme="synthwave,light"
  on:click={() => mode = mode === "synthwave" ? "light" : "synthwave"}
  class="p-1 fixed">
  {#if mode === "synthwave"}
    <Fa icon={faSun}/>
  {:else}
    <Fa icon={faMoon}/>
  {/if}
</button>