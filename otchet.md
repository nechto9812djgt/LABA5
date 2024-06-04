<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body style="font-family: 'Times New Roman', Times, serif;">
    <p align = "center" style="font-size: 14;">
        МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ <br>
        РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
        ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
        ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
        «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»<br>
    </p>
    <br><br><br><br><br><br>
    <body font-size = "12">
        <p align = "center"> 
            Институт естественных наук и техносферной безопасности<br>
            Кафедра информатики<br>
            Бахтина Елена Владимировна<br>
        </p>
        <br><br><br>
        <p align = "center">
            <strong>Лабораторная работа №5. JS»</strong><br>
            01.03.02 Прикладная математика и информатика
        </p>
        <br><br><br><br><br><br><br><br><br><br><br><br>
        <p align = "right"> 
            Научный руководитель<br>
            Соболев Евгений Игоревич
        </p>
        <br><br><br>
        <p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
    </body>
    <body style="font-family: 'Times New Roman', Times, serif;">
        <h2 align = "center">Введение</h2>
        <p font-size = "12">
            <b>JavaScript</b> — мультипарадигменный язык программирования. Поддерживает объектно-ориентированный, императивный и функциональный стили.
        </p>
        <br>
        <h2 align = "center">Цель и задачи</h2>
        <p align = "left" font-size = "12"> 
            Цель: решить задачи при помощи JS.<br>
            Задачи:<br>
                1.	Создайте переменную str и присвойте ей значение 'hdfgv'. Обращаясь к отдельным символам этой строки выведите на экран символ 'h', символ 'd', символ 'v'.<br>
                2.	Напишите скрипт, который считает количество секунд в часе.<br>
                3.	Переделайте приведенный код так, чтобы в нем использовались операции +=, -=, *=, /=, ++, --. Количество строк кода при этом не должно измениться. Код для переделки:<br>
                var num = 1;<br>
                num = num + 12;<br>
                num = num - 14;<br>
                num = num * 5;<br>
                num = num / 7;<br>
                num = num + 1;<br>
                num = num - 1;<br>
                alert(num);<br>
                4.	Создайте переменную num и присвойте ей значение 3. Выведите значение этой переменной на экран с помощью метода alert.<br>
                5.	Создайте переменные a=10 и b=2. Выведите на экран их сумму, разность, произведение и частное (результат деления).<br>
                6.	Создайте переменные c=15 и d=2. Просуммируйте их, а результат присвойте переменной result. Выведите на экран значение переменной result.<br>
                7.	Создайте переменные a=10, b=2 и c=5. Выведите на экран их сумму.<br>
                8.	Создайте переменные a=17 и b=10. Отнимите от a переменную b и результат присвойте переменной c. Затем создайте переменную d, присвойте ей значение 7. Сложите переменные c и d, а результат запишите в переменную result. Выведите на экран значение переменной result.<br>
                9.	Напишите скрипт, который считает количество секунд в часе, в сутках, в месяце.<br>
                10.	Создайте три переменные - час, минута, секунда. С их помощью выведите текущее время в формате 'час:минута:секунда'.<br>
                11.	Создайте переменную, присвойте ей число. Возведите это число в квадрат. Выведите его на экран.<br>
                12.	Напишите однострочное решение, которое вычисляет сумму квадратных корней для всех чётных чисел целочисленного массива.<br>
                13.	Яблоко стоит 1.15, апельсин стоит 2.30. Сколько они стоят вместе – чему равна сумма 1.15 + 2.30 с точки зрения JavaScript?<br>
                14.	Какое будет выведено значение: let x = 5; alert(x++); ?<br>
                15.	Чему равно такое выражение: [ ] + false - null + true ?<br>
                16.	Что выведет этот код: let y = 1; let x = y = 2; console.log(x); ?<br>
                17.	Чему равна сумма [ ] + 1 + 2?<br>
                18.	Создайте переменные a6, a7, a8, a9, a10. Поместите в них результат выражений:<br>
                5 % 3,<br>
                3 % 5,<br>
                5 + '3',<br>
                '5' - 3,<br>
                75 + 'кг'<br>
                19.	Напишите скрипт, который находит площадь прямоугольника высота 23см. (в числовую переменную height), шириной 10см (в числовую переменную width), значение площади должно хранится в числовой переменной s.<br>
                20.	Напиши скрипт, который находит объем цилиндра высотой 10м (переменная heightC) и диаметром основания 4м (dC), результат поместите в переменную v.<br>
                21.	Даны размер ипотечного кредита (S — 2 млн.руб), процентная ставка (p  — 10%), кол-во лет (years — 5). Найти переплату по кредиту, значение переплаты должно содержаться в переменной perepl.<br>
                22.	Определите переменные str, num, flag и txt со значениями «Привет», 123, true, «true». При помощи оператора определения типа убедитесь, что переменных принадлежат типам: string, number, boolean.<br>
                23.	Дано число, необходимо вернуть противоположное число.<br>
                <https://www.codewars.com/kata/56530b444e831334c0000020><br>
                <https://www.codewars.com/kata/583710ccaa6717322c000105><br>
                <https://www.codewars.com/kata/5a805d8cafa10f8b930005ba><br>
                <https://www.codewars.com/kata/5763bb0af716cad8fb000580><br>
                <https://www.codewars.com/kata/578a8a01e9fd1549e50001f1><br>
                <https://www.codewars.com/kata/57eae20f5500ad98e50002c5><br>
        </p>
        <h2 align = "center">Решение</h2>
        <p font-size = "12">Для выполнения этой лабораторной работы, я пользовалась:</p>
        <p> 1.  Материалом в сети интернет</p>
        </body>
<h3 align = "center">Файл lab5.html</h3>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>lab5</title>
    <style>
        .title{ font-weight: bold;}
    </style>
</head>
<body>
    <div>
        <p class="title">Первое задание:</p>
        <p id="first"></p>
        <p class="title">Второе задание:</p>
        <p id="second"></p>
        <p class="title">Третье задание:</p>
        <button id="btn1">Нажмите</button>
        <p class="title">Четвертое задание:</p>
        <button id="btn2">Нажмите</button>
        <p class="title">Пятое задание:</p>
        <p id="third"></p>
        <p class="title">Шестое задание:</p>
        <p id="fourth"></p>
        <p class="title">Седьмое задание:</p>
        <p id="fifth"></p>
        <p class="title">Восьмое задание:</p>
        <p id="Sixth"></p>
        <p class="title">Девятое задание:</p>
        <p id="seventh"></p>
        <p class="title">Десятое задание:</p>
        <p id="eight"></p>
        <p class="title">Одинадцатое задание:</p>
        <p id="nine"></p>
        <p class="title">Двенадцатое задание:</p>
        <p id="ten"></p>
        <p class="title">Тринадцатое задание:</p>
        <p id="eleven"></p>
        <p class="title">Четырнадцатое задание:</p>
        <button id="btn3">Нажмите</button> <button id="btn4">Нажмите</button>
        <p class="title">Пятнадцатое задание:</p>
        <p id="twelve"></p>
        <p class="title">Шестнадцатое задание:</p>
        <p>2</p>
        <p class="title">Семнадцатое задание:</p>
        <p id="thirteen"></p>
        <p class="title">Восемнадцатое задание:</p>
        <p id="fourteen"></p>
        <p class="title">Девятнадцатое задание:</p>
        <p id="fiveteen"></p>
        <p class="title">Двенадцатое задание:</p>
        <p id="sixteen"></p>
        <p class="title">Двадцать первое задание:</p>
        <p id="seventeen"></p>
        <p class="title">Двадцать второе задание:</p>
        <p id="eighteen"></p>
        <p class="title">Двадцать третье задание:</p>
        <p id="nineteen"></p>
    </div>
    <script>
        let str = 'hdfgv';
        let N1 = document.getElementById('first');

        N1.innerHTML = `${str[0]} <br> ${str[1]} <br> ${str[4]}`;
    </script>
    <script>
        const secondsInHour = 60 * 60;
        document.getElementById('second').innerText = `В часе ${secondsInHour} секунд`;
    </script>
    <script>
        function numm()
        {
            var num = 1;
            num += 12;
            num -= 14;
            num *= 5;
            num /= 7;
            num += 1;
            num -= 1;
            alert(num);
        }
        document.getElementById('btn1').addEventListener('click', numm);
    </script>
    <script>
        function numm()
        {
            var num = 3;
            alert(num);
        }
        document.getElementById('btn2').addEventListener('click', numm);
    </script>
    <script>
        var a = 10;
        var b = 2;
        const sum = a + b;
        const dif = a - b;
        const prod = a * b;
        const div = a / b;
        document.getElementById('third').innerHTML = `a + b = ${sum} <br> a - b = ${dif} <br> a * b = ${prod} <br> a / b = ${div}`;
    </script>
    <script>
        var c = 15;
        var d = 2;
        const result = c + d;
        document.getElementById('fourth').innerHTML = `c + d = ${result}`;
    </script>
    <script>
        var a = 10;
        var b = 2;
        var c = 5;
        document.getElementById('fifth').innerHTML = `a + b + c = ${a + b + c}`;
    </script>
    <script>
        var a = 17;
        var b = 10;
        var c = a - b;
        var d = 7;
        const result1 = c + d;
        document.getElementById('Sixth').innerHTML = `${result1}`;
    </script>
    <script>
        const secondsInDay = secondsInHour * 24;
        const secondsInMonth = secondsInDay * 30;
        document.getElementById('seventh').innerHTML = `В часе ${secondsInHour} секунд <br> В дне ${secondsInDay} секунд <br> В месяце ${secondsInMonth} секунд <br>`;
    </script>
    <script>
        const now = new Date();
        const hour = now.getHours();
        const minute = now.getMinutes();
        const second = now.getSeconds();
        document.getElementById('eight').innerText = `Текущее время: ${hour}:${minute}:${second}`;
    </script>
    <script>
        var a = 8;
        document.getElementById('nine').innerText = `8^2 = ${Math.pow(a, 2)}`;
    </script>
    <script>
        const array = [1, 2, 3, 4, 5, 6];
        const sumAr = array.filter(num => num % 2 === 0).reduce((sum, num) => sum + Math.sqrt(num), 0);
        document.getElementById('ten').innerText = `${sumAr}`;
    </script>
    <script>
        var apple = 1.15;
        var orange = 2.30;
        document.getElementById('eleven').innerText = `${apple + orange}`;
    </script>
    <script>
        function wrong()
        {
            let x = 5;
            alert(x++);
        }
        function right()
        {
            let x = 5;
            alert(++x);
        }
        document.getElementById('btn3').addEventListener('click', wrong);
        document.getElementById('btn4').addEventListener('click', right);
    </script>
    <script>
        document.getElementById('twelve').innerText = `${[ ] + false - null + true }`;
    </script>
    <script>
        let y = 1;
        let x = y = 2;
        console.log(x); //выведет 2
    </script>
    <script>
        document.getElementById('thirteen').innerText = `${[ ] + 1 + 2}`;
    </script>
    <script>
        a6 = 5 % 3;
        a7 = 3 % 5;
        a8 = 5 + '3';
        a9 = '5' - 3;
        a10 = 75 + 'кг';
        document.getElementById('fourteen').innerText = `${a6} | ${a7} | ${a8} | ${a9} | ${a10}`;
    </script>
    <script>
        var height = 23;
        var width = 10;
        var s = height * width;
        document.getElementById('fiveteen').innerText = `Площадь: ${s} кв. см.`;
    </script>
    <script>
        let heightC = 10;
        let dC = 4;
        let r = dC / 2;
        let v = Math.PI * Math.pow(r, 2) * heightC;
        document.getElementById('sixteen').innerText = `Объем цилиндра: ${v.toFixed(2)} куб. см.`;
    </script>
    <script>
        const S = 2000000;
        const p = 0.10;
        const years = 5;
        const monthlyRate = p / 12;
        const numMonths = years * 12;
        const monthlyPayment = S * monthlyRate * (1 + monthlyRate)**(numMonths) / ((1 + monthlyRate)**(numMonths) - 1);
        const totalPayments = monthlyPayment * numMonths;
        const perpel = totalPayments - S;
        document.getElementById('seventeen').innerText = `Переплата: ${perpel.toFixed(2)} руб.`;
    </script>
    <script>
        var strr = "Привет";
        var num = 123;
        var flag = true;
        var txt = "true";
        var output = document.getElementById('eighteen');
        output.innerHTML = `Тип переменной str: ${typeof strr} <br>`;
        output.innerHTML += `Тип переменной num: ${typeof num} <br>`;
        output.innerHTML += `Тип переменной flag: ${typeof flag} <br>`;
        output.innerHTML += `Тип переменной txt: ${typeof txt} <br>`;
    </script>
    <script>
        var numb = 10;
        var numb1 = -10;
        document.getElementById('nineteen').innerHTML = `Противоположение 10: ${-numb} <br> Противоположное -10: ${-numb1}`;
    </script>
</body>
</html>
```
</html>
<br>
 <h2 align = "center">Вывод</h2>
 <p align = "left" font-size = "12">
    По итогу данной лабороторной работы, я изучила азы JS и научилась решать базовые задания на этом язке 😊   
</p>
</body>
</html>