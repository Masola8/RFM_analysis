# RFM_analysis
RFM analysis and other analitical tasks for e-learning platform
# Описание проекта
В данном проекте произволдится RFM анализ пользователей онлайн школы. 

Cтек: Для решения задания используется Python, библиотеки pandas, numpy, seaborn. 

Цель проекта: провести качественный анализ аудитории. Проанализировать популярность и сложность предметов, сроки сдачи экзаменов для улучшения качества образования.

В ходе проекта:
1. Производится анализ качества данных. Найдены пустые строки.
2. Определяетя, солько студентов успешно сдали только один курс.
3. Выявлен самый сложный и самый простой экзамен: найдены курсы и экзамены в рамках курса, которые обладают самой низкой и самой высокой завершаемостью.
4. По каждому предмету определен средний срок сдачи экзаменов. 
5. Выявлены самые популярные предметы (ТОП-3) по количеству регистраций на них. А также предметы с самым большим оттоком (ТОП-3). 
6. В период с начала 2013 по конец 2014 выявлен семестр с самой низкой завершаемостью курсов и самыми долгими средними сроками сдачи курсов.  
7. Построены адаптированные RFM-кластеры студентов, чтобы качественно оценить аудиторию. В адаптированной кластеризации выбраны следующие метрики: R - среднее время сдачи одного экзамена, F - завершаемость курсов, M - среднее количество баллов, получаемое за экзамен.  Для каждого RFM-сегмента построены границы метрик recency, frequency и monetary для интерпретации этих кластеров. 

В результате найдены курсы и экзамены в рамках курса, которые обладают самой низкой и самой высокой завершаемостью. По каждому предмету определен средний срок сдачи экзаменов. Выявлены самые популярные предметы и предметы с самым большим оттоком. Построены адаптированные RFM-кластеры студентов. На основе полученных данных даны рекомендации по улучшению учебного процесса.
