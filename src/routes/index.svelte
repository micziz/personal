<script>
	import Contact from './_componenets/contact.svelte';
    import Avatar from "./_componenets/avatar.svelte";
	import Projects from './_componenets/projects.svelte';
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=VT323&display=swap');
    @import "https://cdn.jsdelivr.net/npm/bulma@0.9.4/css/bulma.min.css";

    #title{
        text-align: center;
        font-family: 'VT323', monospace;
        margin-top: 30px;      
    }
</style>

<head>
    <title>Micziz Website</title>
</head>

<h1 id="title" class="title is-1">Hi! Im micziz! Welcome to my website!</h1>

<Avatar/>

<Projects/>

<Contact/>