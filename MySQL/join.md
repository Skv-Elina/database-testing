# 🐬 MySQL
### 🛠️ Инструмент: DBeaver

## JOIN-запросы

### **Задание 1:** 
Выведите логин вашего пользователя, номера его заказов и их стоимость (таблицы users и orders).

**Запрос:**

```sql
SELECT u.login, o.order_id, o.total 
FROM users u
INNER JOIN orders o ON u.user_id = o.user_id 
WHERE u.login = 'lin_05';
```
Результат:<br><br>
<img src="./images/1-join.jpg" width="80%">
<br><br><br>
