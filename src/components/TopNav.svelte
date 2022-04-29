<script lang="ts">
  import NavLink from "@components/NavLink.svelte";
</script>

<div class="flex justify-between py-10 px-20 text-white">
  <h1 class="font-extrabold text-white">Zac Crumpton</h1>
  <div class="flex gap-10">
    <NavLink path="/" name="Home" />
    <NavLink path="/projects" name="Projects" />
    <NavLink path="/blog" name="Blog" />
    <NavLink path="/contact" name="Contact" />
  </div>
</div>
