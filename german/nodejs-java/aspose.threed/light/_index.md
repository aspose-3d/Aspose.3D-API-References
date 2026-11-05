---
title: "Light"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/light/
---
## Light class

Das Licht beleuchtet die Szene. Die Formel zur Berechnung der gesamten Lichtabschwächung lautet:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation)


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz der Light-Klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(name) | Initialisiert eine neue Instanz der Light-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(name, type) | Initialisiert eine neue Instanz der Light-Klasse. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Name |
| Typ | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| Name | Beschreibung |
| --- | --- |
| getColor() | Liest oder setzt die Farbe des Lichts |

 **Result:**



---


### setColor{#setColor}

| Name | Beschreibung |
| --- | --- |
| setColor(value) | Liest oder setzt die Farbe des Lichts |

 **Result:**



---


### getLightType{#getLightType}

| Name | Beschreibung |
| --- | --- |
| getLightType() | Liest oder setzt den Typ des Lichts. Der Wert der Eigenschaft ist die ganzzahlige Konstante LightType. |

 **Result:**



---


### setLightType{#setLightType}

| Name | Beschreibung |
| --- | --- |
| setLightType(value) | Liest oder setzt den Typ des Lichts. Der Wert der Eigenschaft ist die ganzzahlige Konstante LightType. |

 **Result:**



---


### getCastLight{#getCastLight}

| Name | Beschreibung |
| --- | --- |
| getCastLight() | Liest oder setzt, ob die aktuelle Lichtinstanz andere Objekte beleuchten kann. |

 **Result:**



---


### setCastLight{#setCastLight}

| Name | Beschreibung |
| --- | --- |
| setCastLight(value) | Liest oder setzt, ob die aktuelle Lichtinstanz andere Objekte beleuchten kann. |

 **Result:**



---


### getIntensity{#getIntensity}

| Name | Beschreibung |
| --- | --- |
| getIntensity() | Liest oder setzt die Intensität des Lichts, der Standardwert ist 100 |

 **Result:**



---


### setIntensity{#setIntensity}

| Name | Beschreibung |
| --- | --- |
| setIntensity(value) | Liest oder setzt die Intensität des Lichts, der Standardwert ist 100 |

 **Result:**



---


### getHotSpot{#getHotSpot}

| Name | Beschreibung |
| --- | --- |
| getHotSpot() | Liest oder setzt den Kegelwinkel des Hot Spots (in Grad). |

 **Result:**



---


### setHotSpot{#setHotSpot}

| Name | Beschreibung |
| --- | --- |
| setHotSpot(value) | Liest oder setzt den Kegelwinkel des Hot Spots (in Grad). |

 **Result:**



---


### getFalloff{#getFalloff}

| Name | Beschreibung |
| --- | --- |
| getFalloff() | Liest oder setzt den Falloff-Kegelwinkel (in Grad). |

 **Result:**



---


### setFalloff{#setFalloff}

| Name | Beschreibung |
| --- | --- |
| setFalloff(value) | Liest oder setzt den Falloff-Kegelwinkel (in Grad). |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| Name | Beschreibung |
| --- | --- |
| getConstantAttenuation() | Liest oder setzt die konstante Dämpfung, um die Gesamtdämpfung des Lichts zu berechnen |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| Name | Beschreibung |
| --- | --- |
| setConstantAttenuation(value) | Liest oder setzt die konstante Dämpfung, um die Gesamtdämpfung des Lichts zu berechnen |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| Name | Beschreibung |
| --- | --- |
| getLinearAttenuation() | Liest oder setzt die lineare Dämpfung, um die Gesamtdämpfung des Lichts zu berechnen |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| Name | Beschreibung |
| --- | --- |
| setLinearAttenuation(value) | Liest oder setzt die lineare Dämpfung, um die Gesamtdämpfung des Lichts zu berechnen |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| Name | Beschreibung |
| --- | --- |
| getQuadraticAttenuation() | Liest oder setzt die quadratische Dämpfung, um die Gesamtdämpfung des Lichts zu berechnen |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| Name | Beschreibung |
| --- | --- |
| setQuadraticAttenuation(value) | Liest oder setzt die quadratische Dämpfung, um die Gesamtdämpfung des Lichts zu berechnen |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Name | Beschreibung |
| --- | --- |
| getCastShadows() | Liest oder setzt, ob das Licht Schatten auf andere Objekte werfen kann. |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Name | Beschreibung |
| --- | --- |
| setCastShadows(value) | Liest oder setzt, ob das Licht Schatten auf andere Objekte werfen kann. |

 **Result:**



---


### getShadowColor{#getShadowColor}

| Name | Beschreibung |
| --- | --- |
| getShadowColor() | Liest oder setzt die Farbe des Schattens. |

 **Result:**



---


### setShadowColor{#setShadowColor}

| Name | Beschreibung |
| --- | --- |
| setShadowColor(value) | Liest oder setzt die Farbe des Schattens. |

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



