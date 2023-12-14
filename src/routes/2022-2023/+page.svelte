<script>
    import Nav from "../../lib/components/nav.svelte";
    import beccaria from "../immagini/beccaria.jpg";
    if (typeof window !== "undefined") {
        let prevScrollPos = window.pageYOffset;
        window.onscroll = function () {
            const currentScrollPos = window.pageYOffset;
            document.querySelector(".topnav").style.top =
                prevScrollPos > currentScrollPos ? "0" : "-70px";
            prevScrollPos = currentScrollPos;
        };
    }
</script>

<main>
    <header>
        <h1>2022-2023</h1>
    </header>

    <Nav />

    <div class="centro">
        <h2>LETTERE ITALIANE</h2>
        <p>
            La pena di morte è un argomento di grande rilevanza e dibattito in
            tutto il mondo, incluso l'Italia. Quest'anno, ci siamo concentrati
            principalmente sulla sua abolizione e sulle opinioni di Cesare
            Beccaria, un eminente giurista italiano del XVIII secolo noto per il
            suo influsso sulla filosofia del diritto penale.
        </p>
        <div class="immg1">
            <img class="img1" src={beccaria} alt="beccaria.jpg" />
        </div>
        <p>
            Cesare Beccaria è famoso per il suo libro "Dei delitti e delle
            pene", pubblicato nel 1764. In quest'opera, Beccaria ha condannato
            fortemente l'uso della pena di morte e ha avanzato argomentazioni
            contro di essa. Egli sosteneva che la pena di morte non fosse
            efficace come deterrente per i crimini e che rappresentasse una
            forma di tortura inutile e crudele. <br /><br />Beccaria ha anche
            sottolineato l'importanza della proporzionalità tra il crimine
            commesso e la pena inflitta, sostenendo che le pene dovrebbero
            essere determinate in modo razionale e non basate su vendetta o
            crudeltà. Le idee di Beccaria hanno influenzato significativamente
            la legislazione penale in molti paesi, compresa l'Italia, dove la
            pena di morte è stata abolita nel 1889.<br /><br />
            Ho anche fatto un tema riguardante la pena di morte durante quest'anno.
            Ecco a voi di seguito il tema.
        </p>
        <iframe
            title="presentazione1"
            src="https://docs.google.com/document/d/e/2PACX-1vSJfgu53E-QZ_zfQs1g7-_KVQ4h92qQYx0QXcTPMQElNV84TLyUKwQZF8-eIom3ejHP124riovYizT7/pub?embedded=true"
            width="100%"
            height="500px"
            style="border: none;"
        />
        <p>
            Inoltre, per lettere italiane, abbiamo scelto un personaggio legato
            alle "Agende rosse" o ad esse collegato, ed io ho optato per Padre
            Pino Puglisi. Successivamente, abbiamo preparato una presentazione
            da mostrare alla classe.
        </p>
        <iframe
            title="presentazione2"
            src="https://docs.google.com/presentation/d/e/2PACX-1vQ5Ff3OYdmy-UgyX9-bq4Mv3mx7Rc4APhFi1l5G0Mweho5c3W-dFwCAFgPPQQ7hCg/embed?start=true&loop=true&delayms=3000"
            frameborder="0"
            width="100%"
            height="569"
            allowfullscreen="true"
            mozallowfullscreen="true"
            webkitallowfullscreen="true"
        />
        <h2>INGLESE</h2>
        <p>
            Durante la materia di inglese di quest'anno, abbiamo realizzato
            delle presentazioni PowerPoint su argomenti a nostra scelta legati
            all'informatica. Ho scelto di parlare del Metaverso.<br />
            Ora vi presenterò il mio PowerPoint sul Metaverso che ho preparato.
            <br /><br /><br />
            <iframe
                title="presentazione3"
                src="https://docs.google.com/presentation/d/e/2PACX-1vQ58p0XMuVoi4tmcnpGMOfmbUyB-jLEPZEHCg1YrG1i2aUcSO7EYmmjdjRrfAgLiy0l1B1TwW07JNdO/embed?start=true&loop=true&delayms=3000"
                frameborder="0"
                width="100%"
                height="569px"
                allowfullscreen="true"
                mozallowfullscreen="true"
                webkitallowfullscreen="true"
            />
        </p>
    </div>

    <footer>
        <h4>Copyright &copy; Alessandro Scattaglia</h4>
    </footer>
</main>

<style>
    iframe {
        border-radius: 40px;
    }
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
    footer {
        text-align: center;
        color: #777;
        margin-top: 20px;
    }
</style>
