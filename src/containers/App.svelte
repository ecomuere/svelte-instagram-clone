<script>
    import Header from "../components/Header.svelte"
    import Main from "../components/Main.svelte"
    import TimeLine from "../components/TimeLine"
    import SideBar from "../components/SideBar"
</script>

<style>
    @import url('https://fonts.googleapis.com/css?family=Lato|Pacifico&display=swap');

    :global(body) {
        color: rgba(38, 38, 38, 0.7);
        background: #fafafa;
        font-family: "Lato", sans-serif;
        margin: 0px;
        padding: 0px;
    }
    :global(h1,h2,h3) {
        margin: 0px;
        padding: 0px;
    }
</style>

<Header />
<Main>
    <TimeLine />
    <SideBar />
</Main>