<script>
    function generate(){
        let languages = ["C", "C++", "Java", "Python", "JavaScript", "Objective-C", "Matlab", "Ruby", "Lua", "PHP", "Swift", "Go", "Perl", "R", "Scala", "Haskell", "Clojure", "ClojureScript", "Rust", "Dart", "Elixir", "Erlang", "F#", "Fortran", "Groovy", "Haskell", "Kotlin", "Lisp", "Lua", "OCaml", "Scheme", "Smalltalk", "TypeScript", "Visual Basic", "Cobol", "Prolog", "Ada", "Assembly", "C#", "D", "Go", "Java", "JavaScript", "Objective-C", "Matlab", "Ruby", "Lua", "PHP", "Swift", "Go", "Perl", "R", "Scala", "Haskell", "Clojure", "ClojureScript", "Rust", "Dart", "Elixir", "Erlang", "F#", "Fortran", "Groovy", "Haskell", "Kotlin", "Lisp", "Lua", "OCaml", "Scheme", "Smalltalk", "TypeScript", "Visual Basic", "Cobol", "Prolog", "Ada", "Assembly", "C#", "D", "Go", "Java", "JavaScript", "Objective-C", "Matlab", "Ruby", "Lua", "PHP", "Swift", "Go", "Perl", "R", "Scala", "Haskell", "Clojure", "ClojureScript", "Rust", "Dart", "Elixir", "Erlang", "F#", "Fortran", "Groovy", "Haskell", "Kotlin", "Lisp", "Lua", "OCaml", "Scheme", "Smalltalk", "TypeScript", "Visual Basic", "Cobol", "Prolog", "Ada", "Assembly", "C#", "D", "Go", "Java", "JavaScript", "Objective-C", "Matlab", "Ruby", "Lua", "PHP", "Swift", "Go", "Perl", "R", "Scala", "Haskell", "Clojure", "ClojureScript", "Rust", "Dart", "Elixir", "Erlang", "F#", "Fortran", "Groovy", "Haskell", "Kotlin", "Lisp", "Lua", "OCaml", "Scheme", "Smalltalk", "TypeScript", "Visual Basic", "Cobol", "Prolog", "Ada", "Assembly", "C#", "D", "Go", "Java", "JavaScript", "Objective-C", "Matlab", "Ruby", "Lua", "PHP", "Swift", "Go", "Perl", "R"];
        let language = languages[Math.floor(Math.random()*languages.length)];
        return language;
    }

    let lang = generate();

    function generateNew(){
        lang = generate();
    }
</script>

<style>
    h1 {
        font-family: 'VT323', monospace;
        text-align: center;
    }

    p {
        font-family: 'VT323', monospace;
        text-align: center;
    }

    #generate{
        margin-top: 25px;
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>

<h1 class="title is-2">Random Programming Language Generator</h1>

<p>Language = {lang}</p>

<div id="generate">
    <button on:click={generateNew}>Generate</button>
</div>