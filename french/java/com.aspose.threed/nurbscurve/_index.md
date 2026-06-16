---
title: "NurbsCurve"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Une courbe NURBS est une courbe représentée par NURBSNon-uniform rational basis spline  Une courbe NURBS est définie par son  un ensemble de points pondérés  et un  Le composant w dans le point de contrôle est utilisé comme poids du point de contrôle, quel que soit ce que c'est un  ou"
type: docs
weight: 112
url: /fr/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | Initialise une nouvelle instance de la classe [NurbsCurve](../../com.aspose.threed/nurbscurve). |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | Initialise une nouvelle instance de la classe [NurbsCurve](../../com.aspose.threed/nurbscurve). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | Évaluer la courbe NURBS |
| [evaluate(int steps)](#evaluate-int-) | Évaluer la courbe NURBS |
| [evaluateAt(double u)](#evaluateAt-double-) | Évaluer le point de la courbe à la position spécifiée |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtient la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1) |
| [getControlPoints()](#getControlPoints--) | Obtient tous les points de contrôle |
| [getCurveType()](#getCurveType--) | Obtient le type de la courbe. |
| [getDegree()](#getDegree--) | Obtient le degré d'une courbe NURBS, le degré est défini comme Ordre - 1 |
| [getDimension()](#getDimension--) | Obtient la dimension de la courbe. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getKnotVectors()](#getKnotVectors--) | Obtient le vecteur de nœuds, c'est une séquence de valeurs de paramètres qui détermine où et comment les points de contrôle affectent la courbe NURBS. |
| [getMultiplicity()](#getMultiplicity--) | Obtient la multiplicité. |
| [getName()](#getName--) | Obtient le nom. |
| [getOrder()](#getOrder--) | Obtient l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent chaque point de la courbe. |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getRational()](#getRational--) | Obtient si elle est rationnelle, cette valeur indique si ce [NurbsCurve](../../com.aspose.threed/nurbscurve) est un spline rationnel ou non rationnel. |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Définit la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1) |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | Définit le type de la courbe. |
| [setDegree(int value)](#setDegree-int-) | Définit le degré d'une courbe NURBS, le degré est défini comme Ordre - 1 |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | Définit la dimension de la courbe. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setOrder(int value)](#setOrder-int-) | Définit l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent chaque point de la courbe. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setRational(boolean value)](#setRational-boolean-) | Définit si elle est rationnelle, cette valeur indique si ce [NurbsCurve](../../com.aspose.threed/nurbscurve) est un spline rationnel ou non rationnel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


Initialise une nouvelle instance de la classe [NurbsCurve](../../com.aspose.threed/nurbscurve).

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


Initialise une nouvelle instance de la classe [NurbsCurve](../../com.aspose.threed/nurbscurve).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


Évaluer la courbe NURBS

**Returns:**
com.aspose.threed.Vector4[] - Points dans la courbe
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


Évaluer la courbe NURBS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| étapes | int | La fréquence d'évaluation entre deux nœuds voisins, la valeur par défaut est 20 |

**Returns:**
com.aspose.threed.Vector4[] - Points dans la courbe
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


Évaluer le point de la courbe à la position spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| u | double | La position dans la courbe, entre 0 et 1 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | Nom de la propriété. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Obtient la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Obtient tous les points de contrôle

**Returns:**
java.util.List<com.aspose.threed.Vector4> - tous les points de contrôle
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


Obtient le type de la courbe.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Obtient le degré d'une courbe NURBS, le degré est défini comme Ordre - 1

**Returns:**
int - le degré d'une courbe NURBS, le degré est défini comme Ordre - 1
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


Obtient la dimension de la courbe.

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Obtient la clé du rendu d'entité enregistré dans le moteur de rendu

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Obtient si l'entité doit être exclue lors de l'exportation.

**Returns:**
booléen - indique si l'entité doit être exclue lors de l'exportation.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Obtient le vecteur de nœuds, c'est une séquence de valeurs de paramètres qui détermine où et comment les points de contrôle affectent la courbe NURBS.

**Returns:**
java.util.List<java.lang.Double> - le vecteur de nœuds, c'est une séquence de valeurs de paramètres qui détermine où et comment les points de contrôle affectent la courbe NURBS.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Obtient la multiplicité.

**Returns:**
java.util.List<java.lang.Integer> - la multiplicité.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Obtient l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent chaque point de la courbe.

**Returns:**
int - l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent tout point donné de la courbe.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtient la collection de toutes les propriétés.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtenir la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |

**Returns:**
java.lang.Object - La valeur de la propriété trouvée
### getRational() {#getRational--}
```
public boolean getRational()
```


Obtient si elle est rationnelle, cette valeur indique si ce [NurbsCurve](../../com.aspose.threed/nurbscurve) est un spline rationnel ou un spline non rationnel. Le B-spline non rationnel est un cas particulier des B-splines rationnels.

**Returns:**
boolean - si elle est rationnelle, cette valeur indique si ce [NurbsCurve](../../com.aspose.threed/nurbscurve) est un spline rationnel ou un spline non rationnel. Le B-spline non rationnel est un cas particulier des B-splines rationnels.
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtient la scène à laquelle cet objet appartient

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Supprime une propriété dynamique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Supprime la propriété spécifiée identifiée par son nom

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Définit la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


Définit le type de la courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nouvelle valeur |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Définit le degré d'une courbe NURBS, le degré est défini comme Ordre - 1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


Définit la dimension de la courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | Nouvelle valeur **Remarques:** Pour une courbe [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL), le composant z du point de contrôle n'est pas utilisé. |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Définit si l'entité doit être exclue lors de l'exportation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Définit l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent chaque point de la courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nouvelle valeur |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Définit la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |
| valeur | java.lang.Object | La valeur de la propriété |

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


Définit si elle est rationnelle, cette valeur indique si ce [NurbsCurve](../../com.aspose.threed/nurbscurve) est un spline rationnel ou un spline non rationnel. Le B-spline non rationnel est un cas particulier des B-splines rationnels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

