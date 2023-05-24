# Code used for dr. med. thesis
## Aggregate quantification

The `quantification.ipynb` file contains is a python script I wrote for the purposes of my dr. med. thesis which enables a researcher to quantify aggregates visible on 1024x1024 fluorescent microscopy images. I have used a skimage library with its modules __morpholgy__ and __measure__ which allowed me to locate, analyze and filter the areas in the image which are representing the fluorescent signal and henceforth find the aggregates.

To use the programme efficiently, provide a folder path with tiff images to the `analyze_folder(folder)` funciton.
If you have both experimental and control groups provide a folder with folders with tiff images for these 2 groups to the `quantification(folder)` function.

You can change the value for intensity of signal and of size of the aggregates for cut-off in the `render(path, threshold, size)` funciton. - You probably do not want to count objects which have week signal or small size, as aggregates. I found that for my images threshold = 70 and size = 400, show reliable results.


## Visualisations
Furthermore, all my plots used in the thesis are done with use of python in particular with matplotlib library.


# Thesis
## Thesis Title: 
__AAV-mediated anti-poly-GA antibody therapy against C9orf72 mutation related ALS/FTD__
## Abstract:
Neurodegenerative diseases constitute a continually increasing problem of the ageing societies of today’s world, however curative therapy options are for the most part lacking. Amyotrophic lateral sclerosis (ALS) and frontotemporal dementia (FTD) are no exception. Genetic, pathophysiological and clinical parallels of ALS and FTD suggest that they represent two ends of one disease spectrum. C9orf72 mutation is the most common genetic reason to cause either one, the other or both diseases simultaneously and is characterized by a massive expansion of GGGGCC repeat in this gene. An important pathophysiological mechanism in C9orf72 mutation is translation of the expanded repeat to dipeptide repeat (DPR) proteins. They form aggregates inside neurons resulting in their malfunction and ultimately leading to neurodegeneration. One of the DPR proteins, poly-GA, is regarded to be the most crucial for this process. Various therapy approaches have been attempted to tackle the DPR protein aggregation problem. Utilization of antibodies directed against the DPR-aggregates is one of the most promising ones. In this work AAV-guided antibody therapy was attempted. The therapy was tested on two poly-GA expressing C9-ALS/FTD mouse models. AAV 2/9 containing anti-poly-GA antibody transgene was used. The AAV was injected into the ventricular system of pups on postnatal day one by means of ultrasound guided intracerebroventricular injection. Conducted in this work in vitro experiments showed that AAV 2/9 transduction resulted in antibody expression in neurons. Moreover, the antibody was secreted by neurons and effectively bound to the poly-DPR aggregates. In vivo it was possible to show that the expression of the antibody after the ICV injection took place only in neurons, courtesy of hSynapsin promoter regulated transcription and that the antibody expression primarily took place in the frontal cortex. In GA-Nestin mouse model the therapy efficacy was investigated by measuring the weight and the extent of poly-GA aggregation at 4 weeks by aggregate quantification in immunofluorescent stains. In GA-Camk2A mouse model Barnes Maze performance was examined. The AAV-guided anti-poly-GA therapy neither inhibited the weight loss and poly-GA aggregation in GA-Nestin mice nor did it improve Barnes Maze performance of GA-Camk2A mice. These findings show that AAV-guided antibody therapy applied via ICV injection does not work in GA-Nestin or GA-Camk2A mouse models. However, different experimental design, like longer observation period in GA-Nestin mice or testing of the therapy on a different mouse model, which was already successfully treated with different therapy approach targeting the DPR-aggregates could be still investigated. Nevertheless, these findings provide additional insight to the realm of treatment possibilities in C9-ALS/FTD.