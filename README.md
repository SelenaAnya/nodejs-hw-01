Доступні команди
npm run get-all
Виводить всі контакти з бази даних
npm run generate
Генерує 5 нових випадкових контактів та додає їх до бази даних
npm run add-one
Додає один новий випадковий контакт до бази даних
npm run count
Виводить кількість контактів у базі даних
npm run remove-last
Видаляє останній контакт з бази даних
npm run remove-all
Видаляє всі контакти з бази даних
Структура контакту
Кожен контакт містить наступні поля:

id - унікальний ідентифікатор (UUID)
name - повне ім'я
phone - номер телефону
email - електронна пошта
job - назва професії

Приклад використання
bash# Згенерувати початкові контакти
npm run generate

# Подивитися всі контакти
npm run get-all

# Додати ще один контакт
npm run add-one

# Підрахувати кількість контактів
npm run count

# Видалити останній контакт
npm run remove-last

# Очистити всю базу даних
npm run remove-all
Технічні деталі

Використовується ES Modules ("type": "module" в package.json)
Для генерації випадкових даних використовується бібліотека @faker-js/faker
Дані зберігаються у форматі JSON
Всі операції з файлами асинхронні з використанням fs/promises
