<script>
    import Nav from "../lib/components/nav.svelte";
</script>

<main>
    <header>
        <h1>Il mio portfolio di educazione civica</h1>
    </header>

    <Nav />
    <div class="container">
        <div class="right">
            <h2>
                Ciao, sono Alessandro Scattaglia della 5° informatica. Sono nato
                il 19 ottobre 2005 a Savigliano (CN) e frequento l'<a
                    href="https://agnelli.it/"
                    target="_blank">Istituto Internazionale Edoardo Agnelli</a
                >. Questo è il mio portfolio su tutti gli argomenti che abbiamo
                trattato durante i 5 anni qui. Il sito verrà aggiornato per aggiungere nuovi contenuti trattati in classe per ogni anno.
            </h2>
            <br />
            <h2>
                Qui sotto è possibile vedere tutto il codice per fare questo
                portfolio.
            </h2>

            <div class="center">
                <center>
                    <a
                        href="https://github.com/Alessandro-Scattaglia/Portfolio_svelte"
                        target="_blank"
                    >
                        <img
                            class="img0"
                            src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"
                            alt="GitHub Logo"
                        />
                    </a>
                </center>
            </div>
        </div>
        <div class="center" />
        <div class="left">
            <div class="video">
                <iframe
                    class="video1"
                    width="560"
                    height="315"
                    src="https://www.youtube.com/embed/ulUgpQHHkRo"
                    title="YouTube video player"
                    frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                    allowfullscreen
                />
            </div>
            <br /><br />
            <h2>
                Spero che questo sito possa essere un'utile risorsa per voi che
                lo state guardando.
            </h2>
        </div>
    </div>
    <br /><br />
    <footer>
        <h4>Copyright &copy; Alessandro Scattaglia</h4>
    </footer>
</main>

<style>
    :root {
        background-color: #207cca;
    }

    main {
        font-family: "Arial", sans-serif;
        max-width: 1000px;
        padding: 15px;
        background-color: #fff;
        border-radius: 40px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        margin: 60px auto;
    }

    header {
        text-align: center;
        font-size: 24px;
        color: #333;
        margin-bottom: 20px;
    }
    ::selection {
        background-color: rgb(10, 226, 10);
        color: white;
    }

    h1 {
        text-align: center;
        font-size: 70px;
        text-shadow: 2px 2px 4px black;
        font-weight: bold;
    }

    footer {
        text-align: center;
        color: #777;
        margin-top: 20px;
    }
    .img0 {
        width: 140px;
        margin-left: 600px;
        margin-bottom: -200px;
    }

    .video1 {
        border-radius: 15px;
    }
</style>
