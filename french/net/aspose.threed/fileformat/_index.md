---
title: "Class FileFormat"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.FileFormat class. Définition du format de fichier"
type: docs
weight: 1060
url: /fr/net/aspose.threed/fileformat/
---
## FileFormat class

Définition du format de fichier.

```csharp
public class FileFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Obtient si Aspose.3D prend en charge l'exportation de la scène vers le format de fichier actuel. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Obtient si Aspose.3D prend en charge l'importation de la scène depuis le format de fichier actuel. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Obtient le type de contenu du format de fichier |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Obtient le nom d'extension de ce type. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Obtient les noms d'extension de ce type. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Obtient le type de format de fichier |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Obtient la version du format de fichier |
| static [Formats](../../aspose.threed/fileformat/formats/) { get; } | Accès à tous les formats pris en charge |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Detect](../../aspose.threed/fileformat/detect/#detect_1)(string) | Détecter le format du fichier à partir du nom du fichier, le fichier doit être lisible afin qu'Aspose.3D puisse détecter le format du fichier via l'en-tête du fichier. |
| static [Detect](../../aspose.threed/fileformat/detect/#detect)(Stream, string) | Détecter le format du fichier à partir du flux de données, le nom du fichier est optionnel pour deviner les types qui n'ont pas d'en-tête magique. |
| static [GetFormatByExtension](../../aspose.threed/fileformat/getformatbyextension/)(string) | Obtient le format de fichier préféré à partir du nom d'extension du fichier. Le nom d'extension doit commencer par un point ('.'). |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Crée des options de chargement par défaut pour ce format de fichier |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Crée des options d'enregistrement par défaut pour ce format de fichier |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formate en chaîne |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [AMF](../../aspose.threed/fileformat/amf/) | Format de fichier de fabrication additive |
| static readonly [ASE](../../aspose.threed/fileformat/ase/) | Format d'exportateur de scène ASCII de 3D Studio Max. |
| static readonly [Aspose3DWeb](../../aspose.threed/fileformat/aspose3dweb/) | Aspose.3D Web format. |
| static readonly [Blender](../../aspose.threed/fileformat/blender/) | Format de fichier 3D de Blender |
| static readonly [Collada](../../aspose.threed/fileformat/collada/) | Format de fichier Collada |
| static readonly [Discreet3DS](../../aspose.threed/fileformat/discreet3ds/) | Format de fichier de 3D Studio |
| static readonly [DXF](../../aspose.threed/fileformat/dxf/) | AutoCAD DXF |
| static readonly [FBX6100ASCII](../../aspose.threed/fileformat/fbx6100ascii/) | Format de fichier FBX ASCII, avec la version 6.1.0 |
| static readonly [FBX6100Binary](../../aspose.threed/fileformat/fbx6100binary/) | Format de fichier FBX binaire, avec la version 6.1.0 |
| static readonly [FBX7200ASCII](../../aspose.threed/fileformat/fbx7200ascii/) | Format de fichier FBX ASCII, avec la version 7.2.0 |
| static readonly [FBX7200Binary](../../aspose.threed/fileformat/fbx7200binary/) | Format de fichier FBX binaire, avec la version 7.2.0 |
| static readonly [FBX7300ASCII](../../aspose.threed/fileformat/fbx7300ascii/) | Format de fichier FBX ASCII, avec la version 7.3.0 |
| static readonly [FBX7300Binary](../../aspose.threed/fileformat/fbx7300binary/) | Format de fichier FBX binaire, avec la version 7.3.0 |
| static readonly [FBX7400ASCII](../../aspose.threed/fileformat/fbx7400ascii/) | Format de fichier FBX ASCII, avec la version 7.4.0 |
| static readonly [FBX7400Binary](../../aspose.threed/fileformat/fbx7400binary/) | Format de fichier FBX binaire, avec la version 7.4.0 |
| static readonly [FBX7500ASCII](../../aspose.threed/fileformat/fbx7500ascii/) | Format de fichier FBX ASCII, avec la version 7.5.0 |
| static readonly [FBX7500Binary](../../aspose.threed/fileformat/fbx7500binary/) | Format de fichier FBX binaire, avec la version 7.5.0 |
| static readonly [FBX7600ASCII](../../aspose.threed/fileformat/fbx7600ascii/) | Format de fichier FBX ASCII, avec la version 7.6.0 |
| static readonly [FBX7600Binary](../../aspose.threed/fileformat/fbx7600binary/) | Format de fichier FBX binaire, avec la version 7.6.0 |
| static readonly [FBX7700ASCII](../../aspose.threed/fileformat/fbx7700ascii/) | Format de fichier FBX ASCII, avec la version 7.7.0 |
| static readonly [FBX7700Binary](../../aspose.threed/fileformat/fbx7700binary/) | Format de fichier FBX binaire, avec la version 7.7.0 |
| static readonly [GLTF](../../aspose.threed/fileformat/gltf/) | glTF du groupe Khronos |
| static readonly [GLTF2](../../aspose.threed/fileformat/gltf2/) | glTF du groupe Khronos version 2.0 |
| static readonly [GLTF2_Binary](../../aspose.threed/fileformat/gltf2_binary/) | glTF du groupe Khronos version 2.0 |
| static readonly [GLTF_Binary](../../aspose.threed/fileformat/gltf_binary/) | glTF du groupe Khronos en format binaire |
| static readonly [HTML5](../../aspose.threed/fileformat/html5/) | Fichier HTML5 |
| static readonly [IFC](../../aspose.threed/fileformat/ifc/) | Modèle de données ISO 16739-1 Industry Foundation Classes. |
| static readonly [MayaASCII](../../aspose.threed/fileformat/mayaascii/) | Autodesk Maya en format ASCII |
| static readonly [MayaBinary](../../aspose.threed/fileformat/mayabinary/) | Autodesk Maya en format binaire |
| static readonly [Pcd](../../aspose.threed/fileformat/pcd/) | Fichier PCL Point Cloud Data en mode ASCII |
| static readonly [PcdBinary](../../aspose.threed/fileformat/pcdbinary/) | Fichier PCL Point Cloud Data en mode binaire |
| static readonly [SiemensJT8](../../aspose.threed/fileformat/siemensjt8/) | Fichier Siemens JT version 8 |
| static readonly [SiemensJT9](../../aspose.threed/fileformat/siemensjt9/) | Fichier Siemens JT version 9 |
| static readonly [STLASCII](../../aspose.threed/fileformat/stlascii/) | Format de fichier STL ASCII |
| static readonly [STLBinary](../../aspose.threed/fileformat/stlbinary/) | Format de fichier STL binaire |
| static readonly [Universal3D](../../aspose.threed/fileformat/universal3d/) | Format de fichier Universal3D |
| static readonly [USD](../../aspose.threed/fileformat/usd/) | Universal Scene Description |
| static readonly [USDA](../../aspose.threed/fileformat/usda/) | Universal Scene Description au format ASCII. |
| static readonly [USDZ](../../aspose.threed/fileformat/usdz/) | Universal Scene Description compressé |
| static readonly [VRML](../../aspose.threed/fileformat/vrml/) | Le Virtual Reality Modeling Language |
| static readonly [WavefrontOBJ](../../aspose.threed/fileformat/wavefrontobj/) | Format de fichier Obj de Wavefront |
| static readonly [XBinary](../../aspose.threed/fileformat/xbinary/) | Fichier X DirectX au format binaire |
| static readonly [XText](../../aspose.threed/fileformat/xtext/) | Fichier X DirectX au format binaire |
| static readonly [Xyz](../../aspose.threed/fileformat/xyz/) | Fichier de nuage de points Xyz |
| static readonly [Zip](../../aspose.threed/fileformat/zip/) | Archive Zip qui contient d'autres formats de fichiers 3d. |
| static readonly [Draco](../../aspose.threed/fileformat/draco/) | Google Draco Mesh |
| static readonly [Microsoft3MF](../../aspose.threed/fileformat/microsoft3mf/) | Microsoft 3D Manufacturing Format |
| static readonly [PDF](../../aspose.threed/fileformat/pdf/) | Format de document portable d'Adobe |
| static readonly [PLY](../../aspose.threed/fileformat/ply/) | Format de fichier Polygon ou Stanford Triangle Format |
| static readonly [RvmBinary](../../aspose.threed/fileformat/rvmbinary/) | Modèle AVEVA Plant Design Management System au format binaire |
| static readonly [RvmText](../../aspose.threed/fileformat/rvmtext/) | Modèle AVEVA Plant Design Management System au format texte |

### Voir aussi

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


