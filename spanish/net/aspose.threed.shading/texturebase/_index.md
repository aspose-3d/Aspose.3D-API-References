---
title: "Clase TextureBase"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Shading.TextureBase. Clase base para todas las texturas concretas. La textura define el aspecto y la sensación de una superficie geométrica"
type: docs
weight: 2610
url: /es/net/aspose.threed.shading/texturebase/
---
## TextureBase class

Clase base para todas las texturas concretas. La textura define el aspecto y la sensación de la superficie de una geometría.

```csharp
public class TextureBase : A3DObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextureBase](texturebase/)(string) | Inicializa una nueva instancia de la clase `TextureBase`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | Obtiene o establece el valor alfa predeterminado de la textura. Esto es válido cuando [`AlphaSource`](./alphasource/) es PixelAlpha. El valor predeterminado es 1.0, el rango de valores válidos está entre 0 y 1 |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | Obtiene o establece si la textura define el canal alfa. El valor predeterminado es Ninguno. |
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

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


