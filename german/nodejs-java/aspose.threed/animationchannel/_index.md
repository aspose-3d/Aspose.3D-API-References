---
title: "AnimationChannel"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
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
| getComponentType() | Liest den Typ des Komponentenfeldes. |

 **Result:**



---


### getName{#getName}

| Name | Beschreibung |
| --- | --- |
| getName() | Liest den Namen des Kanals. |

 **Result:**



---


### getDefaultValue{#getDefaultValue}

| Name | Beschreibung |
| --- | --- |
| getDefaultValue() | Liest oder setzt den Standardwert des Kanals. Wenn ein Kanal keine Keyframe‑Sequenzen verbunden hat, wird der Standardwert während der Animationsauswertung verwendet. Ein reales Szenario: Animation animiert nur die x‑Koordinate eines Knotens, y und z werden nicht geändert, dann wird der Standardwert während der vollständigen Übersetzungsauswertung verwendet. |

 **Result:**



---


### setDefaultValue{#setDefaultValue}

| Name | Beschreibung |
| --- | --- |
| setDefaultValue(value) | Liest oder setzt den Standardwert des Kanals. Wenn ein Kanal keine Keyframe‑Sequenzen verbunden hat, wird der Standardwert während der Animationsauswertung verwendet. Ein reales Szenario: Animation animiert nur die x‑Koordinate eines Knotens, y und z werden nicht geändert, dann wird der Standardwert während der vollständigen Übersetzungsauswertung verwendet. |

 **Result:**



---


### getKeyframeSequences{#getKeyframeSequences}

| Name | Beschreibung |
| --- | --- |
| getKeyframeSequences() | Gibt alle Keyframe‑Sequenzen in diesem Kanal zurück |

 **Result:**



---


### addKeyframeSequence{#addKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| addKeyframeSequence(sequence) | Fügt eine Keyframe‑Sequenz zu diesem Kanal hinzu |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Sequenz | KeyframeSequence | Die hinzuzufügende Keyframe‑Sequenz. |

 **Result:**



---


### iterator{#iterator}

| Name | Beschreibung |
| --- | --- |
| iterator() | Für die interne Verwendung reserviert. |

 **Result:**



---



