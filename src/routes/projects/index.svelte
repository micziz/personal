<style>
    h1{
        text-align: center;
        margin-bottom: 30px;
    }

    #projects{
        text-align: center;
        font-size: 30px;
        font-family: 'VT323', monospace;
    }

    #btn-projects{
        margin-bottom: 15px;
    }
</style>

<script>
    let projects = [
        { id: "rplg", name: "random programming language generator"},
    ]
</script>

<h1 class="title is-2">Some web projects i have made!</h1>

<div id="projects">
    <ul>
        {#each projects as project}
            <li><a target="_blank" href="projects/{project.id}" id="btn-projects" class="button is-large is-rounded is-black is-outlined">
                {project.name}
            </a></li>
        {/each}
    </ul>
</div>  