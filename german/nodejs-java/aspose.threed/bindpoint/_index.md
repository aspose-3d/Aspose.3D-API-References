---
title: BindPoint
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

Ein BindPoint wird normalerweise auf einer Eigenschaft eines Objekts erstellt; einige Eigenschaftstypen enthalten mehrere Komponentenfelder (wie ein Vector3‑Feld).  BindPoint erzeugt für jedes Komponentenfeld einen Kanal und verbindet das Feld über die Kanäle mit einer oder mehreren Keyframe‑Sequenz‑Instanz(en).


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(scene, prop) | Initialisiert eine neue Instanz der Klasse BindPoint. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| scene | Szene | Die Szene, die die Animation enthält. |
| prop | Property | Eigenschaft. |

 **Result:**



---


### getProperty{#getProperty}

| Name | Beschreibung |
| --- | --- |
| getProperty() | Liefert die mit der CurveMapping verknüpfte Eigenschaft |

 **Result:**



---


### setProperty{#setProperty}

| Name | Beschreibung |
| --- | --- |
| setProperty(value) | Liefert die mit der CurveMapping verknüpfte Eigenschaft |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Name | Beschreibung |
| --- | --- |
| getChannelsCount() | Liefert die Gesamtzahl der Eigenschaftskanäle, die in dieser Animationskurvenzuordnung definiert sind. |

 **Result:**
Number


---


### getName{#getName}

| Name | Beschreibung |
| --- | --- |
| getName() | Gibt den Namen zurück oder legt ihn fest. Der Name. |

 **Result:**
Number


---


### setName{#setName}

| Name | Beschreibung |
| --- | --- |
| setName(value) | Gibt den Namen zurück oder legt ihn fest. Der Name. |

 **Result:**
Number


---


### getProperties{#getProperties}

| Name | Beschreibung |
| --- | --- |
| getProperties() | Liefert die Sammlung aller Eigenschaften. |

 **Result:**
Number


---


### get{#get}

| Name | Beschreibung |
| --- | --- |
| get(channelName) |  |

 **Result:**
Number


---


### getKeyframeSequence{#getKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| getKeyframeSequence(channelName) | Liefert die erste Keyframe‑Sequenz im angegebenen Kanal |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| channelName | String | Der zu findende Kanalname |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| Name | Beschreibung |
| --- | --- |
| getKeyframeSequences(channelName) | Ruft alle Keyframe‑Sequenzen im angegebenen Kanal ab |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| channelName | String | Der zu findende Kanalname |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| createKeyframeSequence(name) | Erstellt eine neue Kurve und verbindet sie mit dem ersten Kanal der Kurvenzuordnung |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Der Name der neuen Sequenz. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Binde die Keyframe‑Sequenz an den angegebenen Kanal |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| channelName | String | Welcher Kanal, an den die Keyframe‑Sequenz gebunden wird |
| sequence | KeyframeSequence | Die zu bindende Keyframe‑Sequenz |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Name | Beschreibung |
| --- | --- |
| getChannel(channelName) | Liefert den Kanal mit dem angegebenen Namen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| channelName | String | Der zu findende Kanalname |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| Name | Beschreibung |
| --- | --- |
| addChannel(name, value) | Fügt die angegebene Kanal‑Eigenschaft hinzu. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name. |
| Wert | Object | Wert. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| Name | Beschreibung |
| --- | --- |
| addChannel(name, type, value) | Fügt die angegebene Kanal‑Eigenschaft hinzu. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name. |
| type | Klasse | Typ. |
| Wert | Object | Wert. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Name | Beschreibung |
| --- | --- |
| resetChannels() | Leert die Eigenschaftskanäle dieser Animationskurvenzuordnung. |

 **Result:**
boolean


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Formatiert das Objekt in einen String |

 **Result:**
String


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entfernt eine dynamische Eigenschaft. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | Property | Welche Eigenschaft zu entfernen ist |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entferne die angegebene Eigenschaft, die durch ihren Namen identifiziert wird |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Name | Beschreibung |
| --- | --- |
| getProperty(property) | Liefere den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |

 **Result:**
Object


---


### setProperty{#setProperty}

| Name | Beschreibung |
| --- | --- |
| setProperty(property, value) | Setzt den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |
| Wert | Object | Der Wert der Eigenschaft |

 **Result:**
Object


---


### findProperty{#findProperty}

| Name | Beschreibung |
| --- | --- |
| findProperty(propertyName) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propertyName | String | Eigenschaftsname. |

 **Result:**
Property


---



