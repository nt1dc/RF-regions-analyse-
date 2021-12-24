# RF-regions-analyse
В файле РФ_номер.txt находится информация о субъектах Российской Федерации, а именно: название, площадь(кв. км.), население, округ, административный центр/столица, код ОКАТО, часовой пояс. При этом в первой строке указано в какой последовательности дана эта информация. Выполнить следущие задания:
1) Перевести данные в словарь с единственным ключом "Российская Федерация" и значением - список словарей информации о субъекте(название, площадь(кв. км.), ПЛОЩАДЬ(ПРОЦЕНТ ОТ ВСЕЙ ПЛОЩАДИ РФ), население, НАСЕЛЕНИЕ(ПРОЦЕНТ ОТ ВСЕГО НАСЕЛЕНИЯ РФ), ПЛОТНОСТЬ(ЧЕЛ./КВ. КМ.), округ, административный центр/столица, код ОКАТО, часовой пояс). Название и административный центр/столица должно быть без нижних подчёркиваний, а площади, насление и плотности в числовом формате. Результат сохранить в формате json.
2) Для субъекта с номером ОКАТО, как номер вышего варианта, и любого выбраного региона программно сгенерировать строку-справку: "Субъект Калужская область входящий в ЦФО занимает площадь 29.8 тыс. кв. км., на которой проживает 1 млн. чел.. Адм. центром является город Калуга. Код Окато - 29. Часовой пояс - МСК.". Отметим, что площадь должна быть в тыс. кв. км., а население в млн. чел., тогда, как точность обоих один знак после запятой.
3) Выбрать любой субъект. Создать словарь разниц по времени с ним остальных субъектов. Например, для Калужской области: {"Астраханская область": 1, "Белгородская область": 0, "Алтайский край": 4, ...}.
Итоговый файл назвать "My_work.ipynb" и загрузить в личный кабинет.
