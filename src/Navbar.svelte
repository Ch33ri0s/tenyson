<script context="module">
  const nav = [
    'Home',
    'Contact',
    'About'
  ]
</script>

<style>
.navbar {
  top: 0;
  left: 0;
  background: #121212;
  width: 100%;
  height: 80px;
}
</style>

<div class="navbar">
  {#each nav as item}
    <div>{item}</div>
  {/each}
</div>