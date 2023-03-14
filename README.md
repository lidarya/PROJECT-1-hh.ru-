# project_1. Анализ вакансий на hh.ru

## Оглавление  
[1. Описание проекта](.README.md#Описание-проекта)  
[2. Базовый анализ структуры данных](.README.md#Базовый-анализ-структуры-данных) 
[3. Преобразование данных](.README.md#Преобразование-данных)  
[4. Разведывательный анализ](.README.md#Разведывательный-анализ)  
[5. Очистка данных](.README.md#Очистка-данных)    


### Описание проекта    
В проекте реализуется анализ резюме, размещённых на hh.ru. Используемые датасеты размещены на Google Disk и доступны по ссылке https://drive.google.com/drive/folders/1zkJNr4RPPHxTrFS7NztRTjjCbwTXhkPQ?usp=sharing 

Проект состоит из четырёх частей: базовый анализ структуры данных, преобразование данных, разведывательный анализ, очистка данных.


### Базовый анализ структуры данных

Здесь мы знакомимся со структурой данных и со статистическими характеристиками по столбцам


### Преобразование данных

В данном разделе мы из смешанных признаков вычленяем информацию и создаём новые признаки:
1. Образование (высшее, неоконченное высшее, среднее, среднее специальное), 
2. Пол (м/ж)
3. Возраст
4. Опыт работы в месяцах
5. Город
6. Готовность к переездам, готовность к командировкам
7. Различные типы занятости
8. Различные виды графика
9. Желаемая зарплата в рублях


### Разведывательный анализ

Здесь мы строим и анализируем графики:
1. Распределение возраста соискателей
2. Распределение опыта работы соискателей
3. Распределение желаемой зарплаты (медианной) соискателей
4. Зависимость ЗП от уровня образования
5. Зависимость ЗП от города
6. Зависимость ЗП от готовности к командировкам/переезду
7. Зависимость ЗП от образования и возраста
8. Связь между опытом работы и возрастом
9. Зависимость ЗП от пола и образования


### Очистка данных

В данном разделе мы избавляемся от дубликатов, пропусков и выбросов