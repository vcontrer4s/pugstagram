<script>
  import Profile from "./Profile.svelte";
  import Stories from "./Stories.svelte";
  import Footer from "./Footer.svelte";
</script>

<style>
  .Slidebar {
    position: relative;
    padding: 4.5em 0 0 0;
  }
  .Slidebar-container {
    position: fixed;
  }
</style>

<div class="Slidebar">
  <div class="Slidebar-container">
    <Profile />
    <Stories />
    <Footer />
  </div>
</div>
