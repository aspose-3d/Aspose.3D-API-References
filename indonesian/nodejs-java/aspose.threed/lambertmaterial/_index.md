---
title: "LambertMaterial"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/lambertmaterial/
---
## LambertMaterial class

Material untuk model shading Lambert


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi instance baru dari kelas LambertMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(name) | Menginisialisasi instance baru dari kelas LambertMaterial. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Nama | Deskripsi |
| --- | --- |
| getEmissiveColor() | Mendapatkan atau mengatur warna emisif |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Nama | Deskripsi |
| --- | --- |
| setEmissiveColor(value) | Mendapatkan atau mengatur warna emisif |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| Nama | Deskripsi |
| --- | --- |
| getAmbientColor() | Mendapatkan atau mengatur warna ambient Contoh: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| Nama | Deskripsi |
| --- | --- |
| setAmbientColor(value) | Mendapatkan atau mengatur warna ambient Contoh: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| Nama | Deskripsi |
| --- | --- |
| getDiffuseColor() | Mendapatkan atau mengatur warna difus. Contoh: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); difus. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| Nama | Deskripsi |
| --- | --- |
| setDiffuseColor(value) | Mendapatkan atau mengatur warna difus. Contoh: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); difus. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| Nama | Deskripsi |
| --- | --- |
| getTransparentColor() | Mendapatkan atau mengatur warna transparan. Contoh: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); warna transparan. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| Nama | Deskripsi |
| --- | --- |
| setTransparentColor(value) | Mendapatkan atau mengatur warna transparan. Contoh: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); warna transparan. |

 **Result:**



---


### getTransparency{#getTransparency}

| Nama | Deskripsi |
| --- | --- |
| getTransparency() | Mendapatkan atau mengatur faktor transparansi. Faktor harus berada dalam rentang antara 0 (0%, sepenuhnya buram) dan 1 (100%, sepenuhnya transparan). Nilai faktor yang tidak valid akan dipotong. Contoh: var mat = new LambertMaterial(); mat.Transparency = 0.3; faktor transparansi. |

 **Result:**



---


### setTransparency{#setTransparency}

| Nama | Deskripsi |
| --- | --- |
| setTransparency(value) | Mendapatkan atau mengatur faktor transparansi. Faktor harus berada dalam rentang antara 0 (0%, sepenuhnya buram) dan 1 (100%, sepenuhnya transparan). Nilai faktor yang tidak valid akan dipotong. Contoh: var mat = new LambertMaterial(); mat.Transparency = 0.3; faktor transparansi. |

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



