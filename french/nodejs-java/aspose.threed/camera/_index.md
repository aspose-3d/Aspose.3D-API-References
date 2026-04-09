---
title: Camera
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/camera/
---
## Camera class

La caméra décrit le point de vue de l'observateur regardant la scène.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de la classe Camera. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(projectionType) | Initialise une nouvelle instance de la classe Camera. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(name) | Initialise une nouvelle instance de la classe Camera. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Name. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nom | Description |
| --- | --- |
| constructor_overload3(name, projectionType) | Initialise une nouvelle instance de la classe Camera. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Name. |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### getApertureMode{#getApertureMode}

| Nom | Description |
| --- | --- |
| getApertureMode() | Obtient ou définit le mode d'ouverture de la caméra. La valeur de la propriété est la constante entière ApertureMode. |

 **Result:**



---


### setApertureMode{#setApertureMode}

| Nom | Description |
| --- | --- |
| setApertureMode(value) | Obtient ou définit le mode d'ouverture de la caméra. La valeur de la propriété est la constante entière ApertureMode. |

 **Result:**



---


### getFieldOfView{#getFieldOfView}

| Nom | Description |
| --- | --- |
| getFieldOfView() | Obtient ou définit le champ de vision de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est ApertureMode.HORIZONTAL ou ApertureMode.VERTICAL |

 **Result:**



---


### setFieldOfView{#setFieldOfView}

| Nom | Description |
| --- | --- |
| setFieldOfView(value) | Obtient ou définit le champ de vision de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est ApertureMode.HORIZONTAL ou ApertureMode.VERTICAL |

 **Result:**



---


### getFieldOfViewX{#getFieldOfViewX}

| Nom | Description |
| --- | --- |
| getFieldOfViewX() | Obtient ou définit le champ de vision horizontal de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### setFieldOfViewX{#setFieldOfViewX}

| Nom | Description |
| --- | --- |
| setFieldOfViewX(value) | Obtient ou définit le champ de vision horizontal de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### getFieldOfViewY{#getFieldOfViewY}

| Nom | Description |
| --- | --- |
| getFieldOfViewY() | Obtient ou définit le champ de vision vertical de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### setFieldOfViewY{#setFieldOfViewY}

| Nom | Description |
| --- | --- |
| setFieldOfViewY(value) | Obtient ou définit le champ de vision vertical de la caméra en degrés, cette propriété n'est utilisée que lorsque ApertureMode est ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### getWidth{#getWidth}

| Nom | Description |
| --- | --- |
| getWidth() | Obtient ou définit la largeur du plan de vue mesurée en pouces. |

 **Result:**



---


### setWidth{#setWidth}

| Nom | Description |
| --- | --- |
| setWidth(value) | Obtient ou définit la largeur du plan de vue mesurée en pouces. |

 **Result:**



---


### getHeight{#getHeight}

| Nom | Description |
| --- | --- |
| getHeight() | Obtient ou définit la hauteur du plan de vue mesurée en pouces. |

 **Result:**



---


### setHeight{#setHeight}

| Nom | Description |
| --- | --- |
| setHeight(value) | Obtient ou définit la hauteur du plan de vue mesurée en pouces. |

 **Result:**



---


### getAspectRatio{#getAspectRatio}

| Nom | Description |
| --- | --- |
| getAspectRatio() | Obtient ou définit le rapport d'aspect du plan de vue. |

 **Result:**



---


### setAspectRatio{#setAspectRatio}

| Nom | Description |
| --- | --- |
| setAspectRatio(value) | Obtient ou définit le rapport d'aspect du plan de vue. |

 **Result:**



---


### getMagnification{#getMagnification}

| Nom | Description |
| --- | --- |
| getMagnification() | Obtient ou définit le grossissement utilisé dans la caméra orthographique. |

 **Result:**



---


### setMagnification{#setMagnification}

| Nom | Description |
| --- | --- |
| setMagnification(value) | Obtient ou définit le grossissement utilisé dans la caméra orthographique. |

 **Result:**



---


### getProjectionType{#getProjectionType}

| Nom | Description |
| --- | --- |
| getProjectionType() | Obtient ou définit le type de projection de la caméra. Par défaut, la projection perspective est utilisée. La valeur de la propriété est la constante entière ProjectionType. |

 **Result:**



---


### setProjectionType{#setProjectionType}

| Nom | Description |
| --- | --- |
| setProjectionType(value) | Obtient ou définit le type de projection de la caméra. Par défaut, la projection perspective est utilisée. La valeur de la propriété est la constante entière ProjectionType. |

 **Result:**



---


### getRotationMode{#getRotationMode}

| Nom | Description |
| --- | --- |
| getRotationMode() | Obtient ou définit le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le Target est nul. Si la valeur est RotationMode.FIXED_TARGET, la direction est toujours calculée par la propriété LookAt. Sinon, LookAt est toujours calculé par la Direction. La valeur de la propriété est la constante entière RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Nom | Description |
| --- | --- |
| setRotationMode(value) | Obtient ou définit le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le Target est nul. Si la valeur est RotationMode.FIXED_TARGET, la direction est toujours calculée par la propriété LookAt. Sinon, LookAt est toujours calculé par la Direction. La valeur de la propriété est la constante entière RotationMode. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| Nom | Description |
| --- | --- |
| getNearPlane() | Obtient ou définit la distance du plan proche du frustum. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| Nom | Description |
| --- | --- |
| setNearPlane(value) | Obtient ou définit la distance du plan proche du frustum. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| Nom | Description |
| --- | --- |
| getFarPlane() | Obtient ou définit la distance du plan lointain du frustum. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Nom | Description |
| --- | --- |
| setFarPlane(value) | Obtient ou définit la distance du plan lointain du frustum. |

 **Result:**



---


### getAspect{#getAspect}

| Nom | Description |
| --- | --- |
| getAspect() | Obtient ou définit le rapport d'aspect du frustrum |

 **Result:**



---


### setAspect{#setAspect}

| Nom | Description |
| --- | --- |
| setAspect(value) | Obtient ou définit le rapport d'aspect du frustrum |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| Nom | Description |
| --- | --- |
| getOrthoHeight() | Obtient ou définit la hauteur lorsque le frustrum est en projection orthographique. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Nom | Description |
| --- | --- |
| setOrthoHeight(value) | Obtient ou définit la hauteur lorsque le frustrum est en projection orthographique. |

 **Result:**



---


### getUp{#getUp}

| Nom | Description |
| --- | --- |
| getUp() | Obtient ou définit la direction vers le haut de la caméra |

 **Result:**



---


### setUp{#setUp}

| Nom | Description |
| --- | --- |
| setUp(value) | Obtient ou définit la direction vers le haut de la caméra |

 **Result:**



---


### getLookAt{#getLookAt}

| Nom | Description |
| --- | --- |
| getLookAt() | Obtient ou définit la position d'intérêt que la caméra regarde. |

 **Result:**



---


### setLookAt{#setLookAt}

| Nom | Description |
| --- | --- |
| setLookAt(value) | Obtient ou définit la position d'intérêt que la caméra regarde. |

 **Result:**



---


### getDirection{#getDirection}

| Nom | Description |
| --- | --- |
| getDirection() | Obtient ou définit la direction vers laquelle la caméra regarde. Les modifications de cette propriété affecteront également LookAt et Target. |

 **Result:**



---


### setDirection{#setDirection}

| Nom | Description |
| --- | --- |
| setDirection(value) | Obtient ou définit la direction vers laquelle la caméra regarde. Les modifications de cette propriété affecteront également LookAt et Target. |

 **Result:**



---


### getTarget{#getTarget}

| Nom | Description |
| --- | --- |
| getTarget() | Obtient ou définit la cible que la caméra regarde. Si l'utilisateur prend en charge cette propriété, elle doit précéder la propriété LookAt. |

 **Result:**



---


### setTarget{#setTarget}

| Nom | Description |
| --- | --- |
| setTarget(value) | Obtient ou définit la cible que la caméra regarde. Si l'utilisateur prend en charge cette propriété, elle doit précéder la propriété LookAt. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nom | Description |
| --- | --- |
| getParentNodes() | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie. Les nœuds. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nom | Description |
| --- | --- |
| getExcluded() | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nom | Description |
| --- | --- |
| setExcluded(value) | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nom | Description |
| --- | --- |
| getParentNode() | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. Le nœud parent. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nom | Description |
| --- | --- |
| setParentNode(value) | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. Le nœud parent. |

 **Result:**



---


### getScene{#getScene}

| Nom | Description |
| --- | --- |
| getScene() | Obtient la scène à laquelle cet objet appartient |

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


### moveForward{#moveForward}

| Nom | Description |
| --- | --- |
| moveForward(distance) | Déplace la caméra vers l'avant dans sa direction ou vers sa cible. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| distance | Number | Durée du déplacement vers l'avant |

 **Result:**



---


### getBoundingBox{#getBoundingBox}

| Nom | Description |
| --- | --- |
| getBoundingBox() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |

 **Result:**



---


### getEntityRendererKey{#getEntityRendererKey}

| Nom | Description |
| --- | --- |
| getEntityRendererKey() | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |

 **Result:**
EntityRendererKey


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



