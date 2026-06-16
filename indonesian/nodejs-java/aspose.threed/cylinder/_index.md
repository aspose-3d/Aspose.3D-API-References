---
title: "Silinder"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

Silinder berparameter. Itu juga dapat digunakan untuk merepresentasikan kerucut ketika salah satu radiusTop/radiusBottom bernilai nol.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi sebuah instance baru dari kelas Silinder. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(radius, height) | Menginisialisasi sebuah instance baru dari kelas Silinder. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| radius | Angka | Jari-jari tutup atas dan bawah. |
| height | Angka | Tinggi. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Menginisialisasi sebuah instance baru dari kelas Silinder. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| radiusTop | Angka | Jari-jari atas. |
| radiusBottom | Angka | Jari-jari bawah. |
| height | Angka | Tinggi. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Menginisialisasi sebuah instance baru dari kelas Silinder. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| radiusTop | Angka | Jari-jari tutup atas silinder. |
| radiusBottom | Angka | Jari-jari tutup bawah silinder. |
| height | Angka | Tinggi silinder. |
| radialSegments | Angka | Segmen radial dari kedua lingkaran atas dan bawah.. |
| heightSegments | Angka | Segmen tinggi. |
| openEnded | boolean | Jika disetel ke |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Menginisialisasi sebuah instance baru dari kelas Silinder. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama objek ini |
| radiusTop | Angka | Jari-jari tutup atas silinder. |
| radiusBottom | Angka | Jari-jari tutup bawah silinder. |
| height | Angka | Tinggi silinder. |
| radialSegments | Angka | Segmen radial dari kedua lingkaran atas dan bawah.. |
| heightSegments | Angka | Segmen tinggi. |
| openEnded | boolean | Jika disetel ke |
| thetaStart | Angka | Awal Theta. |
| thetaLength | Angka | Panjang Theta. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| Nama | Deskripsi |
| --- | --- |
| getOffsetBottom() | Mendapatkan atau mengatur offset transformasi vertex pada sisi bawah. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| Nama | Deskripsi |
| --- | --- |
| setOffsetBottom(value) | Mendapatkan atau mengatur offset transformasi vertex pada sisi bawah. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| Nama | Deskripsi |
| --- | --- |
| getOffsetTop() | Mendapatkan atau mengatur offset transformasi vertex pada sisi atas. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| Nama | Deskripsi |
| --- | --- |
| setOffsetTop(value) | Mendapatkan atau mengatur offset transformasi vertex pada sisi atas. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| Nama | Deskripsi |
| --- | --- |
| getGenerateFanCylinder() | Mendapatkan atau mengatur apakah akan menghasilkan silinder gaya kipas ketika ThetaLength kurang dari 2PI, jika tidak model tidak akan dipotong. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| Nama | Deskripsi |
| --- | --- |
| setGenerateFanCylinder(value) | Mendapatkan atau mengatur apakah akan menghasilkan silinder gaya kipas ketika ThetaLength kurang dari 2PI, jika tidak model tidak akan dipotong. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| Nama | Deskripsi |
| --- | --- |
| getShearBottom() | Mendapatkan atau mengatur transformasi geser sisi bawah, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0) |

 **Result:**



---


### setShearBottom{#setShearBottom}

| Nama | Deskripsi |
| --- | --- |
| setShearBottom(value) | Mendapatkan atau mengatur transformasi geser sisi bawah, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0) |

 **Result:**



---


### getShearTop{#getShearTop}

| Nama | Deskripsi |
| --- | --- |
| getShearTop() | Mendapatkan atau mengatur transformasi geser sisi atas, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0) |

 **Result:**



---


### setShearTop{#setShearTop}

| Nama | Deskripsi |
| --- | --- |
| setShearTop(value) | Mendapatkan atau mengatur transformasi geser sisi atas, vektor menyimpan nilai geser (sumbu-x, sumbu-z) yang diukur dalam radian, nilai default adalah (0, 0) |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| Nama | Deskripsi |
| --- | --- |
| getRadiusTop() | Mendapatkan atau mengatur radius tutup atas silinder. Radius tutup atas. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| Nama | Deskripsi |
| --- | --- |
| setRadiusTop(value) | Mendapatkan atau mengatur radius tutup atas silinder. Radius tutup atas. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| Nama | Deskripsi |
| --- | --- |
| getRadiusBottom() | Mendapatkan atau mengatur radius tutup bawah silinder. Radius tutup bawah. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| Nama | Deskripsi |
| --- | --- |
| setRadiusBottom(value) | Mendapatkan atau mengatur radius tutup bawah silinder. Radius tutup bawah. |

 **Result:**



---


### getHeight{#getHeight}

| Nama | Deskripsi |
| --- | --- |
| getHeight() | Mendapatkan atau mengatur tinggi silinder. Tinggi silinder. |

 **Result:**



---


### setHeight{#setHeight}

| Nama | Deskripsi |
| --- | --- |
| setHeight(value) | Mendapatkan atau mengatur tinggi silinder. Tinggi silinder. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| Nama | Deskripsi |
| --- | --- |
| getRadialSegments() | Mendapatkan atau mengatur segmen radial. Segmen radial. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| Nama | Deskripsi |
| --- | --- |
| setRadialSegments(value) | Mendapatkan atau mengatur segmen radial. Segmen radial. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Nama | Deskripsi |
| --- | --- |
| getHeightSegments() | Mendapatkan atau mengatur segmen tinggi. Segmen tinggi. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Nama | Deskripsi |
| --- | --- |
| setHeightSegments(value) | Mendapatkan atau mengatur segmen tinggi. Segmen tinggi. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| Nama | Deskripsi |
| --- | --- |
| getOpenEnded() | Mendapatkan atau mengatur nilai yang menunjukkan apakah Cylinder ini terbuka di ujung. Nilai default adalah false. true jika terbuka di ujung; jika tidak, tutup atas/bawah ada. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| Nama | Deskripsi |
| --- | --- |
| setOpenEnded(value) | Mendapatkan atau mengatur nilai yang menunjukkan apakah Cylinder ini terbuka di ujung. Nilai default adalah false. true jika terbuka di ujung; jika tidak, tutup atas/bawah ada. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| Nama | Deskripsi |
| --- | --- |
| getThetaStart() | Mendapatkan atau mengatur awal theta. Nilai default adalah 0. Awal theta. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| Nama | Deskripsi |
| --- | --- |
| setThetaStart(value) | Mendapatkan atau mengatur awal theta. Nilai default adalah 0. Awal theta. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| Nama | Deskripsi |
| --- | --- |
| getThetaLength() | Mendapatkan atau mengatur panjang theta. Nilai default adalah 2π. Panjang theta. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| Nama | Deskripsi |
| --- | --- |
| setThetaLength(value) | Mendapatkan atau mengatur panjang theta. Nilai default adalah 2π. Panjang theta. |

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
| toMesh() | Mengonversi objek saat ini menjadi mesh |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Nama | Deskripsi |
| --- | --- |
| getBoundingBox() | Mendapatkan kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |

 **Result:**
Mesh


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



