# Aglomerated-Clustering
Clustering Customers' dataset consisting of 316 features and selecting 15 features with highest Information Value(IV), then predicting customer's age based on those 15 features

Dataset: https://drive.google.com/drive/folders/1F5MZIadLW0_yb1cmexZ-7GWdYgjKEBjU?usp=sharing

Данные: Предоставлены данные по клиентам, характеризующие поведение клиентов исходя из данных трафика;
Описание задачи:
Исходя из поведения клиентов, необходимо определить возраст клиента. Используя линейную регрессию. 
Вы должны построить дендрограмму и применив агломерационную кластеризацию на основе корреляции признаков, выбрать максимум 15 признаков. При этом выбирать признак нужно исходя из максимального Information value в группе (кластере).
df_train_datathon.csv файл содержит тренировочную выборку, где вам доступно 316 признаков пронумерованных в колонках с N_0 по N_315. В колонке AGE записан возраст.
Вам необходимо определить возраст для тестовой выборке, которая хранится в файле df_test_datathon.csv.
В каком формате передать ответ?
Необходимо передать данные в виде csv файла и решение в jupyter notebook. В котором будет 2 колонки:
ID – соответствующий записи в тестовой выборке (df_test_datathon.csv)
AGE – возраст

Пример:
ID      AGE
2154684 25
5684654 26
3215888 38

