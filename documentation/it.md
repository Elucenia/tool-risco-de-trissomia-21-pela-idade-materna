<!-- ELUCENIA technical documentation · risco-de-trissomia-21-pela-idade-materna · it · no clinical/professional/rights approval -->

# Rischio di sindrome di Down per età materna

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/risco-de-trissomia-21-pela-idade-materna)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Età materna alla data presunta del parto

`idade`

anni · intervallo: 15–50

## Edizione del metodo

Morris–Mutton–Alberman 2002: modello logistico nati vivi inglese/gallese 1989–1998; non rischio gestazionale universale

## Formula documentata

Morris, Mutton, Alberman (2002): rischio = 1 ÷ \[1 + e(7,330 − 4,211 ÷ (1 + e−0,282 × (età − 37,23)))\]

Modello logistico del registro nazionale Down di Inghilterra/Galles (1989 a 1998), corretto per assenza di screening e interruzione.

## Limiti e popolazione

Questa formula descrive la prevalenza della sindrome di Down nei nati vivi per età materna, da dati di Inghilterra e Galles del 1989–1998, stimando l’assenza di screening e interruzione selettiva della gravidanza. Non fornisce il rischio a qualsiasi età gestazionale e non sostituisce lo screening o la diagnosi individuale.

## Riferimenti

- [Morris JK, Mutton DE, Alberman E. Revised estimates of the maternal age specific live birth prevalence of Down's syndrome. J Med Screen, 2002.](https://doi.org/10.1136/jms.9.1.2)

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

Rischio basale (a priori) a 35 anni: 0,28%

| Dettagli del risultato | |
| --- | --- |
| Probabilità | 0,283% |

È il rischio di partenza: lo screening combinato o il NIPT lo modificano verso l’alto o verso il basso.


### 2

Rischio basale (a priori) a 40 anni: 1,16%

| Dettagli del risultato | |
| --- | --- |
| Probabilità | 1,164% |

È il rischio di partenza: lo screening combinato o il NIPT lo modificano verso l’alto o verso il basso.


### 3

Rischio basale (a priori) a 25 anni: 0,07%

| Dettagli del risultato | |
| --- | --- |
| Probabilità | 0,075% |

È il rischio di partenza: lo screening combinato o il NIPT lo modificano verso l’alto o verso il basso.

