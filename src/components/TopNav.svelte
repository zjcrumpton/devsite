<script lang="ts">
  import NavLink from "@components/NavLink.svelte";
  import Hamsa from "@components/Hamsa.svelte";
</script>

<div class="flex justify-between py-10 px-20 text-white text-lg">
  <div class="font-extrabold text-white text-2xl cursor-pointer">
    <a href="/" class="flex gap-1.5 items-center">
      <span class="mr-2"><Hamsa/></span><span>Zac</span><span>Crumpton</span>
    </a>
  </div>
  <div class="flex gap-10">
    <NavLink path="/" name="Home" />
    <NavLink path="/projects" name="Projects" />
    <NavLink path="/blog" name="Blog" />
    <NavLink path="/contact" name="Contact" />
  </div>
</div>
