---
title: "GltfSaveOptions"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

Opsi simpan untuk format glTF.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(contentType) | Konstruktor GltfSaveOptions |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(format) | Konstruktor GltfSaveOptions |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| bentuk | FileFormat | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| Nama | Deskripsi |
| --- | --- |
| getPrettyPrint() | Konten JSON dari file GLTF diindentasi untuk kemudahan membaca manusia, nilai default adalah false |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| Nama | Deskripsi |
| --- | --- |
| setPrettyPrint(value) | Konten JSON dari file GLTF diindentasi untuk kemudahan membaca manusia, nilai default adalah false |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| Nama | Deskripsi |
| --- | --- |
| getFallbackNormal() | Ketika ekspor GLTF2 mendeteksi normal yang tidak valid, nilai ini akan digunakan menggantikan nilai aslinya untuk melewati validasi. Nilai default adalah (0, 1, 0) |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| Nama | Deskripsi |
| --- | --- |
| getEmbedAssets() | Sematkan semua aset eksternal sebagai base64 ke dalam satu file dalam mode ASCII, nilai default adalah false. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| Nama | Deskripsi |
| --- | --- |
| setEmbedAssets(value) | Sematkan semua aset eksternal sebagai base64 ke dalam satu file dalam mode ASCII, nilai default adalah false. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| Nama | Deskripsi |
| --- | --- |
| getImageFormat() | Standard glTF hanya mendukung PNG/JPG sebagai format teksturnya, opsi ini akan memandu bagaimana Aspose.3D mengonversi gambar non-standar ke format yang didukung selama proses ekspor. Nilai default adalah GltfEmbeddedImageFormat.PNGNilai properti ini adalah konstanta integer GltfEmbeddedImageFormat. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| Nama | Deskripsi |
| --- | --- |
| setImageFormat(value) | Standard glTF hanya mendukung PNG/JPG sebagai format teksturnya, opsi ini akan memandu bagaimana Aspose.3D mengonversi gambar non-standar ke format yang didukung selama proses ekspor. Nilai default adalah GltfEmbeddedImageFormat.PNGNilai properti ini adalah konstanta integer GltfEmbeddedImageFormat. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Nama | Deskripsi |
| --- | --- |
| getMaterialConverter() | Konverter khusus untuk mengonversi material geometri menjadi material PBR. Jika ini tidak ditetapkan, pengekspor glTF 2.0 akan secara otomatis mengonversi material standar menjadi material PBR. Nilai default adalah null. Properti ini digunakan saat mengekspor sebuah adegan ke file glTF 2.0. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Nama | Deskripsi |
| --- | --- |
| setMaterialConverter(value) | Konverter khusus untuk mengonversi material geometri menjadi material PBR. Jika ini tidak ditetapkan, pengekspor glTF 2.0 akan secara otomatis mengonversi material standar menjadi material PBR. Nilai default adalah null. Properti ini digunakan saat mengekspor sebuah adegan ke file glTF 2.0. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| Nama | Deskripsi |
| --- | --- |
| getUseCommonMaterials() | Serialisasikan material menggunakan ekstensi material umum KHR, nilai default adalah false. Mengatur ini ke false akan menyebabkan Aspose.3D mengekspor sekumpulan shader vertex/fragment jika #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| Nama | Deskripsi |
| --- | --- |
| setUseCommonMaterials(value) | Serialisasikan material menggunakan ekstensi material umum KHR, nilai default adalah false. Mengatur ini ke false akan menyebabkan Aspose.3D mengekspor sekumpulan shader vertex/fragment jika #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| Nama | Deskripsi |
| --- | --- |
| getExternalDracoEncoder() | Gunakan encoder draco eksternal untuk mempercepat kecepatan kompresi draco. Aspose.3D akan membuat proses sub baru untuk mengkodekan mesh ke format draco, gunakan dengan risiko Anda sendiri. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| Nama | Deskripsi |
| --- | --- |
| setExternalDracoEncoder(value) | Gunakan encoder draco eksternal untuk mempercepat kecepatan kompresi draco. Aspose.3D akan membuat proses sub baru untuk mengkodekan mesh ke format draco, gunakan dengan risiko Anda sendiri. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| Nama | Deskripsi |
| --- | --- |
| getFlipTexCoordV() | Balik komponen koordinat tekstur v(t), nilai default adalah true. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| Nama | Deskripsi |
| --- | --- |
| setFlipTexCoordV(value) | Balik komponen koordinat tekstur v(t), nilai default adalah true. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| Nama | Deskripsi |
| --- | --- |
| getBufferFile() | Nama file dari file buffer eksternal yang digunakan untuk menyimpan data biner. Jika file ini tidak ditentukan, Aspose.3D akan menghasilkan nama untuk Anda. Ini diabaikan saat mengekspor glTF dalam mode biner. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| Nama | Deskripsi |
| --- | --- |
| setBufferFile(value) | Nama file dari file buffer eksternal yang digunakan untuk menyimpan data biner. Jika file ini tidak ditentukan, Aspose.3D akan menghasilkan nama untuk Anda. Ini diabaikan saat mengekspor glTF dalam mode biner. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| Nama | Deskripsi |
| --- | --- |
| getSaveExtras() | Simpan properti dinamis objek adegan ke dalam bidang 'extra' pada file glTF yang dihasilkan. Ini berguna untuk menyediakan data khusus aplikasi. Nilai default adalah false. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| Nama | Deskripsi |
| --- | --- |
| setSaveExtras(value) | Simpan properti dinamis objek adegan ke dalam bidang 'extra' pada file glTF yang dihasilkan. Ini berguna untuk menyediakan data khusus aplikasi. Nilai default adalah false. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Nama | Deskripsi |
| --- | --- |
| getApplyUnitScale() | Terapkan AssetInfo.UnitScaleFactor ke mesh. Nilai default adalah false. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Nama | Deskripsi |
| --- | --- |
| setApplyUnitScale(value) | Terapkan AssetInfo.UnitScaleFactor ke mesh. Nilai default adalah false. |

 **Result:**



---


### getDracoCompression{#getDracoCompression}

| Nama | Deskripsi |
| --- | --- |
| getDracoCompression() | Mendapatkan atau mengatur apakah mengaktifkan kompresi draco |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| Nama | Deskripsi |
| --- | --- |
| setDracoCompression(value) | Mendapatkan atau mengatur apakah mengaktifkan kompresi draco |

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



