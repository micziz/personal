<script lang="ts">
    import Bulma from '../frameworks/Bulma.svelte';
    import NodeJs from '../frameworks/NodeJs.svelte';
    import Svelte from '../frameworks/Svelte.svelte';
  import Ts from '../languages/Ts.svelte';
</script>

<h1 class="title is-3">HufferPuff</h1>

<p>Link: <a href="https://huff.micziz.dev">here</a></p>

<p id="p">Made with:</p>
<div>
    <Ts/>
    <div style="margin-right: 2rem;"></div>
    <Svelte/>
    <div style="margin-right: 2rem;"></div>
    <NodeJs/>
    <div style="margin-right: 2rem;"></div>
    <Bulma/>
    <div style="margin-right: 2rem;"></div>
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