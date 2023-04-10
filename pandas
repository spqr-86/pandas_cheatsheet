Основы

# Импорт библиотеки pandas
import pandas as pd


Чтение данных из файла
Чтение данных из CSV файла:
python
Copy code
df = pd.read_csv('file.csv')
Чтение данных из Excel файла:
python
Copy code
df = pd.read_excel('file.xlsx')
Чтение данных из базы данных:
python
Copy code
import sqlite3
conn = sqlite3.connect('database.db')
df = pd.read_sql_query('SELECT * FROM table', conn)
Основные операции
Показать первые N строк таблицы:
python
Copy code
df.head(N)
Показать последние N строк таблицы:
python
Copy code
df.tail(N)
Показать общую информацию о таблице:
python
Copy code
df.info()
Показать статистические характеристики таблицы:
python
Copy code
df.describe()
Показать список столбцов таблицы:
python
Copy code
df.columns
Показать список индексов таблицы:
python
Copy code
df.index
Фильтрация данных
Выбрать строки, соответствующие определенному условию:
python
Copy code
df[df['column'] > 5]
Выбрать строки, соответствующие нескольким условиям:
python
Copy code
df[(df['column1'] > 5) & (df['column2'] == 'value')]
Выбрать строки, содержащие определенное значение:
python
Copy code
df[df['column'].str.contains('value')]
Группировка данных
Сгруппировать данные по значению столбца и посчитать среднее значение для каждой группы:
python
Copy code
df.groupby('column')['other_column'].mean()
Сгруппировать данные по значению столбца и посчитать количество элементов в каждой группе:
python
Copy code
df.groupby('column').size()
Обработка пропущенных значений
Проверить, есть ли пропущенные значения в таблице:
python
Copy code
df.isnull().sum()
Удалить строки, содержащие пропущенные значения:
python
Copy code
df.dropna(inplace=True)
Заполнить пропущенные значения определенным значением:
python
Copy code
df.fillna(value, inplace=True)
Сохранение данных
Сохранить данные в CSV файл:
python
Copy code
df.to_csv('file.csv', index=False)
Сохранить данные в Excel файл:
python
Copy code
df.to_excel('file.xlsx', index=False)
Работа с таблицами

Создание таблицы
Создать пустую таблицу:
python
Copy code
df = pd.DataFrame()
Создать таблицу из списка списков:
python
Copy code
data = [['Alice', 25], ['Bob', 30], ['Charlie', 35]]
df = pd.DataFrame(data, columns=['Name',


