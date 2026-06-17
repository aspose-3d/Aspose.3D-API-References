---
title: "RelativeRectangle"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

Relativ rektangel  Formeln mellan relativ komponent och absolut värde är:  Scale  (Reference Width) + offset  Så om vi vill att den ska representera ett absolut värde, lämna alla scale-fält noll, och använd offset-fält istället.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(left, top, width, height) | Skapa en RelativeRectangle |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| vänster | Nummer | null |
| to | Nummer | null |
| bredd | Nummer | null |
| höjd | Nummer | null |

 **Result:**



---


### getScaleX{#getScaleX}

| Namn | Beskrivning |
| --- | --- |
| getScaleX() | Relativ koordinat X |

 **Result:**



---


### setScaleX{#setScaleX}

| Namn | Beskrivning |
| --- | --- |
| setScaleX(value) | Relativ koordinat X |

 **Result:**



---


### getScaleY{#getScaleY}

| Namn | Beskrivning |
| --- | --- |
| getScaleY() | Relativ koordinat Y |

 **Result:**



---


### setScaleY{#setScaleY}

| Namn | Beskrivning |
| --- | --- |
| setScaleY(value) | Relativ koordinat Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| Namn | Beskrivning |
| --- | --- |
| getScaleWidth() | Relativ bredd |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| Namn | Beskrivning |
| --- | --- |
| setScaleWidth(value) | Relativ bredd |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| Namn | Beskrivning |
| --- | --- |
| getScaleHeight() | Relativ höjd |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| Namn | Beskrivning |
| --- | --- |
| setScaleHeight(value) | Relativ höjd |

 **Result:**



---


### getOffsetX{#getOffsetX}

| Namn | Beskrivning |
| --- | --- |
| getOffsetX() | Hämtar eller anger förskjutningen för koordinat X |

 **Result:**



---


### setOffsetX{#setOffsetX}

| Namn | Beskrivning |
| --- | --- |
| setOffsetX(value) | Hämtar eller anger förskjutningen för koordinat X |

 **Result:**



---


### getOffsetY{#getOffsetY}

| Namn | Beskrivning |
| --- | --- |
| getOffsetY() | Hämtar eller anger förskjutningen för koordinat Y |

 **Result:**



---


### setOffsetY{#setOffsetY}

| Namn | Beskrivning |
| --- | --- |
| setOffsetY(value) | Hämtar eller anger förskjutningen för koordinat Y |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| Namn | Beskrivning |
| --- | --- |
| getOffsetWidth() | Hämtar eller anger förskjutningen för bredd |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| Namn | Beskrivning |
| --- | --- |
| setOffsetWidth(value) | Hämtar eller anger förskjutningen för bredd |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| Namn | Beskrivning |
| --- | --- |
| getOffsetHeight() | Hämtar eller anger förskjutningen för höjd |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| Namn | Beskrivning |
| --- | --- |
| setOffsetHeight(value) | Hämtar eller anger förskjutningen för höjd |

 **Result:**



---


### toAbsolute{#toAbsolute}

| Namn | Beskrivning |
| --- | --- |
| toAbsolute(left, top, width, height) | Konvertera den relativa rektangeln till en absolut rektangel |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| vänster | Nummer | Vänster på rektangeln |
| överkant | Nummer | Överst på rektangeln |
| bredd | Nummer | Bredd på rektangeln |
| height | Nummer | Höjd på rektangeln |

 **Result:**
Rect


---


### fromScale{#fromScale}

| Namn | Beskrivning |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | Skapa en RelativeRectangle med alla förskjutningsfält noll och skalafält från angivna parametrar. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| scale | Nummer | null |
| scale | Nummer | null |
| scaleWidt | Nummer | null |
| scaleHeigh | Nummer | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Konverterar värdet av denna instans till en java.lang.String. |

 **Result:**
RelativeRectangle


---



