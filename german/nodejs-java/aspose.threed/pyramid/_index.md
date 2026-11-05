---
title: "Pyramid"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/pyramid/
---
## Pyramid class

Parametrisierte Pyramide.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Erstelle eine neue Pyramiden-Instanz mit dem Standard‑Bodenbereich(10, 10) und der Standardhöhe(5) |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(xbottom, ybottom, height) | Erstelle eine neue Pyramiden-Instanz mit angegebenem Bodenbereich |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| xbottom | Zahl | Die x‑Richtungslänge des Bodens |
| ybottom | Zahl | Die y‑Richtungslänge des Bodens |
| height | Zahl | Die Höhe der Pyramide |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(xbottom, ybottom, xtop, ytop, height) | Erstelle eine neue Pyramiden-Instanz mit angegebenem Bodenbereich, Oberflächenbereich und Höhe. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| xbottom | Zahl | Die x‑Richtungslänge des Bodenbereichs |
| ybottom | Zahl | Die y‑Richtungslänge des Bodenbereichs |
| xtop | Zahl | Die x‑Richtungslänge des Oberflächenbereichs |
| ytop | Zahl | Die y‑Richtungslänge des Oberflächenbereichs |
| height | Zahl | Die Höhe der Pyramide |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Name | Beschreibung |
| --- | --- |
| constructor_overload3(name, xbottom, ybottom, xtop, ytop, height) | Erstelle eine neue Pyramiden-Instanz mit angegebenem Bodenbereich, Oberflächenbereich und Höhe. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Der Name der Pyramide |
| xbottom | Zahl | Die x‑Richtungslänge des Bodenbereichs |
| ybottom | Zahl | Die y‑Richtungslänge des Bodenbereichs |
| xtop | Zahl | Die x‑Richtungslänge des Oberflächenbereichs |
| ytop | Zahl | Die y‑Richtungslänge des Oberflächenbereichs |
| height | Zahl | Die Höhe der Pyramide |

 **Result:**



---


### getBottomArea{#getBottomArea}

| Name | Beschreibung |
| --- | --- |
| getBottomArea() | Fläche der unteren Kappe |

 **Result:**



---


### setBottomArea{#setBottomArea}

| Name | Beschreibung |
| --- | --- |
| setBottomArea(value) | Fläche der unteren Kappe |

 **Result:**



---


### getTopArea{#getTopArea}

| Name | Beschreibung |
| --- | --- |
| getTopArea() | Fläche der oberen Kappe |

 **Result:**



---


### setTopArea{#setTopArea}

| Name | Beschreibung |
| --- | --- |
| setTopArea(value) | Fläche der oberen Kappe |

 **Result:**



---


### getBottomOffset{#getBottomOffset}

| Name | Beschreibung |
| --- | --- |
| getBottomOffset() | Versatz für untere Eckpunkte |

 **Result:**



---


### setBottomOffset{#setBottomOffset}

| Name | Beschreibung |
| --- | --- |
| setBottomOffset(value) | Versatz für untere Eckpunkte |

 **Result:**



---


### getHeight{#getHeight}

| Name | Beschreibung |
| --- | --- |
| getHeight() | Höhe der Pyramide |

 **Result:**



---


### setHeight{#setHeight}

| Name | Beschreibung |
| --- | --- |
| setHeight(value) | Höhe der Pyramide |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Name | Beschreibung |
| --- | --- |
| getCastShadows() | Liest oder setzt, ob diese Geometrie Schatten werfen kann |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Name | Beschreibung |
| --- | --- |
| setCastShadows(value) | Liest oder setzt, ob diese Geometrie Schatten werfen kann |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Name | Beschreibung |
| --- | --- |
| getReceiveShadows() | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Name | Beschreibung |
| --- | --- |
| setReceiveShadows(value) | Liest oder setzt, ob diese Geometrie Schatten empfangen kann. |

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
| toMesh() | Konvertiere das aktuelle Objekt zu einem Mesh |

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



