---
title: "RvmLoadOptions"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/rvmloadoptions/
---
## RvmLoadOptions class

Opsi memuat untuk file RVM Sistem Manajemen Desain Pabrik AVEVA.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(contentType) | Membuat sebuah instance RvmLoadOptions |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload() | Membuat sebuah instance RvmLoadOptions |

 **Result:**



---


### getGenerateMaterials{#getGenerateMaterials}

| Nama | Deskripsi |
| --- | --- |
| getGenerateMaterials() | Menghasilkan material dengan warna acak untuk setiap objek dalam adegan jika tabel warna tidak diekspor dalam file RVM. Nilai default adalah true |

 **Result:**



---


### setGenerateMaterials{#setGenerateMaterials}

| Nama | Deskripsi |
| --- | --- |
| setGenerateMaterials(value) | Menghasilkan material dengan warna acak untuk setiap objek dalam adegan jika tabel warna tidak diekspor dalam file RVM. Nilai default adalah true |

 **Result:**



---


### getCylinderRadialSegments{#getCylinderRadialSegments}

| Nama | Deskripsi |
| --- | --- |
| getCylinderRadialSegments() | Mendapatkan atau mengatur jumlah segmen radial silinder, nilai default adalah 16 |

 **Result:**



---


### setCylinderRadialSegments{#setCylinderRadialSegments}

| Nama | Deskripsi |
| --- | --- |
| setCylinderRadialSegments(value) | Mendapatkan atau mengatur jumlah segmen radial silinder, nilai default adalah 16 |

 **Result:**



---


### getDishLongitudeSegments{#getDishLongitudeSegments}

| Nama | Deskripsi |
| --- | --- |
| getDishLongitudeSegments() | Mendapatkan atau mengatur jumlah segmen bujur piring, nilai default adalah 12 |

 **Result:**



---


### setDishLongitudeSegments{#setDishLongitudeSegments}

| Nama | Deskripsi |
| --- | --- |
| setDishLongitudeSegments(value) | Mendapatkan atau mengatur jumlah segmen bujur piring, nilai default adalah 12 |

 **Result:**



---


### getDishLatitudeSegments{#getDishLatitudeSegments}

| Nama | Deskripsi |
| --- | --- |
| getDishLatitudeSegments() | Mendapatkan atau mengatur jumlah segmen lintang piring, nilai default adalah 8 |

 **Result:**



---


### setDishLatitudeSegments{#setDishLatitudeSegments}

| Nama | Deskripsi |
| --- | --- |
| setDishLatitudeSegments(value) | Mendapatkan atau mengatur jumlah segmen lintang piring, nilai default adalah 8 |

 **Result:**



---


### getTorusTubularSegments{#getTorusTubularSegments}

| Nama | Deskripsi |
| --- | --- |
| getTorusTubularSegments() | Mendapatkan atau mengatur jumlah segmen tabung torus, nilai default adalah 20 |

 **Result:**



---


### setTorusTubularSegments{#setTorusTubularSegments}

| Nama | Deskripsi |
| --- | --- |
| setTorusTubularSegments(value) | Mendapatkan atau mengatur jumlah segmen tabung torus, nilai default adalah 20 |

 **Result:**



---


### getRectangularTorusSegments{#getRectangularTorusSegments}

| Nama | Deskripsi |
| --- | --- |
| getRectangularTorusSegments() | Mendapatkan atau mengatur jumlah segmen radial torus persegi panjang, nilai default adalah 20 |

 **Result:**



---


### setRectangularTorusSegments{#setRectangularTorusSegments}

| Nama | Deskripsi |
| --- | --- |
| setRectangularTorusSegments(value) | Mendapatkan atau mengatur jumlah segmen radial torus persegi panjang, nilai default adalah 20 |

 **Result:**



---


### getCenterScene{#getCenterScene}

| Nama | Deskripsi |
| --- | --- |
| getCenterScene() | Pusatkan adegan setelah dimuat. |

 **Result:**



---


### setCenterScene{#setCenterScene}

| Nama | Deskripsi |
| --- | --- |
| setCenterScene(value) | Pusatkan adegan setelah dimuat. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Nama | Deskripsi |
| --- | --- |
| getAttributePrefix() | Mendapatkan atau mengatur awalan atribut yang didefinisikan dalam file atribut eksternal, Awalan digunakan untuk menghindari konflik nama, nilai default adalah "rvm:" |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Nama | Deskripsi |
| --- | --- |
| setAttributePrefix(value) | Mendapatkan atau mengatur awalan atribut yang didefinisikan dalam file atribut eksternal, Awalan digunakan untuk menghindari konflik nama, nilai default adalah "rvm:" |

 **Result:**



---


### getLookupAttributes{#getLookupAttributes}

| Nama | Deskripsi |
| --- | --- |
| getLookupAttributes() | Mendapatkan atau mengatur apakah akan memuat atribut dari file daftar atribut eksternal (.att/.attrib/.txt), nilai default adalah true. |

 **Result:**



---


### setLookupAttributes{#setLookupAttributes}

| Nama | Deskripsi |
| --- | --- |
| setLookupAttributes(value) | Mendapatkan atau mengatur apakah akan memuat atribut dari file daftar atribut eksternal (.att/.attrib/.txt), nilai default adalah true. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Nama | Deskripsi |
| --- | --- |
| getFileFormat() | Mendapatkan format file yang ditentukan dalam opsi Simpan/Muat saat ini. |

 **Result:**



---


### getEncoding{#getEncoding}

| Nama | Deskripsi |
| --- | --- |
| getEncoding() | Mendapatkan atau mengatur enkoding default untuk file berbasis teks. Nilai default adalah null yang berarti pengimpor/pengekspor akan memutuskan enkoding mana yang akan digunakan. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Nama | Deskripsi |
| --- | --- |
| getFileSystem() | Izinkan pengguna mengelola cara menangani ketergantungan eksternal selama memuat/menyimpan. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Nama | Deskripsi |
| --- | --- |
| setFileSystem(value) | Izinkan pengguna mengelola cara menangani ketergantungan eksternal selama memuat/menyimpan. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Nama | Deskripsi |
| --- | --- |
| getLookupPaths() | Beberapa file seperti OBJ bergantung pada file eksternal, jalur pencarian akan memungkinkan Aspose.3D mencari file eksternal untuk dimuat. |

 **Result:**



---


### getFileName{#getFileName}

| Nama | Deskripsi |
| --- | --- |
| getFileName() | Nama file dari adegan yang diekspor/dimpor. Ini bersifat opsional, tetapi berguna saat menyerialisasi aset eksternal seperti material OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Nama | Deskripsi |
| --- | --- |
| setFileName(value) | Nama file dari adegan yang diekspor/dimpor. Ini bersifat opsional, tetapi berguna saat menyerialisasi aset eksternal seperti material OBJ. |

 **Result:**



---



