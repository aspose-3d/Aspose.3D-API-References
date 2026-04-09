---
title: Light
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/light/
---
## Light class

La lumière éclaire la scène. La formule pour calculer l'atténuation totale de la lumière est : A = ConstantAttenuation + (Dist × LinearAttenuation) + ((Dist^2) × QuadraticAttenuation)


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de la classe Light. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(name) | Initialise une nouvelle instance de la classe Light. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Nom |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(name, type) | Initialise une nouvelle instance de la classe Light. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Nom |
| type | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| Nom | Description |
| --- | --- |
| getColor() | Obtient ou définit la couleur de la lumière |

 **Result:**



---


### setColor{#setColor}

| Nom | Description |
| --- | --- |
| setColor(value) | Obtient ou définit la couleur de la lumière |

 **Result:**



---


### getLightType{#getLightType}

| Nom | Description |
| --- | --- |
| getLightType() | Obtient ou définit le type de la lumière. La valeur de la propriété est la constante entière LightType. |

 **Result:**



---


### setLightType{#setLightType}

| Nom | Description |
| --- | --- |
| setLightType(value) | Obtient ou définit le type de la lumière. La valeur de la propriété est la constante entière LightType. |

 **Result:**



---


### getCastLight{#getCastLight}

| Nom | Description |
| --- | --- |
| getCastLight() | Obtient ou définit si l'instance actuelle de lumière peut éclairer d'autres objets. |

 **Result:**



---


### setCastLight{#setCastLight}

| Nom | Description |
| --- | --- |
| setCastLight(value) | Obtient ou définit si l'instance actuelle de lumière peut éclairer d'autres objets. |

 **Result:**



---


### getIntensity{#getIntensity}

| Nom | Description |
| --- | --- |
| getIntensity() | Obtient ou définit l'intensité de la lumière, la valeur par défaut est 100 |

 **Result:**



---


### setIntensity{#setIntensity}

| Nom | Description |
| --- | --- |
| setIntensity(value) | Obtient ou définit l'intensité de la lumière, la valeur par défaut est 100 |

 **Result:**



---


### getHotSpot{#getHotSpot}

| Nom | Description |
| --- | --- |
| getHotSpot() | Obtient ou définit l'angle du cône du point chaud (en degrés). |

 **Result:**



---


### setHotSpot{#setHotSpot}

| Nom | Description |
| --- | --- |
| setHotSpot(value) | Obtient ou définit l'angle du cône du point chaud (en degrés). |

 **Result:**



---


### getFalloff{#getFalloff}

| Nom | Description |
| --- | --- |
| getFalloff() | Obtient ou définit l'angle du cône de décroissance (en degrés). |

 **Result:**



---


### setFalloff{#setFalloff}

| Nom | Description |
| --- | --- |
| setFalloff(value) | Obtient ou définit l'angle du cône de décroissance (en degrés). |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| Nom | Description |
| --- | --- |
| getConstantAttenuation() | Obtient ou définit l'atténuation constante pour calculer l'atténuation totale de la lumière |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| Nom | Description |
| --- | --- |
| setConstantAttenuation(value) | Obtient ou définit l'atténuation constante pour calculer l'atténuation totale de la lumière |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| Nom | Description |
| --- | --- |
| getLinearAttenuation() | Obtient ou définit l'atténuation linéaire pour calculer l'atténuation totale de la lumière |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| Nom | Description |
| --- | --- |
| setLinearAttenuation(value) | Obtient ou définit l'atténuation linéaire pour calculer l'atténuation totale de la lumière |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| Nom | Description |
| --- | --- |
| getQuadraticAttenuation() | Obtient ou définit l'atténuation quadratique pour calculer l'atténuation totale de la lumière |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| Nom | Description |
| --- | --- |
| setQuadraticAttenuation(value) | Obtient ou définit l'atténuation quadratique pour calculer l'atténuation totale de la lumière |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nom | Description |
| --- | --- |
| getCastShadows() | Obtient ou définit si la lumière peut projeter des ombres sur d'autres objets. |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nom | Description |
| --- | --- |
| setCastShadows(value) | Obtient ou définit si la lumière peut projeter des ombres sur d'autres objets. |

 **Result:**



---


### getShadowColor{#getShadowColor}

| Nom | Description |
| --- | --- |
| getShadowColor() | Obtient ou définit la couleur de l'ombre. |

 **Result:**



---


### setShadowColor{#setShadowColor}

| Nom | Description |
| --- | --- |
| setShadowColor(value) | Obtient ou définit la couleur de l'ombre. |

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



