<script>
    let {data} = $props();
</script>

<h2>My Blog Contents Page</h2>

<nav>
    {#each data.posts as post}
        <a href="/blog/{post.id}">{post.title}</a>
    {/each}
</nav>

<nav>
	<a href="/blog/bananas">Bananas</a>
    <a href="/blog/web-is-cool">Web is Cool</a>
    <a href="/blog/eight">Eight</a>
    <a href="/blog/ideas-are-hard">Ideas are Hard</a>
</nav>

<style>
    nav {
        display: flex;
        flex-direction: column;
    }
</style>