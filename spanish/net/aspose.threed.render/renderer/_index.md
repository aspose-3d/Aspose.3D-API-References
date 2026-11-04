---
title: "Clase Renderer"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Render.Renderer class. El contexto sobre el renderizador"
type: docs
weight: 2340
url: /es/net/aspose.threed.render/renderer/
---
## Renderer class

El contexto sobre el renderizador.

```csharp
public abstract class Renderer : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssetDirectories](../../aspose.threed.render/renderer/assetdirectories/) { get; } | Directorios que almacenan activos externos |
| [EnableShadows](../../aspose.threed.render/renderer/enableshadows/) { get; set; } | Obtiene o establece si se habilitan las sombras. |
| [FallbackEntityRenderer](../../aspose.threed.render/renderer/fallbackentityrenderer/) { get; set; } | Obtiene o establece el renderizador de entidad de reserva cuando la entidad no tiene un renderizador especial definido. |
| virtual [Frustum](../../aspose.threed.render/renderer/frustum/) { get; set; } | Obtiene o establece el frustum que se usa para proporcionar la matriz de vista. |
| virtual [Material](../../aspose.threed.render/renderer/material/) { get; set; } | Obtiene o establece el material que se usa para proporcionar la información del material utilizada por los shaders. |
| [Node](../../aspose.threed.render/renderer/node/) { get; set; } | Obtiene o establece la instancia [`Node`](./node/) que se usa para proporcionar la matriz de transformación mundial. |
| [PostProcessings](../../aspose.threed.render/renderer/postprocessings/) { get; } | Cadena de postprocesamiento activa |
| [PresetShaders](../../aspose.threed.render/renderer/presetshaders/) { get; set; } | Obtiene o establece el conjunto de shaders predefinido |
| abstract [RenderFactory](../../aspose.threed.render/renderer/renderfactory/) { get; } | Obtiene la fábrica para crear objetos relacionados con el renderizado. |
| [RenderStage](../../aspose.threed.render/renderer/renderstage/) { get; } | Obtiene la etapa de renderizado actual. |
| [RenderTarget](../../aspose.threed.render/renderer/rendertarget/) { get; } | Especifique el objetivo de renderizado en el que se realizarán las siguientes operaciones de renderizado. |
| [Shader](../../aspose.threed.render/renderer/shader/) { get; set; } | Obtiene o establece la instancia del shader utilizada para renderizar la geometría. |
| [ShaderSet](../../aspose.threed.render/renderer/shaderset/) { get; set; } | Obtiene o establece el conjunto de shaders que se usa para renderizar la escena |
| [Variables](../../aspose.threed.render/renderer/variables/) { get; } | Acceso a las variables internas utilizadas para el renderizado |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateRenderer](../../aspose.threed.render/renderer/createrenderer/)() | Crea un nuevo `Renderer` con el perfil predeterminado. |
| virtual [ClearCache](../../aspose.threed.render/renderer/clearcache/)() | Borre manualmente la caché. Aspose.3D almacenará en caché algunos objetos como materiales/geometrías en tipos internos compatibles con la canalización de renderizado. Esto debe llamarse manualmente cuando la escena tenga cambios importantes. |
| [Dispose](../../aspose.threed.render/renderer/dispose/)() | Libere el `Renderer` y todos los recursos relacionados |
| abstract [Execute](../../aspose.threed.render/renderer/execute/)(PostProcessing, IRenderTarget) | Ejecute un postprocesamiento en el objetivo de renderizado especificado |
| [GetPostProcessing](../../aspose.threed.render/renderer/getpostprocessing/)(string) | Obtiene un postprocesador integrado que es compatible con el renderizador. |
| virtual [RegisterEntityRenderer](../../aspose.threed.render/renderer/registerentityrenderer/)(EntityRenderer) | Registre el renderizador de entidad para la entidad especificada |
| virtual [Render](../../aspose.threed.render/renderer/render/)(IRenderTarget) | Renderice el objetivo especificado |

### Ver también

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


