---
title: Matrix4
second_title: Aspose.3D for Java API Reference
description: 4x4 मैट्रिक्स कार्यान्वयन।
type: docs
weight: 100
url: /hi/java/com.aspose.threed/matrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Matrix4 implements Struct<Matrix4>, Serializable
```

4x4 मैट्रिक्स कार्यान्वयन। **उदाहरण:**

```
Matrix4 mat = Matrix4.rotateFromEuler(90, 0, 0);
      Matrix4 mat2 = Matrix4.translate(0, 10, -50);
      Matrix4 transform = Matrix4.mul(mat2, mat);
      Vector4 pos = new Vector4(10, 9, 0, 1);
      Vector4 transformed = Matrix4.mul(transform, pos);
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)](#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | 4 पंक्तियों से मैट्रिक्स बनाता है। |
| [Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)](#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-) | नए [Matrix4](../../com.aspose.threed/matrix4) स्ट्रक्ट का एक नया उदाहरण प्रारंभ करता है। |
| [Matrix4(FMatrix4 m)](#Matrix4-com.aspose.threed.FMatrix4-) | [Matrix4](../../com.aspose.threed/matrix4) को एक [FMatrix4](../../com.aspose.threed/fmatrix4) उदाहरण से बनाएं |
| [Matrix4(double[] m)](#Matrix4-double---) | नए [Matrix4](../../com.aspose.threed/matrix4) स्ट्रक्ट का एक नया उदाहरण प्रारंभ करता है। |
| [Matrix4()](#Matrix4--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [m00](#m00) | m00। |
| [m01](#m01) | m01। |
| [m02](#m02) | m02। |
| [m03](#m03) | m03। |
| [m10](#m10) | m10। |
| [m11](#m11) | m11। |
| [m12](#m12) | m12। |
| [m13](#m13) | m13। |
| [m20](#m20) | m20। |
| [m21](#m21) | m21। |
| [m22](#m22) | m22। |
| [m23](#m23) | m23। |
| [m30](#m30) | m30। |
| [m31](#m31) | m31। |
| [m32](#m32) | m32। |
| [m33](#m33) | m33। |
## Methods

| Method | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | दोनों मैट्रिक्स को जोड़ता है |
| [copyFrom(Matrix4 src)](#copyFrom-com.aspose.threed.Matrix4-) |  |
| [decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)](#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | परिवर्तन मैट्रिक्स को विभाजित करें। |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeterminant()](#getDeterminant--) | मैट्रिक्स का डिटरमिनेंट प्राप्त करता है। |
| [getIdentity()](#getIdentity--) | पहचान मैट्रिक्स प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | इस उदाहरण का प्रतिलोम निकालता है। |
| [mul(Matrix4 lhs, Matrix4 rhs)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Matrix4-) | दोनों मैट्रिक्स को गुणा करें |
| [mul(Matrix4 lhs, Vector3 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-) | मैट्रिक्स और vector3 को गुणा करें |
| [mul(Matrix4 lhs, Vector4 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-) | मैट्रिक्स और vector4 को गुणा करें |
| [mul(Matrix4 lhs, double v)](#mul-com.aspose.threed.Matrix4-double-) | मैट्रिक्स को डबल मान से गुणा करें |
| [normalize()](#normalize--) | इस उदाहरण को सामान्यीकृत करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | क्वाटरनियन से एक रोटेशन मैट्रिक्स बनाएं |
| [rotate(double angle, Vector3 axis)](#rotate-double-com.aspose.threed.Vector3-) | रोटेशन कोण और अक्ष द्वारा रोटेशन मैट्रिक्स बनाएं |
| [rotateFromEuler(Vector3 eul)](#rotateFromEuler-com.aspose.threed.Vector3-) | ऑयलर कोण से रोटेशन मैट्रिक्स बनाएं |
| [rotateFromEuler(double rx, double ry, double rz)](#rotateFromEuler-double-double-double-) | ऑयलर कोण से रोटेशन मैट्रिक्स बनाएं |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है। |
| [scale(double s)](#scale-double-) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है। |
| [scale(double sx, double sy, double sz)](#scale-double-double-double-) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है। |
| [setTRS(Vector3 translation, Vector3 rotation, Vector3 scale)](#setTRS-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | मैट्रिक्स को ट्रांसलेशन/रोटेशन/स्केल के साथ प्रारंभ करता है |
| [toArray()](#toArray--) | मैट्रिक्स को एरे में परिवर्तित करता है। |
| [toString()](#toString--) | वर्तमान [Matrix4](../../com.aspose.threed/matrix4) को दर्शाने वाली java.lang.String लौटाता है। |
| [translate(Vector3 t)](#translate-com.aspose.threed.Vector3-) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ ट्रांसलेट करता है |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ ट्रांसलेट करता है |
| [transpose()](#transpose--) | इस इंस्टेंस को ट्रांसपोज़ करें। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3) {#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```


4 पंक्तियों से मैट्रिक्स बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| r0 | [Vector4](../../com.aspose.threed/vector4) | R0. |
| r1 | [Vector4](../../com.aspose.threed/vector4) | R1. |
| r2 | [Vector4](../../com.aspose.threed/vector4) | R2. |
| r3 | [Vector4](../../com.aspose.threed/vector4) | R3. |

### Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33) {#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)
```


नए [Matrix4](../../com.aspose.threed/matrix4) स्ट्रक्ट का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| m00 | double | M00. |
| m01 | double | M01. |
| m02 | double | M02. |
| m03 | double | M03. |
| m10 | double | M10. |
| m11 | double | M11. |
| m12 | double | M12. |
| m13 | double | M13. |
| m20 | double | M20. |
| m21 | double | M21. |
| m22 | double | M22. |
| m23 | double | M23. |
| m30 | double | M30. |
| m31 | double | M31. |
| m32 | double | M32. |
|  | m33 | double | M33. **Example:** |

```
var mat = new Matrix4(
         1, 0, 0, 0,
         0, 1, 0, 0,
         0, 0, 1, 0,
         10, 20, 0, 1);
     var pos = new Vector3(10, 0, -1);
     var transformed = Matrix4.mul(mat, pos);
``` |

### Matrix4(FMatrix4 m) {#Matrix4-com.aspose.threed.FMatrix4-}
```
public Matrix4(FMatrix4 m)
```


[Matrix4](../../com.aspose.threed/matrix4) को एक [FMatrix4](../../com.aspose.threed/fmatrix4) उदाहरण से बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| m | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### Matrix4(double[] m) {#Matrix4-double---}
```
public Matrix4(double[] m)
```


नए [Matrix4](../../com.aspose.threed/matrix4) स्ट्रक्ट का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| m | double[] | M. |

### Matrix4() {#Matrix4--}
```
public Matrix4()
```


### m00 {#m00}
```
public double m00
```


m00।

### m01 {#m01}
```
public double m01
```


m01।

### m02 {#m02}
```
public double m02
```


m02।

### m03 {#m03}
```
public double m03
```


m03।

### m10 {#m10}
```
public double m10
```


m10।

### m11 {#m11}
```
public double m11
```


m11।

### m12 {#m12}
```
public double m12
```


m12।

### m13 {#m13}
```
public double m13
```


m13।

### m20 {#m20}
```
public double m20
```


m20।

### m21 {#m21}
```
public double m21
```


m21।

### m22 {#m22}
```
public double m22
```


m22।

### m23 {#m23}
```
public double m23
```


m23।

### m30 {#m30}
```
public double m30
```


m30।

### m31 {#m31}
```
public double m31
```


m31।

### m32 {#m32}
```
public double m32
```


m32।

### m33 {#m33}
```
public double m33
```


m33।

### clone() {#clone--}
```
public Matrix4 clone()
```


वर्तमान उदाहरण को क्लोन करें

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public Matrix4 concatenate(Matrix4 m2)
```


दोनों मैट्रिक्स को जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - New matrix4 **Example:**

```
Matrix4 t = Matrix4.translate(0, 10, 9);
     Matrix4 s = Matrix4.scale(10, 10, 10);
     Matrix4 transform = t.concatenate(s);
     Vector3 pos = new Vector3(10, 0, -1);
     Vector3 transformed = Matrix4.mul(transform, pos);
```
### copyFrom(Matrix4 src) {#copyFrom-com.aspose.threed.Matrix4-}
```
public void copyFrom(Matrix4 src)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| src | [Matrix4](../../com.aspose.threed/matrix4) |  |

### decompose(Vector3 translation, Vector3 scaling, Quaternion rotation) {#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public boolean decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)
```


परिवर्तन मैट्रिक्स को विभाजित करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | The translation. |
| scaling | [Vector3](../../com.aspose.threed/vector3) | The scaling. |
| rotation | [Quaternion](../../com.aspose.threed/quaternion) | The rotation. |

**Returns:**
boolean - True if successed.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeterminant() {#getDeterminant--}
```
public double getDeterminant()
```


मैट्रिक्स का डिटरमिनेंट प्राप्त करता है।

**Returns:**
double - the determinant of the matrix.
### getIdentity() {#getIdentity--}
```
public static Matrix4 getIdentity()
```


पहचान मैट्रिक्स प्राप्त करता है।

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the identity matrix.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### inverse() {#inverse--}
```
public Matrix4 inverse()
```


इस उदाहरण का प्रतिलोम निकालता है।

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Inverse matrix4 **Example:** The following code shows how to inverse a matrix

```
Matrix4 t = Matrix4.translate(0, 10, 9);
     Matrix4 mat = t.inverse();
     System.out.printf("Inversed Matrix: %s", mat);
```
### mul(Matrix4 lhs, Matrix4 rhs) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Matrix4-}
```
public static Matrix4 mul(Matrix4 lhs, Matrix4 rhs)
```


दोनों मैट्रिक्स को गुणा करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| rhs | [Matrix4](../../com.aspose.threed/matrix4) | Rhs. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### mul(Matrix4 lhs, Vector3 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Matrix4 lhs, Vector3 v)
```


मैट्रिक्स और vector3 को गुणा करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector3](../../com.aspose.threed/vector3) | V. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result matrix
### mul(Matrix4 lhs, Vector4 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Matrix4 lhs, Vector4 v)
```


मैट्रिक्स और vector4 को गुणा करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector4](../../com.aspose.threed/vector4) | V. |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result matrix
### mul(Matrix4 lhs, double v) {#mul-com.aspose.threed.Matrix4-double-}
```
public static Matrix4 mul(Matrix4 lhs, double v)
```


मैट्रिक्स को डबल मान से गुणा करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | double | V. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### normalize() {#normalize--}
```
public Matrix4 normalize()
```


इस उदाहरण को सामान्यीकृत करता है।

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Normalize matrix4
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public static Matrix4 rotate(Quaternion q)
```


क्वाटरनियन से एक रोटेशन मैट्रिक्स बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | q | [Quaternion](../../com.aspose.threed/quaternion) | Rotation quaternion **Example:** The following code shows how to create a matrix for rotate operation. |

```
var t = Matrix4.rotate(Quaternion.fromAngleAxis(Math.PI, Vector3.getUnitY()));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### rotate(double angle, Vector3 axis) {#rotate-double-com.aspose.threed.Vector3-}
```
public static Matrix4 rotate(double angle, Vector3 axis)
```


रोटेशन कोण और अक्ष द्वारा रोटेशन मैट्रिक्स बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| angle | double | Rotate angle in radian |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | Rotation axis **Example:** The following code shows how to create a matrix for rotate operation. |

```
var t = Matrix4.rotate(Math.PI, new Vector3(0, 1, 0));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### rotateFromEuler(Vector3 eul) {#rotateFromEuler-com.aspose.threed.Vector3-}
```
public static Matrix4 rotateFromEuler(Vector3 eul)
```


ऑयलर कोण से रोटेशन मैट्रिक्स बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | eul | [Vector3](../../com.aspose.threed/vector3) | Rotation in radian **Example:** The following code shows how to create a matrix for rotate operation. |

```
var t = Matrix4.rotateFromEuler(new Vector3(0, Math.PI, 0));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### rotateFromEuler(double rx, double ry, double rz) {#rotateFromEuler-double-double-double-}
```
public static Matrix4 rotateFromEuler(double rx, double ry, double rz)
```


ऑयलर कोण से रोटेशन मैट्रिक्स बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rx | double | x-अक्ष पर घूर्णन रेडियन में |
| ry | double | y-अक्ष पर घूर्णन रेडियन में |
|  | rz | double | z-अक्ष पर घूर्णन रेडियन में **उदाहरण:** निम्नलिखित कोड दिखाता है कि घुमाव ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं। |

```
var t = Matrix4.rotateFromEuler(0, Math.PI, 0);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### scale(Vector3 s) {#scale-com.aspose.threed.Vector3-}
```
public static Matrix4 scale(Vector3 s)
```


एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | s | [Vector3](../../com.aspose.threed/vector3) | स्केलिंग फैक्टरीज़ x-अक्ष, y-अक्ष और z-अक्ष पर लागू होती हैं **उदाहरण:** निम्नलिखित कोड दिखाता है कि स्केल ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं। |

```
var t = Matrix4.scale(new Vector3(10, 10, 10));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### scale(double s) {#scale-double-}
```
public static Matrix4 scale(double s)
```


एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | s | double | स्केलिंग फैक्टरीज़ सभी अक्षों पर लागू होती हैं **उदाहरण:** निम्नलिखित कोड दिखाता है कि स्केल ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं। |

```
var t = Matrix4.scale(10);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### scale(double sx, double sy, double sz) {#scale-double-double-double-}
```
public static Matrix4 scale(double sx, double sy, double sz)
```


एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| sx | double | स्केलिंग फैक्टरीज़ x-अक्ष पर लागू होती हैं |
| sy | double | स्केलिंग फैक्टरीज़ y-अक्ष पर लागू होती हैं |
|  | sz | double | स्केलिंग फैक्टरीज़ z-अक्ष पर लागू होती हैं **उदाहरण:** निम्नलिखित कोड दिखाता है कि स्केल ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं। |

```
var t = Matrix4.scale(10, 20, 10);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### setTRS(Vector3 translation, Vector3 rotation, Vector3 scale) {#setTRS-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public void setTRS(Vector3 translation, Vector3 rotation, Vector3 scale)
```


मैट्रिक्स को ट्रांसलेशन/रोटेशन/स्केल के साथ प्रारंभ करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | अनुवाद। |
| rotation | [Vector3](../../com.aspose.threed/vector3) | घूर्णन के लिए यूलर कोण, फ़ील्ड डिग्री में हैं। |
| scale | [Vector3](../../com.aspose.threed/vector3) | स्केल। |

### toArray() {#toArray--}
```
public double[] toArray()
```


मैट्रिक्स को एरे में परिवर्तित करता है।

**Returns:**
double[] - एरे।
### toString() {#toString--}
```
public String toString()
```


वर्तमान [Matrix4](../../com.aspose.threed/matrix4) को दर्शाने वाली java.lang.String लौटाता है।

**Returns:**
java.lang.String - एक java.lang.String जो वर्तमान [Matrix4](../../com.aspose.threed/matrix4) को दर्शाता है।
### translate(Vector3 t) {#translate-com.aspose.threed.Vector3-}
```
public static Matrix4 translate(Vector3 t)
```


एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ ट्रांसलेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | t | [Vector3](../../com.aspose.threed/vector3) | अनुवाद ऑफ़सेट **उदाहरण:** निम्नलिखित कोड दिखाता है कि अनुवाद ऑपरेशन के लिए मैट्रिक्स कैसे बनाएं। |

```
Matrix4 t = Matrix4.translate(new Vector3(10, 0, 0));
     Vector3 pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public static Matrix4 translate(double tx, double ty, double tz)
```


एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ ट्रांसलेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| tx | double | X-निर्देशांक ऑफ़सेट |
| ty | double | Y-निर्देशांक ऑफ़सेट |
|  | tz | double | Z-coordinate offset **Example:** निम्नलिखित कोड दिखाता है कि कैसे अनुवाद ऑपरेशन के लिए मैट्रिक्स बनाया जाए। |

```
var t = Matrix4.translate(10, 0, 0);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### transpose() {#transpose--}
```
public Matrix4 transpose()
```


इस इंस्टेंस को ट्रांसपोज़ करें।

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The transposed matrix. **Example:** The following code shows how to transpose a matrix

```
Matrix4 t = Matrix4.translate(0, 10, 9);
     Matrix4 mat = t.transpose();
     System.out.printf("Transposed Matrix: %s", mat);
```
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

