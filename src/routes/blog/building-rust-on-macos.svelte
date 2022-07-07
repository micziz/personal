<style>
    @import url('https://fonts.googleapis.com/css2?family=VT323&display=swap');
    @import "https://cdn.jsdelivr.net/npm/bulma@0.9.4/css/bulma.min.css";

    h1{
        font-family: 'VT323', monospace;
        text-align: center;
    }

    h3{
        margin-top: 15px;
        font-family: 'VT323', monospace;
        text-align: center;
    }

    p{
        font-family: 'VT323', monospace;
        text-align: center;
    }

    li{
        font-family: 'VT323', monospace;
        text-align: center;
    }

    #code{
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 20px;
    }

    #conclusion{
        margin-bottom: 50px;
    }
</style>

<h1 class="title is-1">Building Rust on macos</h1>

<p>Rust can be installed in many ways. The preferd way is to install it with <a href="https://rustup.rs">rustup</a></p>

<div id="code">
    <img src="/blog/brom/img-1.svg" alt="img-1" width="1000px" height="1000px">
    <code>curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh</code>
</div>

<p>But today, i'm going to tell you how to install rust from source on macos!</p>

<h3 class="title is-3">0-Requirements</h3>

<ul>
    <li> - Internet</li>
    <li> - A terminal</li>
    <li><a href="https://brew.sh"> - Homebrew</a></li>
</ul>

<h3 class="title is-3">1-Dependencies</h3>

<p>Let's install the required dependencies</p>


