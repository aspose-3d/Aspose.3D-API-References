---
title: "Clase LambertMaterial"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Shading.LambertMaterial. Material para el modelo de sombreado Lambert"
type: docs
weight: 2530
url: /es/net/aspose.threed.shading/lambertmaterial/
---
## LambertMaterial class

Material para el modelo de sombreado Lambert.

```csharp
public class LambertMaterial : Material
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LambertMaterial](lambertmaterial/#constructor)() | Inicializa una nueva instancia de la clase `LambertMaterial`. |
| [LambertMaterial](lambertmaterial/#constructor_1)(string) | Inicializa una nueva instancia de la clase `LambertMaterial`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor/) { get; set; } | Obtiene o establece el color ambiental |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor/) { get; set; } | Obtiene o establece el color difuso |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor/) { get; set; } | Obtiene o establece el color emisivo |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency/) { get; set; } | Obtiene o establece el factor de transparencia. El factor debe estar en el rango entre 0 (0%, totalmente opaco) y 1 (100%, totalmente transparente). Cualquier valor de factor no válido será limitado. |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor/) { get; set; } | Obtiene o establece el color transparente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | Obtiene el enumerador para enumerar las ranuras de textura internas. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | Obtiene la textura de la ranura especificada, puede ser el nombre de una propiedad del material o el nombre de un parámetro del shader. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | Establece la textura en la ranura especificada |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | Formatea el objeto a cadena |

### Ver también

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


