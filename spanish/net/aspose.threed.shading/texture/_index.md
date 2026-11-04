---
title: "Clase Texture"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Shading.Texture. Esta clase define la textura a partir de un archivo externo."
type: docs
weight: 2600
url: /es/net/aspose.threed.shading/texture/
---
## Texture class

Esta clase define la textura a partir de un archivo externo.

```csharp
public class Texture : TextureBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Texture](texture/#constructor)() | Inicializa una nueva instancia de la clase `Texture`. |
| [Texture](texture/#constructor_1)(string) | Inicializa una nueva instancia de la clase `Texture`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | Obtiene o establece el valor alfa predeterminado de la textura. Esto es válido cuando el [`AlphaSource`](../texturebase/alphasource/) es PixelAlpha. El valor predeterminado es 1.0, el rango válido está entre 0 y 1. |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | Obtiene o establece si la textura define el canal alfa. El valor predeterminado es Ninguno. |
| [Content](../../aspose.threed.shading/texture/content/) { get; set; } | Obtiene o establece el contenido binario de la textura. El contenido de textura incrustado es opcional, el usuario debe cargar la textura desde un archivo externo si falta. |
| [EnableMipMap](../../aspose.threed.shading/texture/enablemipmap/) { get; set; } | Obtiene o establece si el mipmap está habilitado para esta textura. |
| [FileName](../../aspose.threed.shading/texture/filename/) { get; set; } | Obtiene o establece el archivo de textura asociado. |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter/) { get; set; } | Obtiene o establece el filtro para la ampliación. |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter/) { get; set; } | Obtiene o establece el filtro para la minificación. |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter/) { get; set; } | Obtiene o establece el filtro para el muestreo de niveles mip. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation/) { get; set; } | Obtiene o establece la rotación de la textura |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale/) { get; set; } | Obtiene o establece la escala UV. |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation/) { get; set; } | Obtiene o establece la traslación UV. |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu/) { get; set; } | Obtiene o establece los modos de envoltura de textura en U. |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev/) { get; set; } | Obtiene o establece los modos de envoltura de textura en V. |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew/) { get; set; } | Obtiene o establece los modos de envoltura de textura en W. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation/)(double, double) | Establece la rotación UV. |
| [SetScale](../../aspose.threed.shading/texturebase/setscale/)(double, double) | Establece la escala UV. |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation/)(double, double) | Establece la traslación UV. |

### Ver también

* class [TextureBase](../texturebase/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


