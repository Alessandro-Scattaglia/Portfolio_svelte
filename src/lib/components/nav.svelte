<script>

    if (typeof window !== "undefined") {
        let prevScrollPos = 0;
        window.onscroll = function () {
            const currentScrollPos = window.scrollY;
            document.querySelector(".topnav").style.top =
                prevScrollPos > currentScrollPos ? "0" : "-70px";
            prevScrollPos = currentScrollPos;
        };  
    }
</script>

<section>
    <div class="topnav">
        <img class="logo" src = "https://i.ibb.co/cT54jBm/logo.png" alt="logo_agnelli.png" />
        <a class="active" href="/"><b>Home</b></a>
        <a href="/../2023-2024"><b>2023</b></a>
        <a href="/../2022-2023"><b>2022</b></a>
        <a href="/../2021-2022"><b>2021</b></a>
        <a href="/../2020-2021"><b>2020</b></a>
    </div>
</section>
<style>
.topnav {
    transition: top 0.3s;
    position: fixed;
    top: 7px;
    left: 0;
    right: 0;
    width: 40%;
    background-color: #ffffff;
    overflow: hidden;
    border-radius: 8px;
    z-index: 100;
    margin: 0 auto;
}

.topnav a {
    font-family: Tahoma, Verdana, sans-serif;
    float: right;
    color: black;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
}

.topnav a:hover {
    background-color: rgb(10, 226, 10);
    color: black;
    transition: all 0.2s ease 0s;
    border-radius: 8px;
}

.topnav a.active {
    float: left;
    background-color: rgb(10, 226, 10);
    color: black;
    border-radius: 8px;
}

.logo {
    text-align: left;
    padding-top: 0px;
    max-width: 94px;
}

</style>
