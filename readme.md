# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list"
https://i.ibb.co/7Vt88wq/list.jpg

# Отримуємо контакт по id
node index.js --action="get" --id=5
https://i.ibb.co/4TmRgcr/get.jpg

# Додаємо контакт
node index.js --action="add" --name="Mango" --email="mango@gmail.com" --phone="322-22-22"
https://i.ibb.co/8g7t76D/add.jpg

# Видаляємо контакт
node index.js --action="remove" --id=3
https://i.ibb.co/9cwsyBF/remove.png