# hse_hw2_chip
[Ссылка на Google Colab](https://colab.research.google.com/drive/1CWcc-D30_tFVsLV0rtY0cQMta3Z7nomP?usp=sharing)

### FastQC report
Репорты находятся в репозитории.
Адаптеры были отрезаны везде (но это не требовалось).
| ENCFF659VLH | ENCFF192ZGO | ENCFF572ZEF |
| ------------- | ------------- | ------------- | 
| ![ ](https://github.com/IlonaGA/hse_hw2_chip/blob/main/Images/GC1.png) | ![ ](https://github.com/IlonaGA/hse_hw2_chip/blob/main/Images/GC2.png) | ![ ](https://github.com/IlonaGA/hse_hw2_chip/blob/main/Images/GC3.png) |
| ![ ](https://github.com/IlonaGA/hse_hw2_chip/blob/main/Images/length1.png) | ![ ](https://github.com/IlonaGA/hse_hw2_chip/blob/main/Images/length2.png) | ![ ](https://github.com/IlonaGA/hse_hw2_chip/blob/main/Images/length3.png) |
| ![ ](https://github.com/IlonaGA/hse_hw2_chip/blob/main/Images/ATGC1.png) | ![ ](https://github.com/IlonaGA/hse_hw2_chip/blob/main/Images/ATGC2.png) | ![ ](https://github.com/IlonaGA/hse_hw2_chip/blob/main/Images/ATGC3.png) |

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
Диаграммы Венна показывает кличество пересечений выявленных пиков/пиков ENCODE, а также пиков ENCODE/выявленных пиков, данная операция не является симметричной, поэтому количество пиков разное (ситуация похожа на bedtools intersect). 
Пересечений достачно мало, так получилось из-за выравнивания только на одну (не самую большую) хромосому (В ENCODE пики для всех хромосом)
### Бонусное задание:
| 1 | 2 | 
| ------------- | ------------- | 
| ![ ](https://github.com/IlonaGA/hse_hw2_chip/blob/main/Images/result.png) | ![ ](https://github.com/IlonaGA/hse_hw2_chip/blob/main/Images/result2-2.png) | 
