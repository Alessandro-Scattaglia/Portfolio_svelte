<script>
    import pietro from "../immagini/pietro.jpg";
    import covid from "../immagini/covid19.png";
    import Nav from "../../lib/components/nav.svelte";
    
</script>

<main>
    <header>
        <h1>2020-2021</h1>
    </header>

    <Nav />

    <div class="centro">
        <h2>LETTERE ITALIANE</h2>
        <p>
            Durante questa materia abbiamo affrontato approfonditamente il
            complesso tema della migrazione di persone provenienti dal Nord
            Africa verso il Sud Italia, con particolare attenzione a Lampedusa.
            Inoltre, abbiamo avuto l'opportunità di partecipare a un incontro
            con il dottor <a
                href="https://it.wikipedia.org/wiki/Pietro_Bartolo"
                target="_blank">Pietro Bartolo</a
            >, una figura di spicco nell'ambito dell'assistenza ai migranti e
            della promozione dei diritti umani.
        </p>

        <div class="immg1">
            <img
                class="img1"
                src={pietro}
                width="1800"
                height="1014"
                alt="pietro.jpg"
            />
        </div>
        <p>
            Inoltre, abbiamo avuto l'opportunità di leggere il libro "Le Stelle
            di Lampedusa" scritto dal dottor Pietro Bartolo, che ci ha offerto
            uno sguardo toccante sulle esperienze dei residenti e dei migranti
            sull'isola. Abbiamo anche avuto l'opportunità di vedere il film
            "Fuocoammare" di Gianfranco Rosi, un documentario che racconta la
            vita quotidiana a Lampedusa e il dramma delle migrazioni attraverso
            testimonianze e immagini potenti. Entrambi ci hanno profondamente
            sensibilizzato sulla complessità e l'umanità di questa situazione.
            <br /><br />
        </p>
        <div class="container">
            <iframe
                class="video1"
                width="440"
                height="340"
                src="https://www.youtube.com/embed/eHEZwiyect4"
                title="L'Agnelli incontra il dottor Pietro Bartolo"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                allowfullscreen
            />

            <p>Ecco a voi l'intervista a Pietro Bartolo il 18 novembre 2020</p>
        </div>
        <br />
        <h2>BIOLOGIA</h2>
        <p>
            Di biologia durante l'anno scolastico, abbiamo studiato
            approfonditamente il COVID-19, una malattia infettiva causata dal
            coronavirus SARS-CoV-2, che ha avuto un impatto significativo sulla
            salute globale, mettendo in evidenza l'importanza della ricerca
            scientifica, della prevenzione delle malattie e della collaborazione
            internazionale nella gestione delle pandemie.
        </p>
        <div class="immg2">
            <img class="img2" src={covid} alt="covid19.png" />
        </div>
        <p>
            Abbiamo esplorato i modi in cui il virus si diffonde, i sintomi
            associati e le strategie di prevenzione, compresi i vaccini, che
            sono stati sviluppati a una velocità straordinaria per combattere
            questa pandemia globale. La pandemia da COVID-19 è stata un esempio
            illuminante di come la biologia possa essere una disciplina vitale
            per comprendere e risolvere le sfide emergenti nella salute pubblica
            e nella medicina.
        </p>
        <h2>INFORMATICA</h2>
        <p>
            Quest'anno, nel corso delle lezioni di informatica, abbiamo avuto
            l'opportunità di creare il nostro portfolio utilizzando Google
            Sites. Attraverso questa piattaforma, abbiamo avuto modo di
            raccogliere e organizzare in modo completo tutti gli argomenti
            affrontati durante gli anni di studio di educazione civica.
        </p>
    </div>

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
    .video1 {
        border-radius: 15px;
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
    ::selection {
    background-color: rgb(10, 226, 10); 
      color: white; 
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

    .immg2 {
        text-align: center;
    }
    .img2 {
        width: 50%;
        height: 50%;
    }
    footer {
        text-align: center;
        color: #777;
        margin-top: 20px;
    }
</style>
