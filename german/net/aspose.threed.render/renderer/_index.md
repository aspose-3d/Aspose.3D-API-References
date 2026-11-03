---
title: "Klasse Renderer"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Render.Renderer Klasse. Der Kontext zum Renderer"
type: docs
weight: 2340
url: /de/net/aspose.threed.render/renderer/
---
## Renderer class

Der Kontext zum Renderer.

```csharp
public abstract class Renderer : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssetDirectories](../../aspose.threed.render/renderer/assetdirectories/) { get; } | Verzeichnisse, die externe Assets speichern |
| [EnableShadows](../../aspose.threed.render/renderer/enableshadows/) { get; set; } | Liest oder setzt, ob Schatten aktiviert werden sollen. |
| [FallbackEntityRenderer](../../aspose.threed.render/renderer/fallbackentityrenderer/) { get; set; } | Liest oder setzt den Fallback-Entitätsrenderer, wenn für die Entität kein spezieller Renderer definiert ist. |
| virtual [Frustum](../../aspose.threed.render/renderer/frustum/) { get; set; } | Liest oder setzt das Sichtvolumen, das zur Bereitstellung der Ansichtsmatrix verwendet wird. |
| virtual [Material](../../aspose.threed.render/renderer/material/) { get; set; } | Liest oder setzt das Material, das zur Bereitstellung von Materialinformationen verwendet wird, die von Shadern genutzt werden. |
| [Node](../../aspose.threed.render/renderer/node/) { get; set; } | Liest oder setzt die [`Node`](./node/) Instanz, die zur Bereitstellung der Welttransformationsmatrix verwendet wird. |
| [PostProcessings](../../aspose.threed.render/renderer/postprocessings/) { get; } | Aktive Nachbearbeitungskette |
| [PresetShaders](../../aspose.threed.render/renderer/presetshaders/) { get; set; } | Liest oder setzt das voreingestellte Shader-Set |
| abstract [RenderFactory](../../aspose.threed.render/renderer/renderfactory/) { get; } | Liest die Fabrik zum Erzeugen renderbezogener Objekte. |
| [RenderStage](../../aspose.threed.render/renderer/renderstage/) { get; } | Liest die aktuelle Renderstufe. |
| [RenderTarget](../../aspose.threed.render/renderer/rendertarget/) { get; } | Geben Sie das Renderziel an, auf dem die folgenden Renderoperationen ausgeführt werden. |
| [Shader](../../aspose.threed.render/renderer/shader/) { get; set; } | Liest oder setzt die Shader-Instanz, die zum Rendern der Geometrie verwendet wird. |
| [ShaderSet](../../aspose.threed.render/renderer/shaderset/) { get; set; } | Liest oder setzt das Shader-Set, das zum Rendern der Szene verwendet wird |
| [Variables](../../aspose.threed.render/renderer/variables/) { get; } | Zugriff auf die internen Variablen, die für das Rendern verwendet werden |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateRenderer](../../aspose.threed.render/renderer/createrenderer/)() | Erstellt einen neuen `Renderer` mit dem Standardprofil. |
| virtual [ClearCache](../../aspose.threed.render/renderer/clearcache/)() | Cache manuell leeren. Aspose.3D cached einige Objekte wie Materialien/Geometrien in internen Typen, die mit der Rendering-Pipeline kompatibel sind. Dies sollte manuell aufgerufen werden, wenn die Szene größere Änderungen erfährt. |
| [Dispose](../../aspose.threed.render/renderer/dispose/)() | Entfernen Sie den `Renderer` und alle zugehörigen Ressourcen |
| abstract [Execute](../../aspose.threed.render/renderer/execute/)(PostProcessing, IRenderTarget) | Führen Sie eine Nachbearbeitung auf dem angegebenen Renderziel aus |
| [GetPostProcessing](../../aspose.threed.render/renderer/getpostprocessing/)(string) | Gibt einen integrierten Nachbearbeiter zurück, der vom Renderer unterstützt wird. |
| virtual [RegisterEntityRenderer](../../aspose.threed.render/renderer/registerentityrenderer/)(EntityRenderer) | Registrieren Sie den Entity-Renderer für die angegebene Entität |
| virtual [Render](../../aspose.threed.render/renderer/render/)(IRenderTarget) | Rendern Sie das angegebene Ziel |

### Siehe auch

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


