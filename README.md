Используя данные из VK, нужно сделать сервис намного лучше, чем Tinder, а именно: 
чат-бота “VKinder”. Бот должен искать людей, подходящих под условия, на основании информации о пользователе из VK:
- возраст,
- пол,
- город,
- семейное положение.
У тех людей, которые подошли по требованиям пользователю, получать топ-3 популярных фотографии профиля и отправлять их пользователю в чат вместе со ссылкой на найденного человека.
Популярность определяется по количеству лайков и комментариев.

Входные данные
- Имя пользователя или его id в ВК, для которого мы ищем пару.
если информации недостаточно нужно дополнительно спросить её у пользователя.

Требования к сервису:
1. Код программы удовлетворяет PEP8.
2. Получать токен от пользователя с нужными правами.
3. Программа декомпозирована на функции/классы/модули/пакеты.
4. Результат программы записывать в БД.
5. Люди не должны повторяться при повторном поиске.
6. Не запрещается использовать внешние библиотеки для vk.
