<script>
    import Header from '../components/Header.svelte';
    import Main from '../components/Main.svelte';
    import TimeLine from '../components/TimeLine.svelte';
    import Slidebar from '../components/Slidebar.svelte';

</script>


<style>
    :global(body) {
        background-color: #676778;
        color: white;
    }

</style>

<Header />
<Main >
    <TimeLine />
    <Slidebar />
</Main>
