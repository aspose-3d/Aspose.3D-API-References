---
title: "Eigenschaft"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
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
| getProperties() | Ruft die Sammlung aller Eigenschaften ab. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Name | Beschreibung |
| --- | --- |
| getBindPoint(anim, create) | Liest den Bind-Punkt der Eigenschaft in der angegebenen Animationsinstanz. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| anim | AnimationNode | Bei welcher Animation der Bind-Punkt erstellt werden soll. |
| create | boolean | Erstelle den Bind-Punkt der Eigenschaft, falls er nicht gefunden wird. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| getKeyframeSequence(anim, create) | Ruft die Keyframe‑Sequenz einer angegebenen Animationsinstanz ab. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| anim | AnimationNode | Bei welcher Animation die Keyframe‑Sequenz erstellt werden soll. |
| create | boolean | Erstellt die Keyframe‑Sequenz, falls sie nicht gefunden wird. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Gibt einen String zurück, der die aktuelle Eigenschaft darstellt. |

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



