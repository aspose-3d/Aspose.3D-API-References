---
title: "RevolvedAreaSolid"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/revolvedareasolid/
---
## RevolvedAreaSolid class

Diese Klasse stellt ein Festkörpermodell dar, indem ein Querschnitt, der durch ein Profil bereitgestellt wird, um eine Achse rotiert wird.


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
| getParentNodes() | Gibt alle übergeordneten Knoten zurück, ein Entity kann für Geometrieinstanzierung an mehrere übergeordnete Knoten angehängt werden. Die Knoten. |

 **Result:**



---


### getExcluded{#getExcluded}

| Name | Beschreibung |
| --- | --- |
| getExcluded() | Liest oder setzt, ob dieses Entity beim Exportieren ausgeschlossen werden soll. |

 **Result:**



---


### setExcluded{#setExcluded}

| Name | Beschreibung |
| --- | --- |
| setExcluded(value) | Liest oder setzt, ob dieses Entity beim Exportieren ausgeschlossen werden soll. |

 **Result:**



---


### getParentNode{#getParentNode}

| Name | Beschreibung |
| --- | --- |
| getParentNode() | Liest oder setzt den ersten übergeordneten Knoten, wenn der erste übergeordnete Knoten gesetzt ist, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

 **Result:**



---


### setParentNode{#setParentNode}

| Name | Beschreibung |
| --- | --- |
| setParentNode(value) | Liest oder setzt den ersten übergeordneten Knoten, wenn der erste übergeordnete Knoten gesetzt ist, wird dieses Entity von anderen übergeordneten Knoten getrennt. Der übergeordnete Knoten. |

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


### toMesh{#toMesh}

| Name | Beschreibung |
| --- | --- |
| toMesh() | Konvertiere das RevolverAreaSolid in ein Mesh. |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Ruft die Bounding-Box der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem ab. |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| Name | Beschreibung |
| --- | --- |
| getEntityRendererKey() | Ruft den Schlüssel des im Renderer registrierten Entity-Renderers ab. |

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



