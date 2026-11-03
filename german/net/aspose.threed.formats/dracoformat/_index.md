---
title: "Klasse DracoFormat"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.DracoFormat‑Klasse. Google‑Draco‑Format"
type: docs
weight: 1150
url: /de/net/aspose.threed.formats/dracoformat/
---
## DracoFormat class

Google Draco-Format

```csharp
public class DracoFormat : FileFormat
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
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode)(byte[]) | Dekodiert die Punktwolke oder das Mesh aus Speicher­daten |
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode_1)(string) | Dekodiert die Punktwolke oder das Mesh aus dem angegebenen Dateinamen |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode)(Entity, DracoSaveOptions) | Kodiert das Objekt in rohe Draco‑Daten |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_1)(Entity, Stream, DracoSaveOptions) | Kodiert das Objekt in den angegebenen Stream |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_2)(Entity, string, DracoSaveOptions) | Kodiert das Objekt in die angegebene Datei |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formatiert als Zeichenkette |

## Beispiele

Der folgende Code zeigt, wie man ein Mesh in ein Byte-Array kodiert und daraus dekodiert:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//Mesh in Draco-Format kodieren
byte[] draco = FileFormat.Draco.Encode(mesh);
//Mesh aus Draco-Format dekodieren
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Siehe auch

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


