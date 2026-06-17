---
title: "RelativeRectangle"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

Relatieve rechthoek  De formule tussen een relatief component en een absolute waarde is:  Schaal  (Referentiebreedte) + offset  Dus als we willen dat het een absolute waarde vertegenwoordigt, laat alle schaalvelden op nul staan en gebruik in plaats daarvan offsetvelden.


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
| constructor_overload(left, top, width, height) | Construeer een RelativeRectangle |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| links | Number | null |
| to | Number | null |
| widt | Number | null |
| heigh | Number | null |

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
| getOffsetX() | Haalt de offset op of stelt deze in voor coördinaat X |

 **Result:**



---


### setOffsetX{#setOffsetX}

| Naam | Beschrijving |
| --- | --- |
| setOffsetX(value) | Haalt de offset op of stelt deze in voor coördinaat X |

 **Result:**



---


### getOffsetY{#getOffsetY}

| Naam | Beschrijving |
| --- | --- |
| getOffsetY() | Haalt de offset op of stelt deze in voor coördinaat Y |

 **Result:**



---


### setOffsetY{#setOffsetY}

| Naam | Beschrijving |
| --- | --- |
| setOffsetY(value) | Haalt de offset op of stelt deze in voor coördinaat Y |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| Naam | Beschrijving |
| --- | --- |
| getOffsetWidth() | Haalt de offset op of stelt deze in voor breedte |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| Naam | Beschrijving |
| --- | --- |
| setOffsetWidth(value) | Haalt de offset op of stelt deze in voor breedte |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| Naam | Beschrijving |
| --- | --- |
| getOffsetHeight() | Haalt de offset op of stelt deze in voor hoogte |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| Naam | Beschrijving |
| --- | --- |
| setOffsetHeight(value) | Haalt de offset op of stelt deze in voor hoogte |

 **Result:**



---


### toAbsolute{#toAbsolute}

| Naam | Beschrijving |
| --- | --- |
| toAbsolute(left, top, width, height) | Converteer de relatieve rechthoek naar een absolute rechthoek |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| left | Number | Linkerkant van de rechthoek |
| top | Number | Bovenkant van de rechthoek |
| breedte | Number | Breedte van de rechthoek |
| height | Number | Hoogte van de rechthoek |

 **Result:**
Rect


---


### fromScale{#fromScale}

| Naam | Beschrijving |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | Construeer een RelativeRectangle met alle offsetvelden op nul en schaalvelden uit de opgegeven parameters. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| schaal | Number | null |
| schaal | Number | null |
| scaleWidt | Number | null |
| scaleHeigh | Number | null |

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



