---
title: "Cylindre"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Cylindre paramétré."
type: docs
weight: 40
url: /fr/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

Cylindre paramétré. Il peut également être utilisé pour représenter le cône lorsqu'un des rayons radiusTop/radiusBottom est nul.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Cylinder()](#Cylinder--) | Initialise une nouvelle instance de la classe [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | Initialise une nouvelle instance de la classe [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | Initialise une nouvelle instance de la classe [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | Initialise une nouvelle instance de la classe [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | Initialise une nouvelle instance de la classe [Cylinder](../../com.aspose.threed/cylinder). |
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
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | Obtient si le cylindre de type fan doit être généré lorsque ThetaLength est inférieur à 2\*PI, sinon le modèle ne sera pas découpé. |
| [getHeight()](#getHeight--) | Obtient la hauteur du cylindre. |
| [getHeightSegments()](#getHeightSegments--) | Obtient les segments de hauteur. |
| [getName()](#getName--) | Obtient le nom. |
| [getOffsetBottom()](#getOffsetBottom--) | Obtient le décalage de transformation des sommets du côté inférieur. |
| [getOffsetTop()](#getOffsetTop--) | Obtient le décalage de transformation des sommets du côté supérieur. |
| [getOpenEnded()](#getOpenEnded--) | Obtient une valeur indiquant si ce [Cylinder](../../com.aspose.threed/cylinder) est ouvert aux extrémités. |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getRadialSegments()](#getRadialSegments--) | Obtient les segments radiaux. |
| [getRadiusBottom()](#getRadiusBottom--) | Obtient le rayon du couvercle inférieur du cylindre. |
| [getRadiusTop()](#getRadiusTop--) | Obtient le rayon du couvercle supérieur du cylindre. |
| [getReceiveShadows()](#getReceiveShadows--) | Obtient si cette géométrie peut recevoir une ombre. |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getShearBottom()](#getShearBottom--) | Obtient la transformation de cisaillement du côté inférieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0) |
| [getShearTop()](#getShearTop--) | Obtient la transformation de cisaillement du côté supérieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0) |
| [getThetaLength()](#getThetaLength--) | Obtient la longueur du theta. |
| [getThetaStart()](#getThetaStart--) | Obtient le départ du theta. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Définit si cette géométrie peut projeter une ombre |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | Définit s'il faut générer le cylindre en forme d'éventail lorsque ThetaLength est inférieur à 2\*PI, sinon le modèle ne sera pas découpé. |
| [setHeight(double value)](#setHeight-double-) | Définit la hauteur du cylindre. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Définit les segments de hauteur. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | Définit le décalage de transformation des sommets du côté inférieur. |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | Définit le décalage de transformation des sommets du côté supérieur. |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | Définit une valeur indiquant si ce [Cylinder](../../com.aspose.threed/cylinder) est à extrémité ouverte. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Définit les segments radiaux. |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | Définit le rayon du couvercle inférieur du cylindre. |
| [setRadiusTop(double value)](#setRadiusTop-double-) | Définit le rayon du couvercle supérieur du cylindre. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Définit si cette géométrie peut recevoir une ombre. |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | Définit la transformation de cisaillement du côté inférieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0) |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | Définit la transformation de cisaillement du côté supérieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0) |
| [setThetaLength(double value)](#setThetaLength-double-) | Définit la longueur du theta. |
| [setThetaStart(double value)](#setThetaStart-double-) | Définit le départ du theta. |
| [toMesh()](#toMesh--) | Convertir l'objet actuel en maillage |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


Initialise une nouvelle instance de la classe [Cylinder](../../com.aspose.threed/cylinder).

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


Initialise une nouvelle instance de la classe [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| radius | double | Rayon du couvercle supérieur et inférieur. |
| hauteur | double | Hauteur. |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


Initialise une nouvelle instance de la classe [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| radiusTop | double | Rayon supérieur. |
| radiusBottom | double | Rayon inférieur. |
| hauteur | double | Hauteur. |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


Initialise une nouvelle instance de la classe [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| radiusTop | double | Rayon du couvercle supérieur du cylindre. |
| radiusBottom | double | Rayon du couvercle inférieur du cylindre. |
| hauteur | double | Hauteur du cylindre. |
| radialSegments | int | Segments radiaux des cercles supérieur et inférieur.. |
| heightSegments | int | Segments de hauteur. |
| openEnded | boolean | Si défini sur  true  le cylindre n'aurait pas de capuchons inférieur/supérieur.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


Initialise une nouvelle instance de la classe [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom de cet objet |
| radiusTop | double | Rayon du couvercle supérieur du cylindre. |
| radiusBottom | double | Rayon du couvercle inférieur du cylindre. |
| hauteur | double | Hauteur du cylindre. |
| radialSegments | int | Segments radiaux des cercles supérieur et inférieur.. |
| heightSegments | int | Segments de hauteur. |
| openEnded | boolean | Si défini sur  true  le cylindre n'aurait pas de capuchons inférieur/supérieur.. |
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
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


Obtient si le cylindre de type fan doit être généré lorsque ThetaLength est inférieur à 2\*PI, sinon le modèle ne sera pas découpé.

**Returns:**
booléen - indique s'il faut générer le cylindre en forme d'éventail lorsque ThetaLength est inférieur à 2\*PI, sinon le modèle ne sera pas découpé.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtient la hauteur du cylindre.

**Returns:**
double - la hauteur du cylindre.
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
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


Obtient le décalage de transformation des sommets du côté inférieur.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


Obtient le décalage de transformation des sommets du côté supérieur.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


Obtient une valeur indiquant si ce [Cylinder](../../com.aspose.threed/cylinder) est ouvert. La valeur par défaut est false.

**Returns:**
booléen - une valeur indiquant si ce [Cylinder](../../com.aspose.threed/cylinder) est ouvert. La valeur par défaut est false.
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


Obtient les segments radiaux.

**Returns:**
int - les segments radiaux.
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


Obtient le rayon du couvercle inférieur du cylindre.

**Returns:**
double - le rayon du capuchon inférieur du cylindre.
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


Obtient le rayon du couvercle supérieur du cylindre.

**Returns:**
double - le rayon du capuchon supérieur du cylindre.
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
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


Obtient la transformation de cisaillement du côté inférieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


Obtient la transformation de cisaillement du côté supérieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Obtient la longueur de theta. La valeur par défaut est 2\\u03c0.

**Returns:**
double - la longueur de theta. La valeur par défaut est 2\\u03c0.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Obtient le départ de theta. La valeur par défaut est 0.

**Returns:**
double - le départ de theta. La valeur par défaut est 0.
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

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


Définit s'il faut générer le cylindre en forme d'éventail lorsque ThetaLength est inférieur à 2\*PI, sinon le modèle ne sera pas découpé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Définit la hauteur du cylindre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

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

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


Définit le décalage de transformation des sommets du côté inférieur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


Définit le décalage de transformation des sommets du côté supérieur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


Définit une valeur indiquant si ce [Cylinder](../../com.aspose.threed/cylinder) est ouvert. La valeur par défaut est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


Définit les segments radiaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


Définit le rayon du couvercle inférieur du cylindre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


Définit le rayon du couvercle supérieur du cylindre.

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

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


Définit la transformation de cisaillement du côté inférieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nouvelle valeur |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


Définit la transformation de cisaillement du côté supérieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nouvelle valeur |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Définit la longueur de theta. La valeur par défaut est 2\\u03c0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Définit le départ de theta. La valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

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

