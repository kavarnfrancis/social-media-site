<script>
    let { postData } = $props();
    console.log(postData);
</script>

<section>
<header>
    <img src="{postData.avatar}" alt="{postData.username}">
    <h3>{postData.username}</h3>
</header>
<main>
    <p>{postData.postText}</p>
</main>
<footer>
    <p><em>{postData.postDate}</em></p>
    <p><em>👍 {postData.likes}</em></p>
</footer>    
</section>

<style>
    p em {
        font-size: 0.9em;
    }
    section {
        border: 1px sold #ccc;
        background-color: #eee;
        border-radius: 0.8em;
        padding: 1em;
        margin-bottom: 1em;
    }
    header {
        display: flex;
    }
   img {
    max-width: 3rem;
    float: left;
    margin: 10px 15px 15px 10px;
   }
   h3 {
    margin-top: 1.5rem;
   }
   main {
    clear: left;
    margin-top: 1em;
   }
</style>