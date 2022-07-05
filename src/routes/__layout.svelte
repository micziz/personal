<style>
    #nav{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        margin-top: 20px;
        margin-bottom: 20px;
    }

    #navElement{
        margin-left: 20px;
    }
</style>


<div id="nav">
    <a href="/" id="navElement" class="button is-large is-rounded is-black is-outlined">Home</a>
    <a href="" id="navElement" class="button is-large is-rounded is-black is-outlined">Portfolio</a>
    <a href="" id="navElement" class="button is-large is-rounded is-black is-outlined">Blog</a>
    <a href="/contact" id="navElement" class="button is-large is-rounded is-black is-outlined">Contact</a>
</div>


<slot></slot>