---
title: "PointCloud"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/pointcloud/
---
## PointCloud class

Die Punktwolke enthält keine Topologieinformationen, sondern nur die Kontrollpunkte und die Vertex-Elemente.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(name) | Konstruktor von PointCloud |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Der Name dieser Entität |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload() | Konstruktor von PointCloud |

 **Result:**



---


### getVisible{#getVisible}

| Name | Beschreibung |
| --- | --- |
| getVisible() | Liest oder setzt, ob die Geometrie sichtbar ist |

 **Result:**



---


### setVisible{#setVisible}

| Name | Beschreibung |
| --- | --- |
| setVisible(value) | Liest oder setzt, ob die Geometrie sichtbar ist |

 **Result:**



---


### getDeformers{#getDeformers}

| Name | Beschreibung |
| --- | --- |
| getDeformers() | Liest alle Deformer, die mit dieser Geometrie verknüpft sind. Die Deformer. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Name | Beschreibung |
| --- | --- |
| getControlPoints() | Liest alle Kontrollpunkte |

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


### getVertexElements{#getVertexElements}

| Name | Beschreibung |
| --- | --- |
| getVertexElements() | Liest alle Vertex-Elemente |

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


### getEntityRendererKey{#getEntityRendererKey}

| Name | Beschreibung |
| --- | --- |
| getEntityRendererKey() | Ruft den Schlüssel des im Renderer registrierten Entity-Renderers ab. |

 **Result:**
EntityRendererKey


---


### fromGeometry{#fromGeometry}

| Name | Beschreibung |
| --- | --- |
| fromGeometry(g) | Erstelle eine neue PointCloud-Instanz aus einem Geometrieobjekt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Geometry | null |

 **Result:**
PointCloud


---


### fromGeometry{#fromGeometry}

| Name | Beschreibung |
| --- | --- |
| fromGeometry(g, density) | Erstelle eine neue Punktwolken-Instanz aus einem Geometrieobjekt. Dichte ist die Anzahl der Punkte pro Einheitstriangle (Einheitstriangle ist das Dreieck mit maximaler Oberfläche aus dem Mesh). |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| g | Geometry | Mesh oder andere Geometrie-Instanz |
| Dichte | Zahl | Anzahl der Punkte pro Einheitstriangle |

 **Result:**
PointCloud


---


### getElement{#getElement}

| Name | Beschreibung |
| --- | --- |
| getElement(type) | Liefert ein Vertex-Element mit dem angegebenen Typ |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Typ | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| Name | Beschreibung |
| --- | --- |
| getVertexElementOfUV(textureMapping) | Gibt eine VertexElementUV-Instanz mit dem angegebenen Texturzuordnungstyp zurück |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| Name | Beschreibung |
| --- | --- |
| createElement(type) | Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es zur Geometrie hinzu. Wenn der Typ VertexElementType.UV ist, wird ein VertexElementUV mit Texturzuordnungstyp zu TextureMapping.DIFFUSE erstellt. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Typ | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| Name | Beschreibung |
| --- | --- |
| addElement(element) | Fügt ein vorhandenes Vertex-Element zur aktuellen Geometrie hinzu |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| element | VertexElement | Das hinzuzufügende Vertex-Element |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Name | Beschreibung |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es zur Geometrie hinzu. Wenn der Typ VertexElementType.UV ist, wird ein VertexElementUV mit Texturzuordnungstyp zu TextureMapping.DIFFUSE erstellt. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Typ | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| Name | Beschreibung |
| --- | --- |
| createElementUV(uvMapping) | Erstellt ein VertexElementUV mit dem angegebenen Texturzuordnungstyp. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| Name | Beschreibung |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | Erstellt ein VertexElementUV mit dem angegebenen Texturzuordnungstyp. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Ruft die Bounding-Box der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem ab. |

 **Result:**
VertexElementUV


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



