---
title: "Klasse PlyFormat"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.PlyFormat Klasse. Das PLY-Format"
type: docs
weight: 1430
url: /de/net/aspose.threed.formats/plyformat/
---
## PlyFormat class

Das PLY-Format.

```csharp
public class PlyFormat : FileFormat
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

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Erstelle Standard-Ladeoptionen für dieses Dateiformat |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Erstelle standardmäßige Speicheroptionen für dieses Dateiformat |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode)(Stream) | Dekodieren Sie eine Punktwolke oder ein Mesh aus dem angegebenen Stream. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_2)(string) | Dekodieren Sie eine Punktwolke oder ein Mesh aus dem angegebenen Stream. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_1)(Stream, PlyLoadOptions) | Dekodieren Sie eine Punktwolke oder ein Mesh aus dem angegebenen Stream. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_3)(string, PlyLoadOptions) | Dekodieren Sie eine Punktwolke oder ein Mesh aus dem angegebenen Stream. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode)(Entity, Stream) | Kodieren Sie das Objekt und speichern Sie das Ergebnis in den Stream. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_2)(Entity, string) | Kodieren Sie das Objekt und speichern Sie das Ergebnis in einer externen Datei. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_1)(Entity, Stream, PlySaveOptions) | Kodieren Sie das Objekt und speichern Sie das Ergebnis in den Stream. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_3)(Entity, string, PlySaveOptions) | Kodieren Sie das Objekt und speichern Sie das Ergebnis in einer externen Datei. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formatiert als Zeichenkette |

## Beispiele

Der folgende Code zeigt, wie ein Mesh in eine PLY-Datei kodiert wird:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//Mesh in PLY-Format kodieren
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

Der folgende Code zeigt, wie ein Mesh aus einer PLY-Datei dekodiert wird:

```csharp
//Eine Testdatei zum Dekodieren erzeugen
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Datei dekodieren
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Siehe auch

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


