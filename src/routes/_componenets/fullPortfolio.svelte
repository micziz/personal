<style>
    @import url('https://fonts.googleapis.com/css2?family=VT323&display=swap');
    @import "https://cdn.jsdelivr.net/npm/bulma@0.9.4/css/bulma.min.css";

    #projects{
        text-align: center;
        font-size: 30px;
        font-family: 'VT323', monospace;
    }

    #project-title{
        text-align: center;
        margin-top: 50px;
        margin-bottom: 50px;
        font-family: 'VT323', monospace;
    }

    #contributions{
        text-align: center;
        font-size: 30px;
        font-family: 'VT323', monospace;
    }

    #btn-projects{
        margin-bottom: 15px;
    }

    #btn-contributions{
        margin-bottom: 15px;
    }
</style>

<script lang="ts">
    let projects = [
        { id: "PassMax/PassMax", name: "PassMax"},
        { id: "micziz/SimXV2", name: "SimXV2"},
        { id: "micziz/rplg", name: "RPLG"},
    ]

    let contributions = [
        { id: "ThioJoe/YT-Spammer-Purge", name: "YT-Spammer-Purge"},
        { id: "elebumm/RedditVideoMakerBot", name: "RedditVideoMakerBot"},
    ]
</script>

<h1 class="title is-2" id="project-title">Here are a couple of projects i made!</h1>

<div id="projects">
    <ul>
        {#each projects as project}
            <li><a target="_blank" href="https://www.github.com/{project.id}" id="btn-projects" class="button is-large is-rounded is-black is-outlined">
                {project.name}
            </a></li>
        {/each}
    </ul>
</div>  


<h1 class="title is-2" id="project-title">I also contributed to some other projects</h1>

<div id="contributions">
    <ul>
        {#each contributions as contribution}
            <li><a target="_blank" href="https://www.github.com/{contribution.id}" id="btn-contributions" class="button is-large is-rounded is-black is-outlined">
                {contribution.name}
            </a></li>
        {/each}
    </ul>
</div>

