<script>
    import Post from "$lib/components/Post.svelte";
    let posts = [
    {
        username: "sunny_vibes",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-01",
        postText: "Loving the spring weather! 🌸☀️",
        likes: 120
    },
    {
        username: "tech_guru",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-02",
        postText: "Just built my first AI chatbot. Excited to see where this goes!",
        likes: 89
    },
    {
        username: "foodie_queen",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-03",
        postText: "Brunch at Café Bloom was divine 😍🥐",
        likes: 230
    },
    {
        username: "wanderlust_jake",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-04",
        postText: "Exploring the mountains of New Zealand. Nature is healing 🌿",
        likes: 310
    },
    {
        username: "gamerzone",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-05",
        postText: "Levelled up in Elden Ring today 💀🔥",
        likes: 150
    },
    {
        username: "artsy_amy",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-06",
        postText: "Finished my latest watercolor piece. Thoughts? 🎨",
        likes: 175
    },
    {
        username: "fitness_freak",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-07",
        postText: "Crushed my morning workout 💪 #NoExcuses",
        likes: 200
    },
    {
        username: "bookworm_ben",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-07",
        postText: "Just finished reading 'Project Hail Mary'—what a ride! 📚🚀",
        likes: 95
    },
    {
        username: "style_savvy",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-06",
        postText: "Fall fashion is here 🍂👗",
        likes: 142
    },
    {
        username: "music_maniac",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-05",
        postText: "New track dropping this Friday 🎶🔥 Stay tuned!",
        likes: 260
    }
];
</script>

{#each posts as post}
    <Post postData={post} />
{/each}

<style>
    :global(body) {
        font-family: Verdana, Geneva, Tahoma, sans-serif;
    }
</style>