---
title: "Scene"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/scene/
---
## Scene class

Sebuah scene adalah objek tingkat atas yang berisi node, geometri, material, tekstur, animasi, pose, sub-scene, dan lain-lain.  Scene dapat memiliki sub-scene, berfungsi sebagai dukungan multi-dokumen dalam file seperti collada/blender/fbx.  Hierarki node dapat diakses melalui RootNodeLibrary yang digunakan untuk menyimpan referensi objek yang tidak terikat selama serialisasi (seperti metadata atau objek khusus) sehingga dapat digunakan sebagai perpustakaan.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi instance baru dari kelas Scene. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(entity) | Menginisialisasi instance baru dari kelas Scene dengan entitas yang terpasang pada node baru. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| entity | Entity | Entitas awal yang terpasang pada scene |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload2(parentScene, name) | Menginisialisasi sebuah instance baru dari kelas Scene sebagai sub-scene. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| parentScene | Scene | Scene induk. |
| name | String | Nama Scene. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload3(fileName) | Menginisialisasi sebuah instance baru dari kelas Scene dan membuka file secara langsung. Ini adalah konstruktor yang usang, silakan gunakan #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file yang akan dibuka. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| Nama | Deskripsi |
| --- | --- |
| getSubScenes() | Mendapatkan semua sub-scene. |

 **Result:**



---


### getLibrary{#getLibrary}

| Nama | Deskripsi |
| --- | --- |
| getLibrary() | Objek yang tidak langsung digunakan dalam hierarki scene dapat didefinisikan di Library. Ini berguna ketika Anda menggunakan sub-scene dan menempatkan komponen yang dapat digunakan kembali di bawah sub-scene. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| Nama | Deskripsi |
| --- | --- |
| getAnimationClips() | Mendapatkan semua AnimationClip yang didefinisikan dalam scene. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| Nama | Deskripsi |
| --- | --- |
| getCurrentAnimationClip() | Mendapatkan atau mengatur AnimationClip yang aktif |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| Nama | Deskripsi |
| --- | --- |
| setCurrentAnimationClip(value) | Mendapatkan atau mengatur AnimationClip yang aktif |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Nama | Deskripsi |
| --- | --- |
| getAssetInfo() | Mendapatkan atau mengatur informasi aset tingkat atas. Informasi dokumen. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Nama | Deskripsi |
| --- | --- |
| setAssetInfo(value) | Mendapatkan atau mengatur informasi aset tingkat atas. Informasi dokumen. |

 **Result:**



---


### getPoses{#getPoses}

| Nama | Deskripsi |
| --- | --- |
| getPoses() | Mendapatkan semua Pose yang digunakan dalam scene ini. Pose-pose tersebut. |

 **Result:**



---


### getRootNode{#getRootNode}

| Nama | Deskripsi |
| --- | --- |
| getRootNode() | Mendapatkan node akar dari scene. Node akar. |

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


### getAnimationClip{#getAnimationClip}

| Nama | Deskripsi |
| --- | --- |
| getAnimationClip(name) | Mendapatkan AnimationClip dengan nama tertentu |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | The |

 **Result:**
AnimationClip


---


### clear{#clear}

| Nama | Deskripsi |
| --- | --- |
| clear() | Menghapus konten adegan dan mengembalikan pengaturan default. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| Nama | Deskripsi |
| --- | --- |
| createAnimationClip(name) | Fungsi singkat untuk membuat dan mendaftarkan AnimationClip. AnimationClip pertama akan diberikan ke CurrentAnimationClip |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama klip animasi |

 **Result:**
AnimationClip


---


### open{#open}

| Nama | Deskripsi |
| --- | --- |
| open(fileName, options) | Membuka adegan dari jalur yang diberikan menggunakan format file yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file. |
| opsi | LoadOptions | Konfigurasi lebih detail untuk membuka aliran. |

 **Result:**
AnimationClip


---


### open{#open}

| Nama | Deskripsi |
| --- | --- |
| open(fileName) | Membuka adegan dari jalur yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| Nama | Deskripsi |
| --- | --- |
| fromFile(fileName) | Membuka adegan dari jalur yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file. |

 **Result:**
AnimationClip


---


### save{#save}

| Nama | Deskripsi |
| --- | --- |
| save(fileName) | Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file. |

 **Result:**
AnimationClip


---


### save{#save}

| Nama | Deskripsi |
| --- | --- |
| save(fileName, format) | Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file. |
| format | FileFormat | Format. |

 **Result:**
AnimationClip


---


### save{#save}

| Nama | Deskripsi |
| --- | --- |
| save(fileName, options) | Menyimpan adegan ke jalur yang ditentukan menggunakan format file yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file. |
| opsi | SaveOptions | Konfigurasi lebih detail untuk menyimpan aliran. |

 **Result:**
AnimationClip


---


### render{#render}

| Nama | Deskripsi |
| --- | --- |
| render(camera, fileName) | Render adegan ke file eksternal dari perspektif kamera yang diberikan. Ukuran output default adalah 1024x768 dan format output adalah png |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| kamera | Kamera | Dari perspektif kamera mana untuk merender adegan |
| fileName | String | Nama file output |

 **Result:**
AnimationClip


---


### render{#render}

| Nama | Deskripsi |
| --- | --- |
| render(camera, fileName, size, format) | Render adegan ke file eksternal dari perspektif kamera yang diberikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| kamera | Kamera | Dari perspektif kamera mana untuk merender adegan |
| fileName | String | Nama file output |
| ukuran | Vector2 | Ukuran gambar akhir yang dirender |
| format | String | Format gambar dari file output |

 **Result:**
AnimationClip


---


### render{#render}

| Nama | Deskripsi |
| --- | --- |
| render(camera, fileName, size, format, options) | Render adegan ke file eksternal dari perspektif kamera yang diberikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| kamera | Kamera | Dari perspektif kamera mana untuk merender adegan |
| fileName | String | Nama file output |
| ukuran | Vector2 | Ukuran gambar akhir yang dirender |
| format | String | Format gambar dari file output |
| opsi | ImageRenderOptions | Opsi untuk menyesuaikan beberapa pengaturan internal. |

 **Result:**
AnimationClip


---


### render{#render}

| Nama | Deskripsi |
| --- | --- |
| render(camera, bitmap) | Render adegan ke bitmap dari perspektif kamera yang diberikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| kamera | Kamera | Dari perspektif kamera mana untuk merender adegan |
| bitmap | TextureData | Target dari hasil render |

 **Result:**
AnimationClip


---


### render{#render}

| Nama | Deskripsi |
| --- | --- |
| render(camera, bitmap, options) | Render adegan ke bitmap dari perspektif kamera yang diberikan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| kamera | Kamera | Dari perspektif kamera mana untuk merender adegan |
| bitmap | TextureData | Target dari hasil render |
| opsi | ImageRenderOptions | Opsi untuk menyesuaikan beberapa pengaturan internal. |

 **Result:**
AnimationClip


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



