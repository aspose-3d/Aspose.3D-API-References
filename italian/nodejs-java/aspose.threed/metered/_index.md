---
title: "Metered"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/metered/
---
## Metered class

Fornisce metodi per impostare la chiave misurata.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza di questa classe. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| Nome | Descrizione |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | Imposta le chiavi pubblica e privata (publicKey, privateKey). Se acquisti una licenza a consumo, all'avvio dell'applicazione questa API deve essere chiamata; normalmente è sufficiente. Tuttavia, se il caricamento dei dati di consumo fallisce continuamente e supera le 24 ore, la licenza verrà impostata in modalità valutazione; per evitare questo caso, dovresti controllare regolarmente lo stato della licenza e, se è in modalità valutazione, chiamare nuovamente questa API. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| publicKey | Stringa | chiave pubblica |
| privateKey | Stringa | chiave privata |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| Nome | Descrizione |
| --- | --- |
| getConsumptionQuantity() | Ottiene la dimensione del file di consumo |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| Nome | Descrizione |
| --- | --- |
| getConsumptionCredit() | Ottiene il credito di consumo |

 **Result:**
BigDecimal


---



