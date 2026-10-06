<!-- ELUCENIA technical documentation · pressao-arterial-media · it · no clinical/professional/rights approval -->

# Pressione arteriosa media e pressione differenziale

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/pressao-arterial-media)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Pressione sistolica

`pas`

mmHg · intervallo: 50–300

### Pressione diastolica

`pad`

mmHg · intervallo: 20–200

## Edizione del metodo

PAM=(PAS+2 PAD)/3; pressione differenziale PAS−PAD; approssimazione adulta a ritmo convenzionale; guida brasiliana 2020

## Formula documentata

PAM = PA diastolica + (PA sistolica − PA diastolica) ÷ 3

Pressione differenziale = PA sistolica − PA diastolica

## Limiti e popolazione

L’approssimazione come pressione diastolica più un terzo della pressione differenziale presuppone frequenza cardiaca normale, secondo la dichiarazione AHA 2019; non è l’integrazione diretta della curva pressoria. Usare valori sistolici e diastolici in mmHg ottenuti con tecnica e dispositivo appropriati e documentare le condizioni della misura. Sistolica meno diastolica è la pressione differenziale, non la frequenza del polso. Il risultato isolato non stabilisce diagnosi di ipertensione né un obiettivo universale per pazienti critici.

## Riferimenti

- [Barroso WKS et al. Diretrizes Brasileiras de Hipertensão Arterial – 2020. Arq Bras Cardiol, 2021.](https://doi.org/10.36660/abc.20201238)

- [AHA scientific statement2019,Measurement of Blood Pressure in Humans](https://pmc.ncbi.nlm.nih.gov/articles/PMC11409525/)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Ipertensione stadio 1 (DBHA 2020)

| Dettagli del risultato | |
| --- | --- |
| Pressione differenziale | 50 mmHg |


### 2

Ipertensione stadio 3 (DBHA 2020)

| Dettagli del risultato | |
| --- | --- |
| Pressione differenziale | 90 mmHg |

Pressione del polso > 60 mmHg: negli anziani suggerisce rigidità arteriosa.


### 3

PA ottimale (DBHA 2020)

| Dettagli del risultato | |
| --- | --- |
| Pressione differenziale | 40 mmHg |

