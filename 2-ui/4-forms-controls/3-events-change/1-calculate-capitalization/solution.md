Алгоритм решения такой.

Только численный ввод в поле с суммой разрешаем, повесив обработчик на `keypress`.

Отслеживаем события изменения для перевычисления результатов:
<ul>
<li>На `input`: событие `input` и дополнительно `propertychange/keyup` для совместимости со старыми IE.</li>
<li>На `checkbox`: событие `click` вместо `change` для совместимости с IE<9.</li>
<li>На `select`: событие `change`.</li>
</ul>

[edit src="solution"]Открыть решение в песочнице[/edit]