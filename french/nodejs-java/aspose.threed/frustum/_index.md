---
title: Frustum
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/frustum/
---
## Frustum class

La classe de base de Camera et Light  @hideconstructor


## Méthodes

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



