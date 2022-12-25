<script lang="ts">
	import Rollup from './../other-tools/Rollup.svelte';
    import NodeJs from '../frameworks/NodeJs.svelte';
    import Ts from '../languages/Ts.svelte'
</script>

<h1 class="title is-3">Make a License</h1>

<p>Link: <a href="https://github.com/micziz/make-a-licensed">here</a></p>

<p id="p">Made with:</p>
<div>
    <Ts/>
    <div style="margin-right: 2rem;"></div>
    <NodeJs/>
    <div style="margin-right: 2rem;"></div>
    <Rollup/>
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