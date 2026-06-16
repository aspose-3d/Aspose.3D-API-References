---
title: "PbrSpecularMaterial"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Material untuk rendering berbasis fisik berdasarkan warna difus/spesular/kilap


## Properti

| Nama | Deskripsi |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | Peta tekstur untuk kilap spekular |

## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Konstruktor dari PbrSpecularMaterial |

 **Result:**



---


### getTransparency{#getTransparency}

| Nama | Deskripsi |
| --- | --- |
| getTransparency() | Mendapatkan atau mengatur faktor transparansi. Faktor harus berada dalam rentang antara 0(0%, sepenuhnya buram) dan 1(100%, sepenuhnya transparan). Nilai faktor yang tidak valid akan dipotong. Faktor transparansi. |

 **Result:**



---


### setTransparency{#setTransparency}

| Nama | Deskripsi |
| --- | --- |
| setTransparency(value) | Mendapatkan atau mengatur faktor transparansi. Faktor harus berada dalam rentang antara 0(0%, sepenuhnya buram) dan 1(100%, sepenuhnya transparan). Nilai faktor yang tidak valid akan dipotong. Faktor transparansi. |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| Nama | Deskripsi |
| --- | --- |
| getNormalTexture() | Mendapatkan atau mengatur tekstur pemetaan normal |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| Nama | Deskripsi |
| --- | --- |
| setNormalTexture(value) | Mendapatkan atau mengatur tekstur pemetaan normal |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| Nama | Deskripsi |
| --- | --- |
| getSpecularGlossinessTexture() | Mendapatkan atau mengatur tekstur untuk warna spekular, saluran RGB menyimpan warna spekular dan saluran A menyimpan kilap. |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| Nama | Deskripsi |
| --- | --- |
| setSpecularGlossinessTexture(value) | Mendapatkan atau mengatur tekstur untuk warna spekular, saluran RGB menyimpan warna spekular dan saluran A menyimpan kilap. |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| Nama | Deskripsi |
| --- | --- |
| getGlossinessFactor() | Mendapatkan atau mengatur kilap (kehalusan) material, 1 berarti sangat halus dan 0 berarti sangat kasar, nilai default adalah 1, rentang adalah [0, 1] |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| Nama | Deskripsi |
| --- | --- |
| setGlossinessFactor(value) | Mendapatkan atau mengatur kilap (kehalusan) material, 1 berarti sangat halus dan 0 berarti sangat kasar, nilai default adalah 1, rentang adalah [0, 1] |

 **Result:**



---


### getSpecular{#getSpecular}

| Nama | Deskripsi |
| --- | --- |
| getSpecular() | Mendapatkan atau mengatur warna spekular material, nilai default adalah (1, 1, 1). |

 **Result:**



---


### setSpecular{#setSpecular}

| Nama | Deskripsi |
| --- | --- |
| setSpecular(value) | Mendapatkan atau mengatur warna spekular material, nilai default adalah (1, 1, 1). |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| Nama | Deskripsi |
| --- | --- |
| getDiffuseTexture() | Mendapatkan atau mengatur tekstur untuk difus |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| Nama | Deskripsi |
| --- | --- |
| setDiffuseTexture(value) | Mendapatkan atau mengatur tekstur untuk difus |

 **Result:**



---


### getDiffuse{#getDiffuse}

| Nama | Deskripsi |
| --- | --- |
| getDiffuse() | Mendapatkan atau mengatur warna difus material, nilai default adalah (1, 1, 1) |

 **Result:**



---


### setDiffuse{#setDiffuse}

| Nama | Deskripsi |
| --- | --- |
| setDiffuse(value) | Mendapatkan atau mengatur warna difus material, nilai default adalah (1, 1, 1) |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| Nama | Deskripsi |
| --- | --- |
| getEmissiveTexture() | Mendapatkan atau mengatur tekstur untuk emisif |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| Nama | Deskripsi |
| --- | --- |
| setEmissiveTexture(value) | Mendapatkan atau mengatur tekstur untuk emisif |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Nama | Deskripsi |
| --- | --- |
| getEmissiveColor() | Mendapatkan atau mengatur warna emisif, nilai default adalah (0, 0, 0) |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Nama | Deskripsi |
| --- | --- |
| setEmissiveColor(value) | Mendapatkan atau mengatur warna emisif, nilai default adalah (0, 0, 0) |

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


### getTexture{#getTexture}

| Nama | Deskripsi |
| --- | --- |
| getTexture(slotName) | Mendapatkan tekstur dari slot yang ditentukan, dapat berupa nama properti material atau nama parameter shader |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| slotName | String | Nama slot. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Nama | Deskripsi |
| --- | --- |
| setTexture(slotName, texture) | Mengatur tekstur ke slot yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| slotName | String | Nama slot. |
| texture | TextureBase | Tekstur. |

 **Result:**
TextureBase


---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Memformat objek menjadi string |

 **Result:**
String


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


### iterator{#iterator}

| Nama | Deskripsi |
| --- | --- |
| iterator() | Dipesan untuk penggunaan internal. |

 **Result:**
Property


---



