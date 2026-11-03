---
title: "Klasse Watermark"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Utilities.Watermark Klasse. Dienstprogramm zum Codieren/Dekodieren eines blinden Wasserzeichens zu/von einem Mesh"
type: docs
weight: 2950
url: /de/net/aspose.threed.utilities/watermark/
---
## Watermark class

Hilfsprogramm zum Codieren/Dekodieren eines Blindwasserzeichens in/einem Mesh.

```csharp
public class Watermark
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark)(Mesh) | Dekodiere das Wasserzeichen aus einem Mesh |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark_1)(Mesh, string) | Dekodiere das Wasserzeichen aus einem Mesh |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark)(Mesh, string) | Kodieren Sie einen Text in das blinde Wasserzeichen des Meshes. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_1)(Mesh, string, string) | Kodieren Sie einen Text in das blinde Wasserzeichen des Meshes. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_2)(Mesh, string, string, bool) | Kodieren Sie einen Text in das blinde Wasserzeichen des Meshes. |

## Hinweise

Sowohl [`EncodeWatermark`](./encodewatermark/) als auch [`DecodeWatermark`](./decodewatermark/) führen eine Lizenzprüfung durch. Die Nutzung in der Testversion löst eine Ausnahme aus; Sie können [`SuppressTrialException`](../../aspose.threed/trialexception/suppresstrialexception/) verwenden, um die Ausnahme zu unterdrücken, aber dies hebt die Beschränkung hier nicht auf. Eine gültige Lizenz ist erforderlich, um diese Funktionen ohne Einschränkungen zu nutzen.

## Beispiele

Der folgende Code zeigt, wie man ein blindes Wasserzeichen in ein Mesh einbettet und es dekodiert.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", null);
var watermark = Watermark.DecodeWatermark(encodedMesh, null);
```

### Siehe auch

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


