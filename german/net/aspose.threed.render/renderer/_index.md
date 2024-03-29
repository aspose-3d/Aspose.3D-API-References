---
title: Renderer
second_title: Aspose.3D für .NET-API-Referenz
description: Der Kontext zum Renderer.
type: docs
weight: 2100
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
| [AssetDirectories](../../aspose.threed.render/renderer/assetdirectories) { get; } | Verzeichnisse, die externe Assets gespeichert haben |
| [EnableShadows](../../aspose.threed.render/renderer/enableshadows) { get; set; } | Ruft ab oder legt fest, ob Schatten aktiviert werden sollen. |
| [FallbackEntityRenderer](../../aspose.threed.render/renderer/fallbackentityrenderer) { get; set; } | Ruft den Fallback-Entitätsrenderer ab oder legt ihn fest, wenn für die Entität kein spezieller Renderer definiert ist. |
| virtual [Frustum](../../aspose.threed.render/renderer/frustum) { get; set; } | Ruft das Frustum ab oder legt es fest, das verwendet wurde, um die Ansichtsmatrix bereitzustellen. |
| virtual [Material](../../aspose.threed.render/renderer/material) { get; set; } | Ruft das Material ab oder legt es fest, das verwendet wurde, um von Shadern verwendete Materialinformationen bereitzustellen. |
| [Node](../../aspose.threed.render/renderer/node) { get; set; } | Ruft ab oder setzt die[`Node`](./node) Instanz, die verwendet wird, um die Welttransformationsmatrix bereitzustellen. |
| [PostProcessings](../../aspose.threed.render/renderer/postprocessings) { get; } | Aktive Nachbearbeitungskette |
| [PresetShaders](../../aspose.threed.render/renderer/presetshaders) { get; set; } | Holt oder setzt den voreingestellten Shader set |
| abstract [RenderFactory](../../aspose.threed.render/renderer/renderfactory) { get; } | Ruft die Factory ab, um renderbezogene Objekte zu erstellen. |
| [RenderStage](../../aspose.threed.render/renderer/renderstage) { get; } | Ruft die aktuelle Renderstufe ab. |
| [RenderTarget](../../aspose.threed.render/renderer/rendertarget) { get; } | Geben Sie das Renderziel an, für das die folgenden Rendervorgänge ausgeführt werden. |
| [Shader](../../aspose.threed.render/renderer/shader) { get; set; } | Ruft die zum Rendern der Geometrie verwendete Shader-Instanz ab oder legt sie fest. |
| [ShaderSet](../../aspose.threed.render/renderer/shaderset) { get; set; } | Ruft das Shader-Set ab oder legt es fest, das zum Rendern der Szene verwendet wurde |
| [Variables](../../aspose.threed.render/renderer/variables) { get; } | Zugriff auf die zum Rendern verwendeten internen Variablen |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateRenderer](../../aspose.threed.render/renderer/createrenderer)() | Erstellt eine neue[`Renderer`](../renderer)mit Standardprofil. |
| virtual [ClearCache](../../aspose.threed.render/renderer/clearcache)() | Leeren Sie den Cache manuell. Aspose.3D speichert einige Objekte wie Materialien/Geometrien in internen Typen, die mit der Renderpipeline kompatibel sind. Dies sollte manuell aufgerufen werden, wenn die Szene größere Änderungen aufweist. |
| [Dispose](../../aspose.threed.render/renderer/dispose)() | Entsorgen Sie die[`Renderer`](../renderer) und alle zugehörigen Ressourcen |
| abstract [Execute](../../aspose.threed.render/renderer/execute)(PostProcessing, IRenderTarget) | Führt eine Nachbearbeitung auf dem angegebenen Renderziel aus |
| [GetPostProcessing](../../aspose.threed.render/renderer/getpostprocessing)(string) | Ruft einen integrierten Postprozessor ab, der vom Renderer unterstützt wird. |
| virtual [RegisterEntityRenderer](../../aspose.threed.render/renderer/registerentityrenderer)(EntityRenderer) | Registrieren Sie den Entitäts-Renderer für die angegebene Entität |
| virtual [Render](../../aspose.threed.render/renderer/render)(IRenderTarget) | Rendern des angegebenen Ziels |

### Siehe auch

* namensraum [Aspose.ThreeD.Render](../../aspose.threed.render)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
