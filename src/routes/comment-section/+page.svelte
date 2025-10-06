<script>
    import Comment from '$lib/components/Comment.svelte'
    let { data } = $props();
    console.log(data);
</script>

{#each data.comments as comment}
    <Comment data={comment} />
{/each}