<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>MMA</title>
    <style>
        body {background-color: #0dbe30dd; font-family: Arial, sans-serif; color: #050505dd}
        h1 { text-align: center; color: #060c08; }
        h2 { font-size:20px; color: black}
        nav a {front-weight:bold;color: #c20808dd}
        .txikia {
            width: 150px;
            cursor: pointer;
        }

        .handia {
            width: 400px;
        }
    </style>
    </style>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
    <script src='main.js'></script>
</head>
<body>
    <nav>
        <a href="lehena.html">Jokalariak</a>
        <a href="bigarrena.html">Arauak</a>
        <a href="hirugarrena.html">MMA txapelketak</a>
    <nav>
<body>
    <h1>MMA</h1>
        <h2>Zer da?</h2>
        <p>Arte martzialen mistoak (AMM edo MMA) arte martzialen eta borroka-kirolen arteko tekniken konbinazioa dira, oro har borroka-kiroletan lehiatzeko erabiltzen direnak, baina baita autodefentsarako ere.</em></p>
        <img src="./argazkia.jpg" alt="Irudi txikia" onclick="handitu(this)" class="txikia">

        <script>
            function handitu(irudia) {
                if (irudia.classList.contains("txikia")) {
                    irudia.classList.remove("txikia");
                    irudia.classList.add("handia");
                } else {
                    irudia.classList.remove("handia");
                    irudia.classList.add("txikia");
                }
            }
            </script>
        <br>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/_eYGdvFwXw8?si=okzSN8HElYmsseCj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</html>
