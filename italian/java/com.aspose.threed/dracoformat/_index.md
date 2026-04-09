---
title: DracoFormat
second_title: Aspose.3D for Java API Reference
description: Esempio di formato Google Draco         Il codice seguente mostra come codificare e decodificare una Mesh da/in un array di byte
type: docs
weight: 46
url: /it/java/com.aspose.threed/dracoformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class DracoFormat extends FileFormat
```

Formato Google Draco **Esempio:** Il codice seguente mostra come codificare e decodificare una Mesh da/a un array di byte:

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into Draco format
             byte[] draco = FileFormat.DRACO.encode(mesh);
             //decode mesh from Draco format
             Mesh decodedMesh = (Mesh)FileFormat.DRACO.decode(draco);
```
## Campi

| Campo | Descrizione |
| --- | --- |
| [AMF](#AMF) | Formato file per la produzione additiva |
| [ASE](#ASE) | Formato ASCII di esportazione scena di 3D Studio Max. |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Formato Web Aspose.3D. |
| [BLENDER](#BLENDER) | Formato 3D di Blender |
| [COLLADA](#COLLADA) | Formato file Collada |
| [DISCREET3DS](#DISCREET3DS) | Formato file di 3D Studio |
| [DRACO](#DRACO) | Google Draco Mesh |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | Formato file FBX ASCII, con versione 6.1.0 |
| [FBX6100_BINARY](#FBX6100-BINARY) | Formato file FBX binario, con versione 6.1.0 |
| [FBX7200ASCII](#FBX7200ASCII) | Formato file FBX ASCII, con versione 7.2.0 |
| [FBX7200_BINARY](#FBX7200-BINARY) | Formato file FBX binario, con versione 7.2.0 |
| [FBX7300ASCII](#FBX7300ASCII) | Formato file FBX ASCII, con versione 7.3.0 |
| [FBX7300_BINARY](#FBX7300-BINARY) | Formato file FBX binario, con versione 7.3.0 |
| [FBX7400ASCII](#FBX7400ASCII) | Formato file FBX ASCII, con versione 7.4.0 |
| [FBX7400_BINARY](#FBX7400-BINARY) | Formato file FBX binario, con versione 7.4.0 |
| [FBX7500ASCII](#FBX7500ASCII) | Formato file FBX ASCII, con versione 7.5.0 |
| [FBX7500_BINARY](#FBX7500-BINARY) | Formato file FBX binario, con versione 7.5.0 |
| [FBX7600ASCII](#FBX7600ASCII) | Formato file FBX ASCII, con versione 7.6.0 |
| [FBX7600_BINARY](#FBX7600-BINARY) | Formato file FBX binario, con versione 7.6.0 |
| [FBX7700ASCII](#FBX7700ASCII) | Formato file FBX ASCII, con versione 7.7.0 |
| [FBX7700_BINARY](#FBX7700-BINARY) | Formato file FBX binario, con versione 7.7.0 |
| [GLTF](#GLTF) | glTF del Khronos Group |
| [GLTF2](#GLTF2) | glTF del Khronos Group versione 2.0 |
| [GLTF2_BINARY](#GLTF2-BINARY) | glTF del Khronos Group versione 2.0 |
| [GLTF_BINARY](#GLTF-BINARY) | glTF del Khronos Group in formato binario |
| [HTML5](#HTML5) | File HTML5 |
| [IFC](#IFC) | Modello di dati ISO 16739-1 Industry Foundation Classes. |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya in formato ASCII |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya in formato binario |
| [MICROSOFT3MF](#MICROSOFT3MF) | Microsoft 3D Manufacturing Format |
| [PCD](#PCD) | File PCL Point Cloud Data in modalità ASCII |
| [PCD_BINARY](#PCD-BINARY) | File PCL Point Cloud Data in modalità binario |
| [PDF](#PDF) | Formato Portable Document di Adobe |
| [PLY](#PLY) | Polygon File Format o Stanford Triangle Format |
| [RVM_BINARY](#RVM-BINARY) | Modello AVEVA Plant Design Management System in formato binario |
| [RVM_TEXT](#RVM-TEXT) | Modello AVEVA Plant Design Management System in formato testo |
| [SIEMENSJT8](#SIEMENSJT8) | File JT Siemens versione 8 |
| [SIEMENSJT9](#SIEMENSJT9) | File JT Siemens versione 9 |
| [STLASCII](#STLASCII) | Formato file STL ASCII |
| [STL_BINARY](#STL-BINARY) | Formato file STL binario |
| [UNIVERSAL3D](#UNIVERSAL3D) | Formato file Universal3D |
| [USD](#USD) | Descrizione Universale della Scena |
| [USDA](#USDA) | Descrizione Universale della Scena in formato ASCII. |
| [USDZ](#USDZ) | Descrizione Universale della Scena compressa |
| [VRML](#VRML) | Il Linguaggio di Modellazione per la Realtà Virtuale |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Formato file Obj di Wavefront |
| [XYZ](#XYZ) | File nuvola di punti Xyz |
| [X_BINARY](#X-BINARY) | File X DirectX in formato binario |
| [X_TEXT](#X-TEXT) | File X DirectX in formato binario |
| [ZIP](#ZIP) | Archivio Zip che contiene altri formati di file 3d. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | Crea opzioni di caricamento predefinite per questo formato file |
| [createSaveOptions()](#createSaveOptions--) | Crea opzioni di salvataggio predefinite per questo formato file |
| [decode(byte[] data)](#decode-byte---) | Decodifica la nuvola di punti o la mesh dai dati in memoria |
| [decode(String fileName)](#decode-java.lang.String-) | Decodifica la nuvola di punti o la mesh dal nome file specificato |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | Rileva il formato file dallo stream di dati, il nome del file è opzionale per indovinare i tipi che non hanno intestazione magica. |
| [detect(String fileName)](#detect-java.lang.String-) | Rileva il formato file dal nome del file, il file deve essere leggibile affinché Aspose.3D possa rilevare il formato file tramite l'intestazione del file. |
| [encode(Entity entity)](#encode-com.aspose.threed.Entity-) | Codifica l'entità in dati grezzi Draco |
| [encode(Entity entity, DracoSaveOptions options)](#encode-com.aspose.threed.Entity-com.aspose.threed.DracoSaveOptions-) | Codifica l'entità in dati grezzi Draco |
| [encode(Entity entity, Stream stream)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-) | Codifica l'entità nello stream specificato |
| [encode(Entity entity, Stream stream, DracoSaveOptions options)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.DracoSaveOptions-) | Codifica l'entità nello stream specificato |
| [encode(Entity entity, String fileName)](#encode-com.aspose.threed.Entity-java.lang.String-) | Codifica l'entità nel file specificato |
| [encode(Entity entity, String fileName, DracoSaveOptions options)](#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.DracoSaveOptions-) | Codifica l'entità nel file specificato |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | Restituisce se Aspose.3D supporta l'esportazione della scena al formato file corrente. |
| [getCanImport()](#getCanImport--) | Restituisce se Aspose.3D supporta l'importazione della scena dal formato file corrente. |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | Restituisce il tipo di contenuto del formato file |
| [getExtension()](#getExtension--) | Restituisce il nome dell'estensione di questo tipo. |
| [getExtensions()](#getExtensions--) | Restituisce i nomi delle estensioni di questo tipo. |
| [getFileFormatType()](#getFileFormatType--) | Restituisce il tipo di formato file |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | Restituisce il formato file preferito dal nome dell'estensione del file. Il nome dell'estensione dovrebbe iniziare con un punto ('.'). |
| [getFormats()](#getFormats--) | Accesso a tutti i formati supportati |
| [getVersion()](#getVersion--) | Restituisce la versione del formato file |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Formati in stringa |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


Formato file per la produzione additiva

### ASE {#ASE}
```
public static final FileFormat ASE
```


Formato ASCII di esportazione scena di 3D Studio Max.

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Formato Web Aspose.3D.

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Formato 3D di Blender

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Formato file Collada

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


Formato file di 3D Studio

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


Formato file FBX ASCII, con versione 6.1.0

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


Formato file FBX binario, con versione 6.1.0

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


Formato file FBX ASCII, con versione 7.2.0

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


Formato file FBX binario, con versione 7.2.0

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


Formato file FBX ASCII, con versione 7.3.0

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


Formato file FBX binario, con versione 7.3.0

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


Formato file FBX ASCII, con versione 7.4.0

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


Formato file FBX binario, con versione 7.4.0

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


Formato file FBX ASCII, con versione 7.5.0

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Formato file FBX binario, con versione 7.5.0

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


Formato file FBX ASCII, con versione 7.6.0

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Formato file FBX binario, con versione 7.6.0

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


Formato file FBX ASCII, con versione 7.7.0

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Formato file FBX binario, con versione 7.7.0

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


glTF del Khronos Group

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


glTF del Khronos Group versione 2.0

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


glTF del Khronos Group versione 2.0

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


glTF del Khronos Group in formato binario

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


File HTML5

### IFC {#IFC}
```
public static final FileFormat IFC
```


Modello di dati ISO 16739-1 Industry Foundation Classes.

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya in formato ASCII

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya in formato binario

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Microsoft 3D Manufacturing Format

### PCD {#PCD}
```
public static final FileFormat PCD
```


File PCL Point Cloud Data in modalità ASCII

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


File PCL Point Cloud Data in modalità binario

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Formato Portable Document di Adobe

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Polygon File Format o Stanford Triangle Format

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


Modello AVEVA Plant Design Management System in formato binario

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


Modello AVEVA Plant Design Management System in formato testo

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


File JT Siemens versione 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


File JT Siemens versione 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


Formato file STL ASCII

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Formato file STL binario

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Formato file Universal3D

### USD {#USD}
```
public static final FileFormat USD
```


Descrizione Universale della Scena

### USDA {#USDA}
```
public static final FileFormat USDA
```


Descrizione Universale della Scena in formato ASCII.

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


Descrizione Universale della Scena compressa

### VRML {#VRML}
```
public static final FileFormat VRML
```


Il Linguaggio di Modellazione per la Realtà Virtuale

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Formato file Obj di Wavefront

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


File nuvola di punti Xyz

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


File X DirectX in formato binario

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


File X DirectX in formato binario

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


Archivio Zip che contiene altri formati di file 3d.

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


Crea opzioni di caricamento predefinite per questo formato file

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


Crea opzioni di salvataggio predefinite per questo formato file

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### decode(byte[] data) {#decode-byte---}
```
public Geometry decode(byte[] data)
```


Decodifica la nuvola di punti o la mesh dai dati in memoria

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I byte grezzi drc |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance depends on the content
### decode(String fileName) {#decode-java.lang.String-}
```
public Geometry decode(String fileName)
```


Decodifica la nuvola di punti o la mesh dal nome file specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Il nome file contiene il file drc |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance depends on the file content
### detect(Stream stream, String fileName) {#detect-com.aspose.threed.Stream-java.lang.String-}
```
public static FileFormat detect(Stream stream, String fileName)
```


Rileva il formato file dallo stream di dati, il nome del file è opzionale per indovinare i tipi che non hanno intestazione magica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream contenente dati da rilevare |
| fileName | java.lang.String | Nome file originale dei dati, usato come suggerimento. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


Rileva il formato file dal nome del file, il file deve essere leggibile affinché Aspose.3D possa rilevare il formato file tramite l'intestazione del file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Percorso al file per rilevare il formato file. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### encode(Entity entity) {#encode-com.aspose.threed.Entity-}
```
public byte[] encode(Entity entity)
```


Codifica l'entità in dati grezzi Draco

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | L'entità da codificare |

**Returns:**
byte[] - I dati draco codificati rappresentati in byte **Esempio:** Il codice seguente mostra come codificare e decodificare una Mesh da/in un array di byte:

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into Draco format
             byte[] draco = FileFormat.DRACO.encode(mesh);
             //decode mesh from Draco format
             Mesh decodedMesh = (Mesh)FileFormat.DRACO.decode(draco);
```
### encode(Entity entity, DracoSaveOptions options) {#encode-com.aspose.threed.Entity-com.aspose.threed.DracoSaveOptions-}
```
public byte[] encode(Entity entity, DracoSaveOptions options)
```


Codifica l'entità in dati grezzi Draco

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | L'entità da codificare |
| options | [DracoSaveOptions](../../com.aspose.threed/dracosaveoptions) | Opzioni extra per la codifica della nuvola di punti |

**Returns:**
byte[] - I dati draco codificati rappresentati in byte **Esempio:** Il codice seguente mostra come codificare e decodificare una Mesh da/in un array di byte:

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into Draco format
             byte[] draco = FileFormat.DRACO.encode(mesh);
             //decode mesh from Draco format
             Mesh decodedMesh = (Mesh)FileFormat.DRACO.decode(draco);
```
### encode(Entity entity, Stream stream) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-}
```
public void encode(Entity entity, Stream stream)
```


Codifica l'entità nello stream specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | L'entità da codificare |
| stream | [Stream](../../com.aspose.threed/stream) | Lo stream su cui verranno scritti i dati codificati |

### encode(Entity entity, Stream stream, DracoSaveOptions options) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.DracoSaveOptions-}
```
public void encode(Entity entity, Stream stream, DracoSaveOptions options)
```


Codifica l'entità nello stream specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | L'entità da codificare |
| stream | [Stream](../../com.aspose.threed/stream) | Lo stream su cui verranno scritti i dati codificati |
| options | [DracoSaveOptions](../../com.aspose.threed/dracosaveoptions) | Opzioni extra per la codifica della nuvola di punti |

### encode(Entity entity, String fileName) {#encode-com.aspose.threed.Entity-java.lang.String-}
```
public void encode(Entity entity, String fileName)
```


Codifica l'entità nel file specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | L'entità da codificare |
| fileName | java.lang.String | Il nome file da scrivere |

### encode(Entity entity, String fileName, DracoSaveOptions options) {#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.DracoSaveOptions-}
```
public void encode(Entity entity, String fileName, DracoSaveOptions options)
```


Codifica l'entità nel file specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | L'entità da codificare |
| fileName | java.lang.String | Il nome file da scrivere |
| options | [DracoSaveOptions](../../com.aspose.threed/dracosaveoptions) | Opzioni extra per la codifica della nuvola di punti |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


Restituisce se Aspose.3D supporta l'esportazione della scena al formato file corrente.

**Returns:**
boolean - se Aspose.3D supporta l'esportazione della scena nel formato file corrente. **Esempio:** Il codice seguente mostra come verificare se l'esportazione nel formato specificato è supportata.

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


Restituisce se Aspose.3D supporta l'importazione della scena dal formato file corrente.

**Returns:**
boolean - se Aspose.3D supporta l'importazione della scena dal formato file corrente. **Esempio:** Il codice seguente mostra come verificare se l'importazione dal formato specificato è supportata.

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


Restituisce il tipo di contenuto del formato file

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


Restituisce il nome dell'estensione di questo tipo.

**Returns:**
java.lang.String - il nome dell'estensione di questo tipo. **Esempio:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


Restituisce i nomi delle estensioni di questo tipo.

**Returns:**
java.lang.String[] - i nomi delle estensioni di questo tipo.
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


Restituisce il tipo di formato file

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


Restituisce il formato file preferito dal nome dell'estensione del file. Il nome dell'estensione dovrebbe iniziare con un punto ('.').

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| extensionName | java.lang.String | Il nome dell'estensione inizia con '.' per la query. |

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


Accesso a tutti i formati supportati

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - Accesso a tutti i formati supportati
### getVersion() {#getVersion--}
```
public Version getVersion()
```


Restituisce la versione del formato file

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


Formati in stringa

**Returns:**
java.lang.String - Stringa dell'oggetto
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

