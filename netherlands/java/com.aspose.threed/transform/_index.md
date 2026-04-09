---
title: Transformatie
second_title: Aspose.3D for Java API-referentie
description: Een transformatie bevat informatie die toegang biedt tot de vertaling/schaal/rotatie van objecten of de transformatiematrix tegen minimale kosten  Dit wordt gebruikt door lokale transformatie.
type: docs
weight: 190
url: /nl/java/com.aspose.threed/transform/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Transform extends A3DObject
```

Een transformatie bevat informatie die toegang biedt tot de vertaling/schaal/rotatie van een object of de transformatiematrix tegen minimale kosten. Dit wordt gebruikt door lokale transformatie. **Example:** De volgende code toont hoe de transformatie van de node kan worden gewijzigd:

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | Haalt de rotatie op die wordt weergegeven in Euler-hoeken, gemeten in graden |
| [getGeometricRotation()](#getGeometricRotation--) | Haalt de geometrische Euler-rotatie op (gemeten in graden). |
| [getGeometricScaling()](#getGeometricScaling--) | Haalt de geometrische schaal op. |
| [getGeometricTranslation()](#getGeometricTranslation--) | Haalt de geometrische translatie op. |
| [getName()](#getName--) | Haalt de naam op. |
| [getPostRotation()](#getPostRotation--) | Haalt de post‑rotatie op, weergegeven in graden |
| [getPreRotation()](#getPreRotation--) | Haalt de pre‑rotatie op, weergegeven in graden |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getRotation()](#getRotation--) | Haalt de rotatie op die wordt weergegeven in een quaternion. |
| [getRotationOffset()](#getRotationOffset--) | Haalt de rotatie‑offset op |
| [getRotationPivot()](#getRotationPivot--) | Haalt de rotatiepivot op |
| [getScaling()](#getScaling--) | Haalt de schaal op |
| [getScalingOffset()](#getScalingOffset--) | Haalt de schaalverschuiving op |
| [getScalingPivot()](#getScalingPivot--) | Haalt de schaalpivot op |
| [getTransformMatrix()](#getTransformMatrix--) | Haalt de transformatiematrix op. |
| [getTranslation()](#getTranslation--) | Haalt de translatie op |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setEulerAngles(Vector3 value)](#setEulerAngles-com.aspose.threed.Vector3-) | Stelt de rotatie in, weergegeven in Euler-hoeken, gemeten in graden |
| [setEulerAngles(double rx, double ry, double rz)](#setEulerAngles-double-double-double-) | Stelt de Euler-hoeken in graden van de huidige transformatie in. |
| [setGeometricRotation(Vector3 value)](#setGeometricRotation-com.aspose.threed.Vector3-) | Stelt de geometrische Euler-rotatie in (gemeten in graden). |
| [setGeometricRotation(double rx, double ry, double rz)](#setGeometricRotation-double-double-double-) | Stelt de geometrische Euler-rotatie in (gemeten in graden). |
| [setGeometricScaling(Vector3 value)](#setGeometricScaling-com.aspose.threed.Vector3-) | Stelt de geometrische schaal in. |
| [setGeometricScaling(double sx, double sy, double sz)](#setGeometricScaling-double-double-double-) | Stelt de geometrische schaal in. |
| [setGeometricTranslation(Vector3 value)](#setGeometricTranslation-com.aspose.threed.Vector3-) | Stelt de geometrische translatie in. |
| [setGeometricTranslation(double x, double y, double z)](#setGeometricTranslation-double-double-double-) | Stelt de geometrische translatie in. |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setPostRotation(Vector3 value)](#setPostRotation-com.aspose.threed.Vector3-) | Stelt de post-rotatie in, weergegeven in graden |
| [setPostRotation(double rx, double ry, double rz)](#setPostRotation-double-double-double-) | Stelt de post-rotatie in, weergegeven in graden **Voorbeeld:** |
| [setPreRotation(Vector3 value)](#setPreRotation-com.aspose.threed.Vector3-) | Stelt de pre-rotatie in, weergegeven in graden |
| [setPreRotation(double rx, double ry, double rz)](#setPreRotation-double-double-double-) | Stelt de pre-rotatie in, weergegeven in graden **Voorbeeld:** |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setRotation(Quaternion value)](#setRotation-com.aspose.threed.Quaternion-) | Stelt de rotatie in, weergegeven in quaternion. |
| [setRotation(double rw, double rx, double ry, double rz)](#setRotation-double-double-double-double-) | Stelt de rotatie (als quaternioncomponenten) van de huidige transformatie in. |
| [setRotationOffset(Vector3 value)](#setRotationOffset-com.aspose.threed.Vector3-) | Stelt de rotatieverschuiving in |
| [setRotationPivot(Vector3 value)](#setRotationPivot-com.aspose.threed.Vector3-) | Stelt de rotatiepivot in |
| [setScale(double sx, double sy, double sz)](#setScale-double-double-double-) | Stelt de schaal van de huidige transformatie in. |
| [setScaling(Vector3 value)](#setScaling-com.aspose.threed.Vector3-) | Stelt de schaal in |
| [setScalingOffset(Vector3 value)](#setScalingOffset-com.aspose.threed.Vector3-) | Stelt de schaalverschuiving in |
| [setScalingPivot(Vector3 value)](#setScalingPivot-com.aspose.threed.Vector3-) | Stelt de schaalpivot in |
| [setTransformMatrix(Matrix4 value)](#setTransformMatrix-com.aspose.threed.Matrix4-) | Stelt de transformatiematrix in. |
| [setTranslation(Vector3 value)](#setTranslation-com.aspose.threed.Vector3-) | Stelt de translatie in |
| [setTranslation(double tx, double ty, double tz)](#setTranslation-double-double-double-) | Stelt de translatie van de huidige transformatie in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native eigenschap (geïdentificeerd op naam).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyName | java.lang.String | Eigenschapnaam. |

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


Haalt de rotatie op die wordt weergegeven in Euler-hoeken, gemeten in graden

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


Haalt de geometrische Euler-rotatie op (gemeten in graden). Geometrische transformatie beïnvloedt alleen de gekoppelde entiteiten en laat de onderliggende knooppunten onaangedaan. Het wordt samengevoegd als lokale transformatie wanneer u de geometrische transformatie exporteert naar bestandstypen die dit niet ondersteunen.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.
### getGeometricScaling() {#getGeometricScaling--}
```
public Vector3 getGeometricScaling()
```


Haalt de geometrische schaal op. Geometrische transformatie beïnvloedt alleen de gekoppelde entiteiten en laat de onderliggende knooppunten onaangetast. Het wordt samengevoegd als lokale transformatie wanneer je de geometrische transformatie exporteert naar bestandstypen die dit niet ondersteunen.

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


Haalt de geometrische translatie op. Geometrische transformatie beïnvloedt alleen de gekoppelde entiteiten en laat de onderliggende knooppunten onaangetast. Het wordt samengevoegd als lokale transformatie wanneer je de geometrische transformatie exporteert naar bestandstypen die dit niet ondersteunen.

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


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getPostRotation() {#getPostRotation--}
```
public Vector3 getPostRotation()
```


Haalt de post‑rotatie op, weergegeven in graden

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


Haalt de pre‑rotatie op, weergegeven in graden

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


Haalt de verzameling van alle eigenschappen op.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Haalt de waarde op van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |

**Returns:**
java.lang.Object - De waarde van de gevonden eigenschap
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


Haalt de rotatie op die wordt weergegeven in een quaternion.

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


Haalt de rotatie‑offset op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation offset
### getRotationPivot() {#getRotationPivot--}
```
public Vector3 getRotationPivot()
```


Haalt de rotatiepivot op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation pivot
### getScaling() {#getScaling--}
```
public Vector3 getScaling()
```


Haalt de schaal op

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


Haalt de schaalverschuiving op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling offset
### getScalingPivot() {#getScalingPivot--}
```
public Vector3 getScalingPivot()
```


Haalt de schaalpivot op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling pivot
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


Haalt de transformatiematrix op.

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


Haalt de translatie op

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


Verwijdert een dynamische eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Verwijder de opgegeven eigenschap geïdentificeerd op naam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### setEulerAngles(Vector3 value) {#setEulerAngles-com.aspose.threed.Vector3-}
```
public void setEulerAngles(Vector3 value)
```


Stelt de rotatie in, weergegeven in Euler-hoeken, gemeten in graden

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde **Example:** |

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
``` |

### setEulerAngles(double rx, double ry, double rz) {#setEulerAngles-double-double-double-}
```
public Transform setEulerAngles(double rx, double ry, double rz)
```


Stelt de Euler-hoeken in graden van de huidige transformatie in. **Voorbeeld:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(90, 0, 0);
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Stelt de geometrische Euler-rotatie in (gemeten in graden). Geometrische transformatie beïnvloedt alleen de gekoppelde entiteiten en laat de onderliggende knooppunten onaangetast. Het wordt samengevoegd als lokale transformatie wanneer je de geometrische transformatie exporteert naar bestandstypen die dit niet ondersteunen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setGeometricRotation(double rx, double ry, double rz) {#setGeometricRotation-double-double-double-}
```
public Transform setGeometricRotation(double rx, double ry, double rz)
```


Stelt de geometrische Euler-rotatie in (gemeten in graden). Geometrische transformatie beïnvloedt alleen de gekoppelde entiteiten en laat de onderliggende knooppunten onaangetast. Het wordt samengevoegd als lokale transformatie wanneer je de geometrische transformatie exporteert naar bestandstypen die dit niet ondersteunen. **Voorbeeld:**

```
Node node = new Node();
     node.getTransform().setGeometricRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Stelt de geometrische schaal in. Geometrische transformatie beïnvloedt alleen de gekoppelde entiteiten en laat de onderliggende knooppunten onaangetast. Het wordt samengevoegd als lokale transformatie wanneer je de geometrische transformatie exporteert naar bestandstypen die dit niet ondersteunen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde **Example:** |

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
``` |

### setGeometricScaling(double sx, double sy, double sz) {#setGeometricScaling-double-double-double-}
```
public Transform setGeometricScaling(double sx, double sy, double sz)
```


Stelt de geometrische schaal in. Geometrische transformatie beïnvloedt alleen de gekoppelde entiteiten en laat de onderliggende knooppunten onaangetast. Het wordt samengevoegd als lokale transformatie wanneer je de geometrische transformatie exporteert naar bestandstypen die dit niet ondersteunen. **Voorbeeld:**

```
Node node = new Node();
     node.getTransform().setGeometricScaling(2, 2, 2);
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Stelt de geometrische translatie in. Geometrische transformatie beïnvloedt alleen de gekoppelde entiteiten en laat de onderliggende knooppunten onaangetast. Het wordt samengevoegd als lokale transformatie wanneer je de geometrische transformatie exporteert naar bestandstypen die dit niet ondersteunen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde **Example:** |

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
``` |

### setGeometricTranslation(double x, double y, double z) {#setGeometricTranslation-double-double-double-}
```
public Transform setGeometricTranslation(double x, double y, double z)
```


Stelt de geometrische translatie in. Geometrische transformatie beïnvloedt alleen de gekoppelde entiteiten en laat de onderliggende knooppunten onaangetast. Het wordt samengevoegd als lokale transformatie wanneer je de geometrische transformatie exporteert naar bestandstypen die dit niet ondersteunen. **Voorbeeld:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(10, 0, 0);
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setPostRotation(Vector3 value) {#setPostRotation-com.aspose.threed.Vector3-}
```
public void setPostRotation(Vector3 value)
```


Stelt de post-rotatie in, weergegeven in graden

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde **Example:** |

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
``` |

### setPostRotation(double rx, double ry, double rz) {#setPostRotation-double-double-double-}
```
public Transform setPostRotation(double rx, double ry, double rz)
```


Stelt de post-rotatie in, weergegeven in graden **Voorbeeld:**

```
Node node = new Node();
     node.getTransform().setPostRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Stelt de pre-rotatie in, weergegeven in graden

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde **Example:** |

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
``` |

### setPreRotation(double rx, double ry, double rz) {#setPreRotation-double-double-double-}
```
public Transform setPreRotation(double rx, double ry, double rz)
```


Stelt de pre-rotatie in, weergegeven in graden **Voorbeeld:**

```
Node node = new Node();
     node.getTransform().setPreRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Stelt de waarde in van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |
| waarde | java.lang.Object | De waarde van de eigenschap |

### setRotation(Quaternion value) {#setRotation-com.aspose.threed.Quaternion-}
```
public void setRotation(Quaternion value)
```


Stelt de rotatie in, weergegeven in quaternion.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Quaternion](../../com.aspose.threed/quaternion) | Nieuwe waarde **Example:** |

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
``` |

### setRotation(double rw, double rx, double ry, double rz) {#setRotation-double-double-double-double-}
```
public Transform setRotation(double rw, double rx, double ry, double rz)
```


Stelt de rotatie (als quaternioncomponenten) van de huidige transformatie in. **Voorbeeld:**

```
Node node = new Node();
     node.getTransform().setRotation(1, 0, 0, 0);
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Stelt de rotatieverschuiving in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setRotationPivot(Vector3 value) {#setRotationPivot-com.aspose.threed.Vector3-}
```
public void setRotationPivot(Vector3 value)
```


Stelt de rotatiepivot in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setScale(double sx, double sy, double sz) {#setScale-double-double-double-}
```
public Transform setScale(double sx, double sy, double sz)
```


Stelt de schaal van de huidige transformatie in. **Voorbeeld:**

```
Node node = new Node();
     node.getTransform().setScale(2, 2, 2);
```

**Parameters:**
| Parameter | Type | Beschrijving |
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


Stelt de schaal in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde **Example:** |

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
``` |

### setScalingOffset(Vector3 value) {#setScalingOffset-com.aspose.threed.Vector3-}
```
public void setScalingOffset(Vector3 value)
```


Stelt de schaalverschuiving in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setScalingPivot(Vector3 value) {#setScalingPivot-com.aspose.threed.Vector3-}
```
public void setScalingPivot(Vector3 value)
```


Stelt de schaalpivot in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setTransformMatrix(Matrix4 value) {#setTransformMatrix-com.aspose.threed.Matrix4-}
```
public void setTransformMatrix(Matrix4 value)
```


Stelt de transformatiematrix in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Matrix4](../../com.aspose.threed/matrix4) | Nieuwe waarde **Opmerkingen:** Toewijzing hiervan zal de [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) en [getRotation](../../com.aspose.threed/transform\#getRotation), de [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) en [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) niet worden beïnvloed. **Voorbeeld:** |

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
``` |

### setTranslation(Vector3 value) {#setTranslation-com.aspose.threed.Vector3-}
```
public void setTranslation(Vector3 value)
```


Stelt de translatie in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde **Example:** |

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
``` |

### setTranslation(double tx, double ty, double tz) {#setTranslation-double-double-double-}
```
public Transform setTranslation(double tx, double ty, double tz)
```


Stelt de translatie van de huidige transformatie in. **Voorbeeld:**

```
Node node = new Node();
     node.getTransform().setTranslation(10, 0, 0);
```

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

