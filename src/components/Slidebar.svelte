<script>
  import Profile from "./Profile.svelte";
  import Stories from "./Stories.svelte";
  import Footer from "./Footer.svelte";

  export let nickName;
  export let name;

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
    <Profile {nickName} {name} />
    <Stories />
    <Footer />
  </div>
</div>
