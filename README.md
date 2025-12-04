# AutoMath_
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulator Web Lengkap</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="kalkulator">
        <input type="text" id="display" readonly>

        <div class="tombol-container">
            <button class="operator" onclick="bersihkanDisplay()">C</button>
            <button class="operator" onclick="hapusTerakhir()">DEL</button>
            <button class="operator" onclick="tambahKeDisplay('%')">%</button>
            <button class="operator" onclick="tambahKeDisplay('/')">/</button>

            <button onclick="tambahKeDisplay('7')">7</button>
            <button onclick="tambahKeDisplay('8')">8</button>
            <button onclick="tambahKeDisplay('9')">9</button>
            <button class="operator" onclick="tambahKeDisplay('*')">x</button>

            <button onclick="tambahKeDisplay('4')">4</button>
            <button onclick="tambahKeDisplay('5')">5</button>
            <button onclick="tambahKeDisplay('6')">6</button>
            <button class="operator" onclick="tambahKeDisplay('-')">-</button>

            <button onclick="tambahKeDisplay('1')">1</button>
            <button onclick="tambahKeDisplay('2')">2</button>
            <button onclick="tambahKeDisplay('3')">3</button>
            <button class="operator" onclick="tambahKeDisplay('+')">+</button>

            <button onclick="tambahKeDisplay('0')">0</button>
            <button onclick="tambahKeDisplay('.')">.</button>
            <button class="hasil span-2" onclick="hitungHasil()">=</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
