---
title: "Clase Material"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Shading.Material class. Material define los parámetros necesarios para la apariencia visual de la geometría. Aspose.3D proporciona modelos de sombreado para LambertMaterial, PhongMaterial y ShaderMaterial"
type: docs
weight: 2540
url: /es/net/aspose.threed.shading/material/
---
## Material class

Material define los parámetros necesarios para la apariencia visual de la geometría. Aspose.3D proporciona modelos de sombreado para [`LambertMaterial`](../lambertmaterial/), [`PhongMaterial`](../phongmaterial/) y [`ShaderMaterial`](../shadermaterial/)

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |

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

## Campos

| Nombre | Descripción |
| --- | --- |
| const [MapAmbient](../../aspose.threed.shading/material/mapambient/) | Usado en [`SetTexture`](./settexture/) para asignar un mapeo de textura ambiental. |
| const [MapDiffuse](../../aspose.threed.shading/material/mapdiffuse/) | Usado en [`SetTexture`](./settexture/) para asignar un mapeo de textura difusa. |
| const [MapEmissive](../../aspose.threed.shading/material/mapemissive/) | Usado en [`SetTexture`](./settexture/) para asignar un mapeo de textura emisiva. |
| const [MapNormal](../../aspose.threed.shading/material/mapnormal/) | Usado en [`SetTexture`](./settexture/) para asignar un mapeo de textura normal. |
| const [MapSpecular](../../aspose.threed.shading/material/mapspecular/) | Usado en [`SetTexture`](./settexture/) para asignar un mapeo de textura especular. |

## Ejemplos

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
foreach(var slot in mat)
{
    Console.WriteLine($"Texture slot {slot.SlotName} = {slot.Texture}");
}
```

### Ver también

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [TextureSlot](../textureslot/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


