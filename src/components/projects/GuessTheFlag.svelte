<script lang="ts">
    import Ts from '../languages/Ts.svelte'
    import Svelte from '../frameworks/Svelte.svelte';
    import Bulma from '../frameworks/Bulma.svelte';
</script>

<h1 class="title is-3">Guess the flag</h1>

<p>Link: <a href="https://gtf.micziz.dev">here</a></p>

<p id="p">Made with:</p>
<div>
    <Ts/>
    <div style="margin-right: 2rem;"></div>
    <Svelte/>
    <div style="margin-right: 2rem;"></div>
    <Bulma/>
</div>

<style>
    div{
        display: flex;
        justify-content: center;
        align-items: center;
    }

    h1{
        text-align: center;
    }
    p{
        text-align: center;
    }
    #p{
        text-align: center;
        margin-bottom: 1rem;
    }
</style>