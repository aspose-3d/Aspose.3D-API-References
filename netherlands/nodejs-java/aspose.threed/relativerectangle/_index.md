---
title: "RelativeRectangle"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

Relatieve rechthoek  De formule tussen relatief onderdeel en absolute waarde is:  Schaal  (Referentiebreedte) + offset  Dus als we het een absolute waarde willen laten vertegenwoordigen, laat alle schaalvelden op nul staan en gebruik in plaats daarvan offsetvelden.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(left, top, width, height) | Maak een RelativeRectangle |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| lef | Nummer | null |
| to | Nummer | null |
| breedte | Nummer | null |
| hoogte | Nummer | null |

 **Result:**



---


### getScaleX{#getScaleX}

| Naam | Beschrijving |
| --- | --- |
| getScaleX() | Relatieve coördinaat X |

 **Result:**



---


### setScaleX{#setScaleX}

| Naam | Beschrijving |
| --- | --- |
| setScaleX(value) | Relatieve coördinaat X |

 **Result:**



---


### getScaleY{#getScaleY}

| Naam | Beschrijving |
| --- | --- |
| getScaleY() | Relatieve coördinaat Y |

 **Result:**



---


### setScaleY{#setScaleY}

| Naam | Beschrijving |
| --- | --- |
| setScaleY(value) | Relatieve coördinaat Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| Naam | Beschrijving |
| --- | --- |
| getScaleWidth() | Relatieve breedte |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| Naam | Beschrijving |
| --- | --- |
| setScaleWidth(value) | Relatieve breedte |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| Naam | Beschrijving |
| --- | --- |
| getScaleHeight() | Relatieve hoogte |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| Naam | Beschrijving |
| --- | --- |
| setScaleHeight(value) | Relatieve hoogte |

 **Result:**



---


### getOffsetX{#getOffsetX}

| Naam | Beschrijving |
| --- | --- |
| getOffsetX() | Haalt de offset voor coördinaat X op of stelt deze in |

 **Result:**



---


### setOffsetX{#setOffsetX}

| Naam | Beschrijving |
| --- | --- |
| setOffsetX(value) | Haalt de offset voor coördinaat X op of stelt deze in |

 **Result:**



---


### getOffsetY{#getOffsetY}

| Naam | Beschrijving |
| --- | --- |
| getOffsetY() | Haalt de offset voor coördinaat Y op of stelt deze in |

 **Result:**



---


### setOffsetY{#setOffsetY}

| Naam | Beschrijving |
| --- | --- |
| setOffsetY(value) | Haalt de offset voor coördinaat Y op of stelt deze in |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| Naam | Beschrijving |
| --- | --- |
| getOffsetWidth() | Haalt of stelt de offset voor breedte in |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| Naam | Beschrijving |
| --- | --- |
| setOffsetWidth(value) | Haalt of stelt de offset voor breedte in |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| Naam | Beschrijving |
| --- | --- |
| getOffsetHeight() | Haalt of stelt de offset voor hoogte in |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| Naam | Beschrijving |
| --- | --- |
| setOffsetHeight(value) | Haalt of stelt de offset voor hoogte in |

 **Result:**



---


### toAbsolute{#toAbsolute}

| Naam | Beschrijving |
| --- | --- |
| toAbsolute(left, top, width, height) | Converteer de relatieve rechthoek naar een absolute rechthoek |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| links | Nummer | Linkerzijde van de rechthoek |
| boven | Nummer | Bovenkant van de rechthoek |
| width | Nummer | Breedte van de rechthoek |
| height | Nummer | Hoogte van de rechthoek |

 **Result:**
Rect


---


### fromScale{#fromScale}

| Naam | Beschrijving |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | Construeer een RelativeRectangle met alle offsetvelden op nul en schaalvelden uit de gegeven parameters. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| schaal | Nummer | null |
| schaal | Nummer | null |
| scaleWidt | Nummer | null |
| scaleHeigh | Nummer | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Converteert de waarde van deze instantie naar een java.lang.String. |

 **Result:**
RelativeRectangle


---



