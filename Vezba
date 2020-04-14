<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <input type="number" name="" id="input_a" value="0"> <br>
    <input type="number" name="" id="input_b" value="0"> <br>
    <p id="paragraf">0</p>

    <script>
        function myFunc() {
            
            let rez = a + b;
            let paragraf = document.querySelector('#paragraf');
            paragraf.innerText = rez;
            
        }
        function init(params) {
            var a = document.querySelector('#input_a').innerText;
            var b = document.querySelector('#input_b').innerText;
            a.addEventListener('cnange', myFunc);   
            b.addEventListener('cnange', myFunc);
        }

        window.addEventListener('load', init);
    </script>
</body>
</html>
