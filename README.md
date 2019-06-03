# Visualizzazione delle Informazioni - Progetto iniziale
Progetto iniziale (ed individuale) di Visualizzazione delle Informazioni, svolto da **Camilla Bianca** (matricola **461663**).

## Specifica del progetto
"*Crea un file json con dei dati multivariati: ci sono 20 data-point e ogni data-point ha cinque variabili quantitative i cui valori sono tutti positivi. In base a questi dati disegna 20 facce con diverse caratteristiche (rotondità della faccia, dimensione del naso, dimensione degli occhi, bocca sorridente o triste, ecc) associando ogni caratteristica ad una variabile. Facendo click con il pulsante sinistro su una caratteristica di una faccia, tutte le facce si dispongono in un ordine da sinistra a destra corrispondente all'ordinamento dei rispettivi data-point in base alla variabile associata a quella caratteristica. Fai in modo che i cambi di disposizione delle facce avvengano con un'animazione fluida.*"

### Note del progetto:
Si noti che le orecchie sono un dettaglio estetico aggiuntivo, difatti sono tutte uguali e non fanno parte delle 5 caratteristiche facciali da ordinare. Lo stesso vale per il colore della pelle, che viene assegnato (ogni volta che si carica la pagina) a ciascuna faccia in modo casuale, e non costituisce motivo di ordinamento. Inoltre, sono state aggiunte delle etichette al passaggio del mouse per facilitare la selezione della caratteristica giusta.
Le caratteristiche facciali su cui si può cliccare sono: *bocca, naso, sopracciglia, contorno occhi, interno occhi.*

## Sviluppo in locale
Per visualizzare correttamente il progetto, è necessario creare un server locale sulla directory di lavoro. Una volta posizionati nella cartella corrente, eseguire da terminale il comando seguente:
```
python -m SimpleHTTPServer 8888 &
```
Dopodiché è necessario aprire il browser e digitare:
```
http://localhost:8888
```

## Browser testati
Il progetto è stato testato e viene visualizzato correttamente sui seguenti browser:
- **Google Chrome**, versione 74.0.3729.169 (Build ufficiale) (a 64 bit);
- **Mozilla Firefox**, versione 67.0 (64 bit).

## Anteprima
Immagine
