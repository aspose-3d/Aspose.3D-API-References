---
title: "NurbsCurve"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

Une courbe NURBS est une courbe représentée par NURBS (Non-uniform rational basis spline).  Une courbe NURBS est définie par son Order, un ensemble de Geometry.ControlPoints pondérés et des KnotVectors.  Le composant w du point de contrôle est utilisé comme poids du point de contrôle, quelle que soit la dimension CurveDimension.TWO_DIMENSIONAL ou CurveDimension.THREE_DIMENSIONAL.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de la classe NurbsCurve. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(name) | Initialise une nouvelle instance de la classe NurbsCurve. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Nom | Description |
| --- | --- |
| getControlPoints() | Récupère tous les points de contrôle |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| Nom | Description |
| --- | --- |
| getMultiplicity() | Obtient la multiplicité. La multiplicité. |

 **Result:**



---


### getOrder{#getOrder}

| Nom | Description |
| --- | --- |
| getOrder() | Obtient ou définit l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent tout point donné de la courbe. L'ordre. |

 **Result:**



---


### setOrder{#setOrder}

| Nom | Description |
| --- | --- |
| setOrder(value) | Obtient ou définit l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent tout point donné de la courbe. L'ordre. |

 **Result:**



---


### getDimension{#getDimension}

| Nom | Description |
| --- | --- |
| getDimension() | Obtient ou définit la dimension de la courbe. La valeur de la propriété est une constante entière CurveDimension. Pour une courbe CurveDimension.TWO_DIMENSIONAL, le composant z du point de contrôle n'est pas utilisé. |

 **Result:**



---


### setDimension{#setDimension}

| Nom | Description |
| --- | --- |
| setDimension(value) | Obtient ou définit la dimension de la courbe. La valeur de la propriété est une constante entière CurveDimension. Pour une courbe CurveDimension.TWO_DIMENSIONAL, le composant z du point de contrôle n'est pas utilisé. |

 **Result:**



---


### getCurveType{#getCurveType}

| Nom | Description |
| --- | --- |
| getCurveType() | Obtient ou définit le type de la courbe. La valeur de la propriété est une constante entière NurbsType. Le type de la courbe. |

 **Result:**



---


### setCurveType{#setCurveType}

| Nom | Description |
| --- | --- |
| setCurveType(value) | Obtient ou définit le type de la courbe. La valeur de la propriété est une constante entière NurbsType. Le type de la courbe. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Nom | Description |
| --- | --- |
| getKnotVectors() | Obtient le vecteur de nœuds, c'est une séquence de valeurs de paramètre qui détermine où et comment les points de contrôle affectent la courbe NURBS. |

 **Result:**



---


### getRational{#getRational}

| Nom | Description |
| --- | --- |
| getRational() | Obtient ou définit s'il est rationnel, cette valeur indique si ce NurbsCurve est un spline rationnel ou un spline non rationnel. Le B-spline non rationnel est un cas particulier des B-splines rationnels. true si c'est un spline rationnel ; sinon, false est un spline non rationnel. |

 **Result:**



---


### setRational{#setRational}

| Nom | Description |
| --- | --- |
| setRational(value) | Obtient ou définit s'il est rationnel, cette valeur indique si ce NurbsCurve est un spline rationnel ou un spline non rationnel. Le B-spline non rationnel est un cas particulier des B-splines rationnels. true si c'est un spline rationnel ; sinon, false est un spline non rationnel. |

 **Result:**



---


### getColor{#getColor}

| Nom | Description |
| --- | --- |
| getColor() | Obtient ou définit la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Nom | Description |
| --- | --- |
| setColor(value) | Obtient ou définit la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1) |

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


### evaluate{#evaluate}

| Nom | Description |
| --- | --- |
| evaluate(steps) | Évalue la courbe NURBS |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| steps | Nombre | La fréquence d'évaluation entre deux nœuds voisins, la valeur par défaut est 20 |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| Nom | Description |
| --- | --- |
| evaluateAt(u) | Évalue le point de la courbe à la position spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| u | Nombre | La position sur la courbe, entre 0 et 1 |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| Nom | Description |
| --- | --- |
| getEntityRendererKey() | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Nom | Description |
| --- | --- |
| getBoundingBox() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |

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



