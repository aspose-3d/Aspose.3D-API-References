---
title: "Klasse RvmSaveOptions"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.RvmSaveOptions Klasse. Speicheroptionen für Aveva PDMS RVM-Datei"
type: docs
weight: 1480
url: /de/net/aspose.threed.formats/rvmsaveoptions/
---
## RvmSaveOptions class

Speicheroptionen für die Aveva PDMS RVM-Datei.

```csharp
public class RvmSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RvmSaveOptions](rvmsaveoptions/#constructor)() | Konstruktor von `RvmSaveOptions` |
| [RvmSaveOptions](rvmsaveoptions/#constructor_1)(FileContentType) | Konstruktor von `RvmSaveOptions` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AttributeListFile](../../aspose.threed.formats/rvmsaveoptions/attributelistfile/) { get; set; } | Liest oder setzt den Dateinamen der Attributlistendatei, der Exporter erzeugt einen Namen basierend auf dem .rvm-Dateinamen, wenn diese Eigenschaft nicht definiert ist, Standardwert ist null. |
| [AttributePrefix](../../aspose.threed.formats/rvmsaveoptions/attributeprefix/) { get; set; } | Liest oder setzt das Präfix der Attribute, die exportiert werden sollen; die exportierten Eigenschaften enthalten kein Präfix, benutzerdefinierte Eigenschaften mit anderem Präfix werden nicht exportiert, Standardwert ist 'rvm:'. Zum Beispiel, wenn eine Eigenschaft rvm:Refno=345 ist, wird das exportierte Attribut Refno = 345 sein, das Präfix wird entfernt. |
| [Author](../../aspose.threed.formats/rvmsaveoptions/author/) { get; set; } | Autorinformationen, Standardwert ist '3d@aspose' |
| [CreationTime](../../aspose.threed.formats/rvmsaveoptions/creationtime/) { get; set; } | Der Zeitstempel, der diese Datei exportierte, Standardwert ist die aktuelle Zeit |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Liest oder setzt die Standardkodierung für textbasierte Dateien. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter die zu verwendende Kodierung entscheidet. |
| [ExportAttributes](../../aspose.threed.formats/rvmsaveoptions/exportattributes/) { get; set; } | Liest oder setzt, ob die Attributliste in eine externe .att-Datei exportiert werden soll, Standardwert ist false. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Versucht, Texturen, die in der Szene verwendet werden, in das Ausgabeverzeichnis zu kopieren. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Liest das Dateiformat, das in der aktuellen Speicher-/Ladeoption angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Der Dateiname der exportierenden/importierenden Szene. Dies ist optional, aber nützlich beim Serialisieren externer Assets wie dem Material von OBJ. |
| [FileNote](../../aspose.threed.formats/rvmsaveoptions/filenote/) { get; set; } | Dateikommentar im Dateikopf. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Ermöglicht dem Benutzer zu steuern, wie externe Abhängigkeiten während Laden/Speichern verwaltet werden. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Einige Dateien wie OBJ hängen von externen Dateien ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |

## Beispiele

Der folgende Code zeigt, wie man Attribute in RVM exportiert.

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//Der Name des Knotens ist erforderlich, um Attribute zu exportieren
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//Eigenschaften mit dem Präfix rvm: werden exportiert.
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### Siehe auch

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


