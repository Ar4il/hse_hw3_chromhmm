# hse_hw3_chromhmm
https://colab.research.google.com/drive/1vAjI5GKsFCJ-OvvPsCrvlmp9J39JkX6l?usp=sharing

ГИСТОНОВЫЕ МЕТКИ

wgEncodeBroadHistoneK562H2azStdAlnRep1.bam H2AFZ

wgEncodeBroadHistoneK562H3k27acStdAlnRep1.bam  H3k27ac

wgEncodeBroadHistoneK562H3k27me3StdAlnRep1.bam  H3k27me3

wgEncodeBroadHistoneK562H3k36me3StdAlnRep1.bam  H3k36me3

wgEncodeBroadHistoneK562H3k4me1StdAlnRep1.bam  H3k4me1

wgEncodeBroadHistoneK562H3k4me2StdAlnRep1.bam  H3k4me2

wgEncodeBroadHistoneK562H3k4me3StdAlnRep1.bam  H3k4me3

wgEncodeBroadHistoneK562H3k79me2StdAlnRep1.bam H3k79me2

wgEncodeBroadHistoneK562H3k9acStdAlnRep1.bam  H3k9ac

wgEncodeBroadHistoneK562H3k9me1StdAlnRep1.bam  H3k9me1

wgEncodeBroadHistoneK562H3k9me3StdAlnRep1.bam  H3k9me3

wgEncodeBroadHistoneK562H4k20me1StdAlnRep1.bam  K20me1

cellmarkfiletable.txt

K562	H2AFZ	H2AFZ.bam	Control.bam

K562	H3k27ac	H3k27ac.bam	Control.bam

K562	H3k27me3	H3k27me3.bam	Control.bam

K562	H3k36me3	H3k36me3.bam	Control.bam

K562	H3k4me1	H3k4me1.bam	Control.bam

K562	H3k4me2	H3k4me2.bam	Control.bam

K562	H3k4me3	H3k4me3.bam	Control.bam

K562	H3k79me2	H3k79me2.bam	Control.bam

K562	H3k9ac	H3k9ac.bam	Control.bam

K562	H3k9me1	H3k9me1.bam	Control.bam

K562	H3k9me3	H3k9me3.bam	Control.bam

K562	K20me1	K20me1.bam	Control.bam

Emission

![image](https://user-images.githubusercontent.com/84396301/230056180-9d939832-2e3b-49a7-8a57-b4742a3e23cf.png)

Transition

![image](https://user-images.githubusercontent.com/84396301/230056292-8682acf2-4e7c-405c-8439-07612a05d1c1.png)

Overlap

![image](https://user-images.githubusercontent.com/84396301/230056585-27aa739e-25ea-4b72-a5cc-26d9e76dfb93.png)

RefSeqTSS

![image](https://user-images.githubusercontent.com/84396301/230056814-6b5cbc6a-f9c4-43c4-a174-e7ed4f1e5d06.png)

RefSeqTES

![image](https://user-images.githubusercontent.com/84396301/230056947-9bf1e900-13df-453f-ad0c-d7ff4f013a86.png)

Эпигенетические типы

1.Polycomb-repressed. Чаще всего находятся на ядерной ламине, попадает на репрессированный участок. Выражен на H3k27me3. Не попадает на ген (видно на overlap)

![image](https://user-images.githubusercontent.com/84396301/230058738-ff1d5e50-0254-47cf-99b7-f1c5ba9c3dad.png)

2.Polycomb-repressed. Чаще всего находятся на ядерной ламине, попадает на репрессированный участок. Не попадает на ген (видно на overlap)

![image](https://user-images.githubusercontent.com/84396301/230059054-693c94f1-a135-405b-8fb3-bb725f3d2fb3.png)


3. Weak enhancer. Чаще всего находятся на ядерной ламине, так же попадает на RefSeqExon и RefSeqTES.

![image](https://user-images.githubusercontent.com/84396301/230059367-853ce19c-ad7d-43d4-87c1-9e4caf045846.png)

4.Weak transcribed. Находится на RefSeqGen, RefSeqTES и RefSeqExon. Выражен на H3k36me3. Попадает на экзон или интрон.

![image](https://user-images.githubusercontent.com/84396301/230059991-d4d1d53c-9325-448c-ba39-3d4d9f819c40.png)

5. Weak enhancer. Выражен на H3k79me2 и H3k04me1. Преимущественно находится на RefSeqGene. Попадает на интрон.

![image](https://user-images.githubusercontent.com/84396301/230061453-653670cf-3379-4876-a41e-5e1873c2787c.png)
