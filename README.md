# hse_hw3_chromhmm

Ссылка на колаб: https://colab.research.google.com/drive/1LtAOsHvVb8nF5jZpGW3DPZW8sbrn4D7z?usp=sharing

Клеточная линия - HSMMtube
|Гистоновая метка|Имя файла|
|:--|--:|
|H2AFZ|H2AFZ.bam|
|H3K27ac|H3K27ac.bam|
|H3K27me3|H3K27me3.bam|
|H3K36me3|H3K36me3.bam|
|H3K4me1|H3K4me1.bam|
|H3K4me2|H3K4me2.bam|
|H3K4me3|H3K4me3.bam|
|H3K79me2|H3K79me2.bam|
|H3K9ac|H3K9ac.bam|
|H3K9me3|H3K9me3.bam|
|H4K20me1|H4K20me1.bam|

### Выдача ChromHMM
|||
|:--|--:|
|![](https://github.com/kolbunovaa/hse_hw3_chromhmm/blob/main/results/HSMMtube_11_RefSeqTES_neighborhood.png)|![](https://github.com/kolbunovaa/hse_hw3_chromhmm/blob/main/results/HSMMtube_11_RefSeqTSS_neighborhood.png)|!

||||
|:--|--|--:|
|![](https://github.com/kolbunovaa/hse_hw3_chromhmm/blob/main/results/HSMMtube_11_overlap.png)|![](https://github.com/kolbunovaa/hse_hw3_chromhmm/blob/main/results/emissions_11.png)|![](https://github.com/kolbunovaa/hse_hw3_chromhmm/blob/main/results/transitions_11.png)|

|Состояние|Гистоновые метки|Место нахождения (относительно TSS)|Место нахождения (относительно TES)|Часть генома|Итог|
|:--|--|--|--|--|--:|
|1|немного H3K4me1, в еще меньших кол-вах H2AFZ, H3K4me2, H3K27me3, H4K20me1|||||
|2|H3K27ac, меньше H3K4me1, еще меньше H3K4me2; мало H2AFZ|||||
|3|H2AFZ, чуть реже H3K4me2; в меньних кол-вах H3K4me3, H3K27ac|||||
|4|H3K79me2, H3K9ac; чуть реже H3K4me2; мало H3K4me3 и H3K27ac (в еще меньших кол-вах H3K4me1, H2AFZ, H4K20me1)|||||
|5|H3K79me2, H3K9ac; реже H4K20me1|||||
|6|H3K79me2, H3K9ac|||||
|7|очень мало H4K20me1 и H3K36me3|||||
|8|H4K20me1|||||
|9|очень мало H4K20me1|||||
|10|H3K27me3|||||
|11|H3K9me3|||Ядерная ламина||
