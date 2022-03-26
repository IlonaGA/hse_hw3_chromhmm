# hse_hw3_chromhmm
Скрипт находится в папке src.
## Часть 1
Список 10-ти гистоновых меток (и соотв имен файлов) , для которых был сделан анализ
### Гистоновые метки
Клеточная линия: A549  
H3k79me2 wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k79me2Dex100nmAlnRep1.bam -> H3k79me2.bam
H3k09ac wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k09acEtoh02AlnRep1.bam -> H3k09ac.bam
H3k04me2 wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k04me2Dex100nmAlnRep1.bam -> H3k04me2.bam
H3k27me3 wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k27me3Dex100nmAlnRep1.bam -> H3k27me3.bam
H3k27ac wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k27acDex100nmAlnRep1.bam -> H3k27ac.bam
H2AZ wgEncodeBroadHistoneA549H2azDex100nmAlnRep1.bam -> H2AZ.bam
H3k04me3 wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k04me4Dex100nmAlnRep1.bam -> H3k04me4.bam
H3k04me1  wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k04me1Dex100nmAlnRep1.bam -> H3k04me1.bam
H3k09me3  wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k09me3Etoh02AlnRep1.bam -> H3k09me3.bam
H3k36me3 wgEncodeBroadHistone/wgEncodeBroadHistoneA549H3k36me3Dex100nmAlnRep1.bam -> H3k36me3.bam

Файл cellmarkfiletable.txt находится в папке src.

### Картинки из выдачи ChromHMM
| | | | 
| ------------- | ------------- | ------------- |  
| ![ ](https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/A549_10_RefSeqTES_neighborhood.png) | ![ ](https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/A549_10_RefSeqTSS_neighborhood.png) | ![ ](https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/A549_10_overlap.png) |
| ![ ](https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/emissions_10.png) | ![ ](https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/transitions_10.png) | |



### Картинки из UCSC GenomeBrowser
![ ](https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/GB1.png)
![ ](https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/GB2.png)
![ ](https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/GB3.png)

| | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| ------------- | ------------- | ------------- | ------------- | ------------- |  ------------- | ------------- |  ------------- | ------------- | ------------- |   
| Частые гистоновые метки | H3k04me2, H3k04me3 | H3k04me2, H3k04me3 |H3k04me2, H3k04me3 | - | - | - | H3k04me3 | H3k04me1, H3k04me2, H3k04me3  | - |
| Название | Промотор | Промотор | Промотор | - | - | - | Похоже на энхансер | Инсулятор | - |

Промоторы заметные, часто встречаются и находятся перед генами. 

## Часть 2
<img src="https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/names.png" width=400>
С помощью python был получен файл такого вида:
<img src="https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/Data_example.png" width=600>

### Картинки из UCSC GenomeBrowser
![ ](https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/GB_labeled1.png)
![ ](https://github.com/IlonaGA/hse_hw3_chromhmm/blob/main/images/GB_labeled2.png)

