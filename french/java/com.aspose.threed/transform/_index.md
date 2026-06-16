---
title: "Transformation"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Une transformation contient des informations qui permettent d'accéder à la translation/échelle/rotation des objets ou à la matrice de transformation avec un coût minimal  Ceci est utilisé par la transformation locale."
type: docs
weight: 190
url: /fr/java/com.aspose.threed/transform/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Transform extends A3DObject
```

Une transformation contient des informations qui permettent d'accéder à la translation/échelle/rotation de l'objet ou à la matrice de transformation avec un coût minimal. Ceci est utilisé par la transformation locale. **Exemple:** Le code suivant montre comment modifier la transformation du nœud :

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | Obtient la rotation représentée en angles d'Euler, mesurée en degrés |
| [getGeometricRotation()](#getGeometricRotation--) | Obtient la rotation d'Euler géométrique (mesurée en degrés). |
| [getGeometricScaling()](#getGeometricScaling--) | Obtient l'échelle géométrique. |
| [getGeometricTranslation()](#getGeometricTranslation--) | Obtient la translation géométrique. |
| [getName()](#getName--) | Obtient le nom. |
| [getPostRotation()](#getPostRotation--) | Obtient la post-rotation représentée en degrés |
| [getPreRotation()](#getPreRotation--) | Obtient la pré-rotation représentée en degrés |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getRotation()](#getRotation--) | Obtient la rotation représentée en quaternion. |
| [getRotationOffset()](#getRotationOffset--) | Obtient le décalage de rotation |
| [getRotationPivot()](#getRotationPivot--) | Obtient le pivot de rotation |
| [getScaling()](#getScaling--) | Obtient la mise à l'échelle |
| [getScalingOffset()](#getScalingOffset--) | Obtient le décalage de mise à l'échelle |
| [getScalingPivot()](#getScalingPivot--) | Obtient le pivot de mise à l'échelle |
| [getTransformMatrix()](#getTransformMatrix--) | Obtient la matrice de transformation. |
| [getTranslation()](#getTranslation--) | Obtient la translation |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setEulerAngles(Vector3 value)](#setEulerAngles-com.aspose.threed.Vector3-) | Définit la rotation représentée en angles d'Euler, mesurée en degrés |
| [setEulerAngles(double rx, double ry, double rz)](#setEulerAngles-double-double-double-) | Définit les angles d'Euler en degrés de la transformation actuelle. |
| [setGeometricRotation(Vector3 value)](#setGeometricRotation-com.aspose.threed.Vector3-) | Définit la rotation géométrique d'Euler (mesurée en degrés). |
| [setGeometricRotation(double rx, double ry, double rz)](#setGeometricRotation-double-double-double-) | Définit la rotation géométrique d'Euler (mesurée en degrés). |
| [setGeometricScaling(Vector3 value)](#setGeometricScaling-com.aspose.threed.Vector3-) | Définit la mise à l'échelle géométrique. |
| [setGeometricScaling(double sx, double sy, double sz)](#setGeometricScaling-double-double-double-) | Définit la mise à l'échelle géométrique. |
| [setGeometricTranslation(Vector3 value)](#setGeometricTranslation-com.aspose.threed.Vector3-) | Définit la translation géométrique. |
| [setGeometricTranslation(double x, double y, double z)](#setGeometricTranslation-double-double-double-) | Définit la translation géométrique. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setPostRotation(Vector3 value)](#setPostRotation-com.aspose.threed.Vector3-) | Définit la post-rotation exprimée en degrés |
| [setPostRotation(double rx, double ry, double rz)](#setPostRotation-double-double-double-) | Définit la post-rotation représentée en degrés **Exemple:** |
| [setPreRotation(Vector3 value)](#setPreRotation-com.aspose.threed.Vector3-) | Définit la pré-rotation exprimée en degrés |
| [setPreRotation(double rx, double ry, double rz)](#setPreRotation-double-double-double-) | Définit la pré-rotation représentée en degrés **Exemple:** |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setRotation(Quaternion value)](#setRotation-com.aspose.threed.Quaternion-) | Définit la rotation représentée en quaternion. |
| [setRotation(double rw, double rx, double ry, double rz)](#setRotation-double-double-double-double-) | Définit la rotation (en tant que composants quaternion) de la transformation actuelle. |
| [setRotationOffset(Vector3 value)](#setRotationOffset-com.aspose.threed.Vector3-) | Définit le décalage de rotation |
| [setRotationPivot(Vector3 value)](#setRotationPivot-com.aspose.threed.Vector3-) | Définit le pivot de rotation |
| [setScale(double sx, double sy, double sz)](#setScale-double-double-double-) | Définit l'échelle de la transformation actuelle. |
| [setScaling(Vector3 value)](#setScaling-com.aspose.threed.Vector3-) | Définit la mise à l'échelle |
| [setScalingOffset(Vector3 value)](#setScalingOffset-com.aspose.threed.Vector3-) | Définit le décalage de mise à l'échelle |
| [setScalingPivot(Vector3 value)](#setScalingPivot-com.aspose.threed.Vector3-) | Définit le pivot de mise à l'échelle |
| [setTransformMatrix(Matrix4 value)](#setTransformMatrix-com.aspose.threed.Matrix4-) | Définit la matrice de transformation. |
| [setTranslation(Vector3 value)](#setTranslation-com.aspose.threed.Vector3-) | Définit la translation |
| [setTranslation(double tx, double ty, double tz)](#setTranslation-double-double-double-) | Définit la translation de la transformation actuelle. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEulerAngles() {#getEulerAngles--}
```
public Vector3 getEulerAngles()
```


Obtient la rotation représentée en angles d'Euler, mesurée en degrés

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation represented in Euler angles, measured in degree **Example:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
```
### getGeometricRotation() {#getGeometricRotation--}
```
public Vector3 getGeometricRotation()
```


Obtient la rotation géométrique d'Euler (mesurée en degrés). La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée comme transformation locale lorsque vous exportez la transformation géométrique vers des types de fichiers qui ne le prennent pas en charge.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.
### getGeometricScaling() {#getGeometricScaling--}
```
public Vector3 getGeometricScaling()
```


Obtient l'échelle géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric scaling. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
```
### getGeometricTranslation() {#getGeometricTranslation--}
```
public Vector3 getGeometricTranslation()
```


Obtient la translation géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric translation. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
```
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getPostRotation() {#getPostRotation--}
```
public Vector3 getPostRotation()
```


Obtient la post-rotation représentée en degrés

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the post-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
```
### getPreRotation() {#getPreRotation--}
```
public Vector3 getPreRotation()
```


Obtient la pré-rotation représentée en degrés

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the pre-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
```
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
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


Obtient la rotation représentée en quaternion.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - the rotation represented in quaternion. **Example:**

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
```
### getRotationOffset() {#getRotationOffset--}
```
public Vector3 getRotationOffset()
```


Obtient le décalage de rotation

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation offset
### getRotationPivot() {#getRotationPivot--}
```
public Vector3 getRotationPivot()
```


Obtient le pivot de rotation

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation pivot
### getScaling() {#getScaling--}
```
public Vector3 getScaling()
```


Obtient la mise à l'échelle

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling **Example:**

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
```
### getScalingOffset() {#getScalingOffset--}
```
public Vector3 getScalingOffset()
```


Obtient le décalage de mise à l'échelle

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling offset
### getScalingPivot() {#getScalingPivot--}
```
public Vector3 getScalingPivot()
```


Obtient le pivot de mise à l'échelle

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling pivot
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


Obtient la matrice de transformation.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix. **Remarks:** Assign on this will reset the [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) and [getRotation](../../com.aspose.threed/transform\#getRotation), the [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) and [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) will not be affected. **Example:**

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
```
### getTranslation() {#getTranslation--}
```
public Vector3 getTranslation()
```


Obtient la translation

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the translation **Example:**

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
```
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
### setEulerAngles(Vector3 value) {#setEulerAngles-com.aspose.threed.Vector3-}
```
public void setEulerAngles(Vector3 value)
```


Définit la rotation représentée en angles d'Euler, mesurée en degrés

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur **Exemple:** |

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
``` |

### setEulerAngles(double rx, double ry, double rz) {#setEulerAngles-double-double-double-}
```
public Transform setEulerAngles(double rx, double ry, double rz)
```


Définit les angles d'Euler en degrés de la transformation actuelle. **Exemple:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(90, 0, 0);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricRotation(Vector3 value) {#setGeometricRotation-com.aspose.threed.Vector3-}
```
public void setGeometricRotation(Vector3 value)
```


Définit la rotation Euler géométrique (mesurée en degrés). La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setGeometricRotation(double rx, double ry, double rz) {#setGeometricRotation-double-double-double-}
```
public Transform setGeometricRotation(double rx, double ry, double rz)
```


Définit la rotation Euler géométrique (mesurée en degrés). La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. **Exemple:**

```
Node node = new Node();
     node.getTransform().setGeometricRotation(90, 0, 0);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricScaling(Vector3 value) {#setGeometricScaling-com.aspose.threed.Vector3-}
```
public void setGeometricScaling(Vector3 value)
```


Définit l'échelle géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur **Exemple:** |

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
``` |

### setGeometricScaling(double sx, double sy, double sz) {#setGeometricScaling-double-double-double-}
```
public Transform setGeometricScaling(double sx, double sy, double sz)
```


Définit l'échelle géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. **Exemple:**

```
Node node = new Node();
     node.getTransform().setGeometricScaling(2, 2, 2);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricTranslation(Vector3 value) {#setGeometricTranslation-com.aspose.threed.Vector3-}
```
public void setGeometricTranslation(Vector3 value)
```


Définit la translation géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur **Exemple:** |

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
``` |

### setGeometricTranslation(double x, double y, double z) {#setGeometricTranslation-double-double-double-}
```
public Transform setGeometricTranslation(double x, double y, double z)
```


Définit la translation géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. **Exemple:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(10, 0, 0);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setPostRotation(Vector3 value) {#setPostRotation-com.aspose.threed.Vector3-}
```
public void setPostRotation(Vector3 value)
```


Définit la post-rotation exprimée en degrés

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur **Exemple:** |

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
``` |

### setPostRotation(double rx, double ry, double rz) {#setPostRotation-double-double-double-}
```
public Transform setPostRotation(double rx, double ry, double rz)
```


Définit la post-rotation représentée en degrés **Exemple:**

```
Node node = new Node();
     node.getTransform().setPostRotation(90, 0, 0);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setPreRotation(Vector3 value) {#setPreRotation-com.aspose.threed.Vector3-}
```
public void setPreRotation(Vector3 value)
```


Définit la pré-rotation exprimée en degrés

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur **Exemple:** |

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
``` |

### setPreRotation(double rx, double ry, double rz) {#setPreRotation-double-double-double-}
```
public Transform setPreRotation(double rx, double ry, double rz)
```


Définit la pré-rotation représentée en degrés **Exemple:**

```
Node node = new Node();
     node.getTransform().setPreRotation(90, 0, 0);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

### setRotation(Quaternion value) {#setRotation-com.aspose.threed.Quaternion-}
```
public void setRotation(Quaternion value)
```


Définit la rotation représentée en quaternion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Quaternion](../../com.aspose.threed/quaternion) | Nouvelle valeur **Exemple:** |

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
``` |

### setRotation(double rw, double rx, double ry, double rz) {#setRotation-double-double-double-double-}
```
public Transform setRotation(double rw, double rx, double ry, double rz)
```


Définit la rotation (sous forme de composantes quaternion) de la transformation actuelle. **Exemple:**

```
Node node = new Node();
     node.getTransform().setRotation(1, 0, 0, 0);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rw | double |  |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setRotationOffset(Vector3 value) {#setRotationOffset-com.aspose.threed.Vector3-}
```
public void setRotationOffset(Vector3 value)
```


Définit le décalage de rotation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setRotationPivot(Vector3 value) {#setRotationPivot-com.aspose.threed.Vector3-}
```
public void setRotationPivot(Vector3 value)
```


Définit le pivot de rotation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setScale(double sx, double sy, double sz) {#setScale-double-double-double-}
```
public Transform setScale(double sx, double sy, double sz)
```


Définit l'échelle de la transformation actuelle. **Exemple:**

```
Node node = new Node();
     node.getTransform().setScale(2, 2, 2);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setScaling(Vector3 value) {#setScaling-com.aspose.threed.Vector3-}
```
public void setScaling(Vector3 value)
```


Définit la mise à l'échelle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur **Exemple:** |

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
``` |

### setScalingOffset(Vector3 value) {#setScalingOffset-com.aspose.threed.Vector3-}
```
public void setScalingOffset(Vector3 value)
```


Définit le décalage de mise à l'échelle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setScalingPivot(Vector3 value) {#setScalingPivot-com.aspose.threed.Vector3-}
```
public void setScalingPivot(Vector3 value)
```


Définit le pivot de mise à l'échelle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setTransformMatrix(Matrix4 value) {#setTransformMatrix-com.aspose.threed.Matrix4-}
```
public void setTransformMatrix(Matrix4 value)
```


Définit la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Matrix4](../../com.aspose.threed/matrix4) | Nouvelle valeur **Remarques :** L'affectation ici réinitialisera les [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) et [getRotation](../../com.aspose.threed/transform\#getRotation), les [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) et [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) ne seront pas affectés. **Exemple:** |

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
``` |

### setTranslation(Vector3 value) {#setTranslation-com.aspose.threed.Vector3-}
```
public void setTranslation(Vector3 value)
```


Définit la translation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur **Exemple:** |

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
``` |

### setTranslation(double tx, double ty, double tz) {#setTranslation-double-double-double-}
```
public Transform setTranslation(double tx, double ty, double tz)
```


Définit la translation de la transformation actuelle. **Exemple:**

```
Node node = new Node();
     node.getTransform().setTranslation(10, 0, 0);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tx | double |  |
| ty | double |  |
| tz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

