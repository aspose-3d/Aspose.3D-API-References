---
title: "RelativeRectangle"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

Rettangolo relativo  La formula tra componente relativo e valore assoluto è:  Scala  (Larghezza di riferimento) + offset  Quindi, se vogliamo rappresentare un valore assoluto, impostare tutti i campi scala a zero e utilizzare invece i campi offset.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(left, top, width, height) | Crea un RelativeRectangle |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| lef | Numero | null |
| to | Numero | null |
| widt | Numero | null |
| heigh | Numero | null |

 **Result:**



---


### getScaleX{#getScaleX}

| Nome | Descrizione |
| --- | --- |
| getScaleX() | Coordinata relativa X |

 **Result:**



---


### setScaleX{#setScaleX}

| Nome | Descrizione |
| --- | --- |
| setScaleX(value) | Coordinata relativa X |

 **Result:**



---


### getScaleY{#getScaleY}

| Nome | Descrizione |
| --- | --- |
| getScaleY() | Coordinata relativa Y |

 **Result:**



---


### setScaleY{#setScaleY}

| Nome | Descrizione |
| --- | --- |
| setScaleY(value) | Coordinata relativa Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| Nome | Descrizione |
| --- | --- |
| getScaleWidth() | Larghezza relativa |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| Nome | Descrizione |
| --- | --- |
| setScaleWidth(value) | Larghezza relativa |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| Nome | Descrizione |
| --- | --- |
| getScaleHeight() | Altezza relativa |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| Nome | Descrizione |
| --- | --- |
| setScaleHeight(value) | Altezza relativa |

 **Result:**



---


### getOffsetX{#getOffsetX}

| Nome | Descrizione |
| --- | --- |
| getOffsetX() | Ottiene o imposta lo scostamento per la coordinata X |

 **Result:**



---


### setOffsetX{#setOffsetX}

| Nome | Descrizione |
| --- | --- |
| setOffsetX(value) | Ottiene o imposta lo scostamento per la coordinata X |

 **Result:**



---


### getOffsetY{#getOffsetY}

| Nome | Descrizione |
| --- | --- |
| getOffsetY() | Ottiene o imposta lo scostamento per la coordinata Y |

 **Result:**



---


### setOffsetY{#setOffsetY}

| Nome | Descrizione |
| --- | --- |
| setOffsetY(value) | Ottiene o imposta lo scostamento per la coordinata Y |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| Nome | Descrizione |
| --- | --- |
| getOffsetWidth() | Ottiene o imposta lo scostamento per la larghezza |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| Nome | Descrizione |
| --- | --- |
| setOffsetWidth(value) | Ottiene o imposta lo scostamento per la larghezza |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| Nome | Descrizione |
| --- | --- |
| getOffsetHeight() | Ottiene o imposta lo scostamento per l'altezza |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| Nome | Descrizione |
| --- | --- |
| setOffsetHeight(value) | Ottiene o imposta lo scostamento per l'altezza |

 **Result:**



---


### toAbsolute{#toAbsolute}

| Nome | Descrizione |
| --- | --- |
| toAbsolute(left, top, width, height) | Converti il rettangolo relativo in rettangolo assoluto |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | Numero | Sinistra del rettangolo |
| alto | Numero | Alto del rettangolo |
| width | Numero | Larghezza del rettangolo |
| height | Numero | Altezza del rettangolo |

 **Result:**
Rect


---


### fromScale{#fromScale}

| Nome | Descrizione |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | Costruisci un RelativeRectangle con tutti i campi di offset a zero e i campi di scala dai parametri forniti. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| scala | Numero | null |
| scala | Numero | null |
| scaleWidt | Numero | null |
| scaleHeigh | Numero | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Converte il valore di questa istanza in una java.lang.String. |

 **Result:**
RelativeRectangle


---



