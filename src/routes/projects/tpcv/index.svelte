<script lang="ts">
    import { browser } from "$app/env";
</script>

<style>
    h1{
        font-family: 'VT323', monospace;
        text-align: center;
    }

    a{
        font-family: 'VT323', monospace;
        margin-right: 20px;
    }

    #a{
        display: flex;
        justify-content: center;
        align-items: center;
    }
    
    #b{
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 20px;
    }
</style>

<h1 class="title">Temperature Convertor</h1>

<div id="a">
    <a href="/projects/tpcv/celcius" class="button is-large is-rounded is-black is-outlined">Celsius to Fahrenheit</a>    
    <a href="/projects/tpcv/fahrenheit" class="button is-large is-rounded is-black is-outlined">Fahrenheit to Celsius</a>
</div>

<div id="b">
    <a href="https://github.com/micziz" class="button is-large is-rounded is-black is-outlined">More Temperature Convertor</a>
</div>

