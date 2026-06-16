---
title: "TextureData"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

Kelas ini berisi data mentah dan definisi format sebuah tekstur.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | Konstruktor dari TextureData |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| widt | Angka | null |
| heigh | Angka | null |
| strid | Angka | null |
| bytesPerPixe | Angka | null |
| pixelFormat | PixelFormat | PixelFormat |
| dat | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | Membuat TextureData baru dan mengalokasikan data piksel. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| widt | Angka | null |
| heigh | Angka | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload2() | Konstruktor dari TextureData |

 **Result:**



---


### getData{#getData}

| Nama | Deskripsi |
| --- | --- |
| getData() | Byte mentah data piksel |

 **Result:**



---


### getWidth{#getWidth}

| Nama | Deskripsi |
| --- | --- |
| getWidth() | Jumlah piksel horizontal |

 **Result:**



---


### getHeight{#getHeight}

| Nama | Deskripsi |
| --- | --- |
| getHeight() | Jumlah piksel vertikal |

 **Result:**



---


### getStride{#getStride}

| Nama | Deskripsi |
| --- | --- |
| getStride() | Jumlah byte pada satu baris scanline. |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| Nama | Deskripsi |
| --- | --- |
| getBytesPerPixel() | Jumlah byte per piksel |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| Nama | Deskripsi |
| --- | --- |
| getPixelFormat() | Format piksel. Nilai properti adalah konstanta integer PixelFormat. |

 **Result:**



---


### fromFile{#fromFile}

| Nama | Deskripsi |
| --- | --- |
| fromFile(fileName) | Muat tekstur dari file |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
TextureData


---


### save{#save}

| Nama | Deskripsi |
| --- | --- |
| save(fileName) | Simpan data tekstur ke file gambar |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file tempat gambar akan disimpan. |

 **Result:**
TextureData


---


### save{#save}

| Nama | Deskripsi |
| --- | --- |
| save(fileName, format) | Simpan data tekstur ke file gambar |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file tempat gambar akan disimpan. |
| format | String | Format gambar dari file keluaran. |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| Nama | Deskripsi |
| --- | --- |
| mapPixels(mapMode) | Petakan semua piksel untuk baca/tulis |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Nama | Deskripsi |
| --- | --- |
| mapPixels(mapMode, format) | Petakan semua piksel untuk baca/tulis dalam format piksel yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| Nama | Deskripsi |
| --- | --- |
| mapPixels(rect, mapMode, format) | Petakan piksel yang ditunjuk oleh rect untuk membaca/menulis dalam format piksel yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rect | Area piksel yang akan diakses |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| Nama | Deskripsi |
| --- | --- |
| transformPixelFormat(pixelFormat) | Ubah tata letak piksel ke format piksel baru. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



