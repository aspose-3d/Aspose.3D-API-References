---
title: Cylinder
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

Parametrisierter Zylinder.  Er kann auch verwendet werden, um den Kegel darzustellen, wenn einer der Werte radiusTop/radiusBottom null ist.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Klasse Cylinder. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(radius, height) | Initialisiert eine neue Instanz der Klasse Cylinder. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| radius | Number | Radius der oberen und unteren Kappe. |
| height | Number | Höhe. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Initialisiert eine neue Instanz der Klasse Cylinder. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| radiusTop | Number | Oberer Radius. |
| radiusBottom | Number | Unterer Radius. |
| height | Number | Höhe. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Name | Beschreibung |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Initialisiert eine neue Instanz der Klasse Cylinder. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| radiusTop | Number | Radius der oberen Kappe des Zylinders. |
| radiusBottom | Number | Radius der unteren Kappe des Zylinders. |
| height | Number | Höhe des Zylinders. |
| radialSegments | Number | Radiale Segmente beider oberer und unterer Kreise.. |
| heightSegments | Number | Höhensegmente. |
| openEnded | boolean | Wenn gesetzt auf |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Name | Beschreibung |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Initialisiert eine neue Instanz der Klasse Cylinder. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Der Name dieses Objekts |
| radiusTop | Number | Radius der oberen Kappe des Zylinders. |
| radiusBottom | Number | Radius der unteren Kappe des Zylinders. |
| height | Number | Höhe des Zylinders. |
| radialSegments | Number | Radiale Segmente beider oberer und unterer Kreise.. |
| heightSegments | Number | Höhensegmente. |
| openEnded | boolean | Wenn gesetzt auf |
| thetaStart | Number | Theta-Start. |
| thetaLength | Number | Theta-Länge. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| Name | Beschreibung |
| --- | --- |
| getOffsetBottom() | Liest oder setzt den Transformationsversatz der Scheitelpunkte der unteren Seite. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| Name | Beschreibung |
| --- | --- |
| setOffsetBottom(value) | Liest oder setzt den Transformationsversatz der Scheitelpunkte der unteren Seite. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| Name | Beschreibung |
| --- | --- |
| getOffsetTop() | Liest oder setzt den Transformationsversatz der Scheitelpunkte der oberen Seite. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| Name | Beschreibung |
| --- | --- |
| setOffsetTop(value) | Liest oder setzt den Transformationsversatz der Scheitelpunkte der oberen Seite. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| Name | Beschreibung |
| --- | --- |
| getGenerateFanCylinder() | Liest oder setzt, ob ein Zylinder im Fächerstil erzeugt werden soll, wenn die ThetaLength kleiner als 2PI ist, andernfalls wird das Modell nicht geschnitten. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| Name | Beschreibung |
| --- | --- |
| setGenerateFanCylinder(value) | Liest oder setzt, ob ein Zylinder im Fächerstil erzeugt werden soll, wenn die ThetaLength kleiner als 2PI ist, andernfalls wird das Modell nicht geschnitten. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| Name | Beschreibung |
| --- | --- |
| getShearBottom() | Liest oder setzt die Schertransformation der unteren Seite, ein Vektor speichert den (x‑Achse, z‑Achse) Scherwert, gemessen im Bogenmaß, Standardwert ist (0, 0) |

 **Result:**



---


### setShearBottom{#setShearBottom}

| Name | Beschreibung |
| --- | --- |
| setShearBottom(value) | Liest oder setzt die Schertransformation der unteren Seite, ein Vektor speichert den (x‑Achse, z‑Achse) Scherwert, gemessen im Bogenmaß, Standardwert ist (0, 0) |

 **Result:**



---


### getShearTop{#getShearTop}

| Name | Beschreibung |
| --- | --- |
| getShearTop() | Liest oder setzt die Schertransformation der oberen Seite, ein Vektor speichert den (x‑Achse, z‑Achse) Scherwert, gemessen im Bogenmaß, Standardwert ist (0, 0) |

 **Result:**



---


### setShearTop{#setShearTop}

| Name | Beschreibung |
| --- | --- |
| setShearTop(value) | Liest oder setzt die Schertransformation der oberen Seite, ein Vektor speichert den (x‑Achse, z‑Achse) Scherwert, gemessen im Bogenmaß, Standardwert ist (0, 0) |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| Name | Beschreibung |
| --- | --- |
| getRadiusTop() | Liest oder setzt den Radius der oberen Kappe des Zylinders. Der Radius der oberen Kappe. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| Name | Beschreibung |
| --- | --- |
| setRadiusTop(value) | Liest oder setzt den Radius der oberen Kappe des Zylinders. Der Radius der oberen Kappe. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| Name | Beschreibung |
| --- | --- |
| getRadiusBottom() | Liest oder setzt den Radius der unteren Kappe des Zylinders. Der Radius der unteren Kappe. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| Name | Beschreibung |
| --- | --- |
| setRadiusBottom(value) | Liest oder setzt den Radius der unteren Kappe des Zylinders. Der Radius der unteren Kappe. |

 **Result:**



---


### getHeight{#getHeight}

| Name | Beschreibung |
| --- | --- |
| getHeight() | Liest oder setzt die Höhe des Zylinders. Die Höhe. |

 **Result:**



---


### setHeight{#setHeight}

| Name | Beschreibung |
| --- | --- |
| setHeight(value) | Liest oder setzt die Höhe des Zylinders. Die Höhe. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| Name | Beschreibung |
| --- | --- |
| getRadialSegments() | Liest oder setzt die radialen Segmente. Die radialen Segmente. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| Name | Beschreibung |
| --- | --- |
| setRadialSegments(value) | Liest oder setzt die radialen Segmente. Die radialen Segmente. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Name | Beschreibung |
| --- | --- |
| getHeightSegments() | Liest oder setzt die Höhensegmente. Die Höhensegmente. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Name | Beschreibung |
| --- | --- |
| setHeightSegments(value) | Liest oder setzt die Höhensegmente. Die Höhensegmente. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| Name | Beschreibung |
| --- | --- |
| getOpenEnded() | Liest oder setzt einen Wert, der angibt, ob dieser Zylinder offen ist. Der Standardwert ist false. true, wenn offen; andernfalls existieren obere/untere Kappen. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| Name | Beschreibung |
| --- | --- |
| setOpenEnded(value) | Liest oder setzt einen Wert, der angibt, ob dieser Zylinder offen ist. Der Standardwert ist false. true, wenn offen; andernfalls existieren obere/untere Kappen. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| Name | Beschreibung |
| --- | --- |
| getThetaStart() | Liest oder setzt den Theta-Start. Der Standardwert ist 0. Der Theta-Start. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| Name | Beschreibung |
| --- | --- |
| setThetaStart(value) | Liest oder setzt den Theta-Start. Der Standardwert ist 0. Der Theta-Start. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| Name | Beschreibung |
| --- | --- |
| getThetaLength() | Liest oder setzt die Länge von Theta. Der Standardwert ist 2π. Die Länge von Theta. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| Name | Beschreibung |
| --- | --- |
| setThetaLength(value) | Liest oder setzt die Länge von Theta. Der Standardwert ist 2π. Die Länge von Theta. |

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
| toMesh() | Konvertiere das aktuelle Objekt zu einem Mesh |

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



