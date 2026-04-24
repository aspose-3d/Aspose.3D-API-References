---
title: Kamera
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/camera/
---
## Camera class

Die Kamera beschreibt den Augenpunkt des Betrachters, der die Szene betrachtet.


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
| Name | String | Name. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Name | Beschreibung |
| --- | --- |
| constructor_overload3(name, projectionType) | Initialisiert eine neue Instanz der Camera-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Name | String | Name. |
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
| getFieldOfView() | Liest oder setzt das Sichtfeld der Kamera in Grad. Diese Eigenschaft wird nur verwendet, wenn ApertureMode gleich ApertureMode.HORIZONTAL oder ApertureMode.VERTICAL ist. |

 **Result:**



---


### setFieldOfView{#setFieldOfView}

| Name | Beschreibung |
| --- | --- |
| setFieldOfView(value) | Liest oder setzt das Sichtfeld der Kamera in Grad. Diese Eigenschaft wird nur verwendet, wenn ApertureMode gleich ApertureMode.HORIZONTAL oder ApertureMode.VERTICAL ist. |

 **Result:**



---


### getFieldOfViewX{#getFieldOfViewX}

| Name | Beschreibung |
| --- | --- |
| getFieldOfViewX() | Liest oder setzt das horizontale Sichtfeld der Kamera in Grad. Diese Eigenschaft wird nur verwendet, wenn ApertureMode gleich ApertureMode.HORIZ_AND_VERT ist. |

 **Result:**



---


### setFieldOfViewX{#setFieldOfViewX}

| Name | Beschreibung |
| --- | --- |
| setFieldOfViewX(value) | Liest oder setzt das horizontale Sichtfeld der Kamera in Grad. Diese Eigenschaft wird nur verwendet, wenn ApertureMode gleich ApertureMode.HORIZ_AND_VERT ist. |

 **Result:**



---


### getFieldOfViewY{#getFieldOfViewY}

| Name | Beschreibung |
| --- | --- |
| getFieldOfViewY() | Liest oder setzt das vertikale Sichtfeld der Kamera in Grad, diese Eigenschaft wird nur verwendet, wenn ApertureMode gleich ApertureMode.HORIZ_AND_VERT ist. |

 **Result:**



---


### setFieldOfViewY{#setFieldOfViewY}

| Name | Beschreibung |
| --- | --- |
| setFieldOfViewY(value) | Liest oder setzt das vertikale Sichtfeld der Kamera in Grad, diese Eigenschaft wird nur verwendet, wenn ApertureMode gleich ApertureMode.HORIZ_AND_VERT ist. |

 **Result:**



---


### getWidth{#getWidth}

| Name | Beschreibung |
| --- | --- |
| getWidth() | Liest oder setzt die Breite der Ansichtsebene, gemessen in Zoll. |

 **Result:**



---


### setWidth{#setWidth}

| Name | Beschreibung |
| --- | --- |
| setWidth(value) | Liest oder setzt die Breite der Ansichtsebene, gemessen in Zoll. |

 **Result:**



---


### getHeight{#getHeight}

| Name | Beschreibung |
| --- | --- |
| getHeight() | Liest oder setzt die Höhe der Ansichtsebene, gemessen in Zoll. |

 **Result:**



---


### setHeight{#setHeight}

| Name | Beschreibung |
| --- | --- |
| setHeight(value) | Liest oder setzt die Höhe der Ansichtsebene, gemessen in Zoll. |

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
| getProjectionType() | Liest oder setzt den Projektionstyp der Kamera. Standardmäßig wird die perspektivische Projektion verwendet. Der Wert der Eigenschaft ist die ganzzahlige Konstante ProjectionType. |

 **Result:**



---


### setProjectionType{#setProjectionType}

| Name | Beschreibung |
| --- | --- |
| setProjectionType(value) | Liest oder setzt den Projektionstyp der Kamera. Standardmäßig wird die perspektivische Projektion verwendet. Der Wert der Eigenschaft ist die ganzzahlige Konstante ProjectionType. |

 **Result:**



---


### getRotationMode{#getRotationMode}

| Name | Beschreibung |
| --- | --- |
| getRotationMode() | Liest oder setzt den Orientierungsmodus des Frustums. Diese Eigenschaft funktioniert nur, wenn das Target null ist. Wenn der Wert RotationMode.FIXED_TARGET ist, wird die Richtung immer über die Eigenschaft LookAt berechnet. Andernfalls wird LookAt immer über die Direction berechnet. Der Wert der Eigenschaft ist die Ganzzahlkonstante RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Name | Beschreibung |
| --- | --- |
| setRotationMode(value) | Liest oder setzt den Orientierungsmodus des Frustums. Diese Eigenschaft funktioniert nur, wenn das Target null ist. Wenn der Wert RotationMode.FIXED_TARGET ist, wird die Richtung immer über die Eigenschaft LookAt berechnet. Andernfalls wird LookAt immer über die Direction berechnet. Der Wert der Eigenschaft ist die Ganzzahlkonstante RotationMode. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| Name | Beschreibung |
| --- | --- |
| getNearPlane() | Liest oder setzt den Abstand der Nah-Ebene des Frustums. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| Name | Beschreibung |
| --- | --- |
| setNearPlane(value) | Liest oder setzt den Abstand der Nah-Ebene des Frustums. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| Name | Beschreibung |
| --- | --- |
| getFarPlane() | Liest oder setzt den Abstand der Fern-Ebene des Frustums. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Name | Beschreibung |
| --- | --- |
| setFarPlane(value) | Liest oder setzt den Abstand der Fern-Ebene des Frustums. |

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
| getOrthoHeight() | Liest oder setzt die Höhe, wenn der Frustum in orthografischer Projektion ist. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Name | Beschreibung |
| --- | --- |
| setOrthoHeight(value) | Liest oder setzt die Höhe, wenn der Frustum in orthografischer Projektion ist. |

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
| getTarget() | Liest oder setzt das Ziel, auf das die Kamera blickt. Wenn der Benutzer diese Eigenschaft unterstützt, sollte sie vor der LookAt‑Eigenschaft liegen. |

 **Result:**



---


### setTarget{#setTarget}

| Name | Beschreibung |
| --- | --- |
| setTarget(value) | Liest oder setzt das Ziel, auf das die Kamera blickt. Wenn der Benutzer diese Eigenschaft unterstützt, sollte sie vor der LookAt‑Eigenschaft liegen. |

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


### moveForward{#moveForward}

| Name | Beschreibung |
| --- | --- |
| moveForward(distance) | Bewege die Kamera vorwärts in Richtung ihrer Ausrichtung oder ihres Ziels. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Entfernung | Number | Wie lange vorwärts bewegt werden soll |

 **Result:**



---


### getBoundingBox{#getBoundingBox}

| Name | Beschreibung |
| --- | --- |
| getBoundingBox() | Liefert die Begrenzungsbox der aktuellen Entität in ihrem Objekt-Raum-Koordinatensystem. |

 **Result:**



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



