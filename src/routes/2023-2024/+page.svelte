<script>
    import Nav from "../../lib/components/nav.svelte";
</script>

<main>
    <header>
        <h1>2023-2024</h1>
    </header>

    <Nav />

    <div class="centro">
        <h2>LETTERE ITALIANE</h2>
        <p>
            Durante questa materia, quest'anno, abbiamo affrontato dei temi
            importanti: Abbiamo parlato dei campi di concentramento in USA, in
            Giappone e ovviamente anche in Germania. <br />Abbiamo discusso del
            significato delle parole che compongono la lingua italiana e le loro
            origini geografiche, abbiamo discusso del significato della parola
            “campo” e come siamo stati costretti a vivere la guerra attraverso i
            documenti che ci sono.<br />
            Ecco dei link utili per approfondire meglio questi argomenti:
        </p>
        <iframe
            width="450"
            height="300"
            src="https://www.youtube.com/embed/SKOP830ETKk?si=QicE24pmXBcJdlmo&amp;start=5"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            referrerpolicy="strict-origin-when-cross-origin"
            allowfullscreen
        ></iframe>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <iframe
            width="450"
            height="300"
            src="https://www.youtube.com/embed/2CMOupbiZ58?si=AkMy9l1X7eVatEae"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            referrerpolicy="strict-origin-when-cross-origin"
            allowfullscreen
        ></iframe>
        <br /><br />
        <div>
            <iframe
                width="450"
                height="300"
                src="https://www.youtube.com/embed/6yXNjIq50Dw?si=7oU8EtxgIo0aFf_Y"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                referrerpolicy="strict-origin-when-cross-origin"
                allowfullscreen
            ></iframe>
        </div>

        <br />
        <h2>INGLESE</h2>
        <p>
            Durante la materia di inglese, quest'anno, abbiamo parlato dei
            social media e i rischi che essi possono portare. Ognuno di noi ha
            realizzato una presentazione su "risk and dangers of social media",
            ecco la mia presentazione:
        </p>
        <iframe
            src="https://docs.google.com/presentation/d/e/2PACX-1vQrg-ELCJTG-kF_UKMd7gFbl3GZXxxuRNkkxt3QB4r-pA-Ip7lk2Il9GehN8gNZPZtgJjo4RmPj6wq_/embed?start=true&loop=true&delayms=3000"
            frameborder="0"
            width="960"
            height="569"
            allowfullscreen="true"
            mozallowfullscreen="true"
            webkitallowfullscreen="true"
        ></iframe>

        <h2>INGLESE MADRELINGUA</h2>
        <p>
            Quest'anno, di inglese madrelingua abbiamo fatto una presentazione
            su un argomento a nostra scelta legato all'informatica, io ho scelto
            la crittografia, ecco la presentazione:
        </p>
        <iframe
            src="https://docs.google.com/presentation/d/e/2PACX-1vRk4lVt7iFxAUGWGwRiri3NpwstCyhYKXeNt5LsyJj46Z17D5Mst9c5fXugQ0W4amncBnaOJ7anDCXf/embed?start=true&loop=true&delayms=3000"
            frameborder="0"
            width="960"
            height="569"
            allowfullscreen="true"
            mozallowfullscreen="true"
            webkitallowfullscreen="true"
        ></iframe>
        <footer>
            <h4>Copyright &copy; Alessandro Scattaglia</h4>
        </footer>
    </div>
</main>

<style>
    div {
        text-align: center;
    }
    :root {
        background-color: #207cca;
    }
    ::selection {
        background-color: rgb(10, 226, 10);
        color: white;
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

    footer {
        text-align: center;
        color: #777;
        margin-top: 20px;
    }
    p {
        padding-top: 0;
        padding: 15px;
        text-align: justify;
        font-size: x-large;
    }
</style>
