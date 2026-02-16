
# Violent_crimes_rate_USA

## Progetto per l'esame di intelligenza artificiale II

L’obiettivo del presente lavoro è cogliere possibili relazioni tra variabili socio-economiche ed il tasso di criminalità negli Stati Uniti d’America nel periodo che va dal 1980 al 2023. Tale problema di regressione è stato affrontato in modi distinti: durante le fasi di evaluation è emersa la necessità di adottare modelli regolarizzati (Ridge Regression) e di passare da uno split temporale a uno casuale (Random Split) per catturare correttamente la varianza dei dati.  
Complessivamente il modello interpreta bene le variabili socio-economiche e il loro trend annuale 
(𝑅2=0.73), ma fatica a gestire i picchi più estremi. Interessante è l’evidenza di un “cambio di paradigma” dopo il 2017. Il modello, infatti, non riesce a prevedere l'aumento recente del crimine basandosi solo sulle serie storiche passate, rivelando una modificazione delle dinamiche sociali che prescindono dai dati. A livello concettuale, l'analisi dimostra che il fattore geografico (lo Stato) pesa più dell'economia; tuttavia, isolando le variabili sociali, la povertà si conferma l'unico vero motore del crimine, mentre urbanizzazione e disuguaglianza mostrano, sorprendentemente, un impatto marginale. 

# Librerie 

Le librerie utilizzate sono state molteplici:  
1. pandas  
2. matplotlib.pyplot   
3. seaborn  
4. numpy  
5. statsmodels.api  
6. sklearn  
   6.1 sklearn.model_selection  
   6.2 sklearn.linear_model  
   6.3 sklearn.preprocessing  
   6.4 sklearn.metrics  

# Dataset

Complessivamente il dataset utilizzato è il risultato di una serie di annessioni di varie tabelle, possiede 2193 righe e 10 colonne: Stato, Anno, popolazione, numero di crimini, tasso di povertà, tasso di educazione, tasso di disoccupazione, tasso di urbanizzazione, indice gini, percentuale di crimini violenti.

# Codice

Il codice è stato leggermente modificato per permettere all'utente di avere il dataset direttamente nell'ambiente colab utilizzando le proprietà di Github, per esegurilo basterà eseguire tutte le celle nell'ordine presente.
