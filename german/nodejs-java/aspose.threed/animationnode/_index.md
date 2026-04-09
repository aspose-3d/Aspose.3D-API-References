---
title: AnimationNode
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D unterstützt die Animationshierarchie, jede Animation kann aus mehreren Animationen und der Keyframe‑Definition einer Animation zusammengesetzt werden.  AnimationNode definiert die Transformation eines Eigenschaftswerts über die Zeit, zum Beispiel kann ein Animationsknoten verwendet werden, um die Transformation eines Knotens oder andere numerische Eigenschaften eines A3DObject‑Objekts zu steuern.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Initialisiert eine neue Instanz der Klasse AnimationNode. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload() | Initialisiert eine neue Instanz der Klasse AnimationNode. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| Name | Beschreibung |
| --- | --- |
| getBindPoints() | Liest die aktuellen Eigenschafts-Bindungspunkte |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| Name | Beschreibung |
| --- | --- |
| getSubAnimations() | Ruft die Unteranimationsknoten unter den aktuellen Animationen ab. |

 **Result:**



---


### getName{#getName}

| Name | Beschreibung |
| --- | --- |
| getName() | Gibt den Namen zurück oder legt ihn fest. Der Name. |

 **Result:**



---


### setName{#setName}

| Name | Beschreibung |
| --- | --- |
| setName(value) | Gibt den Namen zurück oder legt ihn fest. Der Name. |

 **Result:**



---


### getProperties{#getProperties}

| Name | Beschreibung |
| --- | --- |
| getProperties() | Liefert die Sammlung aller Eigenschaften. |

 **Result:**



---


### findBindPoint{#findBindPoint}

| Name | Beschreibung |
| --- | --- |
| findBindPoint(name) | Findet den Bindungspunkt anhand des Namens. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name des Bindungspunkts zum Finden. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| Name | Beschreibung |
| --- | --- |
| getBindPoint(target, propName, create) | Gibt den Animations-Bindungspunkt für die angegebene Eigenschaft zurück. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| target | A3DObject | Auf welchem Objekt der Bindungspunkt erstellt werden soll. |
| propName | String | Der Name der Eigenschaft. |
| erstellen | boolean | Wenn gesetzt auf |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | Ruft die Keyframe‑Sequenz für die angegebene Eigenschaft und den Kanal ab. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| target | A3DObject | Bei welcher Instanz die Keyframe‑Sequenz erstellt werden soll. |
| propName | String | Der Name der Eigenschaft. |
| channelName | String | Der Kanalname. |
| erstellen | boolean | Wenn gesetzt auf |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| getKeyframeSequence(target, propName, create) | Gibt die Keyframe-Sequenz für die angegebene Eigenschaft zurück. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| target | A3DObject | Bei welcher Instanz die Keyframe‑Sequenz erstellt werden soll. |
| propName | String | Der Name der Eigenschaft. |
| erstellen | boolean | Wenn gesetzt auf |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| Name | Beschreibung |
| --- | --- |
| createBindPoint(obj, propName) | Erstellt einen BindPoint basierend auf dem Datentyp der Eigenschaft. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| obj | A3DObject | Objekt. |
| propName | String | Eigenschaftsname. |

 **Result:**
BindPoint


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



