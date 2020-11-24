Разберемся с распределением количества показов и кликов.<br>
Посчитайте среднее количество показов и среднее количество кликов на объявления за весь период (округлите до целых).<br>

Нарисуйте график распределения показов на объявление за весь период.<br>

А теперь давайте посчитаем скользящее среднее показов с окном 2. Какое значение скользящего среднего получим за 6 апреля 2019 года (ответ округлите до целых)?<br>

Скользящее среднее часто используется для поиска аномалий в данных. Давайте попробуем нанести на один график значения арифметического среднего<br>
по дням и скользящего среднего количества показов. В какой день наблюдается наибольшая разница по модулю между арифметическим средним и скользящим средним?<br>
Дни, в которых скользящее среднее равно NaN, не учитываем. <br>

*Напишите функцию, которая найдет проблемное объявление (с наибольшим/наименишим количеством показов) в день, в который была замечена самая большая по модулю аномалия.<br> 

*Теперь подгрузим данные по рекламным клиентам и найдем среднее количество дней от даты создания рекламного клиента и первым запуском рекламного объявления этим клиентом.<br>

*Вычислите конверсию из создания рекламного клиента в запуск первой рекламы в течение не более 365 дней. Ответ дайте в процентах и округлите до сотых. <br>
(Фильтровать нужно по значению в формате pd.Timedelta(365, unit='d'))<br>

*Давайте разобъем наших клиентов по промежуткам от создания до запуска рекламного объявления, равным 30.<br>
Определите, сколько уникальных клиентов запустили свое первое объявление в первый месяц своего существования (от 0 до 30 дней). <br>
Список промежутков для метода pd.cut – [0, 30, 90, 180, 365]<br>

*А теперь давайте выведем на интерактивный график эти категории с количеством уникальных клиентов в них.<br>
