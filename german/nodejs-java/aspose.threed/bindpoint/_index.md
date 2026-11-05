---
title: "BindPoint"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
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
| constructor(scene, prop) | Initialisiert eine neue Instanz der BindPoint-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Szene | Szene | Die Szene, die die Animation enthält. |
| Eigenschaft | Eigenschaft | Eigenschaft. |

 **Result:**



---


### getProperty{#getProperty}

| Name | Beschreibung |
| --- | --- |
| getProperty() | Gibt die mit dem CurveMapping verbundene Eigenschaft zurück |

 **Result:**



---


### setProperty{#setProperty}

| Name | Beschreibung |
| --- | --- |
| setProperty(value) | Gibt die mit dem CurveMapping verbundene Eigenschaft zurück |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Name | Beschreibung |
| --- | --- |
| getChannelsCount() | Gibt die Gesamtzahl der Eigenschaftskanäle zurück, die in dieser Animationskurvenzuordnung definiert sind. |

 **Result:**
Zahl


---


### getName{#getName}

| Name | Beschreibung |
| --- | --- |
| getName() | Liest oder setzt den Namen. Der Name. |

 **Result:**
Zahl


---


### setName{#setName}

| Name | Beschreibung |
| --- | --- |
| setName(value) | Liest oder setzt den Namen. Der Name. |

 **Result:**
Zahl


---


### getProperties{#getProperties}

| Name | Beschreibung |
| --- | --- |
| getProperties() | Ruft die Sammlung aller Eigenschaften ab. |

 **Result:**
Zahl


---


### get{#get}

| Name | Beschreibung |
| --- | --- |
| get(channelName) |  |

 **Result:**
Zahl


---


### getKeyframeSequence{#getKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| getKeyframeSequence(channelName) | Gibt die erste Keyframe-Sequenz im angegebenen Kanal zurück |

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
| name | String | Der Name der neuen Sequenz. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Bindet die Keyframe‑Sequenz an den angegebenen Kanal |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| channelName | String | Welcher Kanal, an den die Keyframe‑Sequenz gebunden wird |
| Sequenz | KeyframeSequence | Die zu bindende Keyframe‑Sequenz |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Name | Beschreibung |
| --- | --- |
| getChannel(channelName) | Ruft den Kanal anhand des angegebenen Namens ab |

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
| name | String | Name. |
| value | Objekt | Wert. |

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
| name | String | Name. |
| Typ | Klasse | Typ. |
| value | Objekt | Wert. |

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
| toString() | Formatiert das Objekt zu einem String. |

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
| Eigenschaft | Eigenschaft | Welche Eigenschaft entfernt werden soll |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Name | Beschreibung |
| --- | --- |
| removeProperty(property) | Entfernt die angegebene Eigenschaft, die durch den Namen identifiziert wird. |

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
| getProperty(property) | Rufe den Wert der angegebenen Eigenschaft ab. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |

 **Result:**
Objekt


---


### setProperty{#setProperty}

| Name | Beschreibung |
| --- | --- |
| setProperty(property, value) | Setzt den Wert der angegebenen Eigenschaft |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Eigenschaft | String | Eigenschaftsname |
| value | Objekt | Der Wert der Eigenschaft |

 **Result:**
Objekt


---


### findProperty{#findProperty}

| Name | Beschreibung |
| --- | --- |
| findProperty(propertyName) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) sein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| propertyName | String | Eigenschaftsname. |

 **Result:**
Eigenschaft


---



