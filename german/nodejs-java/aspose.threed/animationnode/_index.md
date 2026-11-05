---
title: "AnimationNode"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D unterstützt die Animationshierarchie, jede Animation kann aus mehreren Animationen und der Key‑Frame‑Definition einer Animation zusammengesetzt werden.  AnimationNode definiert die Transformation eines Eigenschaftswerts über die Zeit, zum Beispiel kann ein Animationsknoten verwendet werden, um die Transformation eines Knotens oder andere numerische Eigenschaften eines A3DObject‑Objekts zu steuern.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Initialisiert eine neue Instanz der Klasse AnimationNode. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name |

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
| getBindPoints() | Liest die aktuellen Property-Bind-Punkte |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| Name | Beschreibung |
| --- | --- |
| getSubAnimations() | Liest die Unteranimationsknoten unter den aktuellen Animationen |

 **Result:**



---


### getName{#getName}

| Name | Beschreibung |
| --- | --- |
| getName() | Liest oder setzt den Namen. Der Name. |

 **Result:**



---


### setName{#setName}

| Name | Beschreibung |
| --- | --- |
| setName(value) | Liest oder setzt den Namen. Der Name. |

 **Result:**



---


### getProperties{#getProperties}

| Name | Beschreibung |
| --- | --- |
| getProperties() | Ruft die Sammlung aller Eigenschaften ab. |

 **Result:**



---


### findBindPoint{#findBindPoint}

| Name | Beschreibung |
| --- | --- |
| findBindPoint(name) | Findet den Bind-Punkt nach Namen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name des Bind-Punkts, der gefunden werden soll. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| Name | Beschreibung |
| --- | --- |
| getBindPoint(target, propName, create) | Liest den Animations-Bind-Punkt für die angegebene Property. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| target | A3DObject | Auf welchem Objekt der Bind-Punkt erstellt werden soll. |
| propName | String | Der Name der Property. |
| create | boolean | Wenn festgelegt auf |

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
| target | A3DObject | Auf welcher Instanz die Keyframe‑Sequenz erstellt werden soll. |
| propName | String | Der Name der Property. |
| channelName | String | Der Kanalname. |
| create | boolean | Wenn festgelegt auf |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| Name | Beschreibung |
| --- | --- |
| getKeyframeSequence(target, propName, create) | Ruft die Keyframe‑Sequenz für die angegebene Eigenschaft ab. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| target | A3DObject | Auf welcher Instanz die Keyframe‑Sequenz erstellt werden soll. |
| propName | String | Der Name der Property. |
| create | boolean | Wenn festgelegt auf |

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



