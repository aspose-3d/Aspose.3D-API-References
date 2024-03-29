---
title: LambertMaterial
second_title: Referencia de API de Aspose.3D para .NET
description: Material para modelo de sombreado lambert
type: docs
weight: 2280
url: /es/net/aspose.threed.shading/lambertmaterial/
---
## LambertMaterial class

Material para modelo de sombreado lambert

```csharp
public class LambertMaterial : Material
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LambertMaterial](lambertmaterial#constructor)() | Inicializa una nueva instancia del[`LambertMaterial`](../lambertmaterial) clase. |
| [LambertMaterial](lambertmaterial#constructor_1)(string) | Inicializa una nueva instancia del[`LambertMaterial`](../lambertmaterial) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor) { get; set; } | Obtiene o establece el color ambiental |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor) { get; set; } | Obtiene o establece el color difuso |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor) { get; set; } | Obtiene o establece el color emisivo |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency) { get; set; } | Obtiene o establece el factor de transparencia. El factor debe oscilar entre 0 (0 %, completamente opaco) y 1 (100 %, completamente transparente) Se restringirá cualquier valor de factor no válido. |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor) { get; set; } | Obtiene o establece el color transparente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator)() | Obtiene el enumerador para enumerar ranuras de texturas internas. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtener el valor de la propiedad especificada |
| [GetTexture](../../aspose.threed.shading/material/gettexture)(string) | Obtiene la textura de la ranura especificada, puede ser el nombre de la propiedad del material o el nombre del parámetro del shader |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Eliminar la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Establece el valor de la propiedad especificada |
| [SetTexture](../../aspose.threed.shading/material/settexture)(string, TextureBase) | Establece la textura en la ranura especificada |
| override [ToString](../../aspose.threed.shading/material/tostring)() | Da formato al objeto a string |

### Ver también

* class [Material](../material)
* espacio de nombres [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
