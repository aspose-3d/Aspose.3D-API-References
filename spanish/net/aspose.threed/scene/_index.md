---
title: "Clase Scene"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Scene. Una escena es un objeto de nivel superior que contiene los nodos, geometrías, materiales, texturas, animaciones, poses, subescenas, etc. La escena puede tener subescenas y actúa como soporte de documentos múltiples en archivos como collada/blender/fbx. La jerarquía de nodos se puede acceder a través de RootNodeLibrary y se utiliza para mantener una referencia de objetos no adjuntos durante la serialización, como metadatos o objetos personalizados, para que pueda usarse como una biblioteca."
type: docs
weight: 2500
url: /es/net/aspose.threed/scene/
---
## Scene class

Una escena es un objeto de nivel superior que contiene los nodos, geometrías, materiales, texturas, animación, poses, sub-escenas, etc. La escena puede tener sub-escenas, actúa como soporte de documentos múltiples en archivos como collada/blender/fbx. La jerarquía de nodos se puede acceder a través de [`RootNode`](./rootnode/)[`Library`](./library/) y se utiliza para mantener una referencia de objetos no adjuntos durante la serialización (como metadatos o objetos personalizados) para que pueda usarse como una biblioteca.

```csharp
public class Scene : SceneObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Scene](scene/#constructor)() | Inicializa una nueva instancia de la clase `Scene`. |
| [Scene](scene/#constructor_1)(Entity) | Inicializa una nueva instancia de la clase `Scene` con una entidad adjunta a un nodo nuevo. |
| [Scene](scene/#constructor_2)(Scene, string) | Inicializa una nueva instancia de la clase `Scene` como una subescena. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnimationClips](../../aspose.threed/scene/animationclips/) { get; } | Obtiene todos los [`AnimationClip`](../../aspose.threed.animation/animationclip/) definidos en la escena. |
| [AssetInfo](../../aspose.threed/scene/assetinfo/) { get; set; } | Obtiene o establece la información de activos de nivel superior |
| [CurrentAnimationClip](../../aspose.threed/scene/currentanimationclip/) { get; set; } | Obtiene o establece el [`AnimationClip`](../../aspose.threed.animation/animationclip/) activo |
| [Library](../../aspose.threed/scene/library/) { get; } | Los objetos que no se usan directamente en la jerarquía de la escena pueden definirse en la Biblioteca. Esto es útil cuando utilizas subescenas y colocas componentes reutilizables bajo subescenas. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Poses](../../aspose.threed/scene/poses/) { get; } | Obtiene todos los [`Pose`](../pose/) usados en esta escena. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [RootNode](../../aspose.threed/scene/rootnode/) { get; } | Obtiene el nodo raíz de la escena. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [SubScenes](../../aspose.threed/scene/subscenes/) { get; } | Obtiene todas las subescenas |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile)(string) | Abre la escena desde la ruta especificada |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_3)(string, CancellationToken) | Abre la escena desde la ruta especificada |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_1)(string, FileFormat, CancellationToken) | Abre la escena desde la ruta especificada usando el formato de archivo especificado. |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_2)(string, LoadOptions, CancellationToken) | Abre la escena desde la ruta especificada usando el formato de archivo especificado. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_2)(Stream, CancellationToken) | Abre la escena desde el flujo especificado |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream)(Stream, FileFormat, CancellationToken) | Abre la escena desde el flujo especificado usando el formato de archivo especificado. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_1)(Stream, LoadOptions, CancellationToken) | Abre la escena desde el flujo especificado usando la configuración de E/S especificada. |
| [Clear](../../aspose.threed/scene/clear/)() | Borra el contenido de la escena y restaura la configuración predeterminada. |
| [CreateAnimationClip](../../aspose.threed/scene/createanimationclip/)(string) | Una función abreviada para crear y registrar el [`AnimationClip`](../../aspose.threed.animation/animationclip/). El primer [`AnimationClip`](../../aspose.threed.animation/animationclip/) será asignado al [`CurrentAnimationClip`](./currentanimationclip/) |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetAnimationClip](../../aspose.threed/scene/getanimationclip/)(string) | Obtiene un [`AnimationClip`](../../aspose.threed.animation/animationclip/) con nombre |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [Open](../../aspose.threed/scene/open/#open)(Stream) | Abre la escena desde el flujo especificado |
| [Open](../../aspose.threed/scene/open/#open_4)(string) | Abre la escena desde la ruta especificada |
| [Open](../../aspose.threed/scene/open/#open_3)(Stream, CancellationToken) | Abre la escena desde el flujo especificado |
| [Open](../../aspose.threed/scene/open/#open_8)(string, CancellationToken) | Abre la escena desde la ruta especificada |
| [Open](../../aspose.threed/scene/open/#open_6)(string, LoadOptions) | Abre la escena desde la ruta especificada usando el formato de archivo especificado. |
| [Open](../../aspose.threed/scene/open/#open_1)(Stream, FileFormat, CancellationToken) | Abre la escena desde el flujo especificado usando el formato de archivo especificado. |
| [Open](../../aspose.threed/scene/open/#open_2)(Stream, LoadOptions, CancellationToken) | Abre la escena desde el flujo especificado usando la configuración de E/S especificada. |
| [Open](../../aspose.threed/scene/open/#open_5)(string, FileFormat, CancellationToken) | Abre la escena desde la ruta especificada usando el formato de archivo especificado. |
| [Open](../../aspose.threed/scene/open/#open_7)(string, LoadOptions, CancellationToken) | Abre la escena desde la ruta especificada usando el formato de archivo especificado. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [Render](../../aspose.threed/scene/render/#render_2)(Camera, string) | Renderiza la escena a un archivo externo desde la perspectiva de la cámara especificada. El tamaño de salida predeterminado es 1024x768 y el formato de salida es png |
| [Render](../../aspose.threed/scene/render/#render)(Camera, TextureData) | Renderiza la escena a un bitmap desde la perspectiva de la cámara especificada. |
| [Render](../../aspose.threed/scene/render/#render_1)(Camera, TextureData, ImageRenderOptions) | Renderiza la escena a un bitmap desde la perspectiva de la cámara especificada. |
| [Render](../../aspose.threed/scene/render/#render_3)(Camera, string, Vector2, string) | Renderiza la escena a un archivo externo desde la perspectiva de la cámara especificada. |
| [Render](../../aspose.threed/scene/render/#render_4)(Camera, string, Vector2, string, ImageRenderOptions) | Renderiza la escena a un archivo externo desde la perspectiva de la cámara especificada. |
| [Save](../../aspose.threed/scene/save/#save_4)(string) | Guarda la escena en la ruta especificada usando el formato de archivo especificado. |
| [Save](../../aspose.threed/scene/save/#save)(Stream, FileFormat) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [Save](../../aspose.threed/scene/save/#save_2)(Stream, SaveOptions) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [Save](../../aspose.threed/scene/save/#save_5)(string, FileFormat) | Guarda la escena en la ruta especificada usando el formato de archivo especificado. |
| [Save](../../aspose.threed/scene/save/#save_7)(string, SaveOptions) | Guarda la escena en la ruta especificada usando el formato de archivo especificado. |
| [Save](../../aspose.threed/scene/save/#save_1)(Stream, FileFormat, CancellationToken) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [Save](../../aspose.threed/scene/save/#save_3)(Stream, SaveOptions, CancellationToken) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [Save](../../aspose.threed/scene/save/#save_6)(string, FileFormat, CancellationToken) | Guarda la escena en la ruta especificada usando el formato de archivo especificado. |
| [Save](../../aspose.threed/scene/save/#save_8)(string, SaveOptions, CancellationToken) | Guarda la escena en la ruta especificada usando el formato de archivo especificado. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [Version](../../aspose.threed/scene/version/) | Obtiene la versión de lanzamiento actual |

### Ver también

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


