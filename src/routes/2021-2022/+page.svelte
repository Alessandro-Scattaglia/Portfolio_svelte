<script>
    import Nav from "../../lib/components/nav.svelte";
  
</script>

<main>
    <header>
        <h1>2021-2022</h1>
    </header>

    <Nav />
    <div class="centro">
        <h2>LETTERE ITALIANE</h2>
        <p>
            Quest'anno, durante il corso di lettere italiane, abbiamo affrontato
            due temi di grande interesse: l'emancipazione femminile e la mafia.
            Abbiamo approfondito il tema della mafia, concentrandoci in
            particolare su due tragiche stragi che hanno profondamente scosso
            l'Italia: quella di Capaci, che ha portato alla morte del giudice <a
                href="https://it.wikipedia.org/wiki/Giovanni_Falcone"
                target="_blank">Giovanni Falcone</a
            >, e quella in via D'Amelio, che ha causato la scomparsa di
            <a
                href="https://it.wikipedia.org/wiki/Paolo_Borsellino"
                target="_blank">Paolo Borsellino</a
            >.<br /> <br />La nostra scuola, l'Istituto Edoardo Agnelli, ci ha
            offerto l'opportunità unica di intervistare Salvatore Borsellino, il
            fratello di uno dei due coraggiosi magistrati che hanno perso la
            vita nella lotta contro la mafia. L'intervista si è svolta il 5
            maggio 2022, e ha rappresentato un momento straordinario in cui
            abbiamo potuto approfondire la conoscenza di queste tragiche vicende
            e delle loro implicazioni per la società italiana.
        </p>
        <div class="container">
            <div>
                <iframe
                    width="560"
                    height="315"
                    src="https://www.youtube.com/embed/b3_VRm8kE8E?si=7nkXcmKplY0YA2aE"
                    title="YouTube video player"
                    frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                    allowfullscreen
                />
            </div>

            <p class="p1">Ecco a voi l'intervista a Salvatore Borsellino</p>
        </div>

        <p>
            Nell'ambito dell'emancipazione femminile, abbiamo esaminato
            attentamente il ruolo cruciale del movimento per i diritti delle
            donne e la promulgazione del "Codice Rosso". Questo codice
            rappresenta un importante passo avanti nella tutela dei diritti
            delle donne in Italia, focalizzandosi sulla prevenzione e la lotta
            contro la violenza di genere.
        </p>
        <div class="immg1">
            <img class="img1" src="/Portfolio_svelte/immagini/donna.jpg" alt="donna.jpg" />
        </div>
        <p>
            Abbiamo discusso approfonditamente delle implicazioni di questo
            strumento legislativo e del suo impatto nella società italiana,
            sottolineando come esso sia parte integrante del percorso verso una
            maggiore parità di genere e l'emancipazione delle donne. L'analisi
            di queste tematiche ci ha offerto una prospettiva più ampia sulla
            lotta per i diritti delle donne e sulle sfide ancora presenti nella
            ricerca dell'uguaglianza di genere.
            
        </p>
        <h2>INFORMATICA</h2>
        <p>
            Quest'anno, durante il corso di informatica, abbiamo affrontato il
            tema della sicurezza informatica e abbiamo realizzato un sito web o
            una presentazione per approfondirlo. Qui sotto vi lascio la mia
            presentazione.
        </p>
        <iframe
            src="https://docs.google.com/presentation/d/e/2PACX-1vTDiM9f9rXOQ_yU0bg8TFyXcMfBzSt_1SHWrtezMTm81oCU0enZXnxdztsIkyx-whT4UCE25P9__Gq0/embed?start=true&loop=true&delayms=2000"
            title="Presentazione Google"
            frameborder="0"
            width="100%"
            height="569"
            allowfullscreen="true"
            mozallowfullscreen="true"
            webkitallowfullscreen="true"
        />
    </div>

    <footer>
        <h4>Copyright &copy; Alessandro Scattaglia</h4>
    </footer>
</main>

<style>
    :root {
        background-color: #207cca;
    }
    ::selection {
    background-color: rgb(10, 226, 10); 
      color: white; 
    }
    a {
        text-decoration: none;
        color: #007bff;
        cursor: pointer;
    }
    a:hover {
        text-decoration: underline;
    }

    main {
        font-family: "Arial", sans-serif;
        max-width: 1000px;
        margin: 60px auto;
        padding: 15px;
        background-color: #fff;
        border-radius: 40px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    header {
        text-align: center;
        font-size: 24px;
        color: #333;
        margin-bottom: 20px;
    }
    h1 {
        text-align: center;
        font-size: 70px;
        text-shadow: 2px 2px 4px black;
        font-weight: bold;
    }

    .centro {
        margin: auto;
        width: 100%;

        border-radius: 4px;
    }

    h2 {
        padding: 10px;
        font-size: xx-large;
        color: rgb(10, 226, 10);
        text-align: center;
    }

    p {
        padding-top: 0;
        padding: 15px;
        text-align: justify;
        font-size: x-large;
    }

    .immg1 {
        text-align: center;
    }

    .img1 {
        border-radius: 20px;
        width: 70%;
        height: 70%;
    }

    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    footer {
        text-align: center;
        color: #777;
        margin-top: 20px;
    }
</style>
