---
title: Transformation
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/transform/
---
## Transform class

Une transformation contient des informations qui permettent d'accéder à la translation/échelle/rotation de l'objet ou à la matrice de transformation avec un coût minimal.  Ceci est utilisé par la transformation locale.  @hideconstructor


## Méthodes

### getGeometricTranslation{#getGeometricTranslation}

| Nom | Description |
| --- | --- |
| getGeometricTranslation() | Obtient ou définit la translation géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| Nom | Description |
| --- | --- |
| setGeometricTranslation(value) | Obtient ou définit la translation géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |

 **Result:**



---


### getGeometricScaling{#getGeometricScaling}

| Nom | Description |
| --- | --- |
| getGeometricScaling() | Obtient ou définit le redimensionnement géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Nom | Description |
| --- | --- |
| setGeometricScaling(value) | Obtient ou définit le redimensionnement géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |

 **Result:**



---


### getGeometricRotation{#getGeometricRotation}

| Nom | Description |
| --- | --- |
| getGeometricRotation() | Obtient ou définit la rotation d'Euler géométrique (mesurée en degrés). La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Nom | Description |
| --- | --- |
| setGeometricRotation(value) | Obtient ou définit la rotation d'Euler géométrique (mesurée en degrés). La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |

 **Result:**



---


### getTranslation{#getTranslation}

| Nom | Description |
| --- | --- |
| getTranslation() | Obtient ou définit la translation |

 **Result:**



---


### setTranslation{#setTranslation}

| Nom | Description |
| --- | --- |
| setTranslation(value) | Obtient ou définit la translation |

 **Result:**



---


### getScale{#getScale}

| Nom | Description |
| --- | --- |
| getScale() | Obtient ou définit l'échelle |

 **Result:**



---


### setScale{#setScale}

| Nom | Description |
| --- | --- |
| setScale(value) | Obtient ou définit l'échelle |

 **Result:**



---


### getPreRotation{#getPreRotation}

| Nom | Description |
| --- | --- |
| getPreRotation() | Obtient ou définit la pré-rotation représentée en degrés |

 **Result:**



---


### setPreRotation{#setPreRotation}

| Nom | Description |
| --- | --- |
| setPreRotation(value) | Obtient ou définit la pré-rotation représentée en degrés |

 **Result:**



---


### getPostRotation{#getPostRotation}

| Nom | Description |
| --- | --- |
| getPostRotation() | Obtient ou définit la post-rotation représentée en degrés |

 **Result:**



---


### setPostRotation{#setPostRotation}

| Nom | Description |
| --- | --- |
| setPostRotation(value) | Obtient ou définit la post-rotation représentée en degrés |

 **Result:**



---


### getEulerAngles{#getEulerAngles}

| Nom | Description |
| --- | --- |
| getEulerAngles() | Obtient ou définit la rotation représentée par des angles d'Euler, mesurée en degrés |

 **Result:**



---


### setEulerAngles{#setEulerAngles}

| Nom | Description |
| --- | --- |
| setEulerAngles(value) | Obtient ou définit la rotation représentée par des angles d'Euler, mesurée en degrés |

 **Result:**



---


### getRotation{#getRotation}

| Nom | Description |
| --- | --- |
| getRotation() | Obtient ou définit la rotation représentée sous forme de quaternion. |

 **Result:**



---


### setRotation{#setRotation}

| Nom | Description |
| --- | --- |
| setRotation(value) | Obtient ou définit la rotation représentée sous forme de quaternion. |

 **Result:**



---


### getTransformMatrix{#getTransformMatrix}

| Nom | Description |
| --- | --- |
| getTransformMatrix() | Obtient ou définit la matrice de transformation. L'assignation à celle-ci réinitialisera la Translation, le Scale et la Rotation, le GeometricRotation, le GeometricScaling et le GeometricTranslation ne seront pas affectés. |

 **Result:**



---


### setTransformMatrix{#setTransformMatrix}

| Nom | Description |
| --- | --- |
| setTransformMatrix(value) | Obtient ou définit la matrice de transformation. L'assignation à celle-ci réinitialisera la Translation, le Scale et la Rotation, le GeometricRotation, le GeometricScaling et le GeometricTranslation ne seront pas affectés. |

 **Result:**



---


### getName{#getName}

| Nom | Description |
| --- | --- |
| getName() | Obtient ou définit le nom. Le nom. |

 **Result:**



---


### setName{#setName}

| Nom | Description |
| --- | --- |
| setName(value) | Obtient ou définit le nom. Le nom. |

 **Result:**



---


### getProperties{#getProperties}

| Nom | Description |
| --- | --- |
| getProperties() | Obtient la collection de toutes les propriétés. |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| Nom | Description |
| --- | --- |
| setGeometricTranslation(x, y, z) | Définit la translation géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Nom | Description |
| --- | --- |
| setGeometricScaling(sx, sy, sz) | Définit l'échelle géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Nom | Description |
| --- | --- |
| setGeometricRotation(rx, ry, rz) | Définit la rotation Euler géométrique (mesurée en degrés). La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |

 **Result:**



---


### setTranslation{#setTranslation}

| Nom | Description |
| --- | --- |
| setTranslation(tx, ty, tz) | Définit la translation de la transformation actuelle. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| t | Number | null |
| t | Number | null |
| t | Number | null |

 **Result:**
Transformation


---


### setScale{#setScale}

| Nom | Description |
| --- | --- |
| setScale(sx, sy, sz) | Définit l'échelle de la transformation actuelle. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| s | Number | null |
| s | Number | null |
| s | Number | null |

 **Result:**
Transformation


---


### setEulerAngles{#setEulerAngles}

| Nom | Description |
| --- | --- |
| setEulerAngles(rx, ry, rz) | Définit les angles d'Euler en degrés de la transformation actuelle. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| r | Number | null |
| r | Number | null |
| r | Number | null |

 **Result:**
Transformation


---


### setRotation{#setRotation}

| Nom | Description |
| --- | --- |
| setRotation(rw, rx, ry, rz) | Définit la rotation (en tant que composants quaternion) de la transformation actuelle. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| r | Number | null |
| r | Number | null |
| r | Number | null |
| r | Number | null |

 **Result:**
Transformation


---


### setPreRotation{#setPreRotation}

| Nom | Description |
| --- | --- |
| setPreRotation(rx, ry, rz) | Définit la pré-rotation exprimée en degrés |

 **Result:**
Transformation


---


### setPostRotation{#setPostRotation}

| Nom | Description |
| --- | --- |
| setPostRotation(rx, ry, rz) | Définit la post-rotation exprimée en degrés |

 **Result:**
Transformation


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime une propriété dynamique. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | Property | Quelle propriété supprimer |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime la propriété spécifiée identifiée par son nom |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nom | Description |
| --- | --- |
| getProperty(property) | Obtenir la valeur de la propriété spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | String | Nom de la propriété |

 **Result:**
Object


---


### setProperty{#setProperty}

| Nom | Description |
| --- | --- |
| setProperty(property, value) | Définit la valeur de la propriété spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | String | Nom de la propriété |
| valeur | Object | La valeur de la propriété |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nom | Description |
| --- | --- |
| findProperty(propertyName) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propertyName | String | Nom de la propriété. |

 **Result:**
Property


---



