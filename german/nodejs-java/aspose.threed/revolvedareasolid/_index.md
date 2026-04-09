---
title: RevolvedAreaSolid
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/revolvedareasolid/
---
## RevolvedAreaSolid class

Diese Klasse repräsentiert ein Festkörpermodell, indem sie einen Querschnitt, der von einem Profil bereitgestellt wird, um eine Achse dreht.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getAngleStart{#getAngleStart}

| Name | Beschreibung |
| --- | --- |
| getAngleStart() | Liest oder setzt den Startwinkel des Drehvorgangs, gemessen in Radiant, Standardwert ist 0. |

 **Result:**



---


### setAngleStart{#setAngleStart}

| Name | Beschreibung |
| --- | --- |
| setAngleStart(value) | Liest oder setzt den Startwinkel des Drehvorgangs, gemessen in Radiant, Standardwert ist 0. |

 **Result:**



---


### getAngleEnd{#getAngleEnd}

| Name | Beschreibung |
| --- | --- |
| getAngleEnd() | Liest oder setzt den Endwinkel des Drehvorgangs, gemessen in Radiant, Standardwert ist π. |

 **Result:**



---


### setAngleEnd{#setAngleEnd}

| Name | Beschreibung |
| --- | --- |
| setAngleEnd(value) | Liest oder setzt den Endwinkel des Drehvorgangs, gemessen in Radiant, Standardwert ist π. |

 **Result:**



---


### getAxis{#getAxis}

| Name | Beschreibung |
| --- | --- |
| getAxis() | Liest oder setzt die Achsenrichtung, Standardwert ist (0, 1, 0). |

 **Result:**



---


### setAxis{#setAxis}

| Name | Beschreibung |
| --- | --- |
| setAxis(value) | Liest oder setzt die Achsenrichtung, Standardwert ist (0, 1, 0). |

 **Result:**



---


### getOrigin{#getOrigin}

| Name | Beschreibung |
| --- | --- |
| getOrigin() | Liest oder setzt den Ursprungspunkt des Drehvorgangs, Standardwert ist (0, 0, 0). |

 **Result:**



---


### setOrigin{#setOrigin}

| Name | Beschreibung |
| --- | --- |
| setOrigin(value) | Liest oder setzt den Ursprungspunkt des Drehvorgangs, Standardwert ist (0, 0, 0). |

 **Result:**



---


### getShape{#getShape}

| Name | Beschreibung |
| --- | --- |
| getShape() | Liest oder setzt das Basisprofil, das zum Drehen verwendet wird. |

 **Result:**



---


### setShape{#setShape}

| Name | Beschreibung |
| --- | --- |
| setShape(value) | Liest oder setzt das Basisprofil, das zum Drehen verwendet wird. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Name | Beschreibung |
| --- | --- |
| getParentNodes() | Gibt alle übergeordneten Knoten zurück, ein Entity kann für Geometrie-Instanziierung an mehrere übergeordnete Knoten angehängt werden. Die Knoten. |

 **Result:**



---


### getExcluded{#getExcluded}

| Name | Beschreibung |
| --- | --- |
| getExcluded() | Gibt an oder legt fest, ob dieses Entity beim Exportieren ausgeschlossen wird. |

 **Result:**



---


### setExcluded{#setExcluded}

| Name | Beschreibung |
| --- | --- |
| setExcluded(value) | Gibt an oder legt fest, ob dieses Entity beim Exportieren ausgeschlossen wird. |

 **Result:**



---


### getParentNode{#getParentNode}

| Name | Beschreibung |
| --- | --- |
| getParentNode() | Gibt den ersten übergeordneten Knoten zurück oder legt ihn fest; wenn der erste übergeordnete Knoten gesetzt wird, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

 **Result:**



---


### setParentNode{#setParentNode}

| Name | Beschreibung |
| --- | --- |
| setParentNode(value) | Gibt den ersten übergeordneten Knoten zurück oder legt ihn fest; wenn der erste übergeordnete Knoten gesetzt wird, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

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


### toMesh{#toMesh}

| Name | Beschreibung |
| --- | --- |
| toMesh() | Konvertiert das RevolvedAreaSolid in ein Mesh. |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Liefert die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| Name | Beschreibung |
| --- | --- |
| getEntityRendererKey() | Liefert den Schlüssel des Entitäts-Renderers, der im Renderer registriert ist |

 **Result:**
EntityRendererKey


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



