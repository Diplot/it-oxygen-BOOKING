# Booking 🏢

 **Booking** - это новое онлайн туристическое агентство, которое специализируется на частных турах кинозвезд. Он заботится обо всех аспектах тура, начиная от полетов до размещения в отеле и конечно же, самого тура с гидом.



Вскоре после того, как вы были наняты в качестве разработчика программного обеспечения в группу отельного размещения. Ваша команда решила переписать свое веб-приложение с нуля, чтобы улучшить взаимодействие с пользователем, и что более важно, повысить производительность.


Ниже вы можете найти требования к проекту. Внимательно прочитайте это, спланируйте свое решение и распределите задачи в порядке выполнения.



Окончательное решение должно быть работоспособным исходным кодом веб-проекта, который реализует большинство требований ниже, в течение указанного срока.

# Основная задача

- Создать рабочее веб-приложение, на основе **Create**** React ****App**
- Реализуйте шаблон, в максимальном соответствии с предоставленными макетами.
- Обратите внимание, что некоторые экраны должны быть предназначены как для мобильных устройств, так и для настольных браузеров.
- Разместите решение в облачной системе контроля версии, такой как **Github** или **Bitbucket**.
- Проект должен выглядеть одинаково во всех современных браузерах.
- Обратите особое внимание на архитектуру, качество кода и производительность.
- Ваш код должен быть понятен. Тем не менее, я советую добавлять комментарии, когда это необходимо.

# Макеты

**Страница поиска**
1) Десктоп версия [https://prnt.sc/tj6mco](https://prnt.sc/tj6mco) 
2) Мобильная версия [https://prnt.sc/tj6mzo](https://prnt.sc/tj6mzo)

##

- Страница отзывчива и должна поддерживать мобильные и настольные системы, как показано на макете.
- Ввод:
  - Направление –текстовое поле с авто подстановкой значений. В нашем случае, все значения находятся в JSON файле
  - Заезд/Выезд – выбордаты.
  - Взрослые/Дети – числовое поле.
- Проверка правильности заполнения полей (они все обязательные).
- Нажатие на кнопку поиска, должно эмитировать ответ от сервера. Которое в вашем случае, должно вернуть список отелей с JSON файла.

##

**Список отелей (результат поиска)**
1) Десктоп версия [https://prnt.sc/tj6tb3](https://prnt.sc/tj6tb3)
2) Мобильная версия [https://prnt.sc/tj6ugx](https://prnt.sc/tj6ugx)


- Страница отзывчива и должна поддерживать мобильные и настольные системы, как показано на макете.
- Блок фильтра:
  - Названиеотеля – текстовое поле.
  - Рейтинг ( **бонус** ) – по нажатию, нужно отображать отели определенного рейтинга.
- Список должен отображать по 10 элементов + кнопка «Показать ещё 10» **(бонус)**
- В мобильной версии, нужно прятать блок фильтров и показывать по нажатию на кнопку в меню
- Если список отелей пустой (нет совпадений по направлению). Тогда нужно показать сообщение **«Нет доступных отелей»**
