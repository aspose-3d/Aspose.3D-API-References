---
title: "Enumeración EntityRendererFeatures"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Render.EntityRendererFeatures enum. Las características adicionales que el renderizador de entidades proporcionará"
type: docs
weight: 1980
url: /es/net/aspose.threed.render/entityrendererfeatures/
---
## EntityRendererFeatures enumeration

Las características extra que proporcionará el renderizador de entidades

```csharp
[Flags]
public enum EntityRendererFeatures : byte
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Default | `0` | Sin características adicionales |
| FrameBegin | `1` | El [`EntityRenderer`](../entityrenderer/) observará la devolución de llamada FrameBegin antes de renderizar cada fotograma de la escena |
| FrameEnd | `2` | El [`EntityRenderer`](../entityrenderer/) observará la devolución de llamada FrameBegin después de renderizar cada fotograma de la escena |
| Shadowmap | `4` | Este renderizador puede funcionar en modo shadowmap. |

### Ver también

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


