---
title: Material
second_title: Referencia de API de Aspose.3D para .NET
description: El material define los parámetros necesarios para la apariencia visual de la geometría. Aspose.3D proporciona un modelo de sombreado paraLambertMaterial./lambertmaterial PhongMaterial./phongmaterial yShaderMaterial./shadermaterial
type: docs
weight: 2290
url: /es/net/aspose.threed.shading/material/
---
## Material class

El material define los parámetros necesarios para la apariencia visual de la geometría. Aspose.3D proporciona un modelo de sombreado para[`LambertMaterial`](../lambertmaterial) ,[`PhongMaterial`](../phongmaterial) y[`ShaderMaterial`](../shadermaterial)

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |

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

## Campos

| Nombre | Descripción |
| --- | --- |
| const [MapAmbient](../../aspose.threed.shading/material/mapambient) | Usado en[`SetTexture`](./settexture) para asignar un mapeo de textura ambiental. |
| const [MapDiffuse](../../aspose.threed.shading/material/mapdiffuse) | Usado en[`SetTexture`](./settexture) para asignar un mapeo de textura difusa. |
| const [MapEmissive](../../aspose.threed.shading/material/mapemissive) | Usado en[`SetTexture`](./settexture) para asignar un mapeo de textura emisivo. |
| const [MapNormal](../../aspose.threed.shading/material/mapnormal) | Usado en[`SetTexture`](./settexture) para asignar un mapeo de textura normal. |
| const [MapSpecular](../../aspose.threed.shading/material/mapspecular) | Usado en[`SetTexture`](./settexture) para asignar un mapeo de textura especular. |

### Ver también

* class [A3DObject](../../aspose.threed/a3dobject)
* class [TextureSlot](../textureslot)
* espacio de nombres [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
