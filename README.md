## Finite-Mixtures-in-R

# Panoramica
Questo progetto analizza il dataset del World Happiness Report per comprendere le relazioni tra vari fattori che influenzano i punteggi di felicità in 155 paesi. Applicando modelli di miscele finite e tecniche di clustering, miriamo a scoprire schemi e somiglianze tra i paesi basati sui loro punteggi di felicità e sulle metriche associate.

# Dataset
Il dataset utilizzato per questa analisi è il World Happiness Report 2018. Include vari indicatori come il PIL pro capite, il supporto sociale, l'aspettativa di vita sana, la libertà di fare scelte, la generosità e la percezione della corruzione.
"https://www.kaggle.com/datasets/unsdsn/world-happiness"

# Obiettivi
Analisi delle correlazioni: Esaminare le relazioni tra i punteggi di felicità e altre variabili.
Clustering: Identificare gruppi di paesi simili in base ai punteggi di felicità e ai loro determinanti.
Modellizzazione delle miscele finite: Esplorare la distribuzione dei punteggi di felicità utilizzando modelli di miscele finite.
Strumenti e Librerie

Il progetto è implementato in R utilizzando i seguenti pacchetti:

mclust per la modellizzazione delle miscele finite
ggplot2 e plotly per la visualizzazione dei dati
dplyr e tidyverse per la manipolazione dei dati
factoextra per le visualizzazioni di clustering
Boruta per la selezione delle variabili
FactoMineR per PCA e MCA
