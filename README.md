# hse_hw2_chip
[Ссылка на Google Colab](https://colab.research.google.com/drive/1-dXmptBlP0_1-4jG2QZhg2dha5yFg3Vt?usp=sharing)

### FastQC report


### Статистика по образцам:
Cводная таблица ридов, закартированных на участки 11347700-11367700 и 40185800-40195800 + дедупликация:
| Название образца  | Сколько ридов выравнилось уникально | Сколько ридов выравнилось НЕ-уникально | Сколько ридов НЕ выравнилось | Overall alignment rate |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| ENCFF659VLH  | 1183045 | 3485247 | 23641954 | 16.49% |
| ENCFF192ZGO  | 1379678 | 3826945 | 29929155 | 14.82% |
| ENCFF572ZEF  (контроль) | 775872 | 2103820 | 15423289 | 15.73% |
 
Процент вырывниывания получился не очень большой, вероятно это связано с тем что мы брали только одну хромосому, причем небольшую (на первой хромосеме процент был бы больше).

### Диаграммы Венна о пересечении наших MACS2 пиков и ENCODE пиков для двух реплик 
pdf в репозитории

### Бонусное задание

### Гистограммы распределения метилирования цитозинов по хромосоме (по X процент метилированных цитозинов, по Y - частота):  
| 1 | 2 | 3 |
| ------------- | ------------- | ------------- | 
| ![ ](https://github.com/IlonaGA/hse_hw1_meth/blob/main/images/hist_8cell.png) | ![ ](https://github.com/IlonaGA/hse_hw1_meth/blob/main/images/hist_epiblast.png) | ![ ](https://github.com/IlonaGA/hse_hw1_meth/blob/main/images/hist_ICM.png) |   
