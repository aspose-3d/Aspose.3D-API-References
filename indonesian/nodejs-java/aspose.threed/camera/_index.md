---
title: "Kamera"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/camera/
---
## Camera class

Kamera menggambarkan titik mata pemirsa yang melihat adegan.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi instance baru dari kelas Camera. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(projectionType) | Menginisialisasi instance baru dari kelas Camera. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload2(name) | Menginisialisasi instance baru dari kelas Camera. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload3(name, projectionType) | Menginisialisasi instance baru dari kelas Camera. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### getApertureMode{#getApertureMode}

| Nama | Deskripsi |
| --- | --- |
| getApertureMode() | Mendapatkan atau mengatur mode aperture kamera. Nilai properti ini adalah konstanta integer ApertureMode. |

 **Result:**



---


### setApertureMode{#setApertureMode}

| Nama | Deskripsi |
| --- | --- |
| setApertureMode(value) | Mendapatkan atau mengatur mode aperture kamera. Nilai properti ini adalah konstanta integer ApertureMode. |

 **Result:**



---


### getFieldOfView{#getFieldOfView}

| Nama | Deskripsi |
| --- | --- |
| getFieldOfView() | Mendapatkan atau mengatur bidang pandang kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah ApertureMode.HORIZONTAL atau ApertureMode.VERTICAL |

 **Result:**



---


### setFieldOfView{#setFieldOfView}

| Nama | Deskripsi |
| --- | --- |
| setFieldOfView(value) | Mendapatkan atau mengatur bidang pandang kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah ApertureMode.HORIZONTAL atau ApertureMode.VERTICAL |

 **Result:**



---


### getFieldOfViewX{#getFieldOfViewX}

| Nama | Deskripsi |
| --- | --- |
| getFieldOfViewX() | Mendapatkan atau mengatur bidang pandang horizontal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### setFieldOfViewX{#setFieldOfViewX}

| Nama | Deskripsi |
| --- | --- |
| setFieldOfViewX(value) | Mendapatkan atau mengatur bidang pandang horizontal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### getFieldOfViewY{#getFieldOfViewY}

| Nama | Deskripsi |
| --- | --- |
| getFieldOfViewY() | Mendapatkan atau mengatur bidang pandang vertikal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### setFieldOfViewY{#setFieldOfViewY}

| Nama | Deskripsi |
| --- | --- |
| setFieldOfViewY(value) | Mendapatkan atau mengatur bidang pandang vertikal kamera dalam derajat, properti ini hanya digunakan ketika ApertureMode adalah ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### getWidth{#getWidth}

| Nama | Deskripsi |
| --- | --- |
| getWidth() | Mendapatkan atau mengatur lebar bidang tampilan yang diukur dalam inci. |

 **Result:**



---


### setWidth{#setWidth}

| Nama | Deskripsi |
| --- | --- |
| setWidth(value) | Mendapatkan atau mengatur lebar bidang tampilan yang diukur dalam inci. |

 **Result:**



---


### getHeight{#getHeight}

| Nama | Deskripsi |
| --- | --- |
| getHeight() | Mendapatkan atau mengatur tinggi bidang tampilan yang diukur dalam inci. |

 **Result:**



---


### setHeight{#setHeight}

| Nama | Deskripsi |
| --- | --- |
| setHeight(value) | Mendapatkan atau mengatur tinggi bidang tampilan yang diukur dalam inci. |

 **Result:**



---


### getAspectRatio{#getAspectRatio}

| Nama | Deskripsi |
| --- | --- |
| getAspectRatio() | Mendapatkan atau mengatur rasio aspek bidang tampilan. |

 **Result:**



---


### setAspectRatio{#setAspectRatio}

| Nama | Deskripsi |
| --- | --- |
| setAspectRatio(value) | Mendapatkan atau mengatur rasio aspek bidang tampilan. |

 **Result:**



---


### getMagnification{#getMagnification}

| Nama | Deskripsi |
| --- | --- |
| getMagnification() | Mendapatkan atau mengatur pembesaran yang digunakan pada kamera ortografik. |

 **Result:**



---


### setMagnification{#setMagnification}

| Nama | Deskripsi |
| --- | --- |
| setMagnification(value) | Mendapatkan atau mengatur pembesaran yang digunakan pada kamera ortografik. |

 **Result:**



---


### getProjectionType{#getProjectionType}

| Nama | Deskripsi |
| --- | --- |
| getProjectionType() | Mendapatkan atau mengatur tipe proyeksi kamera. Secara default proyeksi perspektif digunakan. Nilai properti adalah konstanta integer ProjectionType. |

 **Result:**



---


### setProjectionType{#setProjectionType}

| Nama | Deskripsi |
| --- | --- |
| setProjectionType(value) | Mendapatkan atau mengatur tipe proyeksi kamera. Secara default proyeksi perspektif digunakan. Nilai properti adalah konstanta integer ProjectionType. |

 **Result:**



---


### getRotationMode{#getRotationMode}

| Nama | Deskripsi |
| --- | --- |
| getRotationMode() | Mendapatkan atau mengatur mode orientasi frustum. Properti ini hanya berfungsi ketika Target bernilai null. Jika nilai adalah RotationMode.FIXED_TARGET, arah selalu dihitung oleh properti LookAt. Jika tidak, LookAt selalu dihitung oleh Direction. Nilai properti adalah konstanta integer RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Nama | Deskripsi |
| --- | --- |
| setRotationMode(value) | Mendapatkan atau mengatur mode orientasi frustum. Properti ini hanya berfungsi ketika Target bernilai null. Jika nilai adalah RotationMode.FIXED_TARGET, arah selalu dihitung oleh properti LookAt. Jika tidak, LookAt selalu dihitung oleh Direction. Nilai properti adalah konstanta integer RotationMode. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| Nama | Deskripsi |
| --- | --- |
| getNearPlane() | Mendapatkan atau mengatur jarak near plane frustum. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| Nama | Deskripsi |
| --- | --- |
| setNearPlane(value) | Mendapatkan atau mengatur jarak near plane frustum. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| Nama | Deskripsi |
| --- | --- |
| getFarPlane() | Mendapatkan atau mengatur jarak bidang jauh frustum. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Nama | Deskripsi |
| --- | --- |
| setFarPlane(value) | Mendapatkan atau mengatur jarak bidang jauh frustum. |

 **Result:**



---


### getAspect{#getAspect}

| Nama | Deskripsi |
| --- | --- |
| getAspect() | Mendapatkan atau mengatur rasio aspek frustum |

 **Result:**



---


### setAspect{#setAspect}

| Nama | Deskripsi |
| --- | --- |
| setAspect(value) | Mendapatkan atau mengatur rasio aspek frustum |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| Nama | Deskripsi |
| --- | --- |
| getOrthoHeight() | Mendapatkan atau mengatur tinggi ketika frustum dalam proyeksi ortografik. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Nama | Deskripsi |
| --- | --- |
| setOrthoHeight(value) | Mendapatkan atau mengatur tinggi ketika frustum dalam proyeksi ortografik. |

 **Result:**



---


### getUp{#getUp}

| Nama | Deskripsi |
| --- | --- |
| getUp() | Mendapatkan atau mengatur arah atas kamera |

 **Result:**



---


### setUp{#setUp}

| Nama | Deskripsi |
| --- | --- |
| setUp(value) | Mendapatkan atau mengatur arah atas kamera |

 **Result:**



---


### getLookAt{#getLookAt}

| Nama | Deskripsi |
| --- | --- |
| getLookAt() | Mendapatkan atau mengatur posisi yang diminati yang dilihat kamera. |

 **Result:**



---


### setLookAt{#setLookAt}

| Nama | Deskripsi |
| --- | --- |
| setLookAt(value) | Mendapatkan atau mengatur posisi yang diminati yang dilihat kamera. |

 **Result:**



---


### getDirection{#getDirection}

| Nama | Deskripsi |
| --- | --- |
| getDirection() | Mendapatkan atau mengatur arah yang dilihat kamera. Perubahan pada properti ini juga akan memengaruhi LookAt dan Target. |

 **Result:**



---


### setDirection{#setDirection}

| Nama | Deskripsi |
| --- | --- |
| setDirection(value) | Mendapatkan atau mengatur arah yang dilihat kamera. Perubahan pada properti ini juga akan memengaruhi LookAt dan Target. |

 **Result:**



---


### getTarget{#getTarget}

| Nama | Deskripsi |
| --- | --- |
| getTarget() | Mendapatkan atau mengatur target yang dilihat kamera. Jika pengguna mendukung properti ini, sebaiknya diterapkan sebelum properti LookAt. |

 **Result:**



---


### setTarget{#setTarget}

| Nama | Deskripsi |
| --- | --- |
| setTarget(value) | Mendapatkan atau mengatur target yang dilihat kamera. Jika pengguna mendukung properti ini, sebaiknya diterapkan sebelum properti LookAt. |

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


### moveForward{#moveForward}

| Nama | Deskripsi |
| --- | --- |
| moveForward(distance) | Pindahkan kamera ke depan menuju arah atau targetnya. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| jarak | Angka | Berapa lama untuk bergerak maju |

 **Result:**



---


### getBoundingBox{#getBoundingBox}

| Nama | Deskripsi |
| --- | --- |
| getBoundingBox() | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |

 **Result:**



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



