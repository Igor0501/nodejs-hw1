# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list"
https://monosnap.com/file/pIP2oWafLpdyt247xD9g0rVCz7IDaJ

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.
node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
https://monosnap.com/file/Hzfc67nRJg3ZvJhLscSwSraMuP4cNz

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту
node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/Ywz5pL0s2UHfdvkKQy6MPSYSjNqMWh

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
https://monosnap.com/file/WoL32erkqfn1oXSWX6KzoIjrKPaupM