---
title: RelativeRectangle
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

Relatives Rechteck  Die Formel zur Umrechnung von relativer Komponente in absoluten Wert lautet:  Skalierung  (Referenzbreite) + Versatz  Wenn wir also einen absoluten Wert darstellen wollen, lassen Sie alle Skalierungsfelder auf Null und verwenden stattdessen die Versatzfelder.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(left, top, width, height) | Erstelle ein RelativeRectangle |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| lef | Number | null |
| to | Number | null |
| Breite | Number | null |
| Höhe | Number | null |

 **Result:**



---


### getScaleX{#getScaleX}

| Name | Beschreibung |
| --- | --- |
| getScaleX() | Relative X‑Koordinate |

 **Result:**



---


### setScaleX{#setScaleX}

| Name | Beschreibung |
| --- | --- |
| setScaleX(value) | Relative X‑Koordinate |

 **Result:**



---


### getScaleY{#getScaleY}

| Name | Beschreibung |
| --- | --- |
| getScaleY() | Relative Y‑Koordinate |

 **Result:**



---


### setScaleY{#setScaleY}

| Name | Beschreibung |
| --- | --- |
| setScaleY(value) | Relative Y‑Koordinate |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| Name | Beschreibung |
| --- | --- |
| getScaleWidth() | Relative Breite |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| Name | Beschreibung |
| --- | --- |
| setScaleWidth(value) | Relative Breite |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| Name | Beschreibung |
| --- | --- |
| getScaleHeight() | Relative Höhe |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| Name | Beschreibung |
| --- | --- |
| setScaleHeight(value) | Relative Höhe |

 **Result:**



---


### getOffsetX{#getOffsetX}

| Name | Beschreibung |
| --- | --- |
| getOffsetX() | Liest oder setzt den Versatz für die X-Koordinate |

 **Result:**



---


### setOffsetX{#setOffsetX}

| Name | Beschreibung |
| --- | --- |
| setOffsetX(value) | Liest oder setzt den Versatz für die X-Koordinate |

 **Result:**



---


### getOffsetY{#getOffsetY}

| Name | Beschreibung |
| --- | --- |
| getOffsetY() | Liest oder setzt den Versatz für die Y-Koordinate |

 **Result:**



---


### setOffsetY{#setOffsetY}

| Name | Beschreibung |
| --- | --- |
| setOffsetY(value) | Liest oder setzt den Versatz für die Y-Koordinate |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| Name | Beschreibung |
| --- | --- |
| getOffsetWidth() | Liest oder setzt den Versatz für die Breite |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| Name | Beschreibung |
| --- | --- |
| setOffsetWidth(value) | Liest oder setzt den Versatz für die Breite |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| Name | Beschreibung |
| --- | --- |
| getOffsetHeight() | Liest oder setzt den Versatz für die Höhe |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| Name | Beschreibung |
| --- | --- |
| setOffsetHeight(value) | Liest oder setzt den Versatz für die Höhe |

 **Result:**



---


### toAbsolute{#toAbsolute}

| Name | Beschreibung |
| --- | --- |
| toAbsolute(left, top, width, height) | Konvertiere das relative Rechteck in ein absolutes Rechteck |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| links | Number | Links des Rechtecks |
| oben | Number | Oben des Rechtecks |
| Breite | Number | Breite des Rechtecks |
| height | Number | Höhe des Rechtecks |

 **Result:**
Rect


---


### fromScale{#fromScale}

| Name | Beschreibung |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | Konstruiert ein RelativeRectangle mit allen Versatzfeldern auf Null und Skalierungsfeldern aus den angegebenen Parametern. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Skalierung | Number | null |
| Skalierung | Number | null |
| scaleWidt | Number | null |
| scaleHeigh | Number | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Konvertiert den Wert dieser Instanz in einen java.lang.String. |

 **Result:**
RelativeRectangle


---



