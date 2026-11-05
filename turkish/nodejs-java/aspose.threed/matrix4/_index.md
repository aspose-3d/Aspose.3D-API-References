---
title: "Matrix4"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

4x4 matris uygulaması.


## Özellikler

| Ad | Açıklama |
| --- | --- |
| m00 | m00. |
| m01 | m01. |
| m02 | m02. |
| m03 | Bu m03. |
| m10 | Bu m10. |
| m11 | Bu m11. |
| m12 | Bu m12. |
| m13 | Bu m13. |
| m20 | Bu m20. |
| m21 | Bu m21. |
| m22 | Bu m22. |
| m23 | Bu m23. |
| m30 | Bu m30. |
| m31 | Bu m31. |
| m32 | Bu m32. |
| m33 | Bu m33. |

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
| m00 | Sayı | M00. |
| m01 | Sayı | M01. |
| m02 | Sayı | M02. |
| m03 | Sayı | M03. |
| m10 | Sayı | M10. |
| m11 | Sayı | M11. |
| m12 | Sayı | M12. |
| m13 | Sayı | M13. |
| m20 | Sayı | M20. |
| m21 | Sayı | M21. |
| m22 | Sayı | M22. |
| m23 | Sayı | M23. |
| m30 | Sayı | M30. |
| m31 | Sayı | M31. |
| m32 | Sayı | M32. |
| m33 | Sayı | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Ad | Açıklama |
| --- | --- |
| constructor_overload3(m) | Bir FMatrix4 örneğinden Matrix4 oluştur |

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
| getIdentity() | Birim matrisi alır. Birim. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Ad | Açıklama |
| --- | --- |
| getDeterminant() | Matriksin determinantını alır. Determinant. |

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
| normalize() | Bu örneği normalize eder. |

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
| setTRS(translation, rotation, scale) | Matrisi çeviri/dönüş/ölçek ile başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| çeviri | Vector3 | Çeviri. |
| dönüş | Vector3 | Dönüş için Euler açıları, alanlar derecedir. |
| ölçek | Vector3 | Ölçek. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| Ad | Açıklama |
| --- | --- |
| toArray() | Matrisi diziye dönüştürür. |

 **Result:**
Number[]


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Geçerli Matrix4'ü temsil eden bir java.lang.String döndürür. |

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
| t | Vector3 | Ofseti Çevir |

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
| tx | Sayı | X-koordinat ofseti |
| ty | Sayı | Y-koordinat ofseti |
| tz | Sayı | Z-koordinat ofseti |

 **Result:**
Matrix4


---


### scale{#scale}

| Ad | Açıklama |
| --- | --- |
| scale(s) | x ekseni, y ekseni ve z ekseni boyunca ölçeklendiren bir matris oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| s | Vector3 | Ölçekleme fabrikaları x eksenine, y eksenine ve z eksenine uygulanır. |

 **Result:**
Matrix4


---


### scale{#scale}

| Ad | Açıklama |
| --- | --- |
| scale(s) | x ekseni, y ekseni ve z ekseni boyunca ölçeklendiren bir matris oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| s | Sayı | Ölçekleme fabrikaları tüm eksenlere uygulanır. |

 **Result:**
Matrix4


---


### scale{#scale}

| Ad | Açıklama |
| --- | --- |
| scale(sx, sy, sz) | x ekseni, y ekseni ve z ekseni boyunca ölçeklendiren bir matris oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| sx | Sayı | Ölçekleme fabrikaları x eksenine uygulanır. |
| sy | Sayı | Ölçekleme fabrikaları y eksenine uygulanır. |
| sz | Sayı | Ölçekleme fabrikaları z eksenine uygulanır. |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Ad | Açıklama |
| --- | --- |
| rotateFromEuler(eul) | Euler açısına göre bir dönüşüm matrisi oluşturur. |

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
| rotateFromEuler(rx, ry, rz) | Euler açısına göre bir dönüşüm matrisi oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rx | Sayı | X ekseninde radian cinsinden dönüş |
| ry | Sayı | Y ekseninde radian cinsinden dönüş |
| rz | Sayı | Z ekseninde radian cinsinden dönüş |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Ad | Açıklama |
| --- | --- |
| rotate(angle, axis) | Dönüş açısı ve eksenine göre bir dönüşüm matrisi oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| angle | Sayı | Dönüş açısı radian cinsinden |
| axis | Vector3 | Dönüş ekseni |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Ad | Açıklama |
| --- | --- |
| rotate(q) | Bir quaternion'dan dönüşüm matrisi oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| q | Quaternion | Dönüş quaternion'ı |

 **Result:**
Matrix4


---



