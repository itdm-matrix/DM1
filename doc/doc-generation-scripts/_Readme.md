
<!-- START doctoc -->
<!-- END doctoc -->  

# Спецификация форматов данных  

*(autogenerated - do not edit)*

## О документе

Документ для разработчиков и интеграторов продуктов, связанных с ПО DataMatrix.

## Формат файлов

На вход принимаются табличные данные в формате .csv.  
Обязательные требования к файлам:

  1. Названия файлов должны соответствовать названию схемы.  
  2. Названия колонок в файле должны совпадать с названиями полей из описания структуры.  
  3. Значения полей в каждой колонке должны быть в формате соответсвующего поля схемы.
Каждая строка будет валидироваться в соответствии с описанием формата.
  4. В качестве разделителя использются `;`

## Структуры данных, принимаемых программой Feasibility