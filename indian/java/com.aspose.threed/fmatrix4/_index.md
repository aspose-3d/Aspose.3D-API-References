---
title: FMatrix4
second_title: Aspose.3D for Java API Reference
description: फ़्लोट प्रकार के सभी घटकों वाला 4x4 मैट्रिक्स
type: docs
weight: 58
url: /hi/java/com.aspose.threed/fmatrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FMatrix4 implements Struct<FMatrix4>, Serializable
```

फ़्लोट प्रकार के सभी घटकों वाला 4x4 मैट्रिक्स
## Constructors

| Constructor | विवरण |
| --- | --- |
| [FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)](#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-) | [FMatrix4](../../com.aspose.threed/fmatrix4) का उदाहरण प्रारंभ करता है। |
| [FMatrix4(Matrix4 mat)](#FMatrix4-com.aspose.threed.Matrix4-) | एक [Matrix4](../../com.aspose.threed/matrix4) इंस्टेंस से [FMatrix4](../../com.aspose.threed/fmatrix4) का इंस्टेंस प्रारंभ करें। |
| [FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)](#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | 4 पंक्तियों से मैट्रिक्स बनाता है। |
| [FMatrix4()](#FMatrix4--) |  |
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
| [concatenate(FMatrix4 m2)](#concatenate-com.aspose.threed.FMatrix4-) | दोनों मैट्रिक्स को जोड़ता है |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | दोनों मैट्रिक्स को जोड़ता है |
| [copyFrom(FMatrix4 src)](#copyFrom-com.aspose.threed.FMatrix4-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIdentity()](#getIdentity--) | आइडेंटिटी मैट्रिक्स |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | वर्तमान इंस्टेंस का इनवर्स मैट्रिक्स गणना करें। |
| [mul(FMatrix4 left, FMatrix4 right)](#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-) | दोनों मैट्रिक्स को जोड़ें |
| [mul(FMatrix4 lhs, float v)](#mul-com.aspose.threed.FMatrix4-float-) | मैट्रिक्स को डबल मान से गुणा करें |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transpose()](#transpose--) | इस इंस्टेंस को ट्रांसपोज़ करें। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33) {#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-}
```
public FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)
```


[FMatrix4](../../com.aspose.threed/fmatrix4) का उदाहरण प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| m00 | फ़्लोट | यह m[0, 0] |
| m01 | फ़्लोट | यह m[0, 1] |
| m02 | फ़्लोट | यह m[0, 2] |
| m03 | फ़्लोट | यह m[0, 3] |
| m10 | फ़्लोट | यह m[1, 0] |
| m11 | फ़्लोट | यह m[1, 1] |
| m12 | फ़्लोट | यह m[1, 2] |
| m13 | फ़्लोट | यह m[1, 3] |
| m20 | फ़्लोट | यह m[2, 0] |
| m21 | फ़्लोट | यह m[2, 1] |
| m22 | फ़्लोट | यह m[2, 2] |
| m23 | फ़्लोट | यह m[2, 3] |
| m30 | फ़्लोट | यह m[3, 0] |
| m31 | फ़्लोट | The m[3, 1] |
| m32 | फ़्लोट | The m[3, 2] |
| m33 | फ़्लोट | The m[3, 3] |

### FMatrix4(Matrix4 mat) {#FMatrix4-com.aspose.threed.Matrix4-}
```
public FMatrix4(Matrix4 mat)
```


एक [Matrix4](../../com.aspose.threed/matrix4) इंस्टेंस से [FMatrix4](../../com.aspose.threed/fmatrix4) का इंस्टेंस प्रारंभ करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | The [Matrix4](../../com.aspose.threed/matrix4) instance. |

### FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3) {#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)
```


4 पंक्तियों से मैट्रिक्स बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| r0 | [FVector4](../../com.aspose.threed/fvector4) | R0. |
| r1 | [FVector4](../../com.aspose.threed/fvector4) | R1. |
| r2 | [FVector4](../../com.aspose.threed/fvector4) | R2. |
| r3 | [FVector4](../../com.aspose.threed/fvector4) | R3. |

### FMatrix4() {#FMatrix4--}
```
public FMatrix4()
```


### m00 {#m00}
```
public float m00
```


m00।

### m01 {#m01}
```
public float m01
```


m01।

### m02 {#m02}
```
public float m02
```


m02।

### m03 {#m03}
```
public float m03
```


m03।

### m10 {#m10}
```
public float m10
```


m10।

### m11 {#m11}
```
public float m11
```


m11।

### m12 {#m12}
```
public float m12
```


m12।

### m13 {#m13}
```
public float m13
```


m13।

### m20 {#m20}
```
public float m20
```


m20।

### m21 {#m21}
```
public float m21
```


m21।

### m22 {#m22}
```
public float m22
```


m22।

### m23 {#m23}
```
public float m23
```


m23।

### m30 {#m30}
```
public float m30
```


m30।

### m31 {#m31}
```
public float m31
```


m31।

### m32 {#m32}
```
public float m32
```


m32।

### m33 {#m33}
```
public float m33
```


m33।

### clone() {#clone--}
```
public FMatrix4 clone()
```


वर्तमान उदाहरण को क्लोन करें

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4)
### concatenate(FMatrix4 m2) {#concatenate-com.aspose.threed.FMatrix4-}
```
public FMatrix4 concatenate(FMatrix4 m2)
```


दोनों मैट्रिक्स को जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| m2 | [FMatrix4](../../com.aspose.threed/fmatrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public FMatrix4 concatenate(Matrix4 m2)
```


दोनों मैट्रिक्स को जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### copyFrom(FMatrix4 src) {#copyFrom-com.aspose.threed.FMatrix4-}
```
public void copyFrom(FMatrix4 src)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| src | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

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
### getIdentity() {#getIdentity--}
```
public static FMatrix4 getIdentity()
```


आइडेंटिटी मैट्रिक्स

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The identity matrix
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### inverse() {#inverse--}
```
public FMatrix4 inverse()
```


वर्तमान इंस्टेंस का इनवर्स मैट्रिक्स गणना करें।

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Inverse matrix4
### mul(FMatrix4 left, FMatrix4 right) {#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-}
```
public static FMatrix4 mul(FMatrix4 left, FMatrix4 right)
```


दोनों मैट्रिक्स को जोड़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| left | [FMatrix4](../../com.aspose.threed/fmatrix4) | The left matrix to concatenate |
| right | [FMatrix4](../../com.aspose.threed/fmatrix4) | The right matrix to concatenate |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The concatenated matrix.
### mul(FMatrix4 lhs, float v) {#mul-com.aspose.threed.FMatrix4-float-}
```
public static FMatrix4 mul(FMatrix4 lhs, float v)
```


मैट्रिक्स को डबल मान से गुणा करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [FMatrix4](../../com.aspose.threed/fmatrix4) | Lhs. |
| v | फ़्लोट | V. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Result matrix
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transpose() {#transpose--}
```
public FMatrix4 transpose()
```


इस इंस्टेंस को ट्रांसपोज़ करें।

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The transposed matrix.
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

