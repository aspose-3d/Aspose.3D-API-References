---
title: AnimationChannel
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/animationchannel/
---
## AnimationChannel class

Ein Kanal ordnet das Komponentenfeld einer Eigenschaft einer Menge von Keyframe‑Sequenzen zu  @hideconstructor


## Methoden

### getComponentType{#getComponentType}

| Name | Beschreibung |
| --- | --- |
| getComponentType() | Ermittelt den Typ des Komponentenfeldes |

 **Result:**



---


### getName{#getName}

| Name | Beschreibung |
| --- | --- |
| getName() | Liest den Namen des Kanals |

 **Result:**



---


### getDefaultValue{#getDefaultValue}

| Name | Beschreibung |
| --- | --- |
| getDefaultValue() | Liest oder setzt den Default‑Wert des Kanals. Wenn ein Kanal keine Keyframe‑Sequenzen verbunden hat, wird der Default‑Wert während der Animationsauswertung verwendet. Ein konkretes Szenario: Die Animation animiert nur die x‑Koordinate eines Knotens, y und z werden nicht geändert, dann wird der Default‑Wert während der vollständigen Transformationsauswertung verwendet. |

 **Result:**



---


### setDefaultValue{#setDefaultValue}

| Name | Beschreibung |
| --- | --- |
| setDefaultValue(value) | Liest oder setzt den Default‑Wert des Kanals. Wenn ein Kanal keine Keyframe‑Sequenzen verbunden hat, wird der Default‑Wert während der Animationsauswertung verwendet. Ein konkretes Szenario: Die Animation animiert nur die x‑Koordinate eines Knotens, y und z werden nicht geändert, dann wird der Default‑Wert während der vollständigen Transformationsauswertung verwendet. |

 **Result:**



---


### getKeyframeSequences{#getKeyframeSequences}

| Name | Beschreibung |
| --- | --- |
| getKeyframeSequences() | Liest alle Keyframe‑Sequenzen innerhalb dieses Kanals |

 **Result:**



---


### addKeyframeSequence{#addKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| addKeyframeSequence(sequence) | Fügt eine Keyframe‑Sequenz zu diesem Kanal hinzu |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| sequence | KeyframeSequence | Die hinzuzufügende Keyframe‑Sequenz. |

 **Result:**



---


### iterator{#iterator}

| Name | Beschreibung |
| --- | --- |
| iterator() | Für den internen Gebrauch reserviert. |

 **Result:**



---



