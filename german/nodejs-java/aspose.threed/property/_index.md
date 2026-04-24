---
title: Property
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/property/
---
## Property class

Klasse zum Halten benutzerdefinierter Eigenschaften.  @hideconstructor


## Methoden

### getValue{#getValue}

| Name | Beschreibung |
| --- | --- |
| getValue() | Liest oder setzt den Wert. Der Wert. |

 **Result:**



---


### setValue{#setValue}

| Name | Beschreibung |
| --- | --- |
| setValue(value) | Liest oder setzt den Wert. Der Wert. |

 **Result:**



---


### setName{#setName}

| Name | Beschreibung |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| Name | Beschreibung |
| --- | --- |
| getValueType() | Liest den Typ des Eigenschaftswerts. Der Typ des Wertes. |

 **Result:**



---


### getProperties{#getProperties}

| Name | Beschreibung |
| --- | --- |
| getProperties() | Liefert die Sammlung aller Eigenschaften. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Name | Beschreibung |
| --- | --- |
| getBindPoint(anim, create) | Liest den Bindungspunkt der Eigenschaft in der angegebenen Animationsinstanz. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| anim | AnimationNode | Bei welcher Animation der Bindungspunkt erstellt werden soll. |
| erstellen | boolean | Erstelle den Bindungspunkt der Eigenschaft, falls er nicht gefunden wird. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| getKeyframeSequence(anim, create) | Liest die Keyframe-Sequenz der angegebenen Animationsinstanz. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| anim | AnimationNode | Bei welcher Animation die Keyframe-Sequenz erstellt werden soll. |
| erstellen | boolean | Erstelle die Keyframe-Sequenz, falls sie nicht gefunden wird. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Gibt eine Zeichenkette zurück, die die aktuelle Eigenschaft darstellt. |

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



