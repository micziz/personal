<script lang="ts">
    let q1 = "<strong>What got you into programming?</strong>";
    let a1 = "Like a lot of other people, game developement was my first experience. I then expanded into other fields";
    let q2 = "<strong>What technologies are you currently using?</strong>";
    let a2 = "Mostly svelte and sveltekit (this site was created withe sveltekit). I am coding a <em>secret</em> project.\nFor css in complex projects i use tailwindcss with diasyui, but for simple projects (like this one) i use bulma css. Also i LOOOVE vite";
    let q3 = "<strong>Apart from web technologies, what other technologies are you currently using?</strong>";
    let a3 = "Mainly python and rust";
    let q4 = "<strong>What is  your setup?</strong>";
    let a4 = "M1 iMac, VSCode, Hyper (and iTerm 2, just in case), Firefox Developer Edition (css go brrrrrrrr) and pycharm (why). My terminal setup is: OMZ with Pure as my prompt and some other extensions";
</script>

<style>
    h1{
        text-align: center;
    }
    #qaa{
        text-align: center;
    }
</style>

<h1 class="title is-2">Hi! I'm micziz, a self taught and independent programmer!</h1>

<div id="qaa">
    <h2 class="title is-3">Q & A</h2>
    <p>{@html q1}</p>
    <p>{a1}</p>
    <p>{@html q2}</p>
    <p>{@html a2}</p>
    <p>{@html q3}</p>
    <p>{a3}</p>
    <p>{@html q4}</p>
    <p>{a4}</p>
</div>