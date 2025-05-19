# laba-8
Программа реализует лексический и синтаксический анализ SQL-подобных выражений на языке Python с использованием метода рекурсивного спуска. 
# грамматика 
G[S]:
1. S → select X from X
2. X → AY
3. Y → ,AY | ɛ
4. A → letter {letter}
letter → {a, b, c, ...z, A, B, …, Z}
# язык
L={"select"  a1[,a2,…,an] "from"  b1[,b2,…,bm] ∣ ai,bj∈[a-zA-Z]+, n≥1, m≥1}
# Классификация грамматики
Тип грамматики: Контекстно-свободная 
# Схема вызова функций
![image](https://github.com/user-attachments/assets/74b8722c-fc17-4edc-ad18-3c8b493a9dec)
# Тестовые примеры
![image](https://github.com/user-attachments/assets/3ef1049a-a7f0-4312-b014-46c6754f1e23)
![image](https://github.com/user-attachments/assets/329cd497-0dc2-406f-bf8c-b7db655fdc5c)
# Дополнительное задание
![image](https://github.com/user-attachments/assets/fcaaafdb-51e3-4537-bc92-3ec4b6b60a2c)


