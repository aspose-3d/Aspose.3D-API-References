---
title: "Klasse FileFormat"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.FileFormat Klasse. Dateiformatdefinition"
type: docs
weight: 1060
url: /de/net/aspose.threed/fileformat/
---
## FileFormat class

Dateiformatdefinition

```csharp
public class FileFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Liest, ob Aspose.3D den Export der Szene in das aktuelle Dateiformat unterstützt. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Liest, ob Aspose.3D den Import der Szene aus dem aktuellen Dateiformat unterstützt. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Liest den Inhaltstyp des Dateiformats |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Liest den Erweiterungsnamen dieses Typs. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Liest die Erweiterungsnamen dieses Typs. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Liest den Dateiformattyp |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Liest die Dateiformatversion |
| static [Formats](../../aspose.threed/fileformat/formats/) { get; } | Zugriff auf alle unterstützten Formate |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Detect](../../aspose.threed/fileformat/detect/#detect_1)(string) | Erkennen Sie das Dateiformat anhand des Dateinamens, die Datei muss lesbar sein, damit Aspose.3D das Dateiformat über den Dateikopf erkennen kann. |
| static [Detect](../../aspose.threed/fileformat/detect/#detect)(Stream, string) | Erkennen Sie das Dateiformat aus dem Datenstrom, der Dateiname ist optional, um Typen zu erraten, die keinen Magic-Header haben. |
| static [GetFormatByExtension](../../aspose.threed/fileformat/getformatbyextension/)(string) | Ermittelt das bevorzugte Dateiformat aus dem Dateierweiterungsnamen. Der Erweiterungsname sollte mit einem Punkt ('.') beginnen. |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Erstelle Standard-Ladeoptionen für dieses Dateiformat |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Erstelle standardmäßige Speicheroptionen für dieses Dateiformat |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formatiert als Zeichenkette |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [AMF](../../aspose.threed/fileformat/amf/) | Dateiformat für additive Fertigung |
| static readonly [ASE](../../aspose.threed/fileformat/ase/) | ASCII-Szenenexportformat von 3D Studio Max. |
| static readonly [Aspose3DWeb](../../aspose.threed/fileformat/aspose3dweb/) | Aspose.3D Web-Format. |
| static readonly [Blender](../../aspose.threed/fileformat/blender/) | 3D-Dateiformat von Blender |
| static readonly [Collada](../../aspose.threed/fileformat/collada/) | Collada-Dateiformat |
| static readonly [Discreet3DS](../../aspose.threed/fileformat/discreet3ds/) | Dateiformat von 3D Studio |
| static readonly [DXF](../../aspose.threed/fileformat/dxf/) | AutoCAD DXF |
| static readonly [FBX6100ASCII](../../aspose.threed/fileformat/fbx6100ascii/) | ASCII FBX-Dateiformat, Version 6.1.0 |
| static readonly [FBX6100Binary](../../aspose.threed/fileformat/fbx6100binary/) | Binäres FBX-Dateiformat, Version 6.1.0 |
| static readonly [FBX7200ASCII](../../aspose.threed/fileformat/fbx7200ascii/) | ASCII FBX-Dateiformat, Version 7.2.0 |
| static readonly [FBX7200Binary](../../aspose.threed/fileformat/fbx7200binary/) | Binäres FBX-Dateiformat, Version 7.2.0 |
| static readonly [FBX7300ASCII](../../aspose.threed/fileformat/fbx7300ascii/) | ASCII FBX-Dateiformat, Version 7.3.0 |
| static readonly [FBX7300Binary](../../aspose.threed/fileformat/fbx7300binary/) | Binäres FBX-Dateiformat, Version 7.3.0 |
| static readonly [FBX7400ASCII](../../aspose.threed/fileformat/fbx7400ascii/) | ASCII FBX-Dateiformat, Version 7.4.0 |
| static readonly [FBX7400Binary](../../aspose.threed/fileformat/fbx7400binary/) | Binäres FBX-Dateiformat, Version 7.4.0 |
| static readonly [FBX7500ASCII](../../aspose.threed/fileformat/fbx7500ascii/) | ASCII FBX-Dateiformat, mit Version 7.5.0 |
| static readonly [FBX7500Binary](../../aspose.threed/fileformat/fbx7500binary/) | Binäres FBX-Dateiformat, mit Version 7.5.0 |
| static readonly [FBX7600ASCII](../../aspose.threed/fileformat/fbx7600ascii/) | ASCII FBX-Dateiformat, mit Version 7.6.0 |
| static readonly [FBX7600Binary](../../aspose.threed/fileformat/fbx7600binary/) | Binäres FBX-Dateiformat, mit Version 7.6.0 |
| static readonly [FBX7700ASCII](../../aspose.threed/fileformat/fbx7700ascii/) | ASCII FBX-Dateiformat, mit Version 7.7.0 |
| static readonly [FBX7700Binary](../../aspose.threed/fileformat/fbx7700binary/) | Binäres FBX-Dateiformat, mit Version 7.7.0 |
| static readonly [GLTF](../../aspose.threed/fileformat/gltf/) | glTF der Khronos Group |
| static readonly [GLTF2](../../aspose.threed/fileformat/gltf2/) | glTF Version 2.0 der Khronos Group |
| static readonly [GLTF2_Binary](../../aspose.threed/fileformat/gltf2_binary/) | glTF Version 2.0 der Khronos Group |
| static readonly [GLTF_Binary](../../aspose.threed/fileformat/gltf_binary/) | glTF der Khronos Group im Binärformat |
| static readonly [HTML5](../../aspose.threed/fileformat/html5/) | HTML5-Datei |
| static readonly [IFC](../../aspose.threed/fileformat/ifc/) | ISO 16739-1 Industry Foundation Classes Datenmodell. |
| static readonly [MayaASCII](../../aspose.threed/fileformat/mayaascii/) | Autodesk Maya im ASCII-Format |
| static readonly [MayaBinary](../../aspose.threed/fileformat/mayabinary/) | Autodesk Maya im Binärformat |
| static readonly [Pcd](../../aspose.threed/fileformat/pcd/) | PCL Point Cloud Data-Datei im ASCII-Modus |
| static readonly [PcdBinary](../../aspose.threed/fileformat/pcdbinary/) | PCL Point Cloud Data-Datei im Binärmodus |
| static readonly [SiemensJT8](../../aspose.threed/fileformat/siemensjt8/) | Siemens JT-Datei Version 8 |
| static readonly [SiemensJT9](../../aspose.threed/fileformat/siemensjt9/) | Siemens JT-Datei Version 9 |
| static readonly [STLASCII](../../aspose.threed/fileformat/stlascii/) | ASCII STL-Dateiformat |
| static readonly [STLBinary](../../aspose.threed/fileformat/stlbinary/) | Binäres STL-Dateiformat |
| static readonly [Universal3D](../../aspose.threed/fileformat/universal3d/) | Universal3D-Dateiformat |
| static readonly [USD](../../aspose.threed/fileformat/usd/) | Universal Scene Description |
| static readonly [USDA](../../aspose.threed/fileformat/usda/) | Universal Scene Description im ASCII-Format. |
| static readonly [USDZ](../../aspose.threed/fileformat/usdz/) | Komprimierte Universal Scene Description |
| static readonly [VRML](../../aspose.threed/fileformat/vrml/) | Die Virtual Reality Modeling Language |
| static readonly [WavefrontOBJ](../../aspose.threed/fileformat/wavefrontobj/) | Obj-Dateiformat von Wavefront |
| static readonly [XBinary](../../aspose.threed/fileformat/xbinary/) | DirectX X-Datei im Binärformat |
| static readonly [XText](../../aspose.threed/fileformat/xtext/) | DirectX X-Datei im Binärformat |
| static readonly [Xyz](../../aspose.threed/fileformat/xyz/) | Xyz-Punktwolken-Datei |
| static readonly [Zip](../../aspose.threed/fileformat/zip/) | Zip-Archiv, das andere 3D-Dateiformate enthält. |
| static readonly [Draco](../../aspose.threed/fileformat/draco/) | Google Draco Mesh |
| static readonly [Microsoft3MF](../../aspose.threed/fileformat/microsoft3mf/) | Microsoft 3D Manufacturing Format |
| static readonly [PDF](../../aspose.threed/fileformat/pdf/) | Adobes Portable Document Format |
| static readonly [PLY](../../aspose.threed/fileformat/ply/) | Polygon File Format oder Stanford Triangle Format |
| static readonly [RvmBinary](../../aspose.threed/fileformat/rvmbinary/) | AVEVA Plant Design Management System Modell im Binärformat |
| static readonly [RvmText](../../aspose.threed/fileformat/rvmtext/) | AVEVA Plant Design Management System Modell im Textformat |

### Siehe auch

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


