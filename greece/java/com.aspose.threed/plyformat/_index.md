---
title: PlyFormat
second_title: Aspose.3D for Java API Reference
description: The PLY format.
type: docs
weight: 129
url: /el/java/com.aspose.threed/plyformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class PlyFormat extends FileFormat
```

Η μορφή PLY. **Example:** Ο παρακάτω κώδικας δείχνει πώς να αποκωδικοποιήσετε ένα πλέγμα από αρχείο PLY:

```
//Generate a test file for decoding
             FileFormat.PLY.encode(new Sphere(), "sphere.ply");
             //Decode the file
             var mesh = (Mesh)FileFormat.PLY.decode("sphere.ply")
```
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [AMF](#AMF) | Additive manufacturing file format |
| [ASE](#ASE) | 3D Studio Max's ASCII Scene Exporter format. |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Aspose.3D Web format. |
| [BLENDER](#BLENDER) | Blender's 3D file format |
| [COLLADA](#COLLADA) | Collada file format |
| [DISCREET3DS](#DISCREET3DS) | 3D Studio's file format |
| [DRACO](#DRACO) | Google Draco Mesh |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | ASCII FBX file format, with 6.1.0 version |
| [FBX6100_BINARY](#FBX6100-BINARY) | Binary FBX file format, with 6.1.0 version |
| [FBX7200ASCII](#FBX7200ASCII) | μορφή αρχείου ASCII FBX, με έκδοση 7.2.0 |
| [FBX7200_BINARY](#FBX7200-BINARY) | μορφή αρχείου Binary FBX, με έκδοση 7.2.0 |
| [FBX7300ASCII](#FBX7300ASCII) | μορφή αρχείου ASCII FBX, με έκδοση 7.3.0 |
| [FBX7300_BINARY](#FBX7300-BINARY) | μορφή αρχείου Binary FBX, με έκδοση 7.3.0 |
| [FBX7400ASCII](#FBX7400ASCII) | μορφή αρχείου ASCII FBX, με έκδοση 7.4.0 |
| [FBX7400_BINARY](#FBX7400-BINARY) | μορφή αρχείου Binary FBX, με έκδοση 7.4.0 |
| [FBX7500ASCII](#FBX7500ASCII) | μορφή αρχείου ASCII FBX, με έκδοση 7.5.0 |
| [FBX7500_BINARY](#FBX7500-BINARY) | μορφή αρχείου Binary FBX, με έκδοση 7.5.0 |
| [FBX7600ASCII](#FBX7600ASCII) | μορφή αρχείου ASCII FBX, με έκδοση 7.6.0 |
| [FBX7600_BINARY](#FBX7600-BINARY) | μορφή αρχείου Binary FBX, με έκδοση 7.6.0 |
| [FBX7700ASCII](#FBX7700ASCII) | μορφή αρχείου ASCII FBX, με έκδοση 7.7.0 |
| [FBX7700_BINARY](#FBX7700-BINARY) | μορφή αρχείου Binary FBX, με έκδοση 7.7.0 |
| [GLTF](#GLTF) | glTF της Khronos Group |
| [GLTF2](#GLTF2) | glTF της Khronos Group έκδοση 2.0 |
| [GLTF2_BINARY](#GLTF2-BINARY) | glTF της Khronos Group έκδοση 2.0 |
| [GLTF_BINARY](#GLTF-BINARY) | glTF της Khronos Group σε δυαδική μορφή |
| [HTML5](#HTML5) | Αρχείο HTML5 |
| [IFC](#IFC) | μοντέλο δεδομένων ISO 16739-1 Industry Foundation Classes. |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya σε μορφή ASCII |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya σε μορφή Binary |
| [MICROSOFT3MF](#MICROSOFT3MF) | Microsoft 3D Manufacturing Format |
| [PCD](#PCD) | αρχείο PCL Point Cloud Data σε λειτουργία ASCII |
| [PCD_BINARY](#PCD-BINARY) | αρχείο PCL Point Cloud Data σε λειτουργία Binary |
| [PDF](#PDF) | Portable Document Format της Adobe |
| [PLY](#PLY) | Polygon File Format ή Stanford Triangle Format |
| [RVM_BINARY](#RVM-BINARY) | μοντέλο AVEVA Plant Design Management System σε δυαδική μορφή |
| [RVM_TEXT](#RVM-TEXT) | Μοντέλο του Συστήματος Διαχείρισης Σχεδίασης Εγκαταστάσεων AVEVA σε μορφή κειμένου |
| [SIEMENSJT8](#SIEMENSJT8) | Αρχείο Siemens JT Έκδοση 8 |
| [SIEMENSJT9](#SIEMENSJT9) | Αρχείο Siemens JT Έκδοση 9 |
| [STLASCII](#STLASCII) | Μορφή αρχείου ASCII STL |
| [STL_BINARY](#STL-BINARY) | Μορφή αρχείου Binary STL |
| [UNIVERSAL3D](#UNIVERSAL3D) | Μορφή αρχείου Universal3D |
| [USD](#USD) | Καθολική Περιγραφή Σκηνής |
| [USDA](#USDA) | Καθολική Περιγραφή Σκηνής σε μορφή ASCII. |
| [USDZ](#USDZ) | Συμπιεσμένη Καθολική Περιγραφή Σκηνής |
| [VRML](#VRML) | Η Γλώσσα Μοντελοποίησης Εικονικής Πραγματικότητας |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Μορφή αρχείου Obj της Wavefront |
| [XYZ](#XYZ) | Αρχείο νέφους σημείων Xyz |
| [X_BINARY](#X-BINARY) | Αρχείο DirectX X σε δυαδική μορφή |
| [X_TEXT](#X-TEXT) | Αρχείο DirectX X σε δυαδική μορφή |
| [ZIP](#ZIP) | Αρχείο Zip που περιέχει άλλες μορφές αρχείων 3δ. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | Δημιουργήστε προεπιλεγμένες επιλογές φόρτωσης για αυτή τη μορφή αρχείου |
| [createSaveOptions()](#createSaveOptions--) | Δημιουργήστε προεπιλεγμένες επιλογές αποθήκευσης για αυτή τη μορφή αρχείου |
| [decode(Stream stream)](#decode-com.aspose.threed.Stream-) | Αποκωδικοποιήστε ένα σύννεφο σημείων ή πλέγμα από το καθορισμένο ρεύμα. |
| [decode(Stream stream, PlyLoadOptions opt)](#decode-com.aspose.threed.Stream-com.aspose.threed.PlyLoadOptions-) | Αποκωδικοποιήστε ένα σύννεφο σημείων ή πλέγμα από το καθορισμένο ρεύμα. |
| [decode(String fileName)](#decode-java.lang.String-) | Αποκωδικοποιήστε ένα σύννεφο σημείων ή πλέγμα από το καθορισμένο ρεύμα. |
| [decode(String fileName, PlyLoadOptions opt)](#decode-java.lang.String-com.aspose.threed.PlyLoadOptions-) | Αποκωδικοποιήστε ένα σύννεφο σημείων ή πλέγμα από το καθορισμένο ρεύμα. |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | Ανιχνεύστε τη μορφή αρχείου από τη ροή δεδομένων, το όνομα αρχείου είναι προαιρετικό για την εικασία τύπων που δεν έχουν μαγική κεφαλίδα. |
| [detect(String fileName)](#detect-java.lang.String-) | Ανιχνεύστε τη μορφή αρχείου από το όνομα αρχείου, το αρχείο πρέπει να είναι αναγνώσιμο ώστε το Aspose.3D να μπορεί να ανιχνεύσει τη μορφή αρχείου μέσω της κεφαλίδας του αρχείου. |
| [encode(Entity entity, Stream stream)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-) | Κωδικοποιήστε την οντότητα και αποθηκεύστε το αποτέλεσμα στο ρεύμα. |
| [encode(Entity entity, Stream stream, PlySaveOptions opt)](#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.PlySaveOptions-) | Κωδικοποιήστε την οντότητα και αποθηκεύστε το αποτέλεσμα στο ρεύμα. |
| [encode(Entity entity, String fileName)](#encode-com.aspose.threed.Entity-java.lang.String-) | Κωδικοποιήστε την οντότητα και αποθηκεύστε το αποτέλεσμα σε εξωτερικό αρχείο. |
| [encode(Entity entity, String fileName, PlySaveOptions opt)](#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.PlySaveOptions-) | Κωδικοποιήστε την οντότητα και αποθηκεύστε το αποτέλεσμα σε εξωτερικό αρχείο. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | Λαμβάνει αν το Aspose.3D υποστηρίζει εξαγωγή σκηνής στην τρέχουσα μορφή αρχείου. |
| [getCanImport()](#getCanImport--) | Λαμβάνει αν το Aspose.3D υποστηρίζει εισαγωγή σκηνής από την τρέχουσα μορφή αρχείου. |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | Λαμβάνει τον τύπο περιεχομένου της μορφής αρχείου |
| [getExtension()](#getExtension--) | Λαμβάνει το όνομα επέκτασης αυτού του τύπου. |
| [getExtensions()](#getExtensions--) | Λαμβάνει τα ονόματα επεκτάσεων αυτού του τύπου. |
| [getFileFormatType()](#getFileFormatType--) | Λαμβάνει τον τύπο μορφής αρχείου |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | Λαμβάνει την προτιμώμενη μορφή αρχείου από το όνομα επέκτασης του αρχείου. Το όνομα επέκτασης πρέπει να ξεκινά με τελεία ('.'). |
| [getFormats()](#getFormats--) | Πρόσβαση σε όλες τις υποστηριζόμενες μορφές |
| [getVersion()](#getVersion--) | Λαμβάνει την έκδοση μορφής αρχείου |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Μορφές σε συμβολοσειρά |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


Additive manufacturing file format

### ASE {#ASE}
```
public static final FileFormat ASE
```


3D Studio Max's ASCII Scene Exporter format.

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Aspose.3D Web format.

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Blender's 3D file format

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Collada file format

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


3D Studio's file format

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


ASCII FBX file format, with 6.1.0 version

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


Binary FBX file format, with 6.1.0 version

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


μορφή αρχείου ASCII FBX, με έκδοση 7.2.0

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


μορφή αρχείου Binary FBX, με έκδοση 7.2.0

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


μορφή αρχείου ASCII FBX, με έκδοση 7.3.0

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


μορφή αρχείου Binary FBX, με έκδοση 7.3.0

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


μορφή αρχείου ASCII FBX, με έκδοση 7.4.0

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


μορφή αρχείου Binary FBX, με έκδοση 7.4.0

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


μορφή αρχείου ASCII FBX, με έκδοση 7.5.0

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


μορφή αρχείου Binary FBX, με έκδοση 7.5.0

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


μορφή αρχείου ASCII FBX, με έκδοση 7.6.0

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


μορφή αρχείου Binary FBX, με έκδοση 7.6.0

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


μορφή αρχείου ASCII FBX, με έκδοση 7.7.0

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


μορφή αρχείου Binary FBX, με έκδοση 7.7.0

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


glTF της Khronos Group

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


glTF της Khronos Group έκδοση 2.0

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


glTF της Khronos Group έκδοση 2.0

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


glTF της Khronos Group σε δυαδική μορφή

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


Αρχείο HTML5

### IFC {#IFC}
```
public static final FileFormat IFC
```


μοντέλο δεδομένων ISO 16739-1 Industry Foundation Classes.

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya σε μορφή ASCII

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya σε μορφή Binary

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Microsoft 3D Manufacturing Format

### PCD {#PCD}
```
public static final FileFormat PCD
```


αρχείο PCL Point Cloud Data σε λειτουργία ASCII

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


αρχείο PCL Point Cloud Data σε λειτουργία Binary

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Portable Document Format της Adobe

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Polygon File Format ή Stanford Triangle Format

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


μοντέλο AVEVA Plant Design Management System σε δυαδική μορφή

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


Μοντέλο του Συστήματος Διαχείρισης Σχεδίασης Εγκαταστάσεων AVEVA σε μορφή κειμένου

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


Αρχείο Siemens JT Έκδοση 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


Αρχείο Siemens JT Έκδοση 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


Μορφή αρχείου ASCII STL

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Μορφή αρχείου Binary STL

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Μορφή αρχείου Universal3D

### USD {#USD}
```
public static final FileFormat USD
```


Καθολική Περιγραφή Σκηνής

### USDA {#USDA}
```
public static final FileFormat USDA
```


Καθολική Περιγραφή Σκηνής σε μορφή ASCII.

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


Συμπιεσμένη Καθολική Περιγραφή Σκηνής

### VRML {#VRML}
```
public static final FileFormat VRML
```


Η Γλώσσα Μοντελοποίησης Εικονικής Πραγματικότητας

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Μορφή αρχείου Obj της Wavefront

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


Αρχείο νέφους σημείων Xyz

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


Αρχείο DirectX X σε δυαδική μορφή

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


Αρχείο DirectX X σε δυαδική μορφή

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


Αρχείο Zip που περιέχει άλλες μορφές αρχείων 3δ.

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


Δημιουργήστε προεπιλεγμένες επιλογές φόρτωσης για αυτή τη μορφή αρχείου

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


Δημιουργήστε προεπιλεγμένες επιλογές αποθήκευσης για αυτή τη μορφή αρχείου

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### decode(Stream stream) {#decode-com.aspose.threed.Stream-}
```
public Geometry decode(Stream stream)
```


Αποκωδικοποιήστε ένα σύννεφο σημείων ή πλέγμα από το καθορισμένο ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Η ροή εισόδου |

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


Αποκωδικοποιήστε ένα σύννεφο σημείων ή πλέγμα από το καθορισμένο ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Η ροή εισόδου |
| opt | [PlyLoadOptions](../../com.aspose.threed/plyloadoptions) | Η επιλογή φόρτωσης της μορφής PLY |

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


Αποκωδικοποιήστε ένα σύννεφο σημείων ή πλέγμα από το καθορισμένο ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Η ροή εισόδου |

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


Αποκωδικοποιήστε ένα σύννεφο σημείων ή πλέγμα από το καθορισμένο ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Η ροή εισόδου |
| opt | [PlyLoadOptions](../../com.aspose.threed/plyloadoptions) | Η επιλογή φόρτωσης της μορφής PLY |

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


Ανιχνεύστε τη μορφή αρχείου από τη ροή δεδομένων, το όνομα αρχείου είναι προαιρετικό για την εικασία τύπων που δεν έχουν μαγική κεφαλίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή που περιέχει δεδομένα για ανίχνευση |
| fileName | java.lang.String | Αρχικό όνομα αρχείου των δεδομένων, χρησιμοποιείται ως υπόδειξη. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


Ανιχνεύστε τη μορφή αρχείου από το όνομα αρχείου, το αρχείο πρέπει να είναι αναγνώσιμο ώστε το Aspose.3D να μπορεί να ανιχνεύσει τη μορφή αρχείου μέσω της κεφαλίδας του αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Διαδρομή προς το αρχείο για ανίχνευση μορφής αρχείου. |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### encode(Entity entity, Stream stream) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-}
```
public void encode(Entity entity, Stream stream)
```


Κωδικοποιήστε την οντότητα και αποθηκεύστε το αποτέλεσμα στο ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Η οντότητα προς κωδικοποίηση |
|  | stream | [Stream](../../com.aspose.threed/stream) | The stream to write to, this method will not close this stream **Example:** The following code shows how to encode a mesh into PLY file: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, Stream stream, PlySaveOptions opt) {#encode-com.aspose.threed.Entity-com.aspose.threed.Stream-com.aspose.threed.PlySaveOptions-}
```
public void encode(Entity entity, Stream stream, PlySaveOptions opt)
```


Κωδικοποιήστε την οντότητα και αποθηκεύστε το αποτέλεσμα στο ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Η οντότητα προς κωδικοποίηση |
| stream | [Stream](../../com.aspose.threed/stream) | The stream to write to, this method will not close this stream |
|  | opt | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) | Save options **Example:** The following code shows how to encode a mesh into PLY file: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, String fileName) {#encode-com.aspose.threed.Entity-java.lang.String-}
```
public void encode(Entity entity, String fileName)
```


Κωδικοποιήστε την οντότητα και αποθηκεύστε το αποτέλεσμα σε εξωτερικό αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Η οντότητα προς κωδικοποίηση |
|  | fileName | java.lang.String | The file to write to **Example:** The following code shows how to encode a mesh into PLY file: |

```
Mesh mesh = (new Sphere()).toMesh();
             //encode mesh into PLY format
             FileFormat.PLY.encode(mesh, "sphere.ply");
``` |

### encode(Entity entity, String fileName, PlySaveOptions opt) {#encode-com.aspose.threed.Entity-java.lang.String-com.aspose.threed.PlySaveOptions-}
```
public void encode(Entity entity, String fileName, PlySaveOptions opt)
```


Κωδικοποιήστε την οντότητα και αποθηκεύστε το αποτέλεσμα σε εξωτερικό αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Η οντότητα προς κωδικοποίηση |
| fileName | java.lang.String | Το αρχείο στο οποίο θα γραφτεί |
|  | opt | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) | Save options **Example:** The following code shows how to encode a mesh into PLY file: |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


Λαμβάνει αν το Aspose.3D υποστηρίζει εξαγωγή σκηνής στην τρέχουσα μορφή αρχείου.

**Returns:**
boolean - αν το Aspose.3D υποστηρίζει την εξαγωγή σκηνής στην τρέχουσα μορφή αρχείου. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να ελέγξετε αν η εξαγωγή σε καθορισμένη μορφή υποστηρίζεται.

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


Λαμβάνει αν το Aspose.3D υποστηρίζει εισαγωγή σκηνής από την τρέχουσα μορφή αρχείου.

**Returns:**
boolean - αν το Aspose.3D υποστηρίζει την εισαγωγή σκηνής από την τρέχουσα μορφή αρχείου. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να ελέγξετε αν η εισαγωγή από καθορισμένη μορφή υποστηρίζεται.

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


Λαμβάνει τον τύπο περιεχομένου της μορφής αρχείου

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


Λαμβάνει το όνομα επέκτασης αυτού του τύπου.

**Returns:**
java.lang.String - το όνομα επέκτασης αυτού του τύπου. **Παράδειγμα:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


Λαμβάνει τα ονόματα επεκτάσεων αυτού του τύπου.

**Returns:**
java.lang.String[] - τα ονόματα επεκτάσεων αυτού του τύπου.
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


Λαμβάνει τον τύπο μορφής αρχείου

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


Λαμβάνει την προτιμώμενη μορφή αρχείου από το όνομα επέκτασης του αρχείου. Το όνομα επέκτασης πρέπει να ξεκινά με τελεία ('.').

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| extensionName | java.lang.String | Το όνομα επέκτασης ξεκινά με '.' για ερώτημα. |

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


Πρόσβαση σε όλες τις υποστηριζόμενες μορφές

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - Πρόσβαση σε όλες τις υποστηριζόμενες μορφές
### getVersion() {#getVersion--}
```
public Version getVersion()
```


Λαμβάνει την έκδοση μορφής αρχείου

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


Μορφές σε συμβολοσειρά

**Returns:**
java.lang.String - Συμβολοσειρά αντικειμένου
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

