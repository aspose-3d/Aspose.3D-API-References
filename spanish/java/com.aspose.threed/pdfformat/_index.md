---
title: PdfFormat
second_title: Referencia de API de Aspose.3D para Java
description: Ejemplo del Formato de Documento Portátil de Adobe         El siguiente código muestra cómo extraer todas las escenas 3D compatibles de un archivo PDF 3D y escribirlas en formato obj.
type: docs
weight: 123
url: /es/java/com.aspose.threed/pdfformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class PdfFormat extends FileFormat
```

Formato de Documento Portátil de Adobe **Example:** El siguiente código muestra cómo extraer todas las escenas 3D compatibles de un archivo PDF 3D y escribirlas en formato obj.

```
var scenes = FileFormat.PDF.extractScene("input.pdf");
             for(int i = 0; i < scenes.size(); i++)
             {
                 scenes.get(i).save("output-" + i + ".obj");
             }
```
## Campos

| Campo | Descripción |
| --- | --- |
| [AMF](#AMF) | Formato de archivo de fabricación aditiva |
| [ASE](#ASE) | Formato ASCII de exportador de escena de 3D Studio Max. |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Formato Web de Aspose.3D. |
| [BLENDER](#BLENDER) | Formato de archivo 3D de Blender |
| [COLLADA](#COLLADA) | Formato de archivo Collada |
| [DISCREET3DS](#DISCREET3DS) | Formato de archivo de 3D Studio |
| [DRACO](#DRACO) | Malla Draco de Google |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | Formato de archivo FBX ASCII, con versión 6.1.0 |
| [FBX6100_BINARY](#FBX6100-BINARY) | Formato de archivo FBX binario, con versión 6.1.0 |
| [FBX7200ASCII](#FBX7200ASCII) | Formato de archivo FBX ASCII, con versión 7.2.0 |
| [FBX7200_BINARY](#FBX7200-BINARY) | Formato de archivo FBX binario, con versión 7.2.0 |
| [FBX7300ASCII](#FBX7300ASCII) | Formato de archivo FBX ASCII, con versión 7.3.0 |
| [FBX7300_BINARY](#FBX7300-BINARY) | Formato de archivo FBX binario, con versión 7.3.0 |
| [FBX7400ASCII](#FBX7400ASCII) | Formato de archivo FBX ASCII, con versión 7.4.0 |
| [FBX7400_BINARY](#FBX7400-BINARY) | Formato de archivo FBX binario, con versión 7.4.0 |
| [FBX7500ASCII](#FBX7500ASCII) | Formato de archivo FBX ASCII, con versión 7.5.0 |
| [FBX7500_BINARY](#FBX7500-BINARY) | Formato de archivo FBX binario, con versión 7.5.0 |
| [FBX7600ASCII](#FBX7600ASCII) | Formato de archivo FBX ASCII, con versión 7.6.0 |
| [FBX7600_BINARY](#FBX7600-BINARY) | Formato de archivo FBX binario, con versión 7.6.0 |
| [FBX7700ASCII](#FBX7700ASCII) | Formato de archivo FBX ASCII, con versión 7.7.0 |
| [FBX7700_BINARY](#FBX7700-BINARY) | Formato de archivo FBX binario, con versión 7.7.0 |
| [GLTF](#GLTF) | glTF del Khronos Group |
| [GLTF2](#GLTF2) | glTF del Khronos Group versión 2.0 |
| [GLTF2_BINARY](#GLTF2-BINARY) | glTF del Khronos Group versión 2.0 |
| [GLTF_BINARY](#GLTF-BINARY) | glTF del Khronos Group en formato binario |
| [HTML5](#HTML5) | Archivo HTML5 |
| [IFC](#IFC) | Modelo de datos ISO 16739-1 Industry Foundation Classes. |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya en formato ASCII |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya en formato binario |
| [MICROSOFT3MF](#MICROSOFT3MF) | Formato de fabricación 3D de Microsoft |
| [PCD](#PCD) | Archivo PCL Point Cloud Data en modo ASCII |
| [PCD_BINARY](#PCD-BINARY) | Archivo PCL Point Cloud Data en modo binario |
| [PDF](#PDF) | Formato de documento portátil de Adobe |
| [PLY](#PLY) | Formato de archivo Polygon o Formato de triángulo Stanford |
| [RVM_BINARY](#RVM-BINARY) | Modelo del Sistema de Gestión de Diseño de Planta AVEVA en formato binario |
| [RVM_TEXT](#RVM-TEXT) | Modelo del Sistema de Gestión de Diseño de Planta AVEVA en formato de texto |
| [SIEMENSJT8](#SIEMENSJT8) | Archivo JT de Siemens versión 8 |
| [SIEMENSJT9](#SIEMENSJT9) | Archivo JT de Siemens versión 9 |
| [STLASCII](#STLASCII) | Formato de archivo STL ASCII |
| [STL_BINARY](#STL-BINARY) | Formato de archivo STL binario |
| [UNIVERSAL3D](#UNIVERSAL3D) | Formato de archivo Universal3D |
| [USD](#USD) | Descripción Universal de Escena |
| [USDA](#USDA) | Descripción Universal de Escena en formato ASCII. |
| [USDZ](#USDZ) | Descripción Universal de Escena comprimida |
| [VRML](#VRML) | El Lenguaje de Modelado de Realidad Virtual |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Formato de archivo Obj de Wavefront |
| [XYZ](#XYZ) | Archivo de nube de puntos Xyz |
| [X_BINARY](#X-BINARY) | Archivo X de DirectX en formato binario |
| [X_TEXT](#X-TEXT) | Archivo X de DirectX en formato binario |
| [ZIP](#ZIP) | Archivo Zip que contiene otros formatos de archivo 3d. |
## Métodos

| Método | Descripción |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | Crear opciones de carga predeterminadas para este formato de archivo |
| [createSaveOptions()](#createSaveOptions--) | Crear opciones de guardado predeterminadas para este formato de archivo |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | Detectar el formato de archivo a partir del flujo de datos, el nombre del archivo es opcional para adivinar tipos que no tienen encabezado mágico. |
| [detect(String fileName)](#detect-java.lang.String-) | Detectar el formato de archivo a partir del nombre del archivo, el archivo debe ser legible para que Aspose.3D pueda detectar el formato mediante el encabezado del archivo. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extract(Stream stream)](#extract-com.aspose.threed.Stream-) | Extraer contenido 3D sin procesar del flujo PDF. |
| [extract(Stream stream, byte[] password)](#extract-com.aspose.threed.Stream-byte---) | Extraer contenido 3D sin procesar del flujo PDF. |
| [extract(String fileName)](#extract-java.lang.String-) | Extraer contenido 3D sin procesar del archivo PDF. |
| [extract(String fileName, byte[] password)](#extract-java.lang.String-byte---) | Extraer contenido 3D sin procesar del archivo PDF. |
| [extractScene(Stream stream)](#extractScene-com.aspose.threed.Stream-) | Extraer contenido 3D sin procesar del flujo PDF. |
| [extractScene(Stream stream, byte[] password)](#extractScene-com.aspose.threed.Stream-byte---) | Extraer contenido 3D sin procesar del flujo PDF. |
| [extractScene(String fileName)](#extractScene-java.lang.String-) | Extraer escenas 3D del archivo PDF. |
| [extractScene(String fileName, byte[] password)](#extractScene-java.lang.String-byte---) | Extraer escenas 3D del archivo PDF. |
| [getCanExport()](#getCanExport--) | Obtiene si Aspose.3D admite la exportación de la escena al formato de archivo actual. |
| [getCanImport()](#getCanImport--) | Obtiene si Aspose.3D admite la importación de la escena desde el formato de archivo actual. |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | Obtiene el tipo de contenido del formato de archivo |
| [getExtension()](#getExtension--) | Obtiene el nombre de extensión de este tipo. |
| [getExtensions()](#getExtensions--) | Obtiene los nombres de extensión de este tipo. |
| [getFileFormatType()](#getFileFormatType--) | Obtiene el tipo de formato de archivo |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | Obtiene el formato de archivo preferido a partir del nombre de extensión del archivo. El nombre de extensión debe comenzar con un punto ('.'). |
| [getFormats()](#getFormats--) | Acceso a todos los formatos compatibles |
| [getVersion()](#getVersion--) | Obtiene la versión del formato de archivo |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Formatos a cadena |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


Formato de archivo de fabricación aditiva

### ASE {#ASE}
```
public static final FileFormat ASE
```


Formato ASCII de exportador de escena de 3D Studio Max.

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Formato Web de Aspose.3D.

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Formato de archivo 3D de Blender

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Formato de archivo Collada

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


Formato de archivo de 3D Studio

### DRACO {#DRACO}
```
public static final DracoFormat DRACO
```


Malla Draco de Google

### DXF {#DXF}
```
public static final FileFormat DXF
```


AutoCAD DXF

### FBX6100ASCII {#FBX6100ASCII}
```
public static final FileFormat FBX6100ASCII
```


Formato de archivo FBX ASCII, con versión 6.1.0

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


Formato de archivo FBX binario, con versión 6.1.0

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


Formato de archivo FBX ASCII, con versión 7.2.0

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


Formato de archivo FBX binario, con versión 7.2.0

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


Formato de archivo FBX ASCII, con versión 7.3.0

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


Formato de archivo FBX binario, con versión 7.3.0

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


Formato de archivo FBX ASCII, con versión 7.4.0

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


Formato de archivo FBX binario, con versión 7.4.0

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


Formato de archivo FBX ASCII, con versión 7.5.0

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Formato de archivo FBX binario, con versión 7.5.0

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


Formato de archivo FBX ASCII, con versión 7.6.0

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Formato de archivo FBX binario, con versión 7.6.0

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


Formato de archivo FBX ASCII, con versión 7.7.0

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Formato de archivo FBX binario, con versión 7.7.0

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


glTF del Khronos Group

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


glTF del Khronos Group versión 2.0

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


glTF del Khronos Group versión 2.0

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


glTF del Khronos Group en formato binario

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


Archivo HTML5

### IFC {#IFC}
```
public static final FileFormat IFC
```


Modelo de datos ISO 16739-1 Industry Foundation Classes.

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya en formato ASCII

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya en formato binario

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Formato de fabricación 3D de Microsoft

### PCD {#PCD}
```
public static final FileFormat PCD
```


Archivo PCL Point Cloud Data en modo ASCII

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


Archivo PCL Point Cloud Data en modo binario

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Formato de documento portátil de Adobe

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Formato de archivo Polygon o Formato de triángulo Stanford

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


Modelo del Sistema de Gestión de Diseño de Planta AVEVA en formato binario

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


Modelo del Sistema de Gestión de Diseño de Planta AVEVA en formato de texto

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


Archivo JT de Siemens versión 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


Archivo JT de Siemens versión 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


Formato de archivo STL ASCII

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Formato de archivo STL binario

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Formato de archivo Universal3D

### USD {#USD}
```
public static final FileFormat USD
```


Descripción Universal de Escena

### USDA {#USDA}
```
public static final FileFormat USDA
```


Descripción Universal de Escena en formato ASCII.

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


Descripción Universal de Escena comprimida

### VRML {#VRML}
```
public static final FileFormat VRML
```


El Lenguaje de Modelado de Realidad Virtual

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Formato de archivo Obj de Wavefront

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


Archivo de nube de puntos Xyz

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


Archivo X de DirectX en formato binario

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


Archivo X de DirectX en formato binario

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


Archivo Zip que contiene otros formatos de archivo 3d.

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


Crear opciones de carga predeterminadas para este formato de archivo

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


Crear opciones de guardado predeterminadas para este formato de archivo

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### detect(Stream stream, String fileName) {#detect-com.aspose.threed.Stream-java.lang.String-}
```
public static FileFormat detect(Stream stream, String fileName)
```


Detectar el formato de archivo a partir del flujo de datos, el nombre del archivo es opcional para adivinar tipos que no tienen encabezado mágico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo que contiene datos para detectar |
| fileName | java.lang.String | Nombre de archivo original de los datos, usado como pista. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


Detectar el formato de archivo a partir del nombre del archivo, el archivo debe ser legible para que Aspose.3D pueda detectar el formato mediante el encabezado del archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Ruta al archivo para detectar el formato de archivo. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### extract(Stream stream) {#extract-com.aspose.threed.Stream-}
```
public ArrayList<byte[]> extract(Stream stream)
```


Extraer contenido 3D sin procesar del flujo PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo del archivo PDF de entrada |

**Returns:**
java.util.ArrayList<byte[]> - Una lista de todo el contenido 3D en bytes, incluidos los formatos que Aspose.3D no soporta. **Example:** El siguiente código muestra cómo extraer todo el contenido 3D sin procesar de un archivo PDF 3D y escribirlo en archivos.

```
var raw3DContents = FileFormat.PDF.extract("input.pdf");
             for (int i = 0; i < raw3DContents.size(); i++)
             {
                 Files.write(Paths.get("raw-3d-" + i), raw3DContents.get(i));
             }
```
### extract(Stream stream, byte[] password) {#extract-com.aspose.threed.Stream-byte---}
```
public ArrayList<byte[]> extract(Stream stream, byte[] password)
```


Extraer contenido 3D sin procesar del flujo PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo del archivo PDF de entrada |
| contraseña | byte[] | Contraseña del archivo PDF |

**Returns:**
java.util.ArrayList<byte[]> - Una lista de todo el contenido 3D en bytes, incluidos los formatos que Aspose.3D no soporta. **Example:** El siguiente código muestra cómo extraer todo el contenido 3D sin procesar de un archivo PDF 3D y escribirlo en archivos.

```
var raw3DContents = FileFormat.PDF.extract("input.pdf");
             for (int i = 0; i < raw3DContents.size(); i++)
             {
                 Files.write(Paths.get("raw-3d-" + i), raw3DContents.get(i));
             }
```
### extract(String fileName) {#extract-java.lang.String-}
```
public ArrayList<byte[]> extract(String fileName)
```


Extraer contenido 3D sin procesar del archivo PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre de archivo del PDF de entrada |

**Returns:**
java.util.ArrayList<byte[]> - Una lista de todo el contenido 3D en bytes, incluidos los formatos que Aspose.3D no soporta. **Example:** El siguiente código muestra cómo extraer todo el contenido 3D sin procesar de un archivo PDF 3D y escribirlo en archivos.

```
var raw3DContents = FileFormat.PDF.extract("input.pdf");
             for (int i = 0; i < raw3DContents.size(); i++)
             {
                 Files.write(Paths.get("raw-3d-" + i), raw3DContents.get(i));
             }
```
### extract(String fileName, byte[] password) {#extract-java.lang.String-byte---}
```
public ArrayList<byte[]> extract(String fileName, byte[] password)
```


Extraer contenido 3D sin procesar del archivo PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre de archivo del PDF de entrada |
| contraseña | byte[] | Contraseña del archivo PDF |

**Returns:**
java.util.ArrayList<byte[]> - Una lista de todo el contenido 3D en bytes, incluidos los formatos que Aspose.3D no soporta. **Example:** El siguiente código muestra cómo extraer todo el contenido 3D sin procesar de un archivo PDF 3D y escribirlo en archivos.

```
var raw3DContents = FileFormat.PDF.extract("input.pdf");
             for (int i = 0; i < raw3DContents.size(); i++)
             {
                 Files.write(Paths.get("raw-3d-" + i), raw3DContents.get(i));
             }
```
### extractScene(Stream stream) {#extractScene-com.aspose.threed.Stream-}
```
public ArrayList<Scene> extractScene(Stream stream)
```


Extraer contenido 3D sin procesar del flujo PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo del archivo PDF de entrada |

**Returns:**
java.util.ArrayList<com.aspose.threed.Scene> - Lista de escenas 3D decodificadas que son compatibles con Aspose.3D **Example:** El siguiente código muestra cómo extraer todas las escenas 3D compatibles de un archivo PDF 3D y escribirlas en formato obj.

```
var scenes = FileFormat.PDF.extractScene("input.pdf");
             for(int i = 0; i < scenes.size(); i++)
             {
                 scenes.get(i).save("output-" + i + ".obj");
             }
```
### extractScene(Stream stream, byte[] password) {#extractScene-com.aspose.threed.Stream-byte---}
```
public ArrayList<Scene> extractScene(Stream stream, byte[] password)
```


Extraer contenido 3D sin procesar del flujo PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo del archivo PDF de entrada |
| contraseña | byte[] | Contraseña del archivo PDF |

**Returns:**
java.util.ArrayList<com.aspose.threed.Scene> - Lista de escenas 3D decodificadas que son compatibles con Aspose.3D **Example:** El siguiente código muestra cómo extraer todas las escenas 3D compatibles de un archivo PDF 3D y escribirlas en formato obj.

```
var scenes = FileFormat.PDF.extractScene("input.pdf");
             for(int i = 0; i < scenes.size(); i++)
             {
                 scenes.get(i).save("output-" + i + ".obj");
             }
```
### extractScene(String fileName) {#extractScene-java.lang.String-}
```
public ArrayList<Scene> extractScene(String fileName)
```


Extraer escenas 3D del archivo PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre de archivo del PDF de entrada |

**Returns:**
java.util.ArrayList<com.aspose.threed.Scene> - Lista de escenas 3D decodificadas que son compatibles con Aspose.3D **Example:** El siguiente código muestra cómo extraer todas las escenas 3D compatibles de un archivo PDF 3D y escribirlas en formato obj.

```
var scenes = FileFormat.PDF.extractScene("input.pdf");
             for(int i = 0; i < scenes.size(); i++)
             {
                 scenes.get(i).save("output-" + i + ".obj");
             }
```
### extractScene(String fileName, byte[] password) {#extractScene-java.lang.String-byte---}
```
public ArrayList<Scene> extractScene(String fileName, byte[] password)
```


Extraer escenas 3D del archivo PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre de archivo del PDF de entrada |
| contraseña | byte[] | Contraseña del archivo PDF |

**Returns:**
java.util.ArrayList<com.aspose.threed.Scene> - Lista de escenas 3D decodificadas que son compatibles con Aspose.3D **Example:** El siguiente código muestra cómo extraer todas las escenas 3D compatibles de un archivo PDF 3D y escribirlas en formato obj.

```
var scenes = FileFormat.PDF.extractScene("input.pdf");
             for(int i = 0; i < scenes.size(); i++)
             {
                 scenes.get(i).save("output-" + i + ".obj");
             }
```
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


Obtiene si Aspose.3D admite la exportación de la escena al formato de archivo actual.

**Returns:**
boolean - si Aspose.3D admite la exportación de la escena al formato de archivo actual. **Ejemplo:** El siguiente código muestra cómo comprobar si la exportación al formato especificado es compatible.

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


Obtiene si Aspose.3D admite la importación de la escena desde el formato de archivo actual.

**Returns:**
boolean - si Aspose.3D admite la importación de la escena desde el formato de archivo actual. **Ejemplo:** El siguiente código muestra cómo comprobar si la importación desde el formato especificado es compatible.

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


Obtiene el tipo de contenido del formato de archivo

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


Obtiene el nombre de extensión de este tipo.

**Returns:**
java.lang.String - el nombre de extensión de este tipo. **Ejemplo:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


Obtiene los nombres de extensión de este tipo.

**Returns:**
java.lang.String[] - los nombres de extensión de este tipo.
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


Obtiene el tipo de formato de archivo

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


Obtiene el formato de archivo preferido a partir del nombre de extensión del archivo. El nombre de extensión debe comenzar con un punto ('.').

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extensionName | java.lang.String | El nombre de extensión comienza con '.' para la consulta. |

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


Acceso a todos los formatos compatibles

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - Acceso a todos los formatos compatibles
### getVersion() {#getVersion--}
```
public Version getVersion()
```


Obtiene la versión del formato de archivo

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


Formatos a cadena

**Returns:**
java.lang.String - Cadena del objeto
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

