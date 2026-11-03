---
title: "Class FileFormat"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.FileFormat class. Ορισμός μορφής αρχείου"
type: docs
weight: 1060
url: /el/net/aspose.threed/fileformat/
---
## FileFormat class

Ορισμός μορφής αρχείου

```csharp
public class FileFormat
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Λαμβάνει αν το Aspose.3D υποστηρίζει την εξαγωγή σκηνής στην τρέχουσα μορφή αρχείου. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Λαμβάνει αν το Aspose.3D υποστηρίζει την εισαγωγή σκηνής από την τρέχουσα μορφή αρχείου. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Λαμβάνει τον τύπο περιεχομένου της μορφής αρχείου |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Λαμβάνει το όνομα επέκτασης αυτού του τύπου. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Λαμβάνει τα ονόματα επεκτάσεων αυτού του τύπου. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Λαμβάνει τον τύπο μορφής αρχείου |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Λαμβάνει την έκδοση της μορφής αρχείου |
| static [Formats](../../aspose.threed/fileformat/formats/) { get; } | Πρόσβαση σε όλες τις υποστηριζόμενες μορφές |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Detect](../../aspose.threed/fileformat/detect/#detect_1)(string) | Ανίχνευση της μορφής αρχείου από το όνομα αρχείου, το αρχείο πρέπει να είναι αναγνώσιμο ώστε το Aspose.3D να μπορεί να ανιχνεύσει τη μορφή αρχείου μέσω της κεφαλίδας του αρχείου. |
| static [Detect](../../aspose.threed/fileformat/detect/#detect)(Stream, string) | Ανίχνευση της μορφής αρχείου από τη ροή δεδομένων, το όνομα αρχείου είναι προαιρετικό για την εικασία τύπων που δεν έχουν μαγική κεφαλίδα. |
| static [GetFormatByExtension](../../aspose.threed/fileformat/getformatbyextension/)(string) | Λαμβάνει τη προτιμώμενη μορφή αρχείου από το όνομα επέκτασης του αρχείου. Το όνομα επέκτασης πρέπει να αρχίζει με τελεία ('.'). |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Δημιουργήστε προεπιλεγμένες επιλογές φόρτωσης για αυτή τη μορφή αρχείου |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Δημιουργήστε προεπιλεγμένες επιλογές αποθήκευσης για αυτή τη μορφή αρχείου |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Μετατρέπει σε συμβολοσειρά |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [AMF](../../aspose.threed/fileformat/amf/) | Μορφή αρχείου προσθετικής κατασκευής |
| static readonly [ASE](../../aspose.threed/fileformat/ase/) | Μορφή ASCII εξαγωγέα σκηνής του 3D Studio Max. |
| static readonly [Aspose3DWeb](../../aspose.threed/fileformat/aspose3dweb/) | Aspose.3D Web format. |
| static readonly [Blender](../../aspose.threed/fileformat/blender/) | Μορφή αρχείου 3D του Blender |
| static readonly [Collada](../../aspose.threed/fileformat/collada/) | Μορφή αρχείου Collada |
| static readonly [Discreet3DS](../../aspose.threed/fileformat/discreet3ds/) | Μορφή αρχείου του 3D Studio |
| static readonly [DXF](../../aspose.threed/fileformat/dxf/) | AutoCAD DXF |
| static readonly [FBX6100ASCII](../../aspose.threed/fileformat/fbx6100ascii/) | Μορφή αρχείου ASCII FBX, με έκδοση 6.1.0 |
| static readonly [FBX6100Binary](../../aspose.threed/fileformat/fbx6100binary/) | Μορφή αρχείου Binary FBX, με έκδοση 6.1.0 |
| static readonly [FBX7200ASCII](../../aspose.threed/fileformat/fbx7200ascii/) | Μορφή αρχείου ASCII FBX, με έκδοση 7.2.0 |
| static readonly [FBX7200Binary](../../aspose.threed/fileformat/fbx7200binary/) | Μορφή αρχείου Binary FBX, με έκδοση 7.2.0 |
| static readonly [FBX7300ASCII](../../aspose.threed/fileformat/fbx7300ascii/) | Μορφή αρχείου ASCII FBX, με έκδοση 7.3.0 |
| static readonly [FBX7300Binary](../../aspose.threed/fileformat/fbx7300binary/) | Μορφή αρχείου Binary FBX, με έκδοση 7.3.0 |
| static readonly [FBX7400ASCII](../../aspose.threed/fileformat/fbx7400ascii/) | Μορφή αρχείου ASCII FBX, με έκδοση 7.4.0 |
| static readonly [FBX7400Binary](../../aspose.threed/fileformat/fbx7400binary/) | Μορφή αρχείου Binary FBX, με έκδοση 7.4.0 |
| static readonly [FBX7500ASCII](../../aspose.threed/fileformat/fbx7500ascii/) | Μορφή αρχείου ASCII FBX, με έκδοση 7.5.0 |
| static readonly [FBX7500Binary](../../aspose.threed/fileformat/fbx7500binary/) | Μορφή αρχείου Binary FBX, με έκδοση 7.5.0 |
| static readonly [FBX7600ASCII](../../aspose.threed/fileformat/fbx7600ascii/) | Μορφή αρχείου ASCII FBX, με έκδοση 7.6.0 |
| static readonly [FBX7600Binary](../../aspose.threed/fileformat/fbx7600binary/) | Μορφή αρχείου Binary FBX, με έκδοση 7.6.0 |
| static readonly [FBX7700ASCII](../../aspose.threed/fileformat/fbx7700ascii/) | Μορφή αρχείου ASCII FBX, με έκδοση 7.7.0 |
| static readonly [FBX7700Binary](../../aspose.threed/fileformat/fbx7700binary/) | Μορφή αρχείου Binary FBX, με έκδοση 7.7.0 |
| static readonly [GLTF](../../aspose.threed/fileformat/gltf/) | glTF της Khronos Group |
| static readonly [GLTF2](../../aspose.threed/fileformat/gltf2/) | glTF της Khronos Group, έκδοση 2.0 |
| static readonly [GLTF2_Binary](../../aspose.threed/fileformat/gltf2_binary/) | glTF της Khronos Group, έκδοση 2.0 |
| static readonly [GLTF_Binary](../../aspose.threed/fileformat/gltf_binary/) | glTF της Khronos Group σε δυαδική μορφή |
| static readonly [HTML5](../../aspose.threed/fileformat/html5/) | Αρχείο HTML5 |
| static readonly [IFC](../../aspose.threed/fileformat/ifc/) | Μοντέλο δεδομένων ISO 16739-1 Industry Foundation Classes. |
| static readonly [MayaASCII](../../aspose.threed/fileformat/mayaascii/) | Autodesk Maya σε μορφή ASCII |
| static readonly [MayaBinary](../../aspose.threed/fileformat/mayabinary/) | Autodesk Maya σε μορφή Binary |
| static readonly [Pcd](../../aspose.threed/fileformat/pcd/) | Αρχείο PCL Point Cloud Data σε λειτουργία ASCII |
| static readonly [PcdBinary](../../aspose.threed/fileformat/pcdbinary/) | Αρχείο PCL Point Cloud Data σε λειτουργία Binary |
| static readonly [SiemensJT8](../../aspose.threed/fileformat/siemensjt8/) | Αρχείο Siemens JT Έκδοση 8 |
| static readonly [SiemensJT9](../../aspose.threed/fileformat/siemensjt9/) | Αρχείο Siemens JT Έκδοση 9 |
| static readonly [STLASCII](../../aspose.threed/fileformat/stlascii/) | Μορφή αρχείου ASCII STL |
| static readonly [STLBinary](../../aspose.threed/fileformat/stlbinary/) | Μορφή αρχείου Binary STL |
| static readonly [Universal3D](../../aspose.threed/fileformat/universal3d/) | Μορφή αρχείου Universal3D |
| static readonly [USD](../../aspose.threed/fileformat/usd/) | Universal Scene Description |
| static readonly [USDA](../../aspose.threed/fileformat/usda/) | Universal Scene Description σε μορφή ASCII. |
| static readonly [USDZ](../../aspose.threed/fileformat/usdz/) | Συμπιεσμένο Universal Scene Description |
| static readonly [VRML](../../aspose.threed/fileformat/vrml/) | Η Virtual Reality Modeling Language |
| static readonly [WavefrontOBJ](../../aspose.threed/fileformat/wavefrontobj/) | Μορφή αρχείου Obj της Wavefront |
| static readonly [XBinary](../../aspose.threed/fileformat/xbinary/) | Αρχείο DirectX X σε δυαδική μορφή |
| static readonly [XText](../../aspose.threed/fileformat/xtext/) | Αρχείο DirectX X σε δυαδική μορφή |
| static readonly [Xyz](../../aspose.threed/fileformat/xyz/) | Αρχείο νέφους σημείων Xyz |
| static readonly [Zip](../../aspose.threed/fileformat/zip/) | Αρχείο Zip που περιέχει άλλες μορφές αρχείων 3d. |
| static readonly [Draco](../../aspose.threed/fileformat/draco/) | Google Draco Mesh |
| static readonly [Microsoft3MF](../../aspose.threed/fileformat/microsoft3mf/) | Microsoft 3D Manufacturing Format |
| static readonly [PDF](../../aspose.threed/fileformat/pdf/) | Φορμάτ Φορητών Εγγράφων της Adobe |
| static readonly [PLY](../../aspose.threed/fileformat/ply/) | Μορφή αρχείου Polygon ή Stanford Triangle Format |
| static readonly [RvmBinary](../../aspose.threed/fileformat/rvmbinary/) | Μοντέλο AVEVA Plant Design Management System σε δυαδική μορφή |
| static readonly [RvmText](../../aspose.threed/fileformat/rvmtext/) | Μοντέλο AVEVA Plant Design Management System σε μορφή κειμένου |

### Δείτε επίσης

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


