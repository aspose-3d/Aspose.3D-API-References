---
title: Node
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/node/
---
## Node class

Stellt ein Element im Szenengraphen dar. Ein Szenengraph ist ein Baum von Node-Objekten. Die Baumverwaltungsdienste sind in dieser Klasse eigenständig enthalten. Beachten Sie, dass das Aspose.3D SDK die Gültigkeit des konstruierten Szenengraphen nicht prüft. Es liegt in der Verantwortung des Aufrufers sicherzustellen, dass keine zyklischen Graphen in einer Node-Hierarchie erzeugt werden. Neben der Baumverwaltung definiert diese Klasse alle Eigenschaften, die erforderlich sind, um die Position des Objekts in der Szene zu beschreiben. Diese Informationen umfassen die grundlegenden Eigenschaften Translation, Rotation und Skalierung sowie die erweiterten Optionen für Drehpunkte, Grenzen und IK-Gelenkattribute wie Steifigkeit und Dämpfung. Wenn es zum ersten Mal erstellt wird, ist das Node-Objekt "empty" (d.h.: es ist ein Objekt ohne jegliche grafische Darstellung, das nur Positionsinformationen enthält). In diesem Zustand kann es verwendet werden, um Eltern im Node-Baum zu repräsentieren, aber nicht viel mehr. Die übliche Verwendung dieser Objekttypen besteht darin, ihnen eine Entität hinzuzufügen, die den Node spezialisieren wird (siehe die "Entity"). Die Entität ist ein eigenständiges Objekt und ist mit dem Node verbunden. Das bedeutet auch, dass dieselbe Entität zwischen mehreren Nodes geteilt werden kann. Kamera, Licht, Mesh usw. sind alle Entitäten und sie alle leiten sich von der Basisklasse Entity ab.


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
| Name | String | Name. |
| entity | Entity | Standard-Entität. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(name) | Initialisiert eine neue Instanz der Node-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Name | Beschreibung |
| --- | --- |
| getAssetInfo() | Asset-Informationen pro Knoten |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Name | Beschreibung |
| --- | --- |
| setAssetInfo(value) | Asset-Informationen pro Knoten |

 **Result:**



---


### getVisible{#getVisible}

| Name | Beschreibung |
| --- | --- |
| getVisible() | Liest oder setzt, um den Knoten anzuzeigen |

 **Result:**



---


### setVisible{#setVisible}

| Name | Beschreibung |
| --- | --- |
| setVisible(value) | Liest oder setzt, um den Knoten anzuzeigen |

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
| getExcluded() | Liest oder setzt, ob dieser Knoten und alle Kindknoten/Entitäten beim Exportieren ausgeschlossen werden. |

 **Result:**



---


### setExcluded{#setExcluded}

| Name | Beschreibung |
| --- | --- |
| setExcluded(value) | Liest oder setzt, ob dieser Knoten und alle Kindknoten/Entitäten beim Exportieren ausgeschlossen werden. |

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
| getMetaDatas() | Liest die in diesem Knoten definierten Metadaten. Die Metadaten. |

 **Result:**



---


### getMaterials{#getMaterials}

| Name | Beschreibung |
| --- | --- |
| getMaterials() | Liest die mit diesem Knoten verbundenen Materialien. Die Materialien. |

 **Result:**



---


### getMaterial{#getMaterial}

| Name | Beschreibung |
| --- | --- |
| getMaterial() | Liest oder setzt das erste Material, das mit diesem Knoten verbunden ist; beim Setzen werden andere Materialien gelöscht. Das Material. |

 **Result:**



---


### setMaterial{#setMaterial}

| Name | Beschreibung |
| --- | --- |
| setMaterial(value) | Liest oder setzt das erste Material, das mit diesem Knoten verbunden ist; beim Setzen werden andere Materialien gelöscht. Das Material. |

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
| getScene() | Liefert die Szene, zu der dieses Objekt gehört |

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


### createChildNode{#createChildNode}

| Name | Beschreibung |
| --- | --- |
| createChildNode() | Erstellt einen Kindknoten |

 **Result:**
Node


---


### merge{#merge}

| Name | Beschreibung |
| --- | --- |
| merge(node) | Löst alles unter dem Knoten und hängt es am aktuellen Knoten an. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nod | Node | null |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Name | Beschreibung |
| --- | --- |
| createChildNode(nodeName) | Erstelle einen neuen Kindknoten mit dem angegebenen Knotennamen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der Name des neuen Kindknotens |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Name | Beschreibung |
| --- | --- |
| createChildNode(entity) | Erstelle einen neuen Kindknoten mit angehängter gegebener Entität |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| entity | Entity | Standard-Entität, die an den Knoten angehängt ist |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Name | Beschreibung |
| --- | --- |
| createChildNode(nodeName, entity) | Erstelle einen neuen Kindknoten mit dem angegebenen Knotennamen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der Name des neuen Kindknotens |
| entity | Entity | Standard-Entität, die an den Knoten angehängt ist |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Name | Beschreibung |
| --- | --- |
| createChildNode(nodeName, entity, material) | Erstelle einen neuen Kindknoten mit dem angegebenen Knotennamen und hänge die angegebene Entität sowie ein Material an |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der Name des neuen Kindknotens |
| entity | Entity | Standard-Entität, die an den Knoten angehängt ist |
| Material | Material | Das an den Knoten angehängte Material |

 **Result:**
Node


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Name | Beschreibung |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Bewerte die globale Transformation, die geometrische Transformation einbeziehen oder nicht. |

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
| Index | Number | Index. |

 **Result:**
Node


---


### getChild{#getChild}

| Name | Beschreibung |
| --- | --- |
| getChild(nodeName) | Gibt den Kindknoten mit dem angegebenen Namen zurück. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nodeName | String | Der zu findende Kindname. |

 **Result:**
Node


---


### accept{#accept}

| Name | Beschreibung |
| --- | --- |
| accept(visitor) | Durchläuft alle Nachfolgerknoten (einschließlich des aktuellen Knotens) und ruft den Besucher mit dem Knoten auf. Der Besucher kann den Durchlauf abbrechen, indem er false zurückgibt. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Besucher | NodeVisitor | Besucher-Callback, um den Knoten zu besuchen. |

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
| getBoundingBox() | Berechne die Begrenzungsbox des Knotens |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| Name | Beschreibung |
| --- | --- |
| addEntity(entity) | Füge dem Node eine Entität hinzu |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| entity | Entity | Die an den Knoten anzuhängende Entität |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| Name | Beschreibung |
| --- | --- |
| addChildNode(node) | Füge diesem Node einen Kind-Node hinzu |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| node | Node | Der anzuhängende Kindknoten |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| Name | Beschreibung |
| --- | --- |
| selectSingleObject(path) | Wähle ein einzelnes Objekt unter dem aktuellen Knoten mit XPath-ähnlicher Abfragesyntax aus. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| pat | String | null |

 **Result:**
Object


---


### selectObjects{#selectObjects}

| Name | Beschreibung |
| --- | --- |
| selectObjects(path) | Wähle mehrere Objekte unter dem aktuellen Knoten mit XPath-ähnlicher Abfragesyntax aus. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| pat | String | null |

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



