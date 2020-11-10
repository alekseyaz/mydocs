---
template: overrides/main.html
---

# Оператор SQL SELECT

Оператор SQL SELECT является одним из основных операторов языка SQL. Именно с его помощью происходит выборка значений, хранящихся в базе данных. В структуру запроса оператора SQL SELECT могут быть включены многие дополнительные операторы: уточняющие условие выборки, производящие группировку, сортировку выходных значений и т.д.

Оператор SQL SELECT имеет следующий синтаксис:

``` sql
SELECT column_list
FROM table_name
[WHERE сondition
GROUP BY expression
HAVING condition
ORDER BY expression]
```