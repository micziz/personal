<style>
    @import url('https://fonts.googleapis.com/css2?family=VT323&display=swap');
    @import "https://cdn.jsdelivr.net/npm/bulma@0.9.4/css/bulma.min.css";
    #nav{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        margin-top: 20px;
        margin-bottom: 20px;
        font-family: 'VT323', monospace;
    }

    #navElement{
        margin-left: 20px;
    }
</style>


<div id="nav">
    <a href="/" id="navElement" class="button is-large is-rounded is-black is-outlined">Home</a>
    <a href="" id="navElement" class="button is-large is-rounded is-black is-outlined">Portfolio</a>
    <a href="about" id="navElement" class="button is-large is-rounded is-black is-outlined">About Me</a>
    <a href="/posts" id="navElement" class="button is-large is-rounded is-black is-outlined">Blog</a>
    <a href="/contact" id="navElement" class="button is-large is-rounded is-black is-outlined">Contact</a>
</div>


<slot></slot>