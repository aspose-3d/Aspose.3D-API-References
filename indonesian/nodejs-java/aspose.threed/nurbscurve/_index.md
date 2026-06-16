---
title: "NurbsCurve"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

Kurva NURBS adalah kurva yang direpresentasikan oleh NURBS (Non-uniform rational basis spline), sebuah kurva NURBS didefinisikan oleh Order-nya, sekumpulan Geometry.ControlPoints berbobot, dan KnotVectors. Komponen w pada control point digunakan sebagai bobot control point, terlepas apakah itu CurveDimension.TWO_DIMENSIONAL atau CurveDimension.THREE_DIMENSIONAL.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi instance baru dari kelas NurbsCurve. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(name) | Menginisialisasi instance baru dari kelas NurbsCurve. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Nama | Deskripsi |
| --- | --- |
| getControlPoints() | Mendapatkan semua titik kontrol |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| Nama | Deskripsi |
| --- | --- |
| getMultiplicity() | Mendapatkan multiplicity. Multiplicity. |

 **Result:**



---


### getOrder{#getOrder}

| Nama | Deskripsi |
| --- | --- |
| getOrder() | Mendapatkan atau mengatur urutan dari kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva. Urutan. |

 **Result:**



---


### setOrder{#setOrder}

| Nama | Deskripsi |
| --- | --- |
| setOrder(value) | Mendapatkan atau mengatur urutan dari kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva. Urutan. |

 **Result:**



---


### getDimension{#getDimension}

| Nama | Deskripsi |
| --- | --- |
| getDimension() | Mendapatkan atau mengatur dimensi kurva. Nilai properti ini adalah konstanta integer CurveDimension. Untuk kurva CurveDimension.TWO_DIMENSIONAL, komponen z pada titik kontrol tidak digunakan. |

 **Result:**



---


### setDimension{#setDimension}

| Nama | Deskripsi |
| --- | --- |
| setDimension(value) | Mendapatkan atau mengatur dimensi kurva. Nilai properti ini adalah konstanta integer CurveDimension. Untuk kurva CurveDimension.TWO_DIMENSIONAL, komponen z pada titik kontrol tidak digunakan. |

 **Result:**



---


### getCurveType{#getCurveType}

| Nama | Deskripsi |
| --- | --- |
| getCurveType() | Mendapatkan atau mengatur tipe kurva. Nilai properti adalah konstanta integer NurbsType. Tipe kurva. |

 **Result:**



---


### setCurveType{#setCurveType}

| Nama | Deskripsi |
| --- | --- |
| setCurveType(value) | Mendapatkan atau mengatur tipe kurva. Nilai properti adalah konstanta integer NurbsType. Tipe kurva. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Nama | Deskripsi |
| --- | --- |
| getKnotVectors() | Mendapatkan vektor knot, yaitu urutan nilai parameter yang menentukan di mana dan bagaimana titik kontrol memengaruhi kurva NURBS. |

 **Result:**



---


### getRational{#getRational}

| Nama | Deskripsi |
| --- | --- |
| getRational() | Mendapatkan atau mengatur apakah bersifat rasional, nilai ini menunjukkan apakah NurbsCurve ini merupakan spline rasional atau spline non-rasional. B-spline non-rasional adalah kasus khusus dari B-spline rasional. true jika merupakan spline rasional; selain itu, false berarti spline non-rasional. |

 **Result:**



---


### setRational{#setRational}

| Nama | Deskripsi |
| --- | --- |
| setRational(value) | Mendapatkan atau mengatur apakah bersifat rasional, nilai ini menunjukkan apakah NurbsCurve ini merupakan spline rasional atau spline non-rasional. B-spline non-rasional adalah kasus khusus dari B-spline rasional. true jika merupakan spline rasional; selain itu, false berarti spline non-rasional. |

 **Result:**



---


### getColor{#getColor}

| Nama | Deskripsi |
| --- | --- |
| getColor() | Mendapatkan atau mengatur warna garis, nilai default adalah putih(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Nama | Deskripsi |
| --- | --- |
| setColor(value) | Mendapatkan atau mengatur warna garis, nilai default adalah putih(1, 1, 1) |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nama | Deskripsi |
| --- | --- |
| getParentNodes() | Mendapatkan semua node induk, sebuah entitas dapat dilampirkan ke beberapa node induk untuk instansiasi geometri. Node-node tersebut. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nama | Deskripsi |
| --- | --- |
| getExcluded() | Mendapatkan atau mengatur apakah entitas ini harus dikecualikan selama ekspor. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nama | Deskripsi |
| --- | --- |
| setExcluded(value) | Mendapatkan atau mengatur apakah entitas ini harus dikecualikan selama ekspor. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nama | Deskripsi |
| --- | --- |
| getParentNode() | Mendapatkan atau mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan terlepas dari node induk lainnya. Node induk. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nama | Deskripsi |
| --- | --- |
| setParentNode(value) | Mendapatkan atau mengatur node induk pertama, jika mengatur node induk pertama, entitas ini akan terlepas dari node induk lainnya. Node induk. |

 **Result:**



---


### getScene{#getScene}

| Nama | Deskripsi |
| --- | --- |
| getScene() | Mendapatkan adegan yang dimiliki objek ini |

 **Result:**



---


### getName{#getName}

| Nama | Deskripsi |
| --- | --- |
| getName() | Mendapatkan atau mengatur nama. Nama. |

 **Result:**



---


### setName{#setName}

| Nama | Deskripsi |
| --- | --- |
| setName(value) | Mendapatkan atau mengatur nama. Nama. |

 **Result:**



---


### getProperties{#getProperties}

| Nama | Deskripsi |
| --- | --- |
| getProperties() | Mendapatkan koleksi semua properti. |

 **Result:**



---


### evaluate{#evaluate}

| Nama | Deskripsi |
| --- | --- |
| evaluate(steps) | Mengevaluasi kurva NURBS |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| steps | Angka | Frekuensi evaluasi antara dua knot tetangga, nilai default adalah 20 |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| Nama | Deskripsi |
| --- | --- |
| evaluateAt(u) | Mengevaluasi titik kurva pada posisi yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| u | Angka | Posisi dalam kurva, antara 0 dan 1 |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| Nama | Deskripsi |
| --- | --- |
| getEntityRendererKey() | Mendapatkan kunci renderer entitas yang terdaftar di renderer |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Nama | Deskripsi |
| --- | --- |
| getBoundingBox() | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Nama | Deskripsi |
| --- | --- |
| removeProperty(property) | Menghapus properti dinamis. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| property | Property | Properti mana yang akan dihapus |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nama | Deskripsi |
| --- | --- |
| removeProperty(property) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nama | Deskripsi |
| --- | --- |
| getProperty(property) | Dapatkan nilai properti yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| property | String | Nama properti |

 **Result:**
Object


---


### setProperty{#setProperty}

| Nama | Deskripsi |
| --- | --- |
| setProperty(property, value) | Menetapkan nilai properti yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| property | String | Nama properti |
| value | Object | Nilai properti |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nama | Deskripsi |
| --- | --- |
| findProperty(propertyName) | Menemukan properti. Bisa berupa properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti native (Diidentifikasi berdasarkan namanya) |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| propertyName | String | Nama properti. |

 **Result:**
Property


---



