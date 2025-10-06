<script>
    let { data } = $props();
</script>

<section>
    <h3>{data.title}</h3>
    <p>{data.body}</p>
</section>

<style>
section {
        border: 1px sold #ccc;
        background-color: #eee;
        border-radius: 0.8em;
        padding: 1em;
        margin-bottom: 1em;
    }
</style>
    