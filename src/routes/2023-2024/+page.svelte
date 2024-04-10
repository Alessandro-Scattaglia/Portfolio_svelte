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
</style>
