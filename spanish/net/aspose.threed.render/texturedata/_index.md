---
title: "Clase TextureData"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Render.TextureData. Esta clase contiene los datos sin procesar y la definición de formato de una textura."
type: docs
weight: 2460
url: /es/net/aspose.threed.render/texturedata/
---
## TextureData class

Esta clase contiene los datos sin procesar y la definición de formato de una textura.

```csharp
public class TextureData : A3DObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextureData](texturedata/#constructor)() | Constructor de `TextureData` |
| [TextureData](texturedata/#constructor_1)(int, int, PixelFormat) | Construye un nuevo `TextureData` y asigna los datos de píxeles. |
| [TextureData](texturedata/#constructor_2)(int, int, int, int, PixelFormat, byte[]) | Constructor de `TextureData` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BytesPerPixel](../../aspose.threed.render/texturedata/bytesperpixel/) { get; } | Número de bytes de un píxel |
| [Data](../../aspose.threed.render/texturedata/data/) { get; } | Bytes sin procesar de los datos de píxel |
| [Height](../../aspose.threed.render/texturedata/height/) { get; } | Número de píxeles verticales |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [PixelFormat](../../aspose.threed.render/texturedata/pixelformat/) { get; } | Formato del píxel |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Stride](../../aspose.threed.render/texturedata/stride/) { get; } | Número de bytes de una línea de escaneo. |
| [Width](../../aspose.threed.render/texturedata/width/) { get; } | Número de píxeles horizontales |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromFile](../../aspose.threed.render/texturedata/fromfile/)(string) | Cargar una textura desde un archivo |
| static [FromStream](../../aspose.threed.render/texturedata/fromstream/)(Stream) | Cargar una textura desde un flujo |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels)(PixelMapMode) | Mapear todos los píxeles para lectura/escritura |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_1)(PixelMapMode, PixelFormat) | Mapear todos los píxeles para lectura/escritura en el formato de píxel dado |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_2)(Rect, PixelMapMode, PixelFormat) | Mapear píxeles dirigidos por rectángulo para lectura/escritura en el formato de píxel dado |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [Save](../../aspose.threed.render/texturedata/save/#save_1)(string) | Guardar los datos de la textura en un archivo de imagen |
| [Save](../../aspose.threed.render/texturedata/save/#save)(Stream, string) | Guardar los datos de la textura en el formato de imagen especificado |
| [Save](../../aspose.threed.render/texturedata/save/#save_2)(string, string) | Guardar los datos de la textura en un archivo de imagen |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |
| [TransformPixelFormat](../../aspose.threed.render/texturedata/transformpixelformat/)(PixelFormat) | Transformar la disposición del píxel a un nuevo formato de píxel. |

### Ver también

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


