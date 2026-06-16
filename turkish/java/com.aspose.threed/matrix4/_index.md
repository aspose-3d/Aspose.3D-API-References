---
title: "Matrix4"
second_title: "Aspose.3D for Java API Referansı"
description: "4x4 matris uygulaması."
type: docs
weight: 100
url: /tr/java/com.aspose.threed/matrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Matrix4 implements Struct<Matrix4>, Serializable
```

4x4 matris uygulaması. **Örnek:**

```
Matrix4 mat = Matrix4.rotateFromEuler(90, 0, 0);
      Matrix4 mat2 = Matrix4.translate(0, 10, -50);
      Matrix4 transform = Matrix4.mul(mat2, mat);
      Vector4 pos = new Vector4(10, 9, 0, 1);
      Vector4 transformed = Matrix4.mul(transform, pos);
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)](#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Matrisi 4 satırdan oluşturur. |
| [Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)](#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-) | Yeni bir [Matrix4](../../com.aspose.threed/matrix4) yapısının bir örneğini başlatır. |
| [Matrix4(FMatrix4 m)](#Matrix4-com.aspose.threed.FMatrix4-) | [FMatrix4](../../com.aspose.threed/fmatrix4) örneğinden [Matrix4](../../com.aspose.threed/matrix4) oluştur. |
| [Matrix4(double[] m)](#Matrix4-double---) | Yeni bir [Matrix4](../../com.aspose.threed/matrix4) yapısının bir örneğini başlatır. |
| [Matrix4()](#Matrix4--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [m00](#m00) | m00. |
| [m01](#m01) | m01. |
| [m02](#m02) | m02. |
| [m03](#m03) | m03. |
| [m10](#m10) | m10. |
| [m11](#m11) | m11. |
| [m12](#m12) | m12. |
| [m13](#m13) | m13. |
| [m20](#m20) | m20. |
| [m21](#m21) | m21. |
| [m22](#m22) | m22. |
| [m23](#m23) | m23. |
| [m30](#m30) | m30. |
| [m31](#m31) | m31. |
| [m32](#m32) | m32. |
| [m33](#m33) | m33. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | İki matrisi birleştirir |
| [copyFrom(Matrix4 src)](#copyFrom-com.aspose.threed.Matrix4-) |  |
| [decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)](#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Dönüşüm matrisini ayrıştır. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeterminant()](#getDeterminant--) | Matrisin determinantını al. |
| [getIdentity()](#getIdentity--) | Birim matrisi al. |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | Bu örneğin tersini al. |
| [mul(Matrix4 lhs, Matrix4 rhs)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Matrix4-) | İki matrisi çarp. |
| [mul(Matrix4 lhs, Vector3 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-) | Matris ve vector3'ü çarp. |
| [mul(Matrix4 lhs, Vector4 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-) | Matris ve vector4'ü çarp. |
| [mul(Matrix4 lhs, double v)](#mul-com.aspose.threed.Matrix4-double-) | Matrisi ve çift değeri çarpar |
| [normalize()](#normalize--) | Bu örneği normallaştırır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | Bir quaternion'dan dönüşüm matrisi oluştur. |
| [rotate(double angle, Vector3 axis)](#rotate-double-com.aspose.threed.Vector3-) | Dönüş açı ve eksenine göre dönüşüm matrisi oluştur. |
| [rotateFromEuler(Vector3 eul)](#rotateFromEuler-com.aspose.threed.Vector3-) | Euler açısından dönüşüm matrisi oluştur. |
| [rotateFromEuler(double rx, double ry, double rz)](#rotateFromEuler-double-double-double-) | Euler açısından dönüşüm matrisi oluştur. |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | x, y ve z eksenleri boyunca ölçekleyen bir matris oluşturur. |
| [scale(double s)](#scale-double-) | x, y ve z eksenleri boyunca ölçekleyen bir matris oluşturur. |
| [scale(double sx, double sy, double sz)](#scale-double-double-double-) | x, y ve z eksenleri boyunca ölçekleyen bir matris oluşturur. |
| [setTRS(Vector3 translation, Vector3 rotation, Vector3 scale)](#setTRS-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Matris'i çeviri/dönüş/ölçek ile başlatır. |
| [toArray()](#toArray--) | Matrisi diziye dönüştürür. |
| [toString()](#toString--) | Mevcut [Matrix4](../../com.aspose.threed/matrix4) nesnesini temsil eden bir java.lang.String döndürür. |
| [translate(Vector3 t)](#translate-com.aspose.threed.Vector3-) | x, y ve z eksenleri boyunca çeviren bir matris oluşturur. |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | x, y ve z eksenleri boyunca çeviren bir matris oluşturur. |
| [transpose()](#transpose--) | Bu örneği transpoze eder. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3) {#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```


Matrisi 4 satırdan oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| r0 | [Vector4](../../com.aspose.threed/vector4) | R0. |
| r1 | [Vector4](../../com.aspose.threed/vector4) | R1. |
| r2 | [Vector4](../../com.aspose.threed/vector4) | R2. |
| r3 | [Vector4](../../com.aspose.threed/vector4) | R3. |

### Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33) {#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)
```


Yeni bir [Matrix4](../../com.aspose.threed/matrix4) yapısının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
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


[FMatrix4](../../com.aspose.threed/fmatrix4) örneğinden [Matrix4](../../com.aspose.threed/matrix4) oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| m | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### Matrix4(double[] m) {#Matrix4-double---}
```
public Matrix4(double[] m)
```


Yeni bir [Matrix4](../../com.aspose.threed/matrix4) yapısının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
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


m00.

### m01 {#m01}
```
public double m01
```


m01.

### m02 {#m02}
```
public double m02
```


m02.

### m03 {#m03}
```
public double m03
```


m03.

### m10 {#m10}
```
public double m10
```


m10.

### m11 {#m11}
```
public double m11
```


m11.

### m12 {#m12}
```
public double m12
```


m12.

### m13 {#m13}
```
public double m13
```


m13.

### m20 {#m20}
```
public double m20
```


m20.

### m21 {#m21}
```
public double m21
```


m21.

### m22 {#m22}
```
public double m22
```


m22.

### m23 {#m23}
```
public double m23
```


m23.

### m30 {#m30}
```
public double m30
```


m30.

### m31 {#m31}
```
public double m31
```


m31.

### m32 {#m32}
```
public double m32
```


m32.

### m33 {#m33}
```
public double m33
```


m33.

### clone() {#clone--}
```
public Matrix4 clone()
```


Mevcut örneği kopyala

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public Matrix4 concatenate(Matrix4 m2)
```


İki matrisi birleştirir

**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | [Matrix4](../../com.aspose.threed/matrix4) |  |

### decompose(Vector3 translation, Vector3 scaling, Quaternion rotation) {#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public boolean decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)
```


Dönüşüm matrisini ayrıştır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | Çeviri. |
| scaling | [Vector3](../../com.aspose.threed/vector3) | Ölçekleme. |
| rotation | [Quaternion](../../com.aspose.threed/quaternion) | Dönme. |

**Returns:**
boolean - Başarılıysa True.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Matrisin determinantını al.

**Returns:**
double - matrisin determinantı.
### getIdentity() {#getIdentity--}
```
public static Matrix4 getIdentity()
```


Birim matrisi al.

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


Bu örneğin tersini al.

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


İki matrisi çarp.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| rhs | [Matrix4](../../com.aspose.threed/matrix4) | Rhs. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### mul(Matrix4 lhs, Vector3 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Matrix4 lhs, Vector3 v)
```


Matris ve vector3'ü çarp.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector3](../../com.aspose.threed/vector3) | V. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result matrix
### mul(Matrix4 lhs, Vector4 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Matrix4 lhs, Vector4 v)
```


Matris ve vector4'ü çarp.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector4](../../com.aspose.threed/vector4) | V. |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result matrix
### mul(Matrix4 lhs, double v) {#mul-com.aspose.threed.Matrix4-double-}
```
public static Matrix4 mul(Matrix4 lhs, double v)
```


Matrisi ve çift değeri çarpar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | double | V. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### normalize() {#normalize--}
```
public Matrix4 normalize()
```


Bu örneği normallaştırır.

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


Bir quaternion'dan dönüşüm matrisi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | q | [Quaternion](../../com.aspose.threed/quaternion) | Rotasyon kuaterniyonu **Example:** Aşağıdaki kod, döndürme işlemi için bir matris oluşturmanın nasıl yapılacağını gösterir. |

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


Dönüş açı ve eksenine göre dönüşüm matrisi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | double | Radyan cinsinden döndürme açısı |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | Rotasyon ekseni **Example:** Aşağıdaki kod, döndürme işlemi için bir matris oluşturmanın nasıl yapılacağını gösterir. |

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


Euler açısından dönüşüm matrisi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | eul | [Vector3](../../com.aspose.threed/vector3) | Radyan cinsinden rotasyon **Example:** Aşağıdaki kod, döndürme işlemi için bir matris oluşturmanın nasıl yapılacağını gösterir. |

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


Euler açısından dönüşüm matrisi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rx | double | x ekseninde radian cinsinden dönüş |
| ry | double | y ekseninde radian cinsinden dönüş |
|  | rz | double | z ekseninde radian cinsinden dönüş **Örnek:** Aşağıdaki kod, döndürme işlemi için bir matrisin nasıl oluşturulacağını gösterir. |

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


x, y ve z eksenleri boyunca ölçekleyen bir matris oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | s | [Vector3](../../com.aspose.threed/vector3) | Ölçekleme fabrikaları x eksenine, y eksenine ve z eksenine uygulanır **Örnek:** Aşağıdaki kod, ölçekleme işlemi için bir matrisin nasıl oluşturulacağını gösterir. |

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


x, y ve z eksenleri boyunca ölçekleyen bir matris oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | s | double | Ölçekleme fabrikaları tüm eksenlere uygulanır **Örnek:** Aşağıdaki kod, ölçekleme işlemi için bir matrisin nasıl oluşturulacağını gösterir. |

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


x, y ve z eksenleri boyunca ölçekleyen bir matris oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | double | Ölçekleme fabrikaları x eksenine uygulanır |
| sy | double | Ölçekleme fabrikaları y eksenine uygulanır |
|  | sz | double | Ölçekleme fabrikaları z eksenine uygulanır **Örnek:** Aşağıdaki kod, ölçekleme işlemi için bir matrisin nasıl oluşturulacağını gösterir. |

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


Matris'i çeviri/dönüş/ölçek ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | Çevirme. |
| rotation | [Vector3](../../com.aspose.threed/vector3) | Dönüş için Euler açıları, alanlar derecedir. |
| scale | [Vector3](../../com.aspose.threed/vector3) | Ölçek. |

### toArray() {#toArray--}
```
public double[] toArray()
```


Matrisi diziye dönüştürür.

**Returns:**
double[] - Dizi.
### toString() {#toString--}
```
public String toString()
```


Mevcut [Matrix4](../../com.aspose.threed/matrix4) nesnesini temsil eden bir java.lang.String döndürür.

**Returns:**
java.lang.String - Geçerli [Matrix4](../../com.aspose.threed/matrix4) öğesini temsil eden bir java.lang.String.
### translate(Vector3 t) {#translate-com.aspose.threed.Vector3-}
```
public static Matrix4 translate(Vector3 t)
```


x, y ve z eksenleri boyunca çeviren bir matris oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | t | [Vector3](../../com.aspose.threed/vector3) | Öteleme ofseti **Örnek:** Aşağıdaki kod, çevirme işlemi için bir matrisin nasıl oluşturulacağını gösterir. |

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


x, y ve z eksenleri boyunca çeviren bir matris oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tx | double | X-koordinat ofseti |
| ty | double | Y-koordinat ofseti |
|  | tz | double | Z-koordinat ofseti **Örnek:** Aşağıdaki kod, çeviri işlemi için bir matrisin nasıl oluşturulacağını gösterir. |

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


Bu örneği transpoze eder.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

