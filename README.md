# AutoMath_

<DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Kalkulator Sederhana</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="kalkulator">
    <input type="text" class="layar" id="layar" value="0" disabled>

    <div class="tombol-grid">
        <button class="operasi" onclick="bersihkan()">AC</button>
        <button class="operasi" onclick="hapusTerakhir()">DEL</button>
        <button class="operasi" onclick="tambahKeLayar('%')">%</button>
        <button class="operasi" onclick="tambahKeLayar('/')">/</button>

        <button onclick="tambahKeLayar('7')">7</button>
        <button onclick="tambahKeLayar('8')">8</button>
        <button onclick="tambahKeLayar('9')">9</button>
        <button class="operasi" onclick="tambahKeLayar('*')">*</button>

        <button onclick="tambahKeLayar('4')">4</button>
        <button onclick="tambahKeLayar('5')">5</button>
        <button onclick="tambahKeLayar('6')">6</button>
        <button class="operasi" onclick="tambahKeLayar('-')">-</button>

        <button onclick="tambahKeLayar('1')">1</button>
        <button onclick="tambahKeLayar('2')">2</button>
        <button onclick="tambahKeLayar('3')">3</button>
        <button class="operasi" onclick="tambahKeLayar('+')">+</button>

        <button class="span-2" onclick="tambahKeLayar('0')">0</button>
        <button onclick="tambahKeLayar('.')">.</button>
        <button class="sama-dengan" onclick="hitungHasil()">=</button>
    </div>
</div>

<script src="script.js"></script>
</body>
</html>
