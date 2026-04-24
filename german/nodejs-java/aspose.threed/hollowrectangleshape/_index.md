---
title: HollowRectangleShape
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/hollowrectangleshape/
---
## HollowRectangleShape class

IFC-kompatible hohle rechteckige Form mit sowohl inneren als auch äußeren abgerundeten Ecken.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getWallThickness{#getWallThickness}

| Name | Beschreibung |
| --- | --- |
| getWallThickness() | Die Dicke zwischen der Begrenzung des Rechtecks und dem inneren Loch |

 **Result:**



---


### setWallThickness{#setWallThickness}

| Name | Beschreibung |
| --- | --- |
| setWallThickness(value) | Die Dicke zwischen der Begrenzung des Rechtecks und dem inneren Loch |

 **Result:**



---


### getInnerFilletRadius{#getInnerFilletRadius}

| Name | Beschreibung |
| --- | --- |
| getInnerFilletRadius() | Der innere Rundungsradius des inneren Rechtecks. |

 **Result:**



---


### setInnerFilletRadius{#setInnerFilletRadius}

| Name | Beschreibung |
| --- | --- |
| setInnerFilletRadius(value) | Der innere Rundungsradius des inneren Rechtecks. |

 **Result:**



---


### getRoundingRadius{#getRoundingRadius}

| Name | Beschreibung |
| --- | --- |
| getRoundingRadius() | Liest oder setzt den Radius der kreisförmigen Bögen aller vier Ecken, gemessen in Grad. Standardwert ist 0,0 |

 **Result:**



---


### setRoundingRadius{#setRoundingRadius}

| Name | Beschreibung |
| --- | --- |
| setRoundingRadius(value) | Liest oder setzt den Radius der kreisförmigen Bögen aller vier Ecken, gemessen in Grad. Standardwert ist 0,0 |

 **Result:**



---


### getXDim{#getXDim}

| Name | Beschreibung |
| --- | --- |
| getXDim() | Liest oder setzt die Ausdehnung des Rechtecks in Richtung der x-Achse. Standardwert ist 2,0 |

 **Result:**



---


### setXDim{#setXDim}

| Name | Beschreibung |
| --- | --- |
| setXDim(value) | Liest oder setzt die Ausdehnung des Rechtecks in Richtung der x-Achse. Standardwert ist 2,0 |

 **Result:**



---


### getYDim{#getYDim}

| Name | Beschreibung |
| --- | --- |
| getYDim() | Liest oder setzt die Ausdehnung des Rechtecks in Richtung der y-Achse. Standardwert ist 2,0 |

 **Result:**



---


### setYDim{#setYDim}

| Name | Beschreibung |
| --- | --- |
| setYDim(value) | Liest oder setzt die Ausdehnung des Rechtecks in Richtung der y-Achse. Standardwert ist 2,0 |

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


### getExtent{#getExtent}

| Name | Beschreibung |
| --- | --- |
| getExtent() | Ermittelt die Ausdehnung in x- und y-Richtung. |

 **Result:**
Vector2


---


### getEntityRendererKey{#getEntityRendererKey}

| Name | Beschreibung |
| --- | --- |
| getEntityRendererKey() | Liefert den Schlüssel des Entitäts-Renderers, der im Renderer registriert ist |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Liefert die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |

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



