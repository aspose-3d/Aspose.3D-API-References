---
title: "Kamera"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/camera/
---
## Camera class

Die Kamera beschreibt den Blickpunkt des Betrachters, der die Szene betrachtet.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Camera-Klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(projectionType) | Initialisiert eine neue Instanz der Camera-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(name) | Initialisiert eine neue Instanz der Camera-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Name | Beschreibung |
| --- | --- |
| constructor_overload3(name, projectionType) | Initialisiert eine neue Instanz der Camera-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name. |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### getApertureMode{#getApertureMode}

| Name | Beschreibung |
| --- | --- |
| getApertureMode() | Liest oder setzt den Blendenmodus der Kamera. Der Wert der Eigenschaft ist die Ganzzahlkonstante ApertureMode. |

 **Result:**



---


### setApertureMode{#setApertureMode}

| Name | Beschreibung |
| --- | --- |
| setApertureMode(value) | Liest oder setzt den Blendenmodus der Kamera. Der Wert der Eigenschaft ist die Ganzzahlkonstante ApertureMode. |

 **Result:**



---


### getFieldOfView{#getFieldOfView}

| Name | Beschreibung |
| --- | --- |
| getFieldOfView() | Liest oder setzt das Sichtfeld der Kamera in Grad, diese Eigenschaft wird nur verwendet, wenn ApertureMode ApertureMode.HORIZONTAL oder ApertureMode.VERTICAL ist. |

 **Result:**



---


### setFieldOfView{#setFieldOfView}

| Name | Beschreibung |
| --- | --- |
| setFieldOfView(value) | Liest oder setzt das Sichtfeld der Kamera in Grad, diese Eigenschaft wird nur verwendet, wenn ApertureMode ApertureMode.HORIZONTAL oder ApertureMode.VERTICAL ist. |

 **Result:**



---


### getFieldOfViewX{#getFieldOfViewX}

| Name | Beschreibung |
| --- | --- |
| getFieldOfViewX() | Liest oder setzt das horizontale Sichtfeld der Kamera in Grad, diese Eigenschaft wird nur verwendet, wenn ApertureMode ApertureMode.HORIZ_AND_VERT ist. |

 **Result:**



---


### setFieldOfViewX{#setFieldOfViewX}

| Name | Beschreibung |
| --- | --- |
| setFieldOfViewX(value) | Liest oder setzt das horizontale Sichtfeld der Kamera in Grad, diese Eigenschaft wird nur verwendet, wenn ApertureMode ApertureMode.HORIZ_AND_VERT ist. |

 **Result:**



---


### getFieldOfViewY{#getFieldOfViewY}

| Name | Beschreibung |
| --- | --- |
| getFieldOfViewY() | Liest oder setzt das vertikale Sichtfeld der Kamera in Grad, diese Eigenschaft wird nur verwendet, wenn ApertureMode ApertureMode.HORIZ_AND_VERT ist. |

 **Result:**



---


### setFieldOfViewY{#setFieldOfViewY}

| Name | Beschreibung |
| --- | --- |
| setFieldOfViewY(value) | Liest oder setzt das vertikale Sichtfeld der Kamera in Grad, diese Eigenschaft wird nur verwendet, wenn ApertureMode ApertureMode.HORIZ_AND_VERT ist. |

 **Result:**



---


### getWidth{#getWidth}

| Name | Beschreibung |
| --- | --- |
| getWidth() | Liest oder setzt die Breite der Ansichtsebene in Zoll. |

 **Result:**



---


### setWidth{#setWidth}

| Name | Beschreibung |
| --- | --- |
| setWidth(value) | Liest oder setzt die Breite der Ansichtsebene in Zoll. |

 **Result:**



---


### getHeight{#getHeight}

| Name | Beschreibung |
| --- | --- |
| getHeight() | Liest oder setzt die Höhe der Ansichtsebene in Zoll. |

 **Result:**



---


### setHeight{#setHeight}

| Name | Beschreibung |
| --- | --- |
| setHeight(value) | Liest oder setzt die Höhe der Ansichtsebene in Zoll. |

 **Result:**



---


### getAspectRatio{#getAspectRatio}

| Name | Beschreibung |
| --- | --- |
| getAspectRatio() | Liest oder setzt das Seitenverhältnis der Ansichtsebene. |

 **Result:**



---


### setAspectRatio{#setAspectRatio}

| Name | Beschreibung |
| --- | --- |
| setAspectRatio(value) | Liest oder setzt das Seitenverhältnis der Ansichtsebene. |

 **Result:**



---


### getMagnification{#getMagnification}

| Name | Beschreibung |
| --- | --- |
| getMagnification() | Liest oder setzt die Vergrößerung, die in einer orthografischen Kamera verwendet wird. |

 **Result:**



---


### setMagnification{#setMagnification}

| Name | Beschreibung |
| --- | --- |
| setMagnification(value) | Liest oder setzt die Vergrößerung, die in einer orthografischen Kamera verwendet wird. |

 **Result:**



---


### getProjectionType{#getProjectionType}

| Name | Beschreibung |
| --- | --- |
| getProjectionType() | Liest oder setzt den Projektionstyp der Kamera. Standardmäßig wird die perspektivische Projektion verwendet. Der Wert der Eigenschaft ist die Ganzzahlkonstante ProjectionType. |

 **Result:**



---


### setProjectionType{#setProjectionType}

| Name | Beschreibung |
| --- | --- |
| setProjectionType(value) | Liest oder setzt den Projektionstyp der Kamera. Standardmäßig wird die perspektivische Projektion verwendet. Der Wert der Eigenschaft ist die Ganzzahlkonstante ProjectionType. |

 **Result:**



---


### getRotationMode{#getRotationMode}

| Name | Beschreibung |
| --- | --- |
| getRotationMode() | Liest oder setzt den Orientierungsmodus des Sichtvolumens. Diese Eigenschaft funktioniert nur, wenn das Target null ist. Wenn der Wert RotationMode.FIXED_TARGET ist, wird die Richtung immer über die Eigenschaft LookAt berechnet. Andernfalls wird LookAt immer über die Direction berechnet. Der Wert der Eigenschaft ist die ganzzahlige Konstante RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Name | Beschreibung |
| --- | --- |
| setRotationMode(value) | Liest oder setzt den Orientierungsmodus des Sichtvolumens. Diese Eigenschaft funktioniert nur, wenn das Target null ist. Wenn der Wert RotationMode.FIXED_TARGET ist, wird die Richtung immer über die Eigenschaft LookAt berechnet. Andernfalls wird LookAt immer über die Direction berechnet. Der Wert der Eigenschaft ist die ganzzahlige Konstante RotationMode. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| Name | Beschreibung |
| --- | --- |
| getNearPlane() | Liest oder setzt den Abstand der nahen Ebene des Sichtvolumens. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| Name | Beschreibung |
| --- | --- |
| setNearPlane(value) | Liest oder setzt den Abstand der nahen Ebene des Sichtvolumens. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| Name | Beschreibung |
| --- | --- |
| getFarPlane() | Liest oder setzt den Abstand der fernen Ebene des Sichtvolumens. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Name | Beschreibung |
| --- | --- |
| setFarPlane(value) | Liest oder setzt den Abstand der fernen Ebene des Sichtvolumens. |

 **Result:**



---


### getAspect{#getAspect}

| Name | Beschreibung |
| --- | --- |
| getAspect() | Liest oder setzt das Seitenverhältnis des Frustums |

 **Result:**



---


### setAspect{#setAspect}

| Name | Beschreibung |
| --- | --- |
| setAspect(value) | Liest oder setzt das Seitenverhältnis des Frustums |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| Name | Beschreibung |
| --- | --- |
| getOrthoHeight() | Liest oder setzt die Höhe, wenn das Frustum in orthografischer Projektion ist. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Name | Beschreibung |
| --- | --- |
| setOrthoHeight(value) | Liest oder setzt die Höhe, wenn das Frustum in orthografischer Projektion ist. |

 **Result:**



---


### getUp{#getUp}

| Name | Beschreibung |
| --- | --- |
| getUp() | Liest oder setzt die Aufwärtsrichtung der Kamera |

 **Result:**



---


### setUp{#setUp}

| Name | Beschreibung |
| --- | --- |
| setUp(value) | Liest oder setzt die Aufwärtsrichtung der Kamera |

 **Result:**



---


### getLookAt{#getLookAt}

| Name | Beschreibung |
| --- | --- |
| getLookAt() | Liest oder setzt die interessierende Position, auf die die Kamera blickt. |

 **Result:**



---


### setLookAt{#setLookAt}

| Name | Beschreibung |
| --- | --- |
| setLookAt(value) | Liest oder setzt die interessierende Position, auf die die Kamera blickt. |

 **Result:**



---


### getDirection{#getDirection}

| Name | Beschreibung |
| --- | --- |
| getDirection() | Liest oder setzt die Richtung, in die die Kamera blickt. Änderungen an dieser Eigenschaft wirken sich auch auf LookAt und Target aus. |

 **Result:**



---


### setDirection{#setDirection}

| Name | Beschreibung |
| --- | --- |
| setDirection(value) | Liest oder setzt die Richtung, in die die Kamera blickt. Änderungen an dieser Eigenschaft wirken sich auch auf LookAt und Target aus. |

 **Result:**



---


### getTarget{#getTarget}

| Name | Beschreibung |
| --- | --- |
| getTarget() | Liest oder setzt das Ziel, auf das die Kamera blickt. Wenn der Benutzer diese Eigenschaft unterstützt, sollte sie vor der LookAt-Eigenschaft liegen. |

 **Result:**



---


### setTarget{#setTarget}

| Name | Beschreibung |
| --- | --- |
| setTarget(value) | Liest oder setzt das Ziel, auf das die Kamera blickt. Wenn der Benutzer diese Eigenschaft unterstützt, sollte sie vor der LookAt-Eigenschaft liegen. |

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


### moveForward{#moveForward}

| Name | Beschreibung |
| --- | --- |
| moveForward(distance) | Bewegt die Kamera nach vorne in Richtung ihrer Ausrichtung oder des Ziels. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Entfernung | Zahl | Wie lange nach vorne bewegen |

 **Result:**



---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Ruft die Bounding-Box der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem ab. |

 **Result:**



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



