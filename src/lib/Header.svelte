<script lang="ts">
  import Settings from "$lib/Settings.svelte";
</script>

<header class="flex mb-4 uppercase items-center">
  <div class="flex flex-1 items-center space-x-1">
    <img src="/logo.svg" alt="FLC" class="w-8 h-8" />
    <h1 class="text-orange-600 font-extrabold text-3xl">FLC</h1>
  </div>
  <div>
    <Settings />
  </div>
</header>
