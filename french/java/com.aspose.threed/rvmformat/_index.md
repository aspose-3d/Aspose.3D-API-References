---
title: "RvmFormat"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le format RVM"
type: docs
weight: 156
url: /fr/java/com.aspose.threed/rvmformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class RvmFormat extends FileFormat
```

Le format RVM
## Champs

| Champ | Description |
| --- | --- |
| [AMF](#AMF) | Format de fichier de fabrication additive |
| [ASE](#ASE) | Format d'exportation de scène ASCII de 3D Studio Max. |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Format Web Aspose.3D. |
| [BLENDER](#BLENDER) | Format de fichier 3D de Blender |
| [COLLADA](#COLLADA) | Format de fichier Collada |
| [DISCREET3DS](#DISCREET3DS) | Format de fichier de 3D Studio |
| [DRACO](#DRACO) | Maillage Google Draco |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | Format de fichier FBX ASCII, avec la version 6.1.0 |
| [FBX6100_BINARY](#FBX6100-BINARY) | Format de fichier FBX binaire, avec la version 6.1.0 |
| [FBX7200ASCII](#FBX7200ASCII) | Format de fichier FBX ASCII, avec la version 7.2.0 |
| [FBX7200_BINARY](#FBX7200-BINARY) | Format de fichier FBX binaire, avec la version 7.2.0 |
| [FBX7300ASCII](#FBX7300ASCII) | Format de fichier FBX ASCII, avec la version 7.3.0 |
| [FBX7300_BINARY](#FBX7300-BINARY) | Format de fichier FBX binaire, avec la version 7.3.0 |
| [FBX7400ASCII](#FBX7400ASCII) | Format de fichier FBX ASCII, avec la version 7.4.0 |
| [FBX7400_BINARY](#FBX7400-BINARY) | Format de fichier FBX binaire, avec la version 7.4.0 |
| [FBX7500ASCII](#FBX7500ASCII) | Format de fichier FBX ASCII, version 7.5.0 |
| [FBX7500_BINARY](#FBX7500-BINARY) | Format de fichier FBX binaire, version 7.5.0 |
| [FBX7600ASCII](#FBX7600ASCII) | Format de fichier FBX ASCII, version 7.6.0 |
| [FBX7600_BINARY](#FBX7600-BINARY) | Format de fichier FBX binaire, version 7.6.0 |
| [FBX7700ASCII](#FBX7700ASCII) | Format de fichier FBX ASCII, version 7.7.0 |
| [FBX7700_BINARY](#FBX7700-BINARY) | Format de fichier FBX binaire, version 7.7.0 |
| [GLTF](#GLTF) | glTF du groupe Khronos |
| [GLTF2](#GLTF2) | glTF du groupe Khronos version 2.0 |
| [GLTF2_BINARY](#GLTF2-BINARY) | glTF du groupe Khronos version 2.0 |
| [GLTF_BINARY](#GLTF-BINARY) | glTF du groupe Khronos au format binaire |
| [HTML5](#HTML5) | Fichier HTML5 |
| [IFC](#IFC) | Modèle de données ISO 16739-1 Industry Foundation Classes. |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya au format ASCII |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya au format binaire |
| [MICROSOFT3MF](#MICROSOFT3MF) | Format de fabrication 3D Microsoft |
| [PCD](#PCD) | Fichier de données de nuage de points PCL en mode ASCII |
| [PCD_BINARY](#PCD-BINARY) | Fichier de données de nuage de points PCL en mode binaire |
| [PDF](#PDF) | Format de document portable d'Adobe |
| [PLY](#PLY) | Format de fichier Polygon ou Format de triangle Stanford |
| [RVM_BINARY](#RVM-BINARY) | Modèle du système de gestion de conception d'usine AVEVA au format binaire |
| [RVM_TEXT](#RVM-TEXT) | Modèle du système de gestion de conception d'usine AVEVA au format texte |
| [SIEMENSJT8](#SIEMENSJT8) | Fichier JT Siemens version 8 |
| [SIEMENSJT9](#SIEMENSJT9) | Fichier JT Siemens version 9 |
| [STLASCII](#STLASCII) | Format de fichier STL ASCII |
| [STL_BINARY](#STL-BINARY) | Format de fichier STL binaire |
| [UNIVERSAL3D](#UNIVERSAL3D) | Format de fichier Universal3D |
| [USD](#USD) | Description de scène universelle |
| [USDA](#USDA) | Description de scène universelle au format ASCII. |
| [USDZ](#USDZ) | Description de scène universelle compressée |
| [VRML](#VRML) | Le langage de modélisation de réalité virtuelle |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Format de fichier Obj de Wavefront |
| [XYZ](#XYZ) | Fichier de nuage de points Xyz |
| [X_BINARY](#X-BINARY) | Fichier X DirectX au format binaire |
| [X_TEXT](#X-TEXT) | Fichier X DirectX au format binaire |
| [ZIP](#ZIP) | Archive Zip contenant d'autres formats de fichiers 3D. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | Créer des options de chargement par défaut pour ce format de fichier |
| [createSaveOptions()](#createSaveOptions--) | Créer des options d'enregistrement par défaut pour ce format de fichier |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | Détecter le format de fichier à partir du flux de données, le nom de fichier est facultatif pour deviner les types qui n'ont pas d'en-tête magique. |
| [detect(String fileName)](#detect-java.lang.String-) | Détecter le format de fichier à partir du nom de fichier, le fichier doit être lisible afin qu'Aspose.3D puisse détecter le format de fichier via l'en-tête du fichier. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | Obtient si Aspose.3D prend en charge l'exportation de la scène vers le format de fichier actuel. |
| [getCanImport()](#getCanImport--) | Obtient si Aspose.3D prend en charge l'importation de la scène depuis le format de fichier actuel. |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | Obtient le type de contenu du format de fichier |
| [getExtension()](#getExtension--) | Obtient le nom d'extension de ce type. |
| [getExtensions()](#getExtensions--) | Obtient les noms d'extension de ce type. |
| [getFileFormatType()](#getFileFormatType--) | Obtient le type de format de fichier |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | Obtient le format de fichier préféré à partir du nom d'extension. Le nom d'extension doit commencer par un point ('.'). |
| [getFormats()](#getFormats--) | Accès à tous les formats pris en charge |
| [getVersion()](#getVersion--) | Obtient la version du format de fichier |
| [hashCode()](#hashCode--) |  |
| [loadAttributes(Scene scene, Stream stream)](#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-) | Charger les attributs depuis le flux spécifié |
| [loadAttributes(Scene scene, Stream stream, String prefix)](#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-java.lang.String-) | Charger les attributs depuis le flux spécifié |
| [loadAttributes(Scene scene, String fileName)](#loadAttributes-com.aspose.threed.Scene-java.lang.String-) | Charger les attributs depuis le nom de fichier spécifié |
| [loadAttributes(Scene scene, String fileName, String prefix)](#loadAttributes-com.aspose.threed.Scene-java.lang.String-java.lang.String-) | Charger les attributs depuis le nom de fichier spécifié |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Formats en chaîne |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


Format de fichier de fabrication additive

### ASE {#ASE}
```
public static final FileFormat ASE
```


Format d'exportation de scène ASCII de 3D Studio Max.

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Format Web Aspose.3D.

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Format de fichier 3D de Blender

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Format de fichier Collada

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


Format de fichier de 3D Studio

### DRACO {#DRACO}
```
public static final DracoFormat DRACO
```


Maillage Google Draco

### DXF {#DXF}
```
public static final FileFormat DXF
```


AutoCAD DXF

### FBX6100ASCII {#FBX6100ASCII}
```
public static final FileFormat FBX6100ASCII
```


Format de fichier FBX ASCII, avec la version 6.1.0

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


Format de fichier FBX binaire, avec la version 6.1.0

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


Format de fichier FBX ASCII, avec la version 7.2.0

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


Format de fichier FBX binaire, avec la version 7.2.0

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


Format de fichier FBX ASCII, avec la version 7.3.0

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


Format de fichier FBX binaire, avec la version 7.3.0

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


Format de fichier FBX ASCII, avec la version 7.4.0

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


Format de fichier FBX binaire, avec la version 7.4.0

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


Format de fichier FBX ASCII, version 7.5.0

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Format de fichier FBX binaire, version 7.5.0

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


Format de fichier FBX ASCII, version 7.6.0

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Format de fichier FBX binaire, version 7.6.0

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


Format de fichier FBX ASCII, version 7.7.0

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Format de fichier FBX binaire, version 7.7.0

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


glTF du groupe Khronos

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


glTF du groupe Khronos version 2.0

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


glTF du groupe Khronos version 2.0

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


glTF du groupe Khronos au format binaire

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


Fichier HTML5

### IFC {#IFC}
```
public static final FileFormat IFC
```


Modèle de données ISO 16739-1 Industry Foundation Classes.

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya au format ASCII

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya au format binaire

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Format de fabrication 3D Microsoft

### PCD {#PCD}
```
public static final FileFormat PCD
```


Fichier de données de nuage de points PCL en mode ASCII

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


Fichier de données de nuage de points PCL en mode binaire

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Format de document portable d'Adobe

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Format de fichier Polygon ou Format de triangle Stanford

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


Modèle du système de gestion de conception d'usine AVEVA au format binaire

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


Modèle du système de gestion de conception d'usine AVEVA au format texte

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


Fichier JT Siemens version 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


Fichier JT Siemens version 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


Format de fichier STL ASCII

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Format de fichier STL binaire

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Format de fichier Universal3D

### USD {#USD}
```
public static final FileFormat USD
```


Description de scène universelle

### USDA {#USDA}
```
public static final FileFormat USDA
```


Description de scène universelle au format ASCII.

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


Description de scène universelle compressée

### VRML {#VRML}
```
public static final FileFormat VRML
```


Le langage de modélisation de réalité virtuelle

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Format de fichier Obj de Wavefront

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


Fichier de nuage de points Xyz

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


Fichier X DirectX au format binaire

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


Fichier X DirectX au format binaire

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


Archive Zip contenant d'autres formats de fichiers 3D.

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


Créer des options de chargement par défaut pour ce format de fichier

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


Créer des options d'enregistrement par défaut pour ce format de fichier

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### detect(Stream stream, String fileName) {#detect-com.aspose.threed.Stream-java.lang.String-}
```
public static FileFormat detect(Stream stream, String fileName)
```


Détecter le format de fichier à partir du flux de données, le nom de fichier est facultatif pour deviner les types qui n'ont pas d'en-tête magique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux contenant les données à détecter |
| fileName | java.lang.String | Nom de fichier original des données, utilisé comme indice. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


Détecter le format de fichier à partir du nom de fichier, le fichier doit être lisible afin qu'Aspose.3D puisse détecter le format de fichier via l'en-tête du fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Chemin vers le fichier pour détecter le format de fichier. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


Obtient si Aspose.3D prend en charge l'exportation de la scène vers le format de fichier actuel.

**Returns:**
booléen - indique si Aspose.3D prend en charge l'exportation de la scène vers le format de fichier actuel. **Exemple:** Le code suivant montre comment vérifier si l'exportation vers le format spécifié est prise en charge.

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


Obtient si Aspose.3D prend en charge l'importation de la scène depuis le format de fichier actuel.

**Returns:**
booléen - indique si Aspose.3D prend en charge l'importation de la scène depuis le format de fichier actuel. **Exemple:** Le code suivant montre comment vérifier si l'importation depuis le format spécifié est prise en charge.

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


Obtient le type de contenu du format de fichier

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


Obtient le nom d'extension de ce type.

**Returns:**
java.lang.String - le nom d'extension de ce type. **Exemple:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


Obtient les noms d'extension de ce type.

**Returns:**
java.lang.String[] - les noms d'extension de ce type.
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


Obtient le type de format de fichier

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


Obtient le format de fichier préféré à partir du nom d'extension. Le nom d'extension doit commencer par un point ('.').

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| extensionName | java.lang.String | Le nom d'extension commence par '.' pour la requête. |

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


Accès à tous les formats pris en charge

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - Accès à tous les formats pris en charge
### getVersion() {#getVersion--}
```
public Version getVersion()
```


Obtient la version du format de fichier

**Returns:**
[Version](../../com.aspose.threed/version) - file format version
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadAttributes(Scene scene, Stream stream) {#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-}
```
public void loadAttributes(Scene scene, Stream stream)
```


Charger les attributs depuis le flux spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | La scène où les attributs seront appliqués |
| stream | [Stream](../../com.aspose.threed/stream) | Le flux contenant les attributs |

### loadAttributes(Scene scene, Stream stream, String prefix) {#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-java.lang.String-}
```
public void loadAttributes(Scene scene, Stream stream, String prefix)
```


Charger les attributs depuis le flux spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | La scène où les attributs seront appliqués |
| stream | [Stream](../../com.aspose.threed/stream) | Le flux contenant les attributs |
| préfixe | java.lang.String | Le préfixe des attributs utilisé pour éviter les conflits de noms, la valeur par défaut est "rvm:" |

### loadAttributes(Scene scene, String fileName) {#loadAttributes-com.aspose.threed.Scene-java.lang.String-}
```
public void loadAttributes(Scene scene, String fileName)
```


Charger les attributs depuis le nom de fichier spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | La scène où les attributs seront appliqués |
| fileName | java.lang.String | Le nom du fichier contenant les attributs |

### loadAttributes(Scene scene, String fileName, String prefix) {#loadAttributes-com.aspose.threed.Scene-java.lang.String-java.lang.String-}
```
public void loadAttributes(Scene scene, String fileName, String prefix)
```


Charger les attributs depuis le nom de fichier spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | La scène où les attributs seront appliqués |
| fileName | java.lang.String | Le nom du fichier contenant les attributs |
| préfixe | java.lang.String | Le préfixe des attributs utilisé pour éviter les conflits de noms, la valeur par défaut est "rvm:" |

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


Formats en chaîne

**Returns:**
java.lang.String - Chaîne d'objet
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

