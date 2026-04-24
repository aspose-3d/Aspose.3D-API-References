---
title: PlyFormat
second_title: Aspose.3D for Java API-referentie
description: Het PLY-formaat.
type: docs
weight: 129
url: /nl/java/com.aspose.threed/plyformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class PlyFormat extends FileFormat
```

Het PLY‑formaat. **Example:** De volgende code laat zien hoe een mesh uit een PLY‑bestand te decoderen:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [AMF](#AMF) | Bestandsformaat voor additive manufacturing |
| [ASE](#ASE) | ASCII-scène-exportformaat van 3D Studio Max. |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Aspose.3D Web-formaat. |
| [BLENDER](#BLENDER) | 3D-bestandsformaat van Blender |
| [COLLADA](#COLLADA) | Collada-bestandsformaat |
| [DISCREET3DS](#DISCREET3DS) | Bestandsformaat van 3D Studio |
| [DRACO](#DRACO) | Google Draco Mesh |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | ASCII FBX-bestandsformaat, versie 6.1.0 |
| [FBX6100_BINARY](#FBX6100-BINARY) | Binaire FBX-bestandsformaat, versie 6.1.0 |
| [FBX7200ASCII](#FBX7200ASCII) | ASCII FBX-bestandsformaat, versie 7.2.0 |
| [FBX7200_BINARY](#FBX7200-BINARY) | Binaire FBX-bestandsformaat, versie 7.2.0 |
| [FBX7300ASCII](#FBX7300ASCII) | ASCII FBX-bestandsformaat, versie 7.3.0 |
| [FBX7300_BINARY](#FBX7300-BINARY) | Binaire FBX-bestandsformaat, versie 7.3.0 |
| [FBX7400ASCII](#FBX7400ASCII) | ASCII FBX-bestandsformaat, versie 7.4.0 |
| [FBX7400_BINARY](#FBX7400-BINARY) | Binaire FBX-bestandsformaat, versie 7.4.0 |
| [FBX7500ASCII](#FBX7500ASCII) | ASCII FBX-bestandsformaat, met versie 7.5.0 |
| [FBX7500_BINARY](#FBX7500-BINARY) | Binair FBX-bestandsformaat, met versie 7.5.0 |
| [FBX7600ASCII](#FBX7600ASCII) | ASCII FBX-bestandsformaat, met versie 7.6.0 |
| [FBX7600_BINARY](#FBX7600-BINARY) | Binair FBX-bestandsformaat, met versie 7.6.0 |
| [FBX7700ASCII](#FBX7700ASCII) | ASCII FBX-bestandsformaat, met versie 7.7.0 |
| [FBX7700_BINARY](#FBX7700-BINARY) | Binair FBX-bestandsformaat, met versie 7.7.0 |
| [GLTF](#GLTF) | glTF van de Khronos Group |
| [GLTF2](#GLTF2) | glTF versie 2.0 van de Khronos Group |
| [GLTF2_BINARY](#GLTF2-BINARY) | glTF versie 2.0 van de Khronos Group |
| [GLTF_BINARY](#GLTF-BINARY) | glTF van de Khronos Group in binair formaat |
| [HTML5](#HTML5) | HTML5-bestand |
| [IFC](#IFC) | ISO 16739-1 Industry Foundation Classes datamodel. |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya in ASCII-formaat |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya in binair formaat |
| [MICROSOFT3MF](#MICROSOFT3MF) | Microsoft 3D Manufacturing-formaat |
| [PCD](#PCD) | PCL Point Cloud Data-bestand in ASCII-modus |
| [PCD_BINARY](#PCD-BINARY) | PCL Point Cloud Data-bestand in binair modus |
| [PDF](#PDF) | Portable Document Format van Adobe |
| [PLY](#PLY) | Polygon File Format of Stanford Triangle Format |
| [RVM_BINARY](#RVM-BINARY) | AVEVA Plant Design Management System-model in binair formaat |
| [RVM_TEXT](#RVM-TEXT) | AVEVA Plant Design Management System-model in tekstformaat |
| [SIEMENSJT8](#SIEMENSJT8) | Siemens JT-bestand versie 8 |
| [SIEMENSJT9](#SIEMENSJT9) | Siemens JT-bestand versie 9 |
| [STLASCII](#STLASCII) | ASCII STL-bestandsformaat |
| [STL_BINARY](#STL-BINARY) | Binair STL-bestandsformaat |
| [UNIVERSAL3D](#UNIVERSAL3D) | Universal3D-bestandsformaat |
| [USD](#USD) | Universele Scènebeschrijving |
| [USDA](#USDA) | Universele Scènebeschrijving in ASCII-indeling. |
| [USDZ](#USDZ) | Gecomprimeerde Universele Scènebeschrijving |
| [VRML](#VRML) | De Virtual Reality Modeling Language |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Wavefront's Obj-bestandsformaat |
| [XYZ](#XYZ) | Xyz-puntwolkbestand |
| [X_BINARY](#X-BINARY) | DirectX X-bestand in binaire indeling |
| [X_TEXT](#X-TEXT) | DirectX X-bestand in binaire indeling |
| [ZIP](#ZIP) | Zip-archief dat andere 3D-bestandsformaten bevat. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | Maak standaard laadopties voor dit bestandsformaat |
| [createSaveOptions()](#createSaveOptions--) | Maak standaard opslaanopties voor dit bestandsformaat |
| [decode(Stream stream)](#decode-com.aspose.threed.Stream-) | Decodeer een puntwolk of mesh uit de opgegeven stream. |
| [decode(Stream stream, PlyLoadOptions opt)](#decode-com.aspose.threed.Stream-com.aspose.threed.PlyLoadOptions-) | Decodeer een puntwolk of mesh uit de opgegeven stream. |
| [decode(String fileName)](#decode-java.lang.String-) | Decodeer een puntwolk of mesh uit de opgegeven stream. |
| [decode(String fileName, PlyLoadOptions opt)](#decode-java.lang.String-com.aspose.threed.PlyLoadOptions-) | Decodeer een puntwolk of mesh uit de opgegeven stream. |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | Detecteer het bestandsformaat vanuit datastroom, bestandsnaam is optioneel voor het raden van typen die geen magic header hebben. |
| [detect(String fileName)](#detect-java.lang.String-) | Detecteer het bestandsformaat vanuit bestandsnaam, bestand moet leesbaar zijn zodat Aspose.3D het bestandsformaat via de bestandsheader kan detecteren. |
| [encode(Entity entity, Stream stream)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-) | Encodeer de entiteit en sla het resultaat op in de stream. |
| [encode(Entity entity, Stream stream, PlySaveOptions opt)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.PlySaveOptions-) | Encodeer de entiteit en sla het resultaat op in de stream. |
| [encode(Entity entity, String fileName)](#encode-com.aspose.threed.Entity-java.lang.String-) | Encodeer de entiteit en sla het resultaat op in een extern bestand. |
| [encode(Entity entity, String fileName, PlySaveOptions opt)](#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.PlySaveOptions-) | Encodeer de entiteit en sla het resultaat op in een extern bestand. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | Geeft aan of Aspose.3D export van scène naar het huidige bestandsformaat ondersteunt. |
| [getCanImport()](#getCanImport--) | Geeft aan of Aspose.3D import van scène vanuit het huidige bestandsformaat ondersteunt. |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | Haalt het contenttype van het bestandsformaat op. |
| [getExtension()](#getExtension--) | Haalt de extensienaam van dit type op. |
| [getExtensions()](#getExtensions--) | Haalt de extensienamen van dit type op. |
| [getFileFormatType()](#getFileFormatType--) | Haalt het bestandsformaattype op. |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | Haalt het voorkeursbestandsformaat op basis van de extensienaam. De extensienaam moet beginnen met een punt ('.'). |
| [getFormats()](#getFormats--) | Toegang tot alle ondersteunde formaten |
| [getVersion()](#getVersion--) | Haalt de versie van het bestandsformaat op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Formaten naar string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


Bestandsformaat voor additive manufacturing

### ASE {#ASE}
```
public static final FileFormat ASE
```


ASCII-scène-exportformaat van 3D Studio Max.

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Aspose.3D Web-formaat.

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


3D-bestandsformaat van Blender

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Collada-bestandsformaat

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


Bestandsformaat van 3D Studio

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


ASCII FBX-bestandsformaat, versie 6.1.0

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


Binaire FBX-bestandsformaat, versie 6.1.0

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


ASCII FBX-bestandsformaat, versie 7.2.0

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


Binaire FBX-bestandsformaat, versie 7.2.0

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


ASCII FBX-bestandsformaat, versie 7.3.0

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


Binaire FBX-bestandsformaat, versie 7.3.0

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


ASCII FBX-bestandsformaat, versie 7.4.0

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


Binaire FBX-bestandsformaat, versie 7.4.0

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


ASCII FBX-bestandsformaat, met versie 7.5.0

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Binair FBX-bestandsformaat, met versie 7.5.0

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


ASCII FBX-bestandsformaat, met versie 7.6.0

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Binair FBX-bestandsformaat, met versie 7.6.0

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


ASCII FBX-bestandsformaat, met versie 7.7.0

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Binair FBX-bestandsformaat, met versie 7.7.0

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


glTF van de Khronos Group

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


glTF versie 2.0 van de Khronos Group

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


glTF versie 2.0 van de Khronos Group

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


glTF van de Khronos Group in binair formaat

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


HTML5-bestand

### IFC {#IFC}
```
public static final FileFormat IFC
```


ISO 16739-1 Industry Foundation Classes datamodel.

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya in ASCII-formaat

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya in binair formaat

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Microsoft 3D Manufacturing-formaat

### PCD {#PCD}
```
public static final FileFormat PCD
```


PCL Point Cloud Data-bestand in ASCII-modus

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


PCL Point Cloud Data-bestand in binair modus

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Portable Document Format van Adobe

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Polygon File Format of Stanford Triangle Format

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


AVEVA Plant Design Management System-model in binair formaat

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


AVEVA Plant Design Management System-model in tekstformaat

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


Siemens JT-bestand versie 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


Siemens JT-bestand versie 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


ASCII STL-bestandsformaat

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Binair STL-bestandsformaat

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Universal3D-bestandsformaat

### USD {#USD}
```
public static final FileFormat USD
```


Universele Scènebeschrijving

### USDA {#USDA}
```
public static final FileFormat USDA
```


Universele Scènebeschrijving in ASCII-indeling.

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


Gecomprimeerde Universele Scènebeschrijving

### VRML {#VRML}
```
public static final FileFormat VRML
```


De Virtual Reality Modeling Language

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Wavefront's Obj-bestandsformaat

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


Xyz-puntwolkbestand

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


DirectX X-bestand in binaire indeling

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


DirectX X-bestand in binaire indeling

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


Zip-archief dat andere 3D-bestandsformaten bevat.

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


Maak standaard laadopties voor dit bestandsformaat

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


Maak standaard opslaanopties voor dit bestandsformaat

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### decode(Stream stream) {#decode-com.aspose.threed.Stream-}
```
public Geometry decode(Stream stream)
```


Decodeer een puntwolk of mesh uit de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | De invoerstroom |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance **Example:** The following code shows how to decode a mesh from a PLY file:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
### decode(Stream stream, PlyLoadOptions opt) {#decode-com.aspose.threed.Stream-com.aspose.threed.PlyLoadOptions-}
```
public Geometry decode(Stream stream, PlyLoadOptions opt)
```


Decodeer een puntwolk of mesh uit de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | De invoerstroom |
| opt | [PlyLoadOptions](../../com.aspose.threed/plyloadoptions) | De laadoptie van het PLY-formaat |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance **Example:** The following code shows how to decode a mesh from a PLY file:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
### decode(String fileName) {#decode-java.lang.String-}
```
public Geometry decode(String fileName)
```


Decodeer een puntwolk of mesh uit de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De invoerstroom |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance **Example:** The following code shows how to decode a mesh from a PLY file:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
### decode(String fileName, PlyLoadOptions opt) {#decode-java.lang.String-com.aspose.threed.PlyLoadOptions-}
```
public Geometry decode(String fileName, PlyLoadOptions opt)
```


Decodeer een puntwolk of mesh uit de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De invoerstroom |
| opt | [PlyLoadOptions](../../com.aspose.threed/plyloadoptions) | De laadoptie van het PLY-formaat |

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - A [Mesh](../../com.aspose.threed/mesh) or [PointCloud](../../com.aspose.threed/pointcloud) instance **Example:** The following code shows how to decode a mesh from a PLY file:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
### detect(Stream stream, String fileName) {#detect-com.aspose.threed.Stream-java.lang.String-}
```
public static FileFormat detect(Stream stream, String fileName)
```


Detecteer het bestandsformaat vanuit datastroom, bestandsnaam is optioneel voor het raden van typen die geen magic header hebben.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stroom met gegevens om te detecteren |
| fileName | java.lang.String | Originele bestandsnaam van de gegevens, gebruikt als hint. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


Detecteer het bestandsformaat vanuit bestandsnaam, bestand moet leesbaar zijn zodat Aspose.3D het bestandsformaat via de bestandsheader kan detecteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Pad naar het bestand om het bestandsformaat te detecteren. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### encode(Entity entity, Stream stream) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-}
```
public void encode(Entity entity, Stream stream)
```


Encodeer de entiteit en sla het resultaat op in de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | De entiteit om te coderen |
|  | stream | [Stream](../../com.aspose.threed/stream) | De stroom om naar te schrijven, deze methode sluit deze stroom niet **Example:** De volgende code toont hoe een mesh te coderen naar een PLY‑bestand: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, Stream stream, PlySaveOptions opt) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.PlySaveOptions-}
```
public void encode(Entity entity, Stream stream, PlySaveOptions opt)
```


Encodeer de entiteit en sla het resultaat op in de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | De entiteit om te coderen |
| stream | [Stream](../../com.aspose.threed/stream) | De stroom om naar te schrijven, deze methode sluit deze stroom niet |
|  | opt | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) | Opslagopties **Example:** De volgende code toont hoe een mesh te coderen naar een PLY‑bestand: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, String fileName) {#encode-com.aspose.threed.Entity-java.lang.String-}
```
public void encode(Entity entity, String fileName)
```


Encodeer de entiteit en sla het resultaat op in een extern bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | De entiteit om te coderen |
|  | fileName | java.lang.String | Het bestand om naar te schrijven **Example:** De volgende code toont hoe een mesh te coderen naar een PLY‑bestand: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, String fileName, PlySaveOptions opt) {#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.PlySaveOptions-}
```
public void encode(Entity entity, String fileName, PlySaveOptions opt)
```


Encodeer de entiteit en sla het resultaat op in een extern bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | De entiteit om te coderen |
| fileName | java.lang.String | Het bestand om naar te schrijven |
|  | opt | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) | Opslagopties **Example:** De volgende code toont hoe een mesh te coderen naar een PLY‑bestand: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


Geeft aan of Aspose.3D export van scène naar het huidige bestandsformaat ondersteunt.

**Returns:**
boolean - of Aspose.3D ondersteuning biedt voor het exporteren van een scène naar het huidige bestandsformaat. **Voorbeeld:** De volgende code toont hoe te controleren of exporteren naar het opgegeven formaat wordt ondersteund.

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


Geeft aan of Aspose.3D import van scène vanuit het huidige bestandsformaat ondersteunt.

**Returns:**
boolean - of Aspose.3D ondersteuning biedt voor het importeren van een scène vanuit het huidige bestandsformaat. **Voorbeeld:** De volgende code toont hoe te controleren of importeren vanuit het opgegeven formaat wordt ondersteund.

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


Haalt het contenttype van het bestandsformaat op.

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


Haalt de extensienaam van dit type op.

**Returns:**
java.lang.String - de extensienaam van dit type. **Voorbeeld:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


Haalt de extensienamen van dit type op.

**Returns:**
java.lang.String[] - de extensienamen van dit type.
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


Haalt het bestandsformaattype op.

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


Haalt het voorkeursbestandsformaat op basis van de extensienaam. De extensienaam moet beginnen met een punt ('.').

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| extensionName | java.lang.String | De extensienaam begint met '.' om te zoeken. |

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


Toegang tot alle ondersteunde formaten

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - Toegang tot alle ondersteunde formaten
### getVersion() {#getVersion--}
```
public Version getVersion()
```


Haalt de versie van het bestandsformaat op.

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


Formaten naar string

**Returns:**
java.lang.String - Objecttekenreeks
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

