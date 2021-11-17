# OPEN DATA BATTLE

Турнир для специалистов в области Data Science. В рамках турнира решено две задачи: EDA + correlation, EDA + binary classification.




<code>**Название** | Цель | Навыки и инструменты
:------------- |:-----:| -------:
[Covid-19](https://github.com/DariaGoncharevskaia/open-data-battle/blob/main/Covid-19.ipynb) | Произведена очистка данных, определена статистика случаев заражения в разных частях света за каждый месяц, определена корреляция каждой части света с другой, выделена страна с наименьшей корреляцией. Вывести название части света, которая меньше всего коррелирует с другими | предобработка данных, Python, Pandas, Matplotlib, Seaborn, numpy
[Gender](https://github.com/DariaGoncharevskaia/open-data-battle/blob/main/Gender.ipynb) |Дан датасет gender.csv, в котором записаны признаки человека на фото и его пол: произведена очистка данных, обработка датафрейма(присоединить дублирующие столбцы, уменьшить влияние погрешности путем корректного округления значений, определен пол по параметрам из выборки для первой тысячи значений.           **'Accuracy': 0.9756, 'Precision': 0.9756, 'Recall': 0.9757, 'FScore': 0.9756** | Python, Pandas, исследовательский анализ данных, предобработка данных, XGBClassifier, KNeighborsClassifier, GridSearchCV <code>
