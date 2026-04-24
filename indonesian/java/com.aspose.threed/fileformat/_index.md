---
title: FileFormat
second_title: Referensi API Aspose.3D untuk Java
description: Definisi format file
type: docs
weight: 64
url: /id/java/com.aspose.threed/fileformat/
---

**Inheritance:**
java.lang.Object
```
public class FileFormat
```

Definisi format file
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [AMF](#AMF) | Format file manufaktur aditif |
| [ASE](#ASE) | Format ASCII Scene Exporter milik 3D Studio Max. |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Format Web Aspose.3D. |
| [BLENDER](#BLENDER) | Format file 3D milik Blender |
| [COLLADA](#COLLADA) | Format file Collada |
| [DISCREET3DS](#DISCREET3DS) | Format file milik 3D Studio |
| [DRACO](#DRACO) | Google Draco Mesh |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | Format file FBX ASCII, dengan versi 6.1.0 |
| [FBX6100_BINARY](#FBX6100-BINARY) | Format file FBX Biner, dengan versi 6.1.0 |
| [FBX7200ASCII](#FBX7200ASCII) | Format file FBX ASCII, dengan versi 7.2.0 |
| [FBX7200_BINARY](#FBX7200-BINARY) | Format file FBX Biner, dengan versi 7.2.0 |
| [FBX7300ASCII](#FBX7300ASCII) | Format file FBX ASCII, dengan versi 7.3.0 |
| [FBX7300_BINARY](#FBX7300-BINARY) | Format file FBX Biner, dengan versi 7.3.0 |
| [FBX7400ASCII](#FBX7400ASCII) | Format file FBX ASCII, dengan versi 7.4.0 |
| [FBX7400_BINARY](#FBX7400-BINARY) | Format file FBX Biner, dengan versi 7.4.0 |
| [FBX7500ASCII](#FBX7500ASCII) | Format file FBX ASCII, dengan versi 7.5.0 |
| [FBX7500_BINARY](#FBX7500-BINARY) | Format file FBX Biner, dengan versi 7.5.0 |
| [FBX7600ASCII](#FBX7600ASCII) | Format file FBX ASCII, dengan versi 7.6.0 |
| [FBX7600_BINARY](#FBX7600-BINARY) | Format file FBX Biner, dengan versi 7.6.0 |
| [FBX7700ASCII](#FBX7700ASCII) | Format file FBX ASCII, dengan versi 7.7.0 |
| [FBX7700_BINARY](#FBX7700-BINARY) | Format file FBX Biner, dengan versi 7.7.0 |
| [GLTF](#GLTF) | glTF milik Khronos Group |
| [GLTF2](#GLTF2) | glTF versi 2.0 milik Khronos Group |
| [GLTF2_BINARY](#GLTF2-BINARY) | glTF versi 2.0 milik Khronos Group |
| [GLTF_BINARY](#GLTF-BINARY) | glTF milik Khronos Group dalam format Biner |
| [HTML5](#HTML5) | File HTML5 |
| [IFC](#IFC) | Model data ISO 16739-1 Industry Foundation Classes. |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya dalam format ASCII |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya dalam format Biner |
| [MICROSOFT3MF](#MICROSOFT3MF) | Format Manufaktur 3D Microsoft |
| [PCD](#PCD) | File PCL Point Cloud Data dalam mode ASCII |
| [PCD_BINARY](#PCD-BINARY) | File PCL Point Cloud Data dalam mode Biner |
| [PDF](#PDF) | Portable Document Format milik Adobe |
| [PLY](#PLY) | Polygon File Format atau Stanford Triangle Format |
| [RVM_BINARY](#RVM-BINARY) | Model AVEVA Plant Design Management System dalam format biner |
| [RVM_TEXT](#RVM-TEXT) | Model AVEVA Plant Design Management System dalam format teks |
| [SIEMENSJT8](#SIEMENSJT8) | File JT Siemens Versi 8 |
| [SIEMENSJT9](#SIEMENSJT9) | File JT Siemens Versi 9 |
| [STLASCII](#STLASCII) | Format file STL ASCII |
| [STL_BINARY](#STL-BINARY) | Format file STL Biner |
| [UNIVERSAL3D](#UNIVERSAL3D) | Format file Universal3D |
| [USD](#USD) | Deskripsi Adegan Universal |
| [USDA](#USDA) | Deskripsi Adegan Universal dalam format ASCII. |
| [USDZ](#USDZ) | Deskripsi Adegan Universal Terkompresi |
| [VRML](#VRML) | Bahasa Pemodelan Realitas Virtual |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Format file Obj milik Wavefront |
| [XYZ](#XYZ) | File awan titik Xyz |
| [X_BINARY](#X-BINARY) | File X DirectX dalam format biner |
| [X_TEXT](#X-TEXT) | File X DirectX dalam format biner |
| [ZIP](#ZIP) | Arsip Zip yang berisi format file 3d lainnya. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | Buat opsi muat default untuk format file ini |
| [createSaveOptions()](#createSaveOptions--) | Buat opsi simpan default untuk format file ini |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | Deteksi format file dari aliran data, nama file bersifat opsional untuk menebak tipe yang tidak memiliki header khusus. |
| [detect(String fileName)](#detect-java.lang.String-) | Deteksi format file dari nama file, file harus dapat dibaca sehingga Aspose.3D dapat mendeteksi format file melalui header file. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | Mendapatkan apakah Aspose.3D mendukung ekspor adegan ke format file saat ini. |
| [getCanImport()](#getCanImport--) | Mendapatkan apakah Aspose.3D mendukung impor adegan dari format file saat ini. |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | Mendapatkan tipe konten format file |
| [getExtension()](#getExtension--) | Mendapatkan nama ekstensi tipe ini. |
| [getExtensions()](#getExtensions--) | Mendapatkan nama-nama ekstensi tipe ini. |
| [getFileFormatType()](#getFileFormatType--) | Mendapatkan tipe format file |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | Mendapatkan format file yang disukai dari nama ekstensi file. Nama ekstensi harus dimulai dengan titik ('.'). |
| [getFormats()](#getFormats--) | Akses ke semua format yang didukung |
| [getVersion()](#getVersion--) | Mendapatkan versi format file |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Format menjadi string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


Format file manufaktur aditif

### ASE {#ASE}
```
public static final FileFormat ASE
```


Format ASCII Scene Exporter milik 3D Studio Max.

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Format Web Aspose.3D.

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Format file 3D milik Blender

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Format file Collada

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


Format file milik 3D Studio

### DRACO {#DRACO}
```
public static final DracoFormat DRACO
```


Google Draco Mesh

### DXF {#DXF}
```
public static final FileFormat DXF
```


AutoCAD DXF

### FBX6100ASCII {#FBX6100ASCII}
```
public static final FileFormat FBX6100ASCII
```


Format file FBX ASCII, dengan versi 6.1.0

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


Format file FBX Biner, dengan versi 6.1.0

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


Format file FBX ASCII, dengan versi 7.2.0

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


Format file FBX Biner, dengan versi 7.2.0

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


Format file FBX ASCII, dengan versi 7.3.0

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


Format file FBX Biner, dengan versi 7.3.0

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


Format file FBX ASCII, dengan versi 7.4.0

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


Format file FBX Biner, dengan versi 7.4.0

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


Format file FBX ASCII, dengan versi 7.5.0

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Format file FBX Biner, dengan versi 7.5.0

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


Format file FBX ASCII, dengan versi 7.6.0

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Format file FBX Biner, dengan versi 7.6.0

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


Format file FBX ASCII, dengan versi 7.7.0

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Format file FBX Biner, dengan versi 7.7.0

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


glTF milik Khronos Group

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


glTF versi 2.0 milik Khronos Group

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


glTF versi 2.0 milik Khronos Group

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


glTF milik Khronos Group dalam format Biner

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


File HTML5

### IFC {#IFC}
```
public static final FileFormat IFC
```


Model data ISO 16739-1 Industry Foundation Classes.

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya dalam format ASCII

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya dalam format Biner

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Format Manufaktur 3D Microsoft

### PCD {#PCD}
```
public static final FileFormat PCD
```


File PCL Point Cloud Data dalam mode ASCII

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


File PCL Point Cloud Data dalam mode Biner

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Portable Document Format milik Adobe

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Polygon File Format atau Stanford Triangle Format

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


Model AVEVA Plant Design Management System dalam format biner

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


Model AVEVA Plant Design Management System dalam format teks

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


File JT Siemens Versi 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


File JT Siemens Versi 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


Format file STL ASCII

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Format file STL Biner

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Format file Universal3D

### USD {#USD}
```
public static final FileFormat USD
```


Deskripsi Adegan Universal

### USDA {#USDA}
```
public static final FileFormat USDA
```


Deskripsi Adegan Universal dalam format ASCII.

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


Deskripsi Adegan Universal Terkompresi

### VRML {#VRML}
```
public static final FileFormat VRML
```


Bahasa Pemodelan Realitas Virtual

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Format file Obj milik Wavefront

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


File awan titik Xyz

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


File X DirectX dalam format biner

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


File X DirectX dalam format biner

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


Arsip Zip yang berisi format file 3d lainnya.

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


Buat opsi muat default untuk format file ini

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


Buat opsi simpan default untuk format file ini

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### detect(Stream stream, String fileName) {#detect-com.aspose.threed.Stream-java.lang.String-}
```
public static FileFormat detect(Stream stream, String fileName)
```


Deteksi format file dari aliran data, nama file bersifat opsional untuk menebak tipe yang tidak memiliki header khusus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Aliran yang berisi data untuk dideteksi |
| fileName | java.lang.String | Nama file asli data, digunakan sebagai petunjuk. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


Deteksi format file dari nama file, file harus dapat dibaca sehingga Aspose.3D dapat mendeteksi format file melalui header file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Jalur ke file untuk mendeteksi format file. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


Mendapatkan apakah Aspose.3D mendukung ekspor adegan ke format file saat ini.

**Returns:**
boolean - apakah Aspose.3D mendukung ekspor adegan ke format file saat ini. **Contoh:** Kode berikut menunjukkan cara memeriksa apakah ekspor ke format yang ditentukan didukung.

```
var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     if (format.getCanExport())
         System.out.printf("Can export to %s", outputFormat);
```
### getCanImport() {#getCanImport--}
```
public boolean getCanImport()
```


Mendapatkan apakah Aspose.3D mendukung impor adegan dari format file saat ini.

**Returns:**
boolean - apakah Aspose.3D mendukung impor adegan dari format file saat ini. **Contoh:** Kode berikut menunjukkan cara memeriksa apakah impor dari format yang ditentukan didukung.

```
var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     if (format.getCanImport())
         System.out.printf("Can import from %s", outputFormat);
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentType() {#getContentType--}
```
public FileContentType getContentType()
```


Mendapatkan tipe konten format file

**Returns:**
[FileContentType](../../com.aspose.threed/filecontenttype) - file format content type **Example:**

```
var format = FileFormat.MAYA_BINARY;
     if (format.getContentType() == FileContentType.BINARY)
         System.out.printf("%s is binary format", format);
     else
         System.out.printf("%s is text-based format", format);
```
### getExtension() {#getExtension--}
```
public String getExtension()
```


Mendapatkan nama ekstensi tipe ini.

**Returns:**
java.lang.String - nama ekstensi tipe ini. **Contoh:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


Mendapatkan nama-nama ekstensi tipe ini.

**Returns:**
java.lang.String[] - nama-nama ekstensi tipe ini.
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


Mendapatkan tipe format file

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


Mendapatkan format file yang disukai dari nama ekstensi file. Nama ekstensi harus dimulai dengan titik ('.').

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| extensionName | java.lang.String | Nama ekstensi dimulai dengan '.' untuk kueri. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - Instance of [FileFormat](../../com.aspose.threed/fileformat), otherwise null returned. **Example:** The following code shows how to save scene to memory using specified format

```
Scene scene = new Scene(new Box());
     var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     var output = new ByteArrayOutputStream();
     scene.save(output);
```
### getFormats() {#getFormats--}
```
public static List<FileFormat> getFormats()
```


Akses ke semua format yang didukung

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - Akses ke semua format yang didukung
### getVersion() {#getVersion--}
```
public Version getVersion()
```


Mendapatkan versi format file

**Returns:**
[Version](../../com.aspose.threed/version) - file format version
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Format menjadi string

**Returns:**
java.lang.String - String objek
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

