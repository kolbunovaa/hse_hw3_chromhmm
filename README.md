# hse_hw3_chromhmm

Ссылка на колаб: https://colab.research.google.com/drive/1LtAOsHvVb8nF5jZpGW3DPZW8sbrn4D7z?usp=sharing

Клеточная линия - HSMMtube
|Гистоновая метка|Имя файла|С чем ассоциирована|
|:--|--|--:|
|H2AFZ|H2AFZ.bam|Связана с активацией генов|
|H3K27ac|H3K27ac.bam|Связана с более высокой активацией транскрипции|
|H3K27me3|H3K27me3.bam|Связана с понижением регуляции близлежащих генов посредством образования гетерохроматических областей|
|H3K36me3|H3K36me3.bam|Часто ассоциируется с телами генов|
|H3K4me1|H3K4me1.bam|Часто ассоциируется с энхансерами|
|H3K4me2|H3K4me2.bam|Связана с активацией генов|
|H3K4me3|H3K4me3.bam|Обычно ассоциируется с активацией транскрипции близлежащих генов|
|H3K79me2|H3K79me2.bam|Обнаруживается в транскрибируемых областях активных генов|
|H3K9ac|H3K9ac.bam|Является частью активного промоторного состояния|
|H3K9me3|H3K9me3.bam|Часто ассоциирована с гетерохроматином|
|H4K20me1|H4K20me1.bam|Связана с активацией транскрипции. Присутствует в дополнение к основной группе модификаций в активных промоторах|

### Выдача ChromHMM
|||
|:--|--:|
|![](https://github.com/kolbunovaa/hse_hw3_chromhmm/blob/main/results/HSMMtube_11_RefSeqTES_neighborhood.png)|![](https://github.com/kolbunovaa/hse_hw3_chromhmm/blob/main/results/HSMMtube_11_RefSeqTSS_neighborhood.png)|!

||||
|:--|--|--:|
|![](https://github.com/kolbunovaa/hse_hw3_chromhmm/blob/main/results/HSMMtube_11_overlap.png)|![](https://github.com/kolbunovaa/hse_hw3_chromhmm/blob/main/results/emissions_11.png)|![](https://github.com/kolbunovaa/hse_hw3_chromhmm/blob/main/results/transitions_11.png)|

|Состояние|Гистоновые метки|Место нахождения (относительно TSS)|Место нахождения (относительно TES)|Часть генома|Итог|
|:--|--|--|--|--|--:|
|1|немного H3K4me1, в еще меньших кол-вах H2AFZ, H3K4me2, H3K27me3, H4K20me1|-|Примерно постоянно на всем промежутке|Конец транскрипции, реже ядерная ламина, гены и экзоны|Weak enhancer|
|2|H3K27ac, меньше H3K4me1, еще меньше H3K4me2; мало H2AFZ|-|Примерно постоянно на всем промежутке|Конец транскрипции, реже гены и экзоны|Enhancer|
|3|H2AFZ, чуть реже H3K4me2; в меньних кол-вах H3K4me3, H3K27ac|Максимум на старте, плавно уменьшается в обе стороны|Максимум до TES, плавно уменьшется до положительных координат относительно TES|CpG островки, экзоны, старт транскрипции; реже конец транскрипции и гены|Promoter|
|4|H3K79me2, H3K9ac; чуть реже H3K4me2; мало H3K4me3 и H3K27ac (в еще меньших кол-вах H3K4me1, H2AFZ, H4K20me1)|После TSS|Максимум до TES, плавно уменьшется до положительных координат относительно TES|Гены, старт транкрипции; реже экзоны и конец транскрипции|Transcribed region|
|5|H3K79me2, H3K9ac; реже H4K20me1|-|-|Гены|Transcribed region|
|6|H3K79me2, H3K9ac|-|Чуть в больших кол-вах до TES, а так на всем промежутке|Гены, реже экзоны и конец транскрипции|Transcribed region|
|7|очень мало H4K20me1 и H3K36me3|-|Постоянно на всем промежутке|Конец транксрипции, гены; реже экзоны и ядерная ламина|Weak transcribed|
|8|мало H4K20me1|-|Постоянно на всем промежутке|Гены|Weak promoter|
|9|очень мало H4K20me1|-|-|Ядерная ламина|Weak promoter|
|10|H3K27me3|-|Постоянно на всем промежутке|Ядерная ламина, немного на конце транскрипции|Heterochromatin|
|11|H3K9me3|-|Чуть в больших кол-вах до TES, а так на всем промежутке|Ядерная ламина, реже конец транскрипции|Heterochromatin|

### Скриншоты из геномного браузера

![](https://github.com/kolbunovaa/images/blob/main/2022-03-20_23-37-31.png)

![](https://github.com/kolbunovaa/images/blob/main/2022-03-20_23-38-20.png)

### Бонус

![](https://github.com/kolbunovaa/images/blob/main/gjhjjkj.png)

![](https://github.com/kolbunovaa/images/blob/main/hghhkjkjcsesee.png)

