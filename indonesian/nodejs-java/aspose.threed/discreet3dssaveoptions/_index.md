---
title: "Discreet3dsSaveOptions"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Opsi penyimpanan untuk file 3DS.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Konstruktor Discreet3dsSaveOptions |

 **Result:**



---


### getExportLight{#getExportLight}

| Nama | Deskripsi |
| --- | --- |
| getExportLight() | Mendapatkan atau mengatur apakah mengekspor semua lampu dalam adegan. |

 **Result:**



---


### setExportLight{#setExportLight}

| Nama | Deskripsi |
| --- | --- |
| setExportLight(value) | Mendapatkan atau mengatur apakah mengekspor semua lampu dalam adegan. |

 **Result:**



---


### getExportCamera{#getExportCamera}

| Nama | Deskripsi |
| --- | --- |
| getExportCamera() | Mendapatkan atau mengatur apakah mengekspor semua kamera dalam adegan. |

 **Result:**



---


### setExportCamera{#setExportCamera}

| Nama | Deskripsi |
| --- | --- |
| setExportCamera(value) | Mendapatkan atau mengatur apakah mengekspor semua kamera dalam adegan. |

 **Result:**



---


### getDuplicatedNameSeparator{#getDuplicatedNameSeparator}

| Nama | Deskripsi |
| --- | --- |
| getDuplicatedNameSeparator() | Pemisah antara nama objek dan penghitung duplikat, nilai default adalah "_". Ketika adegan berisi objek-objek yang menggunakan nama yang sama, Aspose.3D 3DS exporter akan menghasilkan nama yang berbeda untuk objek tersebut. Misalnya ada dua node bernama "Box", node pertama akan memiliki nama "Box", dan node kedua akan mendapatkan nama baru "Box_2" menggunakan konfigurasi default. |

 **Result:**



---


### setDuplicatedNameSeparator{#setDuplicatedNameSeparator}

| Nama | Deskripsi |
| --- | --- |
| setDuplicatedNameSeparator(value) | Pemisah antara nama objek dan penghitung duplikat, nilai default adalah "_". Ketika adegan berisi objek-objek yang menggunakan nama yang sama, Aspose.3D 3DS exporter akan menghasilkan nama yang berbeda untuk objek tersebut. Misalnya ada dua node bernama "Box", node pertama akan memiliki nama "Box", dan node kedua akan mendapatkan nama baru "Box_2" menggunakan konfigurasi default. |

 **Result:**



---


### getDuplicatedNameCounterBase{#getDuplicatedNameCounterBase}

| Nama | Deskripsi |
| --- | --- |
| getDuplicatedNameCounterBase() | Penghitung yang digunakan untuk menghasilkan nama baru bagi nama duplikat, nilai default adalah 2. |

 **Result:**



---


### setDuplicatedNameCounterBase{#setDuplicatedNameCounterBase}

| Nama | Deskripsi |
| --- | --- |
| setDuplicatedNameCounterBase(value) | Penghitung yang digunakan untuk menghasilkan nama baru bagi nama duplikat, nilai default adalah 2. |

 **Result:**



---


### getDuplicatedNameCounterFormat{#getDuplicatedNameCounterFormat}

| Nama | Deskripsi |
| --- | --- |
| getDuplicatedNameCounterFormat() | Format penghitung duplikat, nilai default adalah string kosong. |

 **Result:**



---


### setDuplicatedNameCounterFormat{#setDuplicatedNameCounterFormat}

| Nama | Deskripsi |
| --- | --- |
| setDuplicatedNameCounterFormat(value) | Format penghitung duplikat, nilai default adalah string kosong. |

 **Result:**



---


### getMasterScale{#getMasterScale}

| Nama | Deskripsi |
| --- | --- |
| getMasterScale() | Mendapatkan atau mengatur skala utama yang digunakan dalam proses ekspor. |

 **Result:**



---


### setMasterScale{#setMasterScale}

| Nama | Deskripsi |
| --- | --- |
| setMasterScale(value) | Mendapatkan atau mengatur skala utama yang digunakan dalam proses ekspor. |

 **Result:**



---


### getGammaCorrectedColor{#getGammaCorrectedColor}

| Nama | Deskripsi |
| --- | --- |
| getGammaCorrectedColor() | File 3ds dapat berisi warna asli dan warna yang dikoreksi gamma untuk atribut yang sama, Mengatur ini ke true akan menggunakan warna yang dikoreksi gamma jika memungkinkan, jika tidak Aspose.3D akan mencoba menggunakan warna asli. |

 **Result:**



---


### setGammaCorrectedColor{#setGammaCorrectedColor}

| Nama | Deskripsi |
| --- | --- |
| setGammaCorrectedColor(value) | File 3ds dapat berisi warna asli dan warna yang dikoreksi gamma untuk atribut yang sama, Mengatur ini ke true akan menggunakan warna yang dikoreksi gamma jika memungkinkan, jika tidak Aspose.3D akan mencoba menggunakan warna asli. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Nama | Deskripsi |
| --- | --- |
| getFlipCoordinateSystem() | Mendapatkan atau mengatur sistem koordinat flip dari titik kontrol/normal selama mengimpor/mengekspor. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Nama | Deskripsi |
| --- | --- |
| setFlipCoordinateSystem(value) | Mendapatkan atau mengatur sistem koordinat flip dari titik kontrol/normal selama mengimpor/mengekspor. |

 **Result:**



---


### getHighPreciseColor{#getHighPreciseColor}

| Nama | Deskripsi |
| --- | --- |
| getHighPreciseColor() | Jika ini true, file 3ds yang dihasilkan akan menggunakan warna berpresisi tinggi, artinya setiap kanal merah/hijau/biru menggunakan float 32bit. Jika tidak, file yang dihasilkan akan menggunakan warna 24bit, setiap kanal menggunakan byte 8bit. Nilai default adalah false, karena tidak semua aplikasi mendukung warna berpresisi tinggi. |

 **Result:**



---


### setHighPreciseColor{#setHighPreciseColor}

| Nama | Deskripsi |
| --- | --- |
| setHighPreciseColor(value) | Jika ini true, file 3ds yang dihasilkan akan menggunakan warna berpresisi tinggi, artinya setiap kanal merah/hijau/biru menggunakan float 32bit. Jika tidak, file yang dihasilkan akan menggunakan warna 24bit, setiap kanal menggunakan byte 8bit. Nilai default adalah false, karena tidak semua aplikasi mendukung warna berpresisi tinggi. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Nama | Deskripsi |
| --- | --- |
| getExportTextures() | Coba salin tekstur yang digunakan dalam adegan ke direktori output. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Nama | Deskripsi |
| --- | --- |
| setExportTextures(value) | Coba salin tekstur yang digunakan dalam adegan ke direktori output. |

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



