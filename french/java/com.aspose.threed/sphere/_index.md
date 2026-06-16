---
title: "Sphere"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Sphère paramétrée."
type: docs
weight: 174
url: /fr/java/com.aspose.threed/sphere/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Sphere extends Primitive
```

Sphère paramétrée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Sphere()](#Sphere--) | Initialise une nouvelle instance de [Sphere](../../com.aspose.threed/sphere) avec un rayon par défaut de 1. |
| [Sphere(double radius)](#Sphere-double-) | Initialise une nouvelle instance de la classe [Sphere](../../com.aspose.threed/sphere) avec le rayon spécifié. |
| [Sphere(double radius, int widthSegments, int heightSegments)](#Sphere-double-int-int-) | Initialise une nouvelle instance de la classe [Sphere](../../com.aspose.threed/sphere) avec le rayon, les segments de largeur et les segments de hauteur spécifiés. |
| [Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength)](#Sphere-java.lang.String-double-int-int-double-double-double-double-) | Initialise une nouvelle instance de la classe [Sphere](../../com.aspose.threed/sphere). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getCastShadows()](#getCastShadows--) | Obtient si cette géométrie peut projeter une ombre |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getHeightSegments()](#getHeightSegments--) | Obtient les segments de hauteur. |
| [getName()](#getName--) | Obtient le nom. |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getPhiLength()](#getPhiLength--) | Obtient la longueur du phi. |
| [getPhiStart()](#getPhiStart--) | Obtient le départ du phi. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getRadius()](#getRadius--) | Obtient le rayon de la sphère. |
| [getReceiveShadows()](#getReceiveShadows--) | Obtient si cette géométrie peut recevoir une ombre. |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getThetaLength()](#getThetaLength--) | Obtient la longueur du theta. |
| [getThetaStart()](#getThetaStart--) | Obtient le départ du theta. |
| [getWidthSegments()](#getWidthSegments--) | Obtient les segments de largeur. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Définit si cette géométrie peut projeter une ombre |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Définit les segments de hauteur. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setPhiLength(double value)](#setPhiLength-double-) | Définit la longueur du phi. |
| [setPhiStart(double value)](#setPhiStart-double-) | Définit le départ du phi. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setRadius(double value)](#setRadius-double-) | Définit le rayon de la sphère. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Définit si cette géométrie peut recevoir une ombre. |
| [setThetaLength(double value)](#setThetaLength-double-) | Définit la longueur du theta. |
| [setThetaStart(double value)](#setThetaStart-double-) | Définit le départ du theta. |
| [setWidthSegments(int value)](#setWidthSegments-int-) | Définit les segments de largeur. |
| [toMesh()](#toMesh--) | Convertir l'objet actuel en maillage |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Sphere() {#Sphere--}
```
public Sphere()
```


Initialise une nouvelle instance de [Sphere](../../com.aspose.threed/sphere) avec un rayon par défaut de 1.

### Sphere(double radius) {#Sphere-double-}
```
public Sphere(double radius)
```


Initialise une nouvelle instance de la classe [Sphere](../../com.aspose.threed/sphere) avec le rayon spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| radius | double | Rayon. |

### Sphere(double radius, int widthSegments, int heightSegments) {#Sphere-double-int-int-}
```
public Sphere(double radius, int widthSegments, int heightSegments)
```


Initialise une nouvelle instance de la classe [Sphere](../../com.aspose.threed/sphere) avec le rayon, les segments de largeur et les segments de hauteur spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| radius | double | Rayon de la sphère. |
| widthSegments | int | Segments de largeur. |
| heightSegments | int | Segments de hauteur. |

### Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength) {#Sphere-java.lang.String-double-int-int-double-double-double-double-}
```
public Sphere(String name, double radius, int widthSegments, int heightSegments, double phiStart, double phiLength, double thetaStart, double thetaLength)
```


Initialise une nouvelle instance de la classe [Sphere](../../com.aspose.threed/sphere).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom. |
| radius | double | Rayon de la sphère. |
| widthSegments | int | Segments de largeur. |
| heightSegments | int | Segments de hauteur. |
| phiStart | double | Départ du phi. |
| phiLength | double | Longueur du phi. |
| thetaStart | double | Départ du theta. |
| thetaLength | double | Longueur du theta. |

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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Obtient si cette géométrie peut projeter une ombre

**Returns:**
boolean - indique si cette géométrie peut projeter une ombre
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Obtient la clé du rendu d'entité enregistré dans le moteur de rendu

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Obtient si l'entité doit être exclue lors de l'exportation.

**Returns:**
booléen - indique si l'entité doit être exclue lors de l'exportation.
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


Obtient les segments de hauteur.

**Returns:**
int - les segments de hauteur.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
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
### getPhiLength() {#getPhiLength--}
```
public double getPhiLength()
```


Obtient la longueur du phi.

**Returns:**
double - la longueur du phi.
### getPhiStart() {#getPhiStart--}
```
public double getPhiStart()
```


Obtient le départ du phi.

**Returns:**
double - le départ du phi.
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
### getRadius() {#getRadius--}
```
public double getRadius()
```


Obtient le rayon de la sphère.

**Returns:**
double - le rayon de la sphère.
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Obtient si cette géométrie peut recevoir une ombre.

**Returns:**
boolean - si cette géométrie peut recevoir une ombre.
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtient la scène à laquelle cet objet appartient

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Obtient la longueur du theta.

**Returns:**
double - la longueur du theta.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Obtient le départ du theta.

**Returns:**
double - le départ du theta.
### getWidthSegments() {#getWidthSegments--}
```
public int getWidthSegments()
```


Obtient les segments de largeur.

**Returns:**
int - les segments de largeur.
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Définit si cette géométrie peut projeter une ombre

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Définit si l'entité doit être exclue lors de l'exportation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


Définit les segments de hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nouvelle valeur |

### setPhiLength(double value) {#setPhiLength-double-}
```
public void setPhiLength(double value)
```


Définit la longueur du phi.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setPhiStart(double value) {#setPhiStart-double-}
```
public void setPhiStart(double value)
```


Définit le départ du phi.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

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

### setRadius(double value) {#setRadius-double-}
```
public void setRadius(double value)
```


Définit le rayon de la sphère.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Définit si cette géométrie peut recevoir une ombre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Définit la longueur du theta.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Définit le départ du theta.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setWidthSegments(int value) {#setWidthSegments-int-}
```
public void setWidthSegments(int value)
```


Définit les segments de largeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Convertir l'objet actuel en maillage

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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

