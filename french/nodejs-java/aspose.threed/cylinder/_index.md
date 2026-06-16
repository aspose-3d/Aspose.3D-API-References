---
title: "Cylinder"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

Cylindre paramétré. Il peut également être utilisé pour représenter le cône lorsque l'un des rayons radiusTop/radiusBottom est nul.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de la classe Cylinder. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(radius, height) | Initialise une nouvelle instance de la classe Cylinder. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rayon | Nombre | Rayon du couvercle supérieur et inférieur. |
| height | Nombre | Hauteur. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Initialise une nouvelle instance de la classe Cylinder. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| radiusTop | Nombre | Rayon supérieur. |
| radiusBottom | Nombre | Rayon inférieur. |
| height | Nombre | Hauteur. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nom | Description |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Initialise une nouvelle instance de la classe Cylinder. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| radiusTop | Nombre | Rayon du couvercle supérieur du cylindre. |
| radiusBottom | Nombre | Rayon du couvercle inférieur du cylindre. |
| height | Nombre | Hauteur du cylindre. |
| radialSegments | Nombre | Segments radiaux des cercles supérieur et inférieur.. |
| heightSegments | Nombre | Segments de hauteur. |
| openEnded | boolean | Si défini sur |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nom | Description |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Initialise une nouvelle instance de la classe Cylinder. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Le nom de cet objet |
| radiusTop | Nombre | Rayon du couvercle supérieur du cylindre. |
| radiusBottom | Nombre | Rayon du couvercle inférieur du cylindre. |
| height | Nombre | Hauteur du cylindre. |
| radialSegments | Nombre | Segments radiaux des cercles supérieur et inférieur.. |
| heightSegments | Nombre | Segments de hauteur. |
| openEnded | boolean | Si défini sur |
| thetaStart | Nombre | Début theta. |
| thetaLength | Nombre | Longueur theta. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| Nom | Description |
| --- | --- |
| getOffsetBottom() | Obtient ou définit le décalage de transformation des sommets du côté inférieur. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| Nom | Description |
| --- | --- |
| setOffsetBottom(value) | Obtient ou définit le décalage de transformation des sommets du côté inférieur. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| Nom | Description |
| --- | --- |
| getOffsetTop() | Obtient ou définit le décalage de transformation des sommets du côté supérieur. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| Nom | Description |
| --- | --- |
| setOffsetTop(value) | Obtient ou définit le décalage de transformation des sommets du côté supérieur. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| Nom | Description |
| --- | --- |
| getGenerateFanCylinder() | Obtient ou définit si le cylindre en forme d'éventail doit être généré lorsque ThetaLength est inférieur à 2PI, sinon le modèle ne sera pas découpé. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| Nom | Description |
| --- | --- |
| setGenerateFanCylinder(value) | Obtient ou définit si le cylindre en forme d'éventail doit être généré lorsque ThetaLength est inférieur à 2PI, sinon le modèle ne sera pas découpé. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| Nom | Description |
| --- | --- |
| getShearBottom() | Obtient ou définit la transformation de cisaillement du côté inférieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0). |

 **Result:**



---


### setShearBottom{#setShearBottom}

| Nom | Description |
| --- | --- |
| setShearBottom(value) | Obtient ou définit la transformation de cisaillement du côté inférieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0). |

 **Result:**



---


### getShearTop{#getShearTop}

| Nom | Description |
| --- | --- |
| getShearTop() | Obtient ou définit la transformation de cisaillement du côté supérieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0). |

 **Result:**



---


### setShearTop{#setShearTop}

| Nom | Description |
| --- | --- |
| setShearTop(value) | Obtient ou définit la transformation de cisaillement du côté supérieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0). |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| Nom | Description |
| --- | --- |
| getRadiusTop() | Obtient ou définit le rayon du couvercle supérieur du cylindre. Le rayon du couvercle supérieur. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| Nom | Description |
| --- | --- |
| setRadiusTop(value) | Obtient ou définit le rayon du couvercle supérieur du cylindre. Le rayon du couvercle supérieur. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| Nom | Description |
| --- | --- |
| getRadiusBottom() | Obtient ou définit le rayon du couvercle inférieur du cylindre. Le rayon du couvercle inférieur. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| Nom | Description |
| --- | --- |
| setRadiusBottom(value) | Obtient ou définit le rayon du couvercle inférieur du cylindre. Le rayon du couvercle inférieur. |

 **Result:**



---


### getHeight{#getHeight}

| Nom | Description |
| --- | --- |
| getHeight() | Obtient ou définit la hauteur du cylindre. La hauteur. |

 **Result:**



---


### setHeight{#setHeight}

| Nom | Description |
| --- | --- |
| setHeight(value) | Obtient ou définit la hauteur du cylindre. La hauteur. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| Nom | Description |
| --- | --- |
| getRadialSegments() | Obtient ou définit les segments radiaux. Les segments radiaux. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| Nom | Description |
| --- | --- |
| setRadialSegments(value) | Obtient ou définit les segments radiaux. Les segments radiaux. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Nom | Description |
| --- | --- |
| getHeightSegments() | Obtient ou définit les segments de hauteur. Les segments de hauteur. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Nom | Description |
| --- | --- |
| setHeightSegments(value) | Obtient ou définit les segments de hauteur. Les segments de hauteur. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| Nom | Description |
| --- | --- |
| getOpenEnded() | Obtient ou définit une valeur indiquant si ce Cylinder est ouvert aux extrémités. La valeur par défaut est false. true si ouvert aux extrémités ; sinon, les couvercles supérieurs/inférieurs existent. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| Nom | Description |
| --- | --- |
| setOpenEnded(value) | Obtient ou définit une valeur indiquant si ce Cylinder est ouvert aux extrémités. La valeur par défaut est false. true si ouvert aux extrémités ; sinon, les couvercles supérieurs/inférieurs existent. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| Nom | Description |
| --- | --- |
| getThetaStart() | Obtient ou définit le départ theta. La valeur par défaut est 0. Le départ theta. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| Nom | Description |
| --- | --- |
| setThetaStart(value) | Obtient ou définit le départ theta. La valeur par défaut est 0. Le départ theta. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| Nom | Description |
| --- | --- |
| getThetaLength() | Obtient ou définit la longueur du theta. La valeur par défaut est 2π. La longueur du theta. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| Nom | Description |
| --- | --- |
| setThetaLength(value) | Obtient ou définit la longueur du theta. La valeur par défaut est 2π. La longueur du theta. |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nom | Description |
| --- | --- |
| getCastShadows() | Récupère ou définit si cette géométrie peut projeter une ombre |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nom | Description |
| --- | --- |
| setCastShadows(value) | Récupère ou définit si cette géométrie peut projeter une ombre |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Nom | Description |
| --- | --- |
| getReceiveShadows() | Récupère ou définit si cette géométrie peut recevoir une ombre. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Nom | Description |
| --- | --- |
| setReceiveShadows(value) | Récupère ou définit si cette géométrie peut recevoir une ombre. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nom | Description |
| --- | --- |
| getParentNodes() | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation géométrique. Les nœuds. |

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
| getParentNode() | Obtient ou définit le premier nœud parent ; si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. Le nœud parent. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nom | Description |
| --- | --- |
| setParentNode(value) | Obtient ou définit le premier nœud parent ; si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. Le nœud parent. |

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


### toMesh{#toMesh}

| Nom | Description |
| --- | --- |
| toMesh() | Convertir l'objet actuel en maillage |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Nom | Description |
| --- | --- |
| getBoundingBox() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |

 **Result:**
Mesh


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
| property | Property | Quelle propriété supprimer |

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
| property | String | Nom de la propriété |

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
| property | String | Nom de la propriété |
| value | Object | La valeur de la propriété |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nom | Description |
| --- | --- |
| findProperty(propertyName) | Recherche la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propertyName | String | Nom de la propriété. |

 **Result:**
Property


---



