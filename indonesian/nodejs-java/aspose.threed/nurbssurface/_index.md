---
title: "NurbsSurface"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/nurbssurface/
---
## NurbsSurface class

NurbsSurface adalah permukaan yang direpresentasikan oleh NURBS (Non-uniform rational basis spline). Sebuah NurbsSurface didefinisikan oleh dua NurbsDirectionU dan V. Komponen w pada control point digunakan sebagai bobot control point, terlepas apakah tipe arah tersebut adalah CurveDimension.TWO_DIMENSIONAL atau CurveDimension.THREE_DIMENSIONAL.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi instance baru dari kelas NurbsSurface. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(name) | Menginisialisasi instance baru dari kelas NurbsSurface. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |

 **Result:**



---


### getU{#getU}

| Nama | Deskripsi |
| --- | --- |
| getU() | Mendapatkan arah U dari permukaan NURBS |

 **Result:**



---


### getV{#getV}

| Nama | Deskripsi |
| --- | --- |
| getV() | Mendapatkan arah V dari permukaan NURBS |

 **Result:**



---


### getVisible{#getVisible}

| Nama | Deskripsi |
| --- | --- |
| getVisible() | Mendapatkan atau mengatur apakah geometri terlihat |

 **Result:**



---


### setVisible{#setVisible}

| Nama | Deskripsi |
| --- | --- |
| setVisible(value) | Mendapatkan atau mengatur apakah geometri terlihat |

 **Result:**



---


### getDeformers{#getDeformers}

| Nama | Deskripsi |
| --- | --- |
| getDeformers() | Mendapatkan semua deformer yang terkait dengan geometri ini. Deformer. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Nama | Deskripsi |
| --- | --- |
| getControlPoints() | Mendapatkan semua titik kontrol |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nama | Deskripsi |
| --- | --- |
| getCastShadows() | Mendapatkan atau mengatur apakah geometri ini dapat memproyeksikan bayangan |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nama | Deskripsi |
| --- | --- |
| setCastShadows(value) | Mendapatkan atau mengatur apakah geometri ini dapat memproyeksikan bayangan |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Nama | Deskripsi |
| --- | --- |
| getReceiveShadows() | Mendapatkan atau mengatur apakah geometri ini dapat menerima bayangan. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Nama | Deskripsi |
| --- | --- |
| setReceiveShadows(value) | Mendapatkan atau mengatur apakah geometri ini dapat menerima bayangan. |

 **Result:**



---


### getVertexElements{#getVertexElements}

| Nama | Deskripsi |
| --- | --- |
| getVertexElements() | Mendapatkan semua elemen vertex |

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


### toMesh{#toMesh}

| Nama | Deskripsi |
| --- | --- |
| toMesh() | Mengonversi permukaan NURBS menjadi mesh |

 **Result:**
Mesh


---


### getElement{#getElement}

| Nama | Deskripsi |
| --- | --- |
| getElement(type) | Mendapatkan elemen vertex dengan tipe yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| Nama | Deskripsi |
| --- | --- |
| getVertexElementOfUV(textureMapping) | Mendapatkan instance VertexElementUV dengan tipe pemetaan tekstur yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| Nama | Deskripsi |
| --- | --- |
| createElement(type) | Membuat elemen vertex dengan tipe yang ditentukan dan menambahkannya ke geometri. Jika tipe adalah VertexElementType.UV, sebuah VertexElementUV dengan tipe pemetaan tekstur ke TextureMapping.DIFFUSE akan dibuat. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| Nama | Deskripsi |
| --- | --- |
| addElement(element) | Menambahkan elemen vertex yang ada ke geometri saat ini |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| elemen | VertexElement | Elemen vertex yang akan ditambahkan |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Nama | Deskripsi |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Membuat elemen vertex dengan tipe yang ditentukan dan menambahkannya ke geometri. Jika tipe adalah VertexElementType.UV, sebuah VertexElementUV dengan tipe pemetaan tekstur ke TextureMapping.DIFFUSE akan dibuat. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| Nama | Deskripsi |
| --- | --- |
| createElementUV(uvMapping) | Membuat VertexElementUV dengan tipe pemetaan tekstur yang diberikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| Nama | Deskripsi |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | Membuat VertexElementUV dengan tipe pemetaan tekstur yang diberikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| Nama | Deskripsi |
| --- | --- |
| getBoundingBox() | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |

 **Result:**
VertexElementUV


---


### getEntityRendererKey{#getEntityRendererKey}

| Nama | Deskripsi |
| --- | --- |
| getEntityRendererKey() | Mendapatkan kunci renderer entitas yang terdaftar di renderer |

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



