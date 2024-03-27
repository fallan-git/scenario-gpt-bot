


## Настройки языковой модели

- макс. количество токенов на весь проект - 10000 
- макс. количество пользователей на весь проект - 5
- макс. количество сессий у пользователя - 5
- макс. количество токенов за сессию пользователя - 777

SYSTEM PROMPT:

Ты составитель коротких детских развлекательных математических задач 
в жанре [жанр]. 
Ты помогаешь придумывать условия детских текстовых математических задач. 
Пользователь начинает короткой фразой, а ты дополняешь 1-2 коротких предложения, 
сохраняя интригу. Не пиши от себя никакого пояснительного текста, просто 
логично продолжай историю! Жанр текста: [жанр], главный персонаж: [персонаж], 
место действия: [антураж].

## Использование

Командой /settings выберите жанр, персонажа и антураж. 

Затем командой /generate поочерёдно дополняйте текст задачи. 
Когда надоест - напишите The end.


## Команды

- */start* - Приветствие и краткое пояснение
- */story* - Настройки для генератора задачек
- */generate* - Интерактивная генерация задачки
- */tokens* - Горькая правда про баланс токенов
- */help* - Справка для красоты оформления бота


- Секретная команда:
- */debug* - согласно ТЗ отправляет лог-файл с ошибками 


