---
title: "Transformation"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/transform/
---
## Transform class

Eine Transformation enthält Informationen, die den Zugriff auf die Übersetzung/Skalierung/Drehung des Objekts oder die Transformationsmatrix mit minimalem Aufwand ermöglichen.  Dies wird von lokaler Transformation verwendet.  @hideconstructor


## Methoden

### getGeometricTranslation{#getGeometricTranslation}

| Name | Beschreibung |
| --- | --- |
| getGeometricTranslation() | Liest oder setzt die geometrische Translation. Die geometrische Transformation wirkt nur auf die angehängten Entitäten und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateiformate exportieren, die sie nicht unterstützen. |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| Name | Beschreibung |
| --- | --- |
| setGeometricTranslation(value) | Liest oder setzt die geometrische Translation. Die geometrische Transformation wirkt nur auf die angehängten Entitäten und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateiformate exportieren, die sie nicht unterstützen. |

 **Result:**



---


### getGeometricScaling{#getGeometricScaling}

| Name | Beschreibung |
| --- | --- |
| getGeometricScaling() | Liest oder setzt die geometrische Skalierung. Die geometrische Transformation wirkt nur auf die angehängten Entitäten und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateiformate exportieren, die sie nicht unterstützen. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Name | Beschreibung |
| --- | --- |
| setGeometricScaling(value) | Liest oder setzt die geometrische Skalierung. Die geometrische Transformation wirkt nur auf die angehängten Entitäten und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateiformate exportieren, die sie nicht unterstützen. |

 **Result:**



---


### getGeometricRotation{#getGeometricRotation}

| Name | Beschreibung |
| --- | --- |
| getGeometricRotation() | Liest oder setzt die geometrische Euler‑Rotation (gemessen in Grad). Die geometrische Transformation wirkt nur auf die angehängten Entitäten und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateiformate exportieren, die sie nicht unterstützen. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Name | Beschreibung |
| --- | --- |
| setGeometricRotation(value) | Liest oder setzt die geometrische Euler‑Rotation (gemessen in Grad). Die geometrische Transformation wirkt nur auf die angehängten Entitäten und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateiformate exportieren, die sie nicht unterstützen. |

 **Result:**



---


### getTranslation{#getTranslation}

| Name | Beschreibung |
| --- | --- |
| getTranslation() | Liest oder setzt die Translation |

 **Result:**



---


### setTranslation{#setTranslation}

| Name | Beschreibung |
| --- | --- |
| setTranslation(value) | Liest oder setzt die Translation |

 **Result:**



---


### getScale{#getScale}

| Name | Beschreibung |
| --- | --- |
| getScale() | Liest oder setzt die Skalierung |

 **Result:**



---


### setScale{#setScale}

| Name | Beschreibung |
| --- | --- |
| setScale(value) | Liest oder setzt die Skalierung |

 **Result:**



---


### getPreRotation{#getPreRotation}

| Name | Beschreibung |
| --- | --- |
| getPreRotation() | Liest oder setzt die Vorrotation, angegeben in Grad |

 **Result:**



---


### setPreRotation{#setPreRotation}

| Name | Beschreibung |
| --- | --- |
| setPreRotation(value) | Liest oder setzt die Vorrotation, angegeben in Grad |

 **Result:**



---


### getPostRotation{#getPostRotation}

| Name | Beschreibung |
| --- | --- |
| getPostRotation() | Liest oder setzt die Nachrotation, angegeben in Grad |

 **Result:**



---


### setPostRotation{#setPostRotation}

| Name | Beschreibung |
| --- | --- |
| setPostRotation(value) | Liest oder setzt die Nachrotation, angegeben in Grad |

 **Result:**



---


### getEulerAngles{#getEulerAngles}

| Name | Beschreibung |
| --- | --- |
| getEulerAngles() | Liest oder setzt die Rotation, angegeben in Euler-Winkeln, gemessen in Grad |

 **Result:**



---


### setEulerAngles{#setEulerAngles}

| Name | Beschreibung |
| --- | --- |
| setEulerAngles(value) | Liest oder setzt die Rotation, angegeben in Euler-Winkeln, gemessen in Grad |

 **Result:**



---


### getRotation{#getRotation}

| Name | Beschreibung |
| --- | --- |
| getRotation() | Liest oder setzt die Rotation, angegeben als Quaternion. |

 **Result:**



---


### setRotation{#setRotation}

| Name | Beschreibung |
| --- | --- |
| setRotation(value) | Liest oder setzt die Rotation, angegeben als Quaternion. |

 **Result:**



---


### getTransformMatrix{#getTransformMatrix}

| Name | Beschreibung |
| --- | --- |
| getTransformMatrix() | Liest oder setzt die Transformationsmatrix. Das Zuweisen zu dieser wird die Translation, Scale und Rotation zurücksetzen, die GeometricRotation, GeometricScaling und GeometricTranslation werden nicht beeinflusst. |

 **Result:**



---


### setTransformMatrix{#setTransformMatrix}

| Name | Beschreibung |
| --- | --- |
| setTransformMatrix(value) | Liest oder setzt die Transformationsmatrix. Das Zuweisen zu dieser wird die Translation, Scale und Rotation zurücksetzen, die GeometricRotation, GeometricScaling und GeometricTranslation werden nicht beeinflusst. |

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


### setGeometricTranslation{#setGeometricTranslation}

| Name | Beschreibung |
| --- | --- |
| setGeometricTranslation(x, y, z) | Setzt die geometrische Translation. Die geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unbeeinflusst. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Name | Beschreibung |
| --- | --- |
| setGeometricScaling(sx, sy, sz) | Setzt die geometrische Skalierung. Die geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unbeeinflusst. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Name | Beschreibung |
| --- | --- |
| setGeometricRotation(rx, ry, rz) | Setzt die geometrische Euler-Rotation (gemessen in Grad). Die geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unbeeinflusst. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen. |

 **Result:**



---


### setTranslation{#setTranslation}

| Name | Beschreibung |
| --- | --- |
| setTranslation(tx, ty, tz) | Setzt die Translation der aktuellen Transformation. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| t | Zahl | null |
| t | Zahl | null |
| t | Zahl | null |

 **Result:**
Transformation


---


### setScale{#setScale}

| Name | Beschreibung |
| --- | --- |
| setScale(sx, sy, sz) | Setzt die Skalierung der aktuellen Transformation. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| s | Zahl | null |
| s | Zahl | null |
| s | Zahl | null |

 **Result:**
Transformation


---


### setEulerAngles{#setEulerAngles}

| Name | Beschreibung |
| --- | --- |
| setEulerAngles(rx, ry, rz) | Setzt die Euler-Winkel in Grad der aktuellen Transformation. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| r | Zahl | null |
| r | Zahl | null |
| r | Zahl | null |

 **Result:**
Transformation


---


### setRotation{#setRotation}

| Name | Beschreibung |
| --- | --- |
| setRotation(rw, rx, ry, rz) | Setzt die Rotation (als Quaternion-Komponenten) der aktuellen Transformation. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| r | Zahl | null |
| r | Zahl | null |
| r | Zahl | null |
| r | Zahl | null |

 **Result:**
Transformation


---


### setPreRotation{#setPreRotation}

| Name | Beschreibung |
| --- | --- |
| setPreRotation(rx, ry, rz) | Setzt die Vorrotation, angegeben in Grad |

 **Result:**
Transformation


---


### setPostRotation{#setPostRotation}

| Name | Beschreibung |
| --- | --- |
| setPostRotation(rx, ry, rz) | Setzt die Nachrotation, angegeben in Grad |

 **Result:**
Transformation


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



