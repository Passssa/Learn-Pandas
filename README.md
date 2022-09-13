# Learn-Pandas

Здесь представлено учебное задания с курса по ML по pandas.
Задания:
  Задание 1. Соберите всю информацию о студентах в одну таблицу df. В получившейся таблице должна быть информация и оценки всех студентов из всех групп. Напечатайте несколько строк таблицы для демонстрации результата.
  
  Задание 2. Удалите столбец index у полученной таблицы. Напечатайте первые 10 строк таблицы.
  
  Задание 3. Выведите на экран размеры полученной таблицы
  
  Задание 4. Выведите на экран статистические характеристики числовых столбцов таблицы (минимум, максимум, среднее значение, стандартное отклонение)
  
  Задание 5. Проверьте, есть ли в таблице пропущенные значения
  
  Задание 6. Выведите на экран средние баллы студентов по каждому предмету (math, reading, writing)
  
  Задание 7. Как зависят оценки от того, проходил ли студент курс для подготовки к сдаче экзамена (test preparation course)? Выведите на экран для каждого предмета в отдельности средний балл студентов, проходивших курс для подготовки к экзамену и не проходивших курс.
  
  Задание 8. Выведите на экран все различные значения из столбца lunch.
  
  Задание 9. Переименуйте колонку "parental level of education" в "education", а "test preparation course" в "test preparation" с помощью метода pandas rename. Зафиксируем минимальный балл для сдачи экзамена
  
  Задание 10. Ответьте на вопросы:
  
Какая доля студентов сдала экзамен по математике (passmark >= 50)?

Какая доля студентов, проходивших курс подготовки к экзамену, сдала экзамен по математике?

Какая доля женщин, не проходивших курс подготовки к экзамену, не сдала экзамен по математике? 

  Задание 11. С помощью groupby выполните задания ниже. Также выведите время выполнения каждого из заданий.
  
Для каждой этнической группы выведите средний балл за экзамен по чтению

Для каждого уровня образования выведите минимальный балл за экзамен по письму

  Задание 12. Выполните задание 11 с помощью циклов. Сравните время выполнения.
  
  Задание 13. Выведите на экран средние баллы студентов по каждому предмету в зависимости от пола и уровня образования. То есть должно получиться количество групп, равных 2 * (число уровней образования), и для каждой такой группы выыведите средний балл по каждому из предметов.
  
  Задание 14. Сколько студентов успешно сдали экзамен по математике?
  
  Задание 15. Сколько студентов успешно сдали все экзамены?
  
  Задание 16. Переведем баллы в оценки
  
Система перевода баллов в оценки

90 и больше = A

[80;90) = B

[70;80) = C

[60;70) = D

[50;60) = E

меньше 50 = F (Fail)

Создайте вспомогательную функцию, которая будет по среднему баллу за три экзамена выставлять оценку студенту по данным выше критериям.

Создайте столбец Grade и запишите в него оценку каждого студента.

Выведите количество студентов, получивших каждую из оценок.
