---
title: Shape
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/shape/
---
## Shape class

Die Form beschreibt die Deformation an einer Menge von Kontrollpunkten, die dem cluster deformer in Maya ähnlich ist.  Zum Beispiel können wir einer erstellten Geometrie eine Form hinzufügen.  Und die Form und die Geometrie besitzen dieselben topologischen Informationen, jedoch unterschiedliche Positionen der Kontrollpunkte.  Mit variierenden Einflussstärken erzeugt die Geometrie einen Deformationseffekt.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Klasse Shape. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(name) | Initialisiert eine neue Instanz der Klasse Shape. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name |

 **Result:**



---


### getIndices{#getIndices}

| Name | Beschreibung |
| --- | --- |
| getIndices() | Liest die Indizes. Die Indizes. |

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
| getControlPoints() | Ermittelt alle Kontrollpunkte |

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
| getVertexElements() | Ermittelt alle Scheitellemente |

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


### fromControlPoints{#fromControlPoints}

| Name | Beschreibung |
| --- | --- |
| fromControlPoints(controlPoints) | Erstellt eine Form mit angegebenen Kontrollpunkten und Standardindizes. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| controlPoint | Vector3[] | null |

 **Result:**
Shape


---


### getElement{#getElement}

| Name | Beschreibung |
| --- | --- |
| getElement(type) | Ermittelt ein Scheitellement mit dem angegebenen Typ |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

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
| type | VertexElementType | VertexElementType |

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
| type | VertexElementType | VertexElementType |
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
| getBoundingBox() | Liefert die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |

 **Result:**
VertexElementUV


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



