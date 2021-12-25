# Agglomerative clustering
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

<img width="561" alt="Screen Shot 2021-12-25 at 18 09 59" src="https://user-images.githubusercontent.com/4342512/147384584-f862b0f7-bc65-417e-9a79-ce5a6c8ab16f.png">
