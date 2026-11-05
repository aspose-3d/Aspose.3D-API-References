---
title: "RelativeRectangle"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

Relatives Rechteck  Die Formel zur Umrechnung von relativen Komponenten in absolute Werte lautet:  Skalierung  (Referenzbreite) + Offset  Wenn wir also einen absoluten Wert darstellen wollen, setzen wir alle Skalierungsfelder auf Null und verwenden stattdessen Offset-Felder.


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
| lef | Zahl | null |
| to | Zahl | null |
| Breite | Zahl | null |
| Höhe | Zahl | null |

 **Result:**



---


### getScaleX{#getScaleX}

| Name | Beschreibung |
| --- | --- |
| getScaleX() | Relative Koordinate X |

 **Result:**



---


### setScaleX{#setScaleX}

| Name | Beschreibung |
| --- | --- |
| setScaleX(value) | Relative Koordinate X |

 **Result:**



---


### getScaleY{#getScaleY}

| Name | Beschreibung |
| --- | --- |
| getScaleY() | Relative Koordinate Y |

 **Result:**



---


### setScaleY{#setScaleY}

| Name | Beschreibung |
| --- | --- |
| setScaleY(value) | Relative Koordinate Y |

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
| getOffsetX() | Ermittelt oder legt den Versatz für die Koordinate X fest |

 **Result:**



---


### setOffsetX{#setOffsetX}

| Name | Beschreibung |
| --- | --- |
| setOffsetX(value) | Ermittelt oder legt den Versatz für die Koordinate X fest |

 **Result:**



---


### getOffsetY{#getOffsetY}

| Name | Beschreibung |
| --- | --- |
| getOffsetY() | Ermittelt oder legt den Versatz für die Koordinate Y fest |

 **Result:**



---


### setOffsetY{#setOffsetY}

| Name | Beschreibung |
| --- | --- |
| setOffsetY(value) | Ermittelt oder legt den Versatz für die Koordinate Y fest |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| Name | Beschreibung |
| --- | --- |
| getOffsetWidth() | Ermittelt oder legt den Versatz für die Breite fest |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| Name | Beschreibung |
| --- | --- |
| setOffsetWidth(value) | Ermittelt oder legt den Versatz für die Breite fest |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| Name | Beschreibung |
| --- | --- |
| getOffsetHeight() | Ermittelt oder legt den Versatz für die Höhe fest |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| Name | Beschreibung |
| --- | --- |
| setOffsetHeight(value) | Ermittelt oder legt den Versatz für die Höhe fest |

 **Result:**



---


### toAbsolute{#toAbsolute}

| Name | Beschreibung |
| --- | --- |
| toAbsolute(left, top, width, height) | Konvertiert das relative Rechteck in ein absolutes Rechteck |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| links | Zahl | Linke Seite des Rechtecks |
| oben | Zahl | Obere Kante des Rechtecks |
| width | Zahl | Breite des Rechtecks |
| height | Zahl | Höhe des Rechtecks |

 **Result:**
Rect


---


### fromScale{#fromScale}

| Name | Beschreibung |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | Erstelle ein RelativeRectangle mit allen Offset-Feldern auf Null und den Skalierungsfeldern aus den angegebenen Parametern. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Skalierung | Zahl | null |
| Skalierung | Zahl | null |
| scaleWidt | Zahl | null |
| scaleHeigh | Zahl | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Konvertiert den Wert dieser Instanz zu einem java.lang.String. |

 **Result:**
RelativeRectangle


---



