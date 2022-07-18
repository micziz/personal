<script lang="ts">
    let temperature: number;
    let fTemperature: number = 0;

    function changeTemperature(){
        let fT = (temperature - 32) * 5 / 9;
        return fT
    }
    function change(){
        fTemperature = changeTemperature();
    }
</script>

<style>
    h1{
        text-align: center;
        font-family: 'VT323', monospace;
    }

    #form{
        text-align: center;
    }

    #btnsub{
        margin-top: 20px;
        margin-bottom: 20px;
        font-family: 'VT323', monospace;
    }

    p{
        text-align: center;
        font-family: 'VT323', monospace;
    }

    a{
        font-family: 'VT323', monospace;
    }

    #btn{
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>

<h1 class="title is-2">Temperature Convertor (Fahrenheit to Celsius)</h1>

<div id="form">
    <form action="" on:submit|preventDefault={change}>
        <input type="text" bind:value={temperature} class="input" id="inp">
        <input type="submit" value="Submit" class="button is-large is-rounded is-black is-outlined" id="btnsub">
    </form>
</div>

<p>{fTemperature}</p>

<div id="btn">
    <a href="/projects/tpcv/celcius" class="button is-large is-rounded is-black is-outlined">Celsius</a>
</div>

