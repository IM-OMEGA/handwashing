<script>
  import ProgressBar from "./ProgressBar.svelte";
</script>

<div bp="grid">
  <h2>seconds left:</h2>
</div>
<ProgressBar />

<button class="start">start</button>

<style>
  .start {
    height: 40px;
    width: 150px;
    background-color: red;
  }
</style>
