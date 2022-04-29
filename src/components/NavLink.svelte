<script lang="ts">
  import { page } from '$app/stores';

  export let path: string;
  export let name: string;


</script>

<div class="text-white">
  <a 
    class="font-bold"
    href={path}
    class:active={path === $page.url.pathname}
  >
    {name}
  </a>
</div>

<style>
  .active {
    @apply text-primary;
  }
</style>