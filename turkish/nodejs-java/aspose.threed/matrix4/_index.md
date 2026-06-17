---
title: "Matrix4"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

4x4 matris uygulaması.


## Properties

| Ad | Açıklama |
| --- | --- |
| m00 | Bu m00. |
| m01 | Bu m01. |
| m02 | Bu m02. |
| m03 | Bu m03. |
| m10 | Bu m10. |
| m11 | Bu m11. |
| m12 | m12. |
| m13 | m13. |
| m20 | m20. |
| m21 | m21. |
| m22 | m22. |
| m23 | m23. |
| m30 | m30. |
| m31 | m31. |
| m32 | m32. |
| m33 | m33. |

## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(r0, r1, r2, r3) | Matrisi 4 satırdan oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Ad | Açıklama |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Matrix4 yapısının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| m00 | Number | M00. |
| m01 | Number | M01. |
| m02 | Number | M02. |
| m03 | Number | M03. |
| m10 | Number | M10. |
| m11 | Number | M11. |
| m12 | Number | M12. |
| m13 | Number | M13. |
| m20 | Number | M20. |
| m21 | Number | M21. |
| m22 | Number | M22. |
| m23 | Number | M23. |
| m30 | Number | M30. |
| m31 | Number | M31. |
| m32 | Number | M32. |
| m33 | Number | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Ad | Açıklama |
| --- | --- |
| constructor_overload3(m) | Bir FMatrix4 örneğinden Matrix4 oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Ad | Açıklama |
| --- | --- |
| constructor_overload4(m) | Matrix4 yapısının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| Ad | Açıklama |
| --- | --- |
| getIdentity() | Kimlik matrisini alır. Kimlik. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Ad | Açıklama |
| --- | --- |
| getDeterminant() | Matrisin determinantını alır. Determinant. |

 **Result:**



---


### concatenate{#concatenate}

| Ad | Açıklama |
| --- | --- |
| concatenate(m2) | İki matrisi birleştirir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
Matrix4


---


### transpose{#transpose}

| Ad | Açıklama |
| --- | --- |
| transpose() | Bu örneği transpoze eder. |

 **Result:**
Matrix4


---


### normalize{#normalize}

| Ad | Açıklama |
| --- | --- |
| normalize() | Bu örneği normalleştirir. |

 **Result:**
Matrix4


---


### inverse{#inverse}

| Ad | Açıklama |
| --- | --- |
| inverse() | Bu örneği tersine çevirir. |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| Ad | Açıklama |
| --- | --- |
| setTRS(translation, rotation, scale) | Matris'i çeviri/dönme/ölçek ile başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| çeviri | Vector3 | Çeviri. |
| dönme | Vector3 | Dönme için Euler açıları, alanlar derecedir. |
| ölçek | Vector3 | Ölçek. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| Ad | Açıklama |
| --- | --- |
| toArray() | Matris'i diziye dönüştürür. |

 **Result:**
Number[]


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Mevcut Matrix4'ü temsil eden bir java.lang.String döndürür. |

 **Result:**
String


---


### translate{#translate}

| Ad | Açıklama |
| --- | --- |
| translate(t) | x ekseni, y ekseni ve z ekseni boyunca çeviren bir matris oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| t | Vector3 | Çeviri ofseti |

 **Result:**
Matrix4


---


### translate{#translate}

| Ad | Açıklama |
| --- | --- |
| translate(tx, ty, tz) | x ekseni, y ekseni ve z ekseni boyunca çeviren bir matris oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| tx | Number | X-koordinat ofseti |
| ty | Number | Y koordinat ofseti |
| tz | Number | Z koordinat ofseti |

 **Result:**
Matrix4


---


### scale{#scale}

| Ad | Açıklama |
| --- | --- |
| scale(s) | x ekseni, y ekseni ve z ekseni boyunca ölçekleyen bir matris oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| s | Vector3 | Ölçekleme fabrikaları x eksenine, y eksenine ve z eksenine uygulanır |

 **Result:**
Matrix4


---


### scale{#scale}

| Ad | Açıklama |
| --- | --- |
| scale(s) | x ekseni, y ekseni ve z ekseni boyunca ölçekleyen bir matris oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| s | Number | Ölçekleme fabrikaları tüm eksenlere uygulanır |

 **Result:**
Matrix4


---


### scale{#scale}

| Ad | Açıklama |
| --- | --- |
| scale(sx, sy, sz) | x ekseni, y ekseni ve z ekseni boyunca ölçekleyen bir matris oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| sx | Number | Ölçekleme fabrikaları x eksenine uygulanır |
| sy | Number | Ölçekleme fabrikaları y eksenine uygulanır |
| sz | Number | Ölçekleme fabrikaları z eksenine uygulanır |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Ad | Açıklama |
| --- | --- |
| rotateFromEuler(eul) | Euler açısına göre bir rotasyon matrisi oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| eul | Vector3 | Radyan cinsinden dönüş |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Ad | Açıklama |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Euler açısına göre bir rotasyon matrisi oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rx | Number | x ekseninde radyan cinsinden dönüş |
| ry | Number | y ekseninde radyan cinsinden dönüş |
| rz | Number | Z eksenindeki dönüş radyan cinsinden |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Ad | Açıklama |
| --- | --- |
| rotate(angle, axis) | Dönüş açısı ve eksenine göre bir dönüş matrisi oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| açı | Number | Radyan cinsinden döndürme açısı |
| eksen | Vector3 | Dönüş ekseni |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Ad | Açıklama |
| --- | --- |
| rotate(q) | Kuatörden bir dönüş matrisi oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| q | Kuatör | Dönüş kuatörü |

 **Result:**
Matrix4


---



