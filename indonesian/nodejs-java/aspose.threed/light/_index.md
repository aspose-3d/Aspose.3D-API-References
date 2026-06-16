---
title: "Light"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/light/
---
## Light class

Cahaya menerangi adegan.  Rumus untuk menghitung total redaman cahaya adalah:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation)


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi instance baru dari kelas Light. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(name) | Menginisialisasi instance baru dari kelas Light. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload2(name, type) | Menginisialisasi instance baru dari kelas Light. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama |
| tipe | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| Nama | Deskripsi |
| --- | --- |
| getColor() | Mendapatkan atau mengatur warna cahaya |

 **Result:**



---


### setColor{#setColor}

| Nama | Deskripsi |
| --- | --- |
| setColor(value) | Mendapatkan atau mengatur warna cahaya |

 **Result:**



---


### getLightType{#getLightType}

| Nama | Deskripsi |
| --- | --- |
| getLightType() | Mendapatkan atau mengatur tipe cahaya. Nilai properti adalah konstanta integer LightType. |

 **Result:**



---


### setLightType{#setLightType}

| Nama | Deskripsi |
| --- | --- |
| setLightType(value) | Mendapatkan atau mengatur tipe cahaya. Nilai properti adalah konstanta integer LightType. |

 **Result:**



---


### getCastLight{#getCastLight}

| Nama | Deskripsi |
| --- | --- |
| getCastLight() | Mendapatkan atau mengatur apakah instance cahaya saat ini dapat menerangi objek lain. |

 **Result:**



---


### setCastLight{#setCastLight}

| Nama | Deskripsi |
| --- | --- |
| setCastLight(value) | Mendapatkan atau mengatur apakah instance cahaya saat ini dapat menerangi objek lain. |

 **Result:**



---


### getIntensity{#getIntensity}

| Nama | Deskripsi |
| --- | --- |
| getIntensity() | Mendapatkan atau mengatur intensitas cahaya, nilai default adalah 100 |

 **Result:**



---


### setIntensity{#setIntensity}

| Nama | Deskripsi |
| --- | --- |
| setIntensity(value) | Mendapatkan atau mengatur intensitas cahaya, nilai default adalah 100 |

 **Result:**



---


### getHotSpot{#getHotSpot}

| Nama | Deskripsi |
| --- | --- |
| getHotSpot() | Mendapatkan atau mengatur sudut kerucut hot spot (dalam derajat). |

 **Result:**



---


### setHotSpot{#setHotSpot}

| Nama | Deskripsi |
| --- | --- |
| setHotSpot(value) | Mendapatkan atau mengatur sudut kerucut hot spot (dalam derajat). |

 **Result:**



---


### getFalloff{#getFalloff}

| Nama | Deskripsi |
| --- | --- |
| getFalloff() | Mendapatkan atau mengatur sudut kerucut penurunan (dalam derajat). |

 **Result:**



---


### setFalloff{#setFalloff}

| Nama | Deskripsi |
| --- | --- |
| setFalloff(value) | Mendapatkan atau mengatur sudut kerucut penurunan (dalam derajat). |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| Nama | Deskripsi |
| --- | --- |
| getConstantAttenuation() | Mendapatkan atau mengatur atenuasi konstan untuk menghitung total atenuasi cahaya |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| Nama | Deskripsi |
| --- | --- |
| setConstantAttenuation(value) | Mendapatkan atau mengatur atenuasi konstan untuk menghitung total atenuasi cahaya |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| Nama | Deskripsi |
| --- | --- |
| getLinearAttenuation() | Mendapatkan atau mengatur atenuasi linier untuk menghitung total atenuasi cahaya |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| Nama | Deskripsi |
| --- | --- |
| setLinearAttenuation(value) | Mendapatkan atau mengatur atenuasi linier untuk menghitung total atenuasi cahaya |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| Nama | Deskripsi |
| --- | --- |
| getQuadraticAttenuation() | Mendapatkan atau mengatur atenuasi kuadratik untuk menghitung total atenuasi cahaya |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| Nama | Deskripsi |
| --- | --- |
| setQuadraticAttenuation(value) | Mendapatkan atau mengatur atenuasi kuadratik untuk menghitung total atenuasi cahaya |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nama | Deskripsi |
| --- | --- |
| getCastShadows() | Mendapatkan atau mengatur apakah cahaya dapat menghasilkan bayangan pada objek lain. |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nama | Deskripsi |
| --- | --- |
| setCastShadows(value) | Mendapatkan atau mengatur apakah cahaya dapat menghasilkan bayangan pada objek lain. |

 **Result:**



---


### getShadowColor{#getShadowColor}

| Nama | Deskripsi |
| --- | --- |
| getShadowColor() | Mendapatkan atau mengatur warna bayangan. |

 **Result:**



---


### setShadowColor{#setShadowColor}

| Nama | Deskripsi |
| --- | --- |
| setShadowColor(value) | Mendapatkan atau mengatur warna bayangan. |

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



