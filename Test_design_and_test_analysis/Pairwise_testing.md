# Попарное тестирование анкеты для кредита

Анкета имеет 4 параметра с возможными значениями:

- Возраст: 18–35 / 36–55 / 56–75 (3 варианта)
- Наличие задолженностей: да / нет (2 варианта)
- Тип трудовых отношений: ИП / Самозанятый / Бессрочный договор (3 варианта)
- Наличие действующих кредитов: да / нет (2 варианта)

1. **Подсчет всех возможных комбинаций:**
3 (возраст) × 2 (задолженности) × 3 (трудовые отношения) × 2 (кредиты) = 36 комбинаций

2. **Комбинации с использованием попарного тестирования**.
Для проверки покрытия пар каждая возможная пара значений параметров должна встречается хотя бы в одном тестовом случае:
- Все комбинации возраста и задолженностей
- Все комбинации возраста и трудовых отношений
- Все комбинации возраста и кредитов
- Все комбинации задолженностей и трудовых отношений
- Все комбинации задолженностей и кредитов
- Все комбинации трудовых отношений и кредитов

<table>
    <thead>
        <tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4 align="center">№
            <td rowspan=4 align="center">Возраст
            <td rowspan=4 align="center">Задолженности
            <td rowspan=4 align="center">Трудовые отношения
            <td rowspan=4 align="center">Действующие кредиты
            </thead>
    <tbody>
        <tr>
            <td rowspan=4 align="center">1
            <td rowspan=4 align="center">18–35
            <td rowspan=4 align="center">Да
            <td rowspan=4 align="center">ИП
            <td rowspan=4 align="center">Да
            </thead>
    <tbody>
        <tr>
            <td rowspan=4 align="center">2
            <td rowspan=4 align="center">18–35
            <td rowspan=4 align="center">Нет
            <td rowspan=4 align="center">Самозаняты
            <td rowspan=4 align="center">Нет
            </thead>
    <tbody>
        <tr>
            <td rowspan=4 align="center">3
            <td rowspan=4 align="center">18–35
            <td rowspan=4 align="center">Да
            <td rowspan=4 align="center">Бессрочный договор
            <td rowspan=4 align="center">Нет
            </thead>
    <tbody>
        <tr>
            <td rowspan=4 align="center">4
            <td rowspan=4 align="center">36–55
            <td rowspan=4 align="center">Да
            <td rowspan=4 align="center">Самозанятый
            <td rowspan=4 align="center">Да
            </thead>
    <tbody>
        <tr>
            <td rowspan=4 align="center">5
            <td rowspan=4 align="center">36–55
            <td rowspan=4 align="center">Нет
            <td rowspan=4 align="center">Бессрочный договор
            <td rowspan=4 align="center">Да
            </thead>
    <tbody>
        <tr>
            <td rowspan=4 align="center">6
            <td rowspan=4 align="center">36–55
            <td rowspan=4 align="center">Да
            <td rowspan=4 align="center">ИП
            <td rowspan=4 align="center">Нет
            </thead>
    <tbody>
        <tr>
            <td rowspan=4 align="center">7
            <td rowspan=4 align="center">56–75
            <td rowspan=4 align="center">Да
            <td rowspan=4 align="center">Бессрочный договор
            <td rowspan=4 align="center">Да
            </thead>
    <tbody>
        <tr>
            <td rowspan=4 align="center">8
            <td rowspan=4 align="center">56–75
            <td rowspan=4 align="center">Нет
            <td rowspan=4 align="center">ИП
            <td rowspan=4 align="center">Нет
            </thead>
    <tbody>
        <tr>
            <td rowspan=4 align="center">9
            <td rowspan=4 align="center">56–75
            <td rowspan=4 align="center">Нет
            <td rowspan=4 align="center">Самозанятый
            <td rowspan=4 align="center">Да
        </tr>
        <thead>
        <tr>
    <tbody>
        <tr>     
        </tr>
    </tbody>
</table>
