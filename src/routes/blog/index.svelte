<script>
    let blogPost = [
        {id: "the-revolution-of-vite", name: "The Revolution Of Vite"}
    ]
</script>


<style>
    @import url('https://fonts.googleapis.com/css2?family=VT323&display=swap');
    @import "https://cdn.jsdelivr.net/npm/bulma@0.9.4/css/bulma.min.css";

    h1{
        font-family: 'VT323', monospace;
        text-align: center;
    }

    p{
        font-family: 'VT323', monospace;
        text-align: center;
    }

    #projects{
        text-align: center;
        font-size: 30px;
        font-family: 'VT323', monospace;
    }

    #project-title{
        text-align: center;
        margin-top: 25px;
        margin-bottom: 25px;
        font-family: 'VT323', monospace;
    }
</style>

<h1 class="title is-1">Wlecome to my blog!</h1>

<p>I will post about things i like</p>

<p>These will mostly be releted to web development, but also other things...</p>

<p>Thanks for visiting!!!!</p>

<h2 class="title is-2" id="project-title">Recent Posts</h2>

<div id="projects">
    <ul>
        {#each blogPost as post}
            <li><a target="_blank" href="https://www.github.com/{post.id}" id="btn-projects" class="button is-large is-rounded is-black is-outlined">
                {post.name}
            </a></li>
        {/each}
    </ul>
</div>