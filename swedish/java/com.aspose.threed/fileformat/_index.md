---
title: Filformat
second_title: Aspose.3D for Java API-referens
description: Filformatdefinition
type: docs
weight: 64
url: /sv/java/com.aspose.threed/fileformat/
---

**Inheritance:**
java.lang.Object
```
public class FileFormat
```

Filformatdefinition
## Fält

| Fält | Beskrivning |
| --- | --- |
| [AMF](#AMF) | Additiv tillverkningsfilformat |
| [ASE](#ASE) | 3D Studio Maxs ASCII‑scenexportformat. |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Aspose.3D Web-format. |
| [BLENDER](#BLENDER) | Blenders 3D‑filformat |
| [COLLADA](#COLLADA) | Collada‑filformat |
| [DISCREET3DS](#DISCREET3DS) | 3D Studios filformat |
| [DRACO](#DRACO) | Google Draco Mesh |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | ASCII FBX‑filformat, med version 6.1.0 |
| [FBX6100_BINARY](#FBX6100-BINARY) | Binärt FBX‑filformat, med version 6.1.0 |
| [FBX7200ASCII](#FBX7200ASCII) | ASCII FBX‑filformat, med version 7.2.0 |
| [FBX7200_BINARY](#FBX7200-BINARY) | Binärt FBX‑filformat, med version 7.2.0 |
| [FBX7300ASCII](#FBX7300ASCII) | ASCII FBX‑filformat, med version 7.3.0 |
| [FBX7300_BINARY](#FBX7300-BINARY) | Binärt FBX‑filformat, med version 7.3.0 |
| [FBX7400ASCII](#FBX7400ASCII) | ASCII FBX‑filformat, med version 7.4.0 |
| [FBX7400_BINARY](#FBX7400-BINARY) | Binärt FBX‑filformat, med version 7.4.0 |
| [FBX7500ASCII](#FBX7500ASCII) | ASCII FBX-filformat, med version 7.5.0 |
| [FBX7500_BINARY](#FBX7500-BINARY) | Binärt FBX-filformat, med version 7.5.0 |
| [FBX7600ASCII](#FBX7600ASCII) | ASCII FBX-filformat, med version 7.6.0 |
| [FBX7600_BINARY](#FBX7600-BINARY) | Binärt FBX-filformat, med version 7.6.0 |
| [FBX7700ASCII](#FBX7700ASCII) | ASCII FBX-filformat, med version 7.7.0 |
| [FBX7700_BINARY](#FBX7700-BINARY) | Binärt FBX-filformat, med version 7.7.0 |
| [GLTF](#GLTF) | Khronos Groups glTF |
| [GLTF2](#GLTF2) | Khronos Groups glTF version 2.0 |
| [GLTF2_BINARY](#GLTF2-BINARY) | Khronos Groups glTF version 2.0 |
| [GLTF_BINARY](#GLTF-BINARY) | Khronos Groups glTF i binärt format |
| [HTML5](#HTML5) | HTML5-fil |
| [IFC](#IFC) | ISO 16739-1 Industry Foundation Classes datamodell. |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya i ASCII-format |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya i binärt format |
| [MICROSOFT3MF](#MICROSOFT3MF) | Microsoft 3D Manufacturing Format |
| [PCD](#PCD) | PCL Point Cloud Data-fil i ASCII-läge |
| [PCD_BINARY](#PCD-BINARY) | PCL Point Cloud Data-fil i binärt läge |
| [PDF](#PDF) | Adobes Portable Document Format |
| [PLY](#PLY) | Polygon File Format eller Stanford Triangle Format |
| [RVM_BINARY](#RVM-BINARY) | AVEVA Plant Design Management System-modell i binärt format |
| [RVM_TEXT](#RVM-TEXT) | AVEVA Plant Design Management System-modell i textformat |
| [SIEMENSJT8](#SIEMENSJT8) | Siemens JT-fil version 8 |
| [SIEMENSJT9](#SIEMENSJT9) | Siemens JT-fil version 9 |
| [STLASCII](#STLASCII) | ASCII STL-filformat |
| [STL_BINARY](#STL-BINARY) | Binärt STL-filformat |
| [UNIVERSAL3D](#UNIVERSAL3D) | Universal3D-filformat |
| [USD](#USD) | Universell scenbeskrivning |
| [USDA](#USDA) | Universell scenbeskrivning i ASCII-format. |
| [USDZ](#USDZ) | Komprimerad universell scenbeskrivning |
| [VRML](#VRML) | Det Virtual Reality Modeling Language |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Wavefronts Obj-filformat |
| [XYZ](#XYZ) | Xyz-punktmolnfil |
| [X_BINARY](#X-BINARY) | DirectX X File i binärt format |
| [X_TEXT](#X-TEXT) | DirectX X File i binärt format |
| [ZIP](#ZIP) | Zip-arkiv som innehåller andra 3D-filformat. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | Skapa standardläsalternativ för detta filformat |
| [createSaveOptions()](#createSaveOptions--) | Skapa standardsparalternativ för detta filformat |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | Detektera filformatet från datastream, filnamn är valfritt för att gissa typer som saknar magisk header. |
| [detect(String fileName)](#detect-java.lang.String-) | Detektera filformatet från filnamn, filen måste vara läsbar så att Aspose.3D kan detektera filformatet via filhuvud. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | Hämtar om Aspose.3D stöder export av scen till aktuellt filformat. |
| [getCanImport()](#getCanImport--) | Hämtar om Aspose.3D stöder import av scen från aktuellt filformat. |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | Hämtar filformatets innehållstyp |
| [getExtension()](#getExtension--) | Hämtar filtilläggets namn för denna typ. |
| [getExtensions()](#getExtensions--) | Hämtar filtilläggets namn för den här typen. |
| [getFileFormatType()](#getFileFormatType--) | Hämtar filformatstyp |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | Hämtar det föredragna filformatet från filtilläggets namn. Filtilläggets namn bör börja med en punkt ('.'). |
| [getFormats()](#getFormats--) | Tillgång till alla stödjade format |
| [getVersion()](#getVersion--) | Hämtar filformatversion |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Format till sträng |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


Additiv tillverkningsfilformat

### ASE {#ASE}
```
public static final FileFormat ASE
```


3D Studio Maxs ASCII‑scenexportformat.

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Aspose.3D Web-format.

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Blenders 3D‑filformat

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Collada‑filformat

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


3D Studios filformat

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


ASCII FBX‑filformat, med version 6.1.0

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


Binärt FBX‑filformat, med version 6.1.0

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


ASCII FBX‑filformat, med version 7.2.0

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


Binärt FBX‑filformat, med version 7.2.0

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


ASCII FBX‑filformat, med version 7.3.0

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


Binärt FBX‑filformat, med version 7.3.0

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


ASCII FBX‑filformat, med version 7.4.0

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


Binärt FBX‑filformat, med version 7.4.0

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


ASCII FBX-filformat, med version 7.5.0

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Binärt FBX-filformat, med version 7.5.0

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


ASCII FBX-filformat, med version 7.6.0

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Binärt FBX-filformat, med version 7.6.0

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


ASCII FBX-filformat, med version 7.7.0

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Binärt FBX-filformat, med version 7.7.0

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


Khronos Groups glTF

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


Khronos Groups glTF version 2.0

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


Khronos Groups glTF version 2.0

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


Khronos Groups glTF i binärt format

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


HTML5-fil

### IFC {#IFC}
```
public static final FileFormat IFC
```


ISO 16739-1 Industry Foundation Classes datamodell.

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya i ASCII-format

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya i binärt format

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Microsoft 3D Manufacturing Format

### PCD {#PCD}
```
public static final FileFormat PCD
```


PCL Point Cloud Data-fil i ASCII-läge

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


PCL Point Cloud Data-fil i binärt läge

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Adobes Portable Document Format

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Polygon File Format eller Stanford Triangle Format

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


AVEVA Plant Design Management System-modell i binärt format

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


AVEVA Plant Design Management System-modell i textformat

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


Siemens JT-fil version 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


Siemens JT-fil version 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


ASCII STL-filformat

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Binärt STL-filformat

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Universal3D-filformat

### USD {#USD}
```
public static final FileFormat USD
```


Universell scenbeskrivning

### USDA {#USDA}
```
public static final FileFormat USDA
```


Universell scenbeskrivning i ASCII-format.

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


Komprimerad universell scenbeskrivning

### VRML {#VRML}
```
public static final FileFormat VRML
```


Det Virtual Reality Modeling Language

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Wavefronts Obj-filformat

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


Xyz-punktmolnfil

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


DirectX X File i binärt format

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


DirectX X File i binärt format

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


Zip-arkiv som innehåller andra 3D-filformat.

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


Skapa standardläsalternativ för detta filformat

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


Skapa standardsparalternativ för detta filformat

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### detect(Stream stream, String fileName) {#detect-com.aspose.threed.Stream-java.lang.String-}
```
public static FileFormat detect(Stream stream, String fileName)
```


Detektera filformatet från datastream, filnamn är valfritt för att gissa typer som saknar magisk header.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ström som innehåller data att detektera |
| fileName | java.lang.String | Ursprungligt filnamn för data, används som ledtråd. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


Detektera filformatet från filnamn, filen måste vara läsbar så att Aspose.3D kan detektera filformatet via filhuvud.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Sökväg till filen för att detektera filformat. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


Hämtar om Aspose.3D stöder export av scen till aktuellt filformat.

**Returns:**
boolean - om Aspose.3D stödjer export av scen till aktuellt filformat. **Example:** Följande kod visar hur man kontrollerar om export till angivet format stöds.

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


Hämtar om Aspose.3D stöder import av scen från aktuellt filformat.

**Returns:**
boolean - om Aspose.3D stödjer import av scen från aktuellt filformat. **Example:** Följande kod visar hur man kontrollerar om import från angivet format stöds.

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


Hämtar filformatets innehållstyp

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


Hämtar filtilläggets namn för denna typ.

**Returns:**
java.lang.String - filnamnstillägget för denna typ. **Example:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


Hämtar filtilläggets namn för den här typen.

**Returns:**
java.lang.String[] - filnamnstilläggen för denna typ.
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


Hämtar filformatstyp

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


Hämtar det föredragna filformatet från filtilläggets namn. Filtilläggets namn bör börja med en punkt ('.').

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| extensionName | java.lang.String | Filnamnstillägget börjar med '.' för att sökas. |

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


Tillgång till alla stödjade format

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - Åtkomst till alla stödjade format
### getVersion() {#getVersion--}
```
public Version getVersion()
```


Hämtar filformatversion

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


Format till sträng

**Returns:**
java.lang.String - Objektsträng
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

