---
title: "Knoten"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/node/
---
## Node class

Stellt ein Element im Szenengraphen dar.  Ein Szenengraph ist ein Baum von Node-Objekten. Die Baumverwaltungsdienste sind in dieser Klasse selbst enthalten.  Hinweis: Das Aspose.3D SDK prüft nicht die Gültigkeit des konstruierten Szenengraphen. Es liegt in der Verantwortung des Aufrufers sicherzustellen, dass es keine zyklischen Graphen in einer Node-Hierarchie erzeugt.  Neben der Baumverwaltung definiert diese Klasse alle Eigenschaften, die erforderlich sind, um die Position des Objekts in der Szene zu beschreiben. Diese Informationen umfassen die grundlegenden Eigenschaften Translation, Rotation und Skalierung sowie erweiterte Optionen für Drehpunkte, Grenzen und IK-Gelenkattribute wie Steifigkeit und Dämpfung.  Wenn es erstmals erstellt wird, ist das Node-Objekt "empty" (d. h.: es ist ein Objekt ohne grafische Darstellung, das nur Positionsinformationen enthält). In diesem Zustand kann es verwendet werden, um Eltern im Node-Baum zu repräsentieren, aber nicht viel mehr. Die übliche Verwendung dieser Objekttypen besteht darin, ihnen eine Entität hinzuzufügen, die den Node spezialisieren wird (siehe "Entity").  Die Entität ist ein eigenständiges Objekt und ist mit dem Node verbunden. Das bedeutet auch, dass dieselbe Entität zwischen mehreren Nodes geteilt werden kann. Kamera, Licht, Mesh usw. sind alle Entitäten und leiten alle von der Basisklasse Entity ab.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Node-Klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(name, entity) | Initialisiert eine neue Instanz der Node-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name. |
| Entität | Entität | Standard-Entität. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(name) | Initialisiert eine neue Instanz der Node-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Name | Beschreibung |
| --- | --- |
| getAssetInfo() | Pro-Knoten Asset-Informationen |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Name | Beschreibung |
| --- | --- |
| setAssetInfo(value) | Pro-Knoten Asset-Informationen |

 **Result:**



---


### getVisible{#getVisible}

| Name | Beschreibung |
| --- | --- |
| getVisible() | Liest oder setzt, um den Knoten anzuzeigen. |

 **Result:**



---


### setVisible{#setVisible}

| Name | Beschreibung |
| --- | --- |
| setVisible(value) | Liest oder setzt, um den Knoten anzuzeigen. |

 **Result:**



---


### getChildNodes{#getChildNodes}

| Name | Beschreibung |
| --- | --- |
| getChildNodes() | Liest die Kindknoten. Die Knoten. |

 **Result:**



---


### getEntity{#getEntity}

| Name | Beschreibung |
| --- | --- |
| getEntity() | Liest oder setzt die erste Entität, die an diesem Knoten angehängt ist; beim Setzen werden andere Entitäten gelöscht. Die Knotenentität. |

 **Result:**



---


### setEntity{#setEntity}

| Name | Beschreibung |
| --- | --- |
| setEntity(value) | Liest oder setzt die erste Entität, die an diesem Knoten angehängt ist; beim Setzen werden andere Entitäten gelöscht. Die Knotenentität. |

 **Result:**



---


### getExcluded{#getExcluded}

| Name | Beschreibung |
| --- | --- |
| getExcluded() | Liest oder setzt, ob dieser Knoten und alle Kindknoten/Entitäten beim Export ausgeschlossen werden sollen. |

 **Result:**



---


### setExcluded{#setExcluded}

| Name | Beschreibung |
| --- | --- |
| setExcluded(value) | Liest oder setzt, ob dieser Knoten und alle Kindknoten/Entitäten beim Export ausgeschlossen werden sollen. |

 **Result:**



---


### getEntities{#getEntities}

| Name | Beschreibung |
| --- | --- |
| getEntities() | Liest alle Knotenentitäten. Die Knotenentitäten. |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| Name | Beschreibung |
| --- | --- |
| getMetaDatas() | Liest die Metadaten, die in diesem Knoten definiert sind. Die Metadaten. |

 **Result:**



---


### getMaterials{#getMaterials}

| Name | Beschreibung |
| --- | --- |
| getMaterials() | Liest die Materialien, die mit diesem Knoten verknüpft sind. Die Materialien. |

 **Result:**



---


### getMaterial{#getMaterial}

| Name | Beschreibung |
| --- | --- |
| getMaterial() | Liest oder setzt das erste Material, das mit diesem Knoten verknüpft ist; beim Setzen werden andere Materialien gelöscht. Das Material. |

 **Result:**



---


### setMaterial{#setMaterial}

| Name | Beschreibung |
| --- | --- |
| setMaterial(value) | Liest oder setzt das erste Material, das mit diesem Knoten verknüpft ist; beim Setzen werden andere Materialien gelöscht. Das Material. |

 **Result:**



---


### getParentNode{#getParentNode}

| Name | Beschreibung |
| --- | --- |
| getParentNode() | Liest oder setzt den übergeordneten Knoten. Der übergeordnete Knoten. |

 **Result:**



---


### setParentNode{#setParentNode}

| Name | Beschreibung |
| --- | --- |
| setParentNode(value) | Liest oder setzt den übergeordneten Knoten. Der übergeordnete Knoten. |

 **Result:**



---


### getTransform{#getTransform}

| Name | Beschreibung |
| --- | --- |
| getTransform() | Liest die lokale Transformation. Die Transformation. |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| Name | Beschreibung |
| --- | --- |
| getGlobalTransform() | Liest die globale Transformation. Die globale Transformation. |

 **Result:**



---


### getScene{#getScene}

| Name | Beschreibung |
| --- | --- |
| getScene() | Ruft die Szene ab, zu der dieses Objekt gehört |

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


### createChildNode{#createChildNode}

| Name | Beschreibung |
| --- | --- |
| createChildNode() | Erstellt einen Kindknoten |

 **Result:**
Knoten


---


### merge{#merge}

| Name | Beschreibung |
| --- | --- |
| merge(node) | Lösen Sie alles unter dem Knoten und hängen Sie es an den aktuellen Knoten an. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nod | Knoten | null |

 **Result:**
Knoten


---


### createChildNode{#createChildNode}

| Name | Beschreibung |
| --- | --- |
| createChildNode(nodeName) | Erstellen Sie einen neuen Kindknoten mit dem angegebenen Knotennamen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der Name des neuen Kindknotens |

 **Result:**
Knoten


---


### createChildNode{#createChildNode}

| Name | Beschreibung |
| --- | --- |
| createChildNode(entity) | Erstellen Sie einen neuen Kindknoten mit der angegebenen Entität angehängt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Standard-Entität, die dem Knoten angehängt ist |

 **Result:**
Knoten


---


### createChildNode{#createChildNode}

| Name | Beschreibung |
| --- | --- |
| createChildNode(nodeName, entity) | Erstellen Sie einen neuen Kindknoten mit dem angegebenen Knotennamen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der Name des neuen Kindknotens |
| Entität | Entität | Standard-Entität, die dem Knoten angehängt ist |

 **Result:**
Knoten


---


### createChildNode{#createChildNode}

| Name | Beschreibung |
| --- | --- |
| createChildNode(nodeName, entity, material) | Erstellen Sie einen neuen Kindknoten mit dem angegebenen Knotennamen und hängen Sie die angegebene Entität sowie ein Material an |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der Name des neuen Kindknotens |
| Entität | Entität | Standard-Entität, die dem Knoten angehängt ist |
| material | Material | Das Material, das dem Knoten angehängt ist |

 **Result:**
Knoten


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Name | Beschreibung |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Bewerten Sie die globale Transformation, ob die geometrische Transformation einbezogen wird oder nicht. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| withGeometricTransform | boolean | Ob die geometrische Transformation benötigt wird. |

 **Result:**
Matrix4


---


### getChild{#getChild}

| Name | Beschreibung |
| --- | --- |
| getChild(index) | Gibt den Kindknoten am angegebenen Index zurück. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| index | Zahl | Index. |

 **Result:**
Knoten


---


### getChild{#getChild}

| Name | Beschreibung |
| --- | --- |
| getChild(nodeName) | Gibt den Kindknoten mit dem angegebenen Namen zurück |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der zu findende Kindknotenname. |

 **Result:**
Knoten


---


### accept{#accept}

| Name | Beschreibung |
| --- | --- |
| accept(visitor) | Durchläuft alle Nachfolgerknoten (einschließlich des aktuellen Knotens) und ruft den Besucher mit dem Knoten auf. Der Besucher kann den Durchlauf abbrechen, indem er false zurückgibt. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Besucher | NodeVisitor | Besucher-Callback, um den Knoten zu besuchen |

 **Result:**
boolean


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Gibt die Zeichenkettenrepräsentation dieses Knotens zurück. |

 **Result:**
String


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Berechnet die Begrenzungsbox des Knotens |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| Name | Beschreibung |
| --- | --- |
| addEntity(entity) | Fügt dem Knoten eine Entität hinzu. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die Entität, die dem Knoten angehängt werden soll |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| Name | Beschreibung |
| --- | --- |
| addChildNode(node) | Fügt diesem Knoten einen Kindknoten hinzu |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Knoten | Der Kindknoten, der angehängt werden soll |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| Name | Beschreibung |
| --- | --- |
| selectSingleObject(path) | Wählt ein einzelnes Objekt unter dem aktuellen Knoten aus, wobei eine XPath-ähnliche Abfragesyntax verwendet wird. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | null |

 **Result:**
Objekt


---


### selectObjects{#selectObjects}

| Name | Beschreibung |
| --- | --- |
| selectObjects(path) | Wählt mehrere Objekte unter dem aktuellen Knoten aus, wobei eine XPath-ähnliche Abfragesyntax verwendet wird. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


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



