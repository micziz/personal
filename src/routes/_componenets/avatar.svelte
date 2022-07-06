<script>
    function goToGihub(){
        window.location.href = "http://www.github.com/micziz"
    }
</script>

<style>
    img{
        border-radius: 50%;
    }

    #img{
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>

<div id="img">
    <img src="me.jpg" alt="my avatar" on:click={goToGihub} width="200" height="200">
</div>