# Laboratorio di Big Data - a.a. 2022/2023

## Informazioni utili

E-mail: roberto.grasso@phd.unict.it

## Ambiente di sviluppo


Non è necessario installare Spark sui vostri computer! Possiamo configurare l'ambiente di lavoro in maniera totalmente containerizzata.

Tutto ciò che ci servirà sarà Docker e un editor di testo. Il mio suggerimento è di usare Visual Studio Code. Il motivo? Visual Studio Code offre un buon supporto per Python, i container Docker e i Jupyter Notebook.

Per avviare i container basta lanciare (dalla root del progetto) il seguente comando:

`docker compose up -d`

Per arrestarli:

`docker compose stop`

È possibile aumentare il numero di worker, ad esempio a 3, avviando i container con il seguente comando:

`docker compose up -d --scale spark-worker=3`

Spark Web UI:

`http://localhost:8080/`

Per visualizzare i log di uno specifico container:

`docker logs laboratoriobigdataunict-spark-1`

## Dev Container
Il progetto prevede l'utilizzo di un dev container per lo sviluppo. Per avviarlo è necessario installare l'estensione `Remote - Containers` di VSCode. Una volta installata, è possibile avviare il dev container cliccando sull'icona in basso a sinistra nella barra di stato di VSCode e selezionando `Reopen in Container`.


