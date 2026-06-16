---
title: "Material"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/material/
---
## Material class

Material mendefinisikan parameter yang diperlukan untuk tampilan visual geometri. Aspose.3D menyediakan model shading untuk LambertMaterial, PhongMaterial, dan ShaderMaterial  @hideconstructor


## Properti

| Nama | Deskripsi |
| --- | --- |
| MAP_SPECULAR | Digunakan dalam setTexture(java.lang.String, com.aspose.threed.TextureBase) untuk menetapkan pemetaan tekstur specular. |
| MAP_DIFFUSE | Digunakan dalam setTexture(java.lang.String, com.aspose.threed.TextureBase) untuk menetapkan pemetaan tekstur diffuse. |
| MAP_EMISSIVE | Digunakan dalam setTexture(java.lang.String, com.aspose.threed.TextureBase) untuk menetapkan pemetaan tekstur emissive. |
| MAP_AMBIENT | Digunakan dalam setTexture(java.lang.String, com.aspose.threed.TextureBase) untuk menetapkan pemetaan tekstur ambient. |
| MAP_NORMAL | Digunakan dalam setTexture(java.lang.String, com.aspose.threed.TextureBase) untuk menetapkan pemetaan tekstur normal. |

## Metode

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



