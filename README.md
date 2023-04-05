# hse_hw3_chromhmm
## Colab
https://colab.research.google.com/drive/1RSdkkfsV8iAwMIMk4VnugHoR9DGhqaFn?usp=sharing
## Гистоновые Метки
Имя | Файл
--- | ---
H3K27ac | wgEncodeBroadHistoneGm12878H3k27acStdAlnRep1.bam
H3K27me3 | wgEncodeBroadHistoneGm12878H3k27me3StdAlnRep1.bam
H3K36me3 | wgEncodeBroadHistoneGm12878H3k36me3StdAlnRep1.bam
H3K4me1 | wgEncodeBroadHistoneGm12878H3k4me1StdAlnRep1.bam
H3K4me2 | wgEncodeBroadHistoneGm12878H3k4me2StdAlnRep1.bam
H3K4me3 | wgEncodeBroadHistoneGm12878H3k4me3StdAlnRep1.bam
H3K79me2 | wgEncodeBroadHistoneGm12878H3k79me2StdAlnRep1.bam
H3K9ac | wgEncodeBroadHistoneGm12878H3k9acStdAlnRep1.bam
H3K9me3 | wgEncodeBroadHistoneGm12878H3k9me3StdAlnRep1.bam
H4K20me1 | wgEncodeBroadHistoneGm12878H4k20me1StdAlnRep1.bam
## ChromHMM

Emission | Overlap | Transition 
 --- | --- | ---
![Image](/data/emissions_10.png) | ![Image](/data/GM12878_10_overlap.png) | ![Image](/data/transitions_10.png)

RefSeqTSS | RefSeqTES 
 --- | --- 
![Image](/data/GM12878_10_RefSeqTSS_neighborhood.png) | ![Image](/data/GM12878_10_RefSeqTES_neighborhood.png)

## Эпигенетические типы
№ | Название | Описание | Картинка
 --- | --- | ---| ---
1 | Active Promoter | <ul><li> выражен в H3K27me1 </li><li> Чаще всего на RefSeqTES и LaminB1lads </li> | ![Image](/data/state_1.png)
2 | Weak enhancer/Weak transcribed | <ul><li> выражен в H3K27ac, H3K4me2, H3K4me1 </li><li> Чаще всего находятся на RefSeqTES </li> | ![Image](/data/state_2.png)
3 | Strong enhancer/Transcriptional elogation | <ul><li> выражен в H3K4me2 </li><li> Чаще всего находятся на CpGisland, RefseqExon, RefSeqTES и RefSeqTSS2Kb </li> | ![Image](/data/state_3.png)
4 | Active Promoter | <ul><li> выражен в H3K9ac, H3K27ac, H3K4me3, H3K4me2, H3K79me2 </li><li> Чаще всего находятся на CpGIsland, REfRefSeqTSS, REfRefSeqTES, RefSeqExon и RefSeqTSS2Kb </li> | ![Image](/data/state_4.png)
5 | Active Promoter | <ul><li> выражен в H3K79me2 </li><li> Чаще всего находятся на RefSeqGene </li> | ![Image](/data/state_5.png)
6 | Weak enhancer | <ul><li> выражен в H3K79me2 </li><li> Чаще всего находятся на RefSeqGene  </li>| ![Image](/data/state_6.png)
7 | Weak enhancer | <ul><li> выражен в H3K36me3 </li><li> Чаще всего находятся на RefSeqTES </li>| ![Image](/data/state_7.png)
8 | Weak enhancer | <ul><li> слабо выражен </li><li> Чаще всего находятся на LaminB1lads </li> | 
9 | Weak enhancer | <ul><li> выражен в H3K4me3 </li><li> Чаще всего находятся на RefSeqTES и LaminB1lads </li> | ![Image](/data/state_9.png)
10 | Weak transcribed | <ul><li> выражен в H3K27me3 </li><li> Чаще всего находятся на LaminB1lads </li> | ![Image](/data/state_10.png)
