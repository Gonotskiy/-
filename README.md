# -
<!DOCTYPE html>

<html lang="ru">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Калькулятор страхования урожая</title>

    <style>

        /* ... (стили остаются без изменений) */

    </style>

</head>

<body>



    <header>

        <h1>Страховая компания "АгроСтрах"</h1>

        <p>С заботой о Ваших рисках</p>

    </header>



    <nav>

        <a href="#">Главная</a>

        <a href="about.html">О нас</a>

        <a href="contacts.html">Контакты</a>

    </nav>



    <div class="container">

        <h2>Калькулятор страхования урожая</h2>



        <div class="calculator-inputs">

            <h3>Параметры страхования</h3>



            <div>

                <label>Программа страхования:</label>

                <input type="radio" id="basic" name="program" value="basic" checked>

                <label for="basic">Мультириск</label>

                <input type="radio" id="complex" name="program" value="complex">

                <label for="complex">ЧС</label>

                <input type="radio" id="complex_ambulance" name="program" value="complex_ambulance">

            </div>



            <div>

                <label for="cropType">Вид культуры:</label>

                <select id="cropType">

                    <option value="wheat">Пшеница</option>

                    <option value="corn">Кукуруза</option>

                    <option value="sunflower">Подсолнечник</option>

                </select>

            </div>

            <div>

                <label for="area">Площадь (га):</label>

                <input type="number" id="area" value="1" min="0">

            </div>

            <div>

                <label for="marketPrice">Рыночная стоимость (₽/га):</label>

                <input type="number" id="marketPrice" value="10000" min="0">

            </div>

            <div>

                <label for="riskFactor">Коэффициент риска:</label>

                <input type="number" id="riskFactor" value="1" min="0" step="0.1">

            </div>

             <div>

                <label for="startDate">Дата начала страхования:</label>

                <input type="date" id="startDate">

            </div>

            <div id="endDateDisplay" style="margin-top: 10px;">

                <label>Дата окончания страхования:</label>

                <span id="endDate"></span>

            </div>

            <div>

                <label for="coverageAmount">Сумма страхового покрытия (₽):</label>

                <span id="coverageAmount">0</span>

            </div>



            <button onclick="calculatePremium()">Рассчитать</button>



            <div id="premiumResult">Введите данные и нажмите "Рассчитать".</div>

        </div>



        <div class="client-data">

            <h3>Данные клиента</h3>

            <div>

                <label for="insurerFullName">ФИО страхователя:</label>

                <input type="text" id="insurerFullName" required>

            </div>

            <div>

                <label for="insuredFullName">ФИО застрахованного лица:</label>

                <input type="text" id="insuredFullName">

            </div>

            <div>

                <label for="passportData">Паспортные данные:</label>

                <input type="text" id="passportData" required>

            </div>

            <div>

                <label for="registrationAddress">Адрес регистрации:</label>

                <input type="text" id="registrationAddress" required>

            </div>

            <div>

                <label for="phoneNumber">Телефон для связи:</label>

                <input type="tel" id="phoneNumber" required>

            </div>

            <div>

                <label for="email">Электронный почтовый ящик:</label>

                <input type="email" id="email" required>

            </div>

            <div>

                <label for="inn">ИНН:</label>

                <input type="text" id="inn">

            </div>

            <div>

                <label for="ogrn">ОГРН:</label>

                <input type="text" id="ogrn">

            </div>

            <div>

                <label for="kfh">КФХ:</label>

                <input type="text" id="kfh">

            </div>

        </div>



        <!DOCTYPE html>

<html lang="ru">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Калькулятор страхования урожая</title>

    <style>

        /* ... (другие стили) ... */

        .link-container { /* Общий контейнер для всех ссылок */

            display: flex; /* Используем flexbox для размещения в строку */

            align-items: center; /* Выравнивание по вертикали (по желанию) */

            margin-top: 10px; /* Отступ сверху (по желанию) */

        }

        .link-container a { /* Стили для ссылок */

            display: inline-block;

            margin-right: 15px; /* Отступ справа между ссылками */

            padding: 8px 12px; /* Добавляем небольшие отступы внутри ссылок для красоты */

            border: 1px solid #ccc; /* Рамка для ссылок */

            border-radius: 5px; /* Скругление углов рамки */

            text-decoration: none; /* Убираем подчеркивание ссылок */

            color: #333; /* Цвет текста */

        }



        .link-container a:hover {

            background-color: #f0f0f0; /* Изменение фона при наведении */

        }

    </style>

</head>

<body>

    <div class="requisites">

        

    </div>



    <div class="link-container"> <a href="D:\ПОЛИТЕХ\4 сессия\сртаховое дело\договор.pdf" target="_blank">ДОГОВОР</a>

        <a href="D:\ПОЛИТЕХ\4 сессия\сртаховое дело\заявление (2).pdf" target="_blank">ЗАЯВЛЕНИЕ</a>

        <a href="D:\ПОЛИТЕХ\4 сессия\сртаховое дело\акт (3).pdf" target="_blank">АКТ</a>

    </div>



    <script>

        // ... (JavaScript код) ...

    </script>

</body>

</html>

           <div class="requisites">
    <h3>Реквизиты страхования</h3>
    <table>
        <tr>
            <th>Название страхового продукта:</th>
            <td>Программа страхования «Страхование урожая»</td>
        </tr>
        <tr>
            <th>Вид страхования:</th>
            <td>Имущественное, прочее</td>
        </tr>
        <tr>
            <th>Страхователь:</th>
            <td>Юридическое лицо, ИП, КФХ (сельскохозяйственный товаропроизводитель), ИНН, ОГРН ФИО, адрес регистрации.</td>
        </tr>
        <tr>
            <th>Застрахованное лицо:</th>
            <td>Совпадает</td>
        </tr>
        <tr>
            <th>Объект страхования:</th>
            <td>Имущественные интересы страхователя, выгодоприобретателя, связанные с риском утраты (гибели) урожая</td>
        </tr>
        <tr>
            <th>Страховой период:</th>
            <td>Не менее 1 года. Договор страхования должен быть заключен не позднее 15 дней после окончания сева сельхозкультуры.</td>
        </tr>
        <tr>
            <th>Перечень страховых рисков:</th>
            <td>
                <p><strong>Определенные страховые риски:</strong></p>
                <ul>
                    <li>Неблагоприятные погодные условия.</li>
                    <li>Заболевания и вредители.</li>
                    <li>Пожары.</li>
                    <li>Неисправности оборудования.</li>
                    <li>Человеческий фактор.</li>
                </ul>
                <p><strong>Изменяющиеся страховые риски:</strong></p>
                <ul>
                    <li>Экономические риски.</li>
                    <li>Политические и правовые риски</li>
                    <li>Климатические изменения</li>
                    <li>Технологические риски</li>
                    <li>Социальные риски</li>
                </ul>
            </td>
        </tr>
    </table>
</div>



    <script>

        const cropFactors = {

            wheat: 0.8,

            corn: 0.9,

            sunflower: 0.7,

        };



        const cropTypeSelect = document.getElementById('cropType');

        const areaInput = document.getElementById('area');

        const marketPriceInput = document.getElementById('marketPrice');

        const riskFactorInput = document.getElementById('riskFactor');

        const coverageAmountSpan = document.getElementById('coverageAmount');

        const startDateInput = document.getElementById('startDate');

        const endDateSpan = document.getElementById('endDate');

        const premiumResult = document.getElementById('premiumResult'); // Получаем элемент для вывода результата



        function calculateCoverage() {

            const cropType = cropTypeSelect.value;

            const area = parseFloat(areaInput.value);

            const marketPrice = parseFloat(marketPriceInput.value);

            const riskFactor = parseFloat(riskFactorInput.value);



            const cropFactor = cropFactors[cropType] || 1;

            const coverage = area * marketPrice * cropFactor * riskFactor;

            coverageAmountSpan.textContent = coverage.toFixed(2);

        }



        cropTypeSelect.addEventListener('change', calculateCoverage);

        areaInput.addEventListener('input', calculateCoverage);

        marketPriceInput.addEventListener('input', calculateCoverage);

        riskFactorInput.addEventListener('input', calculateCoverage);





        startDateInput.addEventListener('change', () => {

            const startDate = new Date(startDateInput.value);

            if (isNaN(startDate)) {

                endDateSpan.textContent = "";

                return;

            }



            const endDate = new Date(startDate);

            endDate.setFullYear(startDate.getFullYear() + 1);



            const formattedEndDate = endDate.toLocaleDateString('ru-RU');

            endDateSpan.textContent = formattedEndDate;

        });



        function calculatePremium() {

            const program = document.querySelector('input[name="program"]:checked').value;

            const coverageAmount = parseFloat(document.getElementById('coverageAmount').textContent); // Берем сумму покрытия из span

            const startDate = new Date(document.getElementById('startDate').value);



            if (isNaN(coverageAmount) || coverageAmount <= 0 || isNaN(startDate)) {

                premiumResult.textContent = 'Пожалуйста, введите корректные данные для расчёта.';

                return;

            }



            let baseRate;

            switch (program) {

                case 'basic':

                    baseRate = 0.01;

                    break;

                case 'complex':

                    baseRate = 0.015;

                    break;

                case 'complex_ambulance':

                    baseRate = 0.02;

                    break;

                default:

                    baseRate = 0.01;

            }

            const premium = coverageAmount * baseRate;

            premiumResult.textContent = `Расчётная стоимость страхования: ${premium.toFixed(2)} ₽`;

        }

    </script>



</body>

</html>
