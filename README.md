# Case-contador-de-clicks-
Contador de Clicks
<html>
<head>
    <title>Space Clicker</title>
</head>

<body>
    <script type="text/javascript">
    int clicks = 0;
    function click() {
        clicks += 1;
        document.getElementById("clicks").innerHTML = clicks;
    };
    </script>
    <button type="button" onClick="click()">Click me</button>
    <p>Clicks: <a id="clicks">0</a></p>

</body></html>
