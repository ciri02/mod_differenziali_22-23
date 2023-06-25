# Modelli Differenziali
## a.a. 2022-23

Alcune delucidazioni in merito al codice Latex.

1. Il file principale si chiama "mod_differenziali.tex", e al suo interno è contenuta la prima pagina.
2. Tutti i contenuti delle lezioni sono nella cartella "Days", dove sono divisi per data. Ciascuno di questi file è compilato tramite l'apposito comando \input
3. Ogni personalizzazione, pacchetto caricato, etc. è contenuto nel file "unito_ii.tex"

Per quanto riguarda le personalizzazioni:
- ci sono un certo numero di comandi abbastanza intuitivi, volti a dare un minimo di coerenza al documento;
- all'interno del documento, ho creato due ambienti: uno per i teoremi, e uno per tutto il resto; ho cercato pertanto di scrivere tutto all'interno di questi ambienti, e nulla al di fuori; (nota a pié pagina)

Notazione: l'unica cosa un po' particolare è l'uso del grassetto.
Sono **in grassetto**
- elementi di R^n, per n>1
- le funzioni **a valori** in R^n, per n>1 (qualsiasi sia il dominio)

Non sono in grassetto:
- matrici
- funzioni che restituiscono matrici
- scalari

Nota a pié pagina: mi rendo conto di non aver spiegato affatto questa cosa, ma è piuttosto complicata.