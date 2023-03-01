# hse_hw2_chip
## [COLAB](https://colab.research.google.com/drive/1r0SpdWy2rRUAvcUUR-JmzZJk9E0SLaj3?usp=sharing)

## 1. Чтения
| ENCFF000AME (реплика 1) | ENCFF000AMF (реплика 2) | ENCFF000AHM (контроль) |
| :-------------: |:------------------:| :-----:|
| ![](https://github.com/Ne-minus/hse_hw2_chip/blob/main/data/screenshots/AME_not_trimmed.png)    | ![](https://github.com/Ne-minus/hse_hw2_chip/blob/main/data/screenshots/AMF_not_trimmed.png)   | пркатически то же самое, но анализ неподрезанного контроля не сохранился( |
Можно заметить, что качество не очень хорошее (на многих позициях "усы" выходят из зеленой зоны), поэтому я решила произвести подрезание.Я использовала библиотеку `trimmomatic`. Для параметра ILLUMINACLIP  качестве файла с адаптерами я использовала предложенный в исходном колабе, остальные параметры были установлены 2:35:15. (Остальные параметры для команды `LEADING:5 TRAILING:5 SLIDINGWINDOW:4:10 MINLEN:36`)

### Новые результаты
| ENCFF000AME (реплика 1) | ENCFF000AMF (реплика 2) | ENCFF000AHM (контроль) |
| :-------------: |:------------------:| :-----:|
| ![](https://github.com/Ne-minus/hse_hw2_chip/blob/main/data/screenshots/AME_trimmed/AME_base.png)    | ![](https://github.com/Ne-minus/hse_hw2_chip/blob/main/data/screenshots/AMF_not_trimmed.png)   | пркатически то же самое, но анализ неподрезанного контроля не сохранился( |
| ![](https://github.com/Ne-minus/hse_hw2_chip/blob/main/data/screenshots/AME_trimmed/AME_pbsq.png)    | ![](https://github.com/Ne-minus/hse_hw2_chip/blob/main/data/screenshots/AMF_not_trimmed.png)   | пркатически то же самое, но анализ неподрезанного контроля не сохранился( |
| ![](https://github.com/Ne-minus/hse_hw2_chip/blob/main/data/screenshots/AME_trimmed/AME_psqs.png)    | ![](https://github.com/Ne-minus/hse_hw2_chip/blob/main/data/screenshots/AMF_not_trimmed.png)   | пркатически то же самое, но анализ неподрезанного контроля не сохранился( |
| ![](https://github.com/Ne-minus/hse_hw2_chip/blob/main/data/screenshots/AME_trimmed/AME_psgc.png)    | ![](https://github.com/Ne-minus/hse_hw2_chip/blob/main/data/screenshots/AMF_not_trimmed.png)   | пркатически то же самое, но анализ неподрезанного контроля не сохранился( |
