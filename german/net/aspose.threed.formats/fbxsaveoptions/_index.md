---
title: "Klasse FbxSaveOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.FbxSaveOptions‑Klasse. Speicheroptionen für Fbx‑Datei"
type: docs
weight: 1180
url: /de/net/aspose.threed.formats/fbxsaveoptions/
---
## FbxSaveOptions class

Speicheroptionen für FBX-Datei.

```csharp
public class FbxSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FbxSaveOptions](fbxsaveoptions/#constructor)(FileContentType) | Initialisiert ein `FbxSaveOptions` mit der neuesten unterstützten Version. |
| [FbxSaveOptions](fbxsaveoptions/#constructor_1)(FileFormat) | Initialisiert ein `FbxSaveOptions` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/fbxsaveoptions/embedtextures/) { get; set; } | Liest oder setzt, ob die Textur in die endgültige Ausgabedatei eingebettet wird. Der FBX‑Exporter versucht, die Rohdaten der Textur aus [`FileSystem`](../ioconfig/filesystem/) zu finden und die Datei in die endgültige FBX‑Datei einzubetten. Standardwert ist false. |
| [EnableCompression](../../aspose.threed.formats/fbxsaveoptions/enablecompression/) { get; set; } | Komprimiert große Binärdaten in der FBX‑Datei (z. B. Animationsdaten, Kontrollpunkte, Vertex‑Element‑Daten, Indizes), Standardwert ist true. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [ExportLegacyMaterialProperties](../../aspose.threed.formats/fbxsaveoptions/exportlegacymaterialproperties/) { get; set; } | Liest oder setzt, ob veraltete Materialeigenschaften exportiert werden, verwendet für die Rückwärtskompatibilität. Diese Option ist standardmäßig aktiviert. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Versucht, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [FoldRepeatedCurveData](../../aspose.threed.formats/fbxsaveoptions/foldrepeatedcurvedata/) { get; set; } | Liest oder setzt, ob wiederholte Kurvendaten wiederverwendet werden, indem die Referenzzählung der letzten Daten erhöht wird |
| [GenerateVertexElementMaterial](../../aspose.threed.formats/fbxsaveoptions/generatevertexelementmaterial/) { get; set; } | Liest oder setzt, ob stets ein [`VertexElementMaterial`](../../aspose.threed.entities/vertexelementmaterial/) für Geometrien erzeugt wird, wenn der zugehörige Knoten Materialien enthält. Dies ist standardmäßig deaktiviert. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |
| [ReusePrimitiveMesh](../../aspose.threed.formats/fbxsaveoptions/reuseprimitivemesh/) { get; set; } | Verwendet das Mesh für Primitive mit denselben Parametern erneut, wodurch die Größe der FBX‑Ausgabe, die aus einer großen Menge primitiver Formen (z. B. aus CAD‑Dateien) erstellt wurde, erheblich reduziert wird. Standardwert ist false |
| [VideoForTexture](../../aspose.threed.formats/fbxsaveoptions/videofortexture/) { get; set; } | Liest oder setzt, ob beim Exportieren als FBX eine Video‑Instanz für [`Texture`](../../aspose.threed.shading/texture/) erzeugt wird. |

### Siehe auch

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


