Bug Report 1: Меню вибору статі не зникає після вибору
Summary:
Меню вибору статі залишається активним після вибору статі та при переході до наступних етапів або розділів.

Steps to Reproduce:

Перейти до розділу Мій профіль.

Натиснути кнопку Редагувати.

Відкрити меню вибору статі та обрати будь-який варіант.

Перейти до наступного питання (вік).

Продовжити далі або перейти до іншого розділу.

Expected Result:
Меню вибору статі повинно зникнути одразу після вибору й підтвердження.

Actual Result:
Меню залишається активним і зберігається навіть при переході між розділами.

Environment:
Telegram-бот, платформа — будь-який пристрій.

Bug Report 2: Неможливо редагувати раціон в "Готові раціони"
Summary:
У розділі Готові раціони не працює редагування страв — неможливо обрати інгредієнт для заміни.

Steps to Reproduce:

Зайти в Готові раціони.

Обрати калорійність.

Вибрати день тижня.

Натиснути кнопку редагування страв.

Expected Result:
Зʼявляється меню з можливістю обрати страву, яку хочеш замінити, та поле для вводу альтернативи.

Actual Result:
Жодного вибору не зʼявляється, поле вводу не дає результату.

Environment:
Telegram-бот, платформа — будь-який пристрій.

Bug Report 3: Розділи бота не реагують після запиту геолокації
Summary:
Після надсилання гео, бот “зависає”: не реагує на кнопки, не дає повернутися назад.

Steps to Reproduce:

Зайти в Готові раціони.

Обрати калорійність та день.

Натиснути Замовити.

Надіслати геолокацію.

Після повторного запиту контактів — нічого не працює.

Expected Result:
Бот переходить до наступного кроку або дає можливість повернутись назад.

Actual Result:
Кнопки не працюють, потрібно вводити /start.

Environment:
Telegram-бот, будь-який пристрій.

Bug Report 4: Кнопка “Надіслати геолокацію” не зникає
Summary:
Після відправки геолокації кнопка не зникає і залишається активною в інших розділах.

Steps to Reproduce:

Зайти в Готові раціони.

Обрати калорійність, день.

Натиснути Замовити.

Надіслати геолокацію.

Expected Result:
Кнопка має зникнути після обробки гео-запиту.

Actual Result:
Кнопка залишається активною.

Environment:
Telegram-бот, платформа — будь-який пристрій.
