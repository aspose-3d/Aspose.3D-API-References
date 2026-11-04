---
title: "Clase ShaderMaterial"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Shading.ShaderMaterial class. Un material de shader permite describir el material mediante un motor de renderizado externo o un lenguaje de shader. ShaderMaterial usa ShaderTechnique para describir los detalles de renderizado concretos y se utilizará el más adecuado según la plataforma de renderizado final. Por ejemplo, su instancia de ShaderMaterial puede tener dos técnicas, una definida por HLSL y otra definida por GLSL. En plataformas sin ventana, se debe usar GLSL en lugar de HLSL"
type: docs
weight: 2580
url: /es/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

Un material de shader permite describir el material mediante un motor de renderizado externo o un lenguaje de shader. `ShaderMaterial` usa [`ShaderTechnique`](../shadertechnique/) para describir los detalles de renderizado concretos, y el más adecuado se utilizará según la plataforma de renderizado final. Por ejemplo, su instancia de `ShaderMaterial` puede tener dos técnicas, una definida por HLSL y otra definida por GLSL. En plataformas sin ventana, se debe usar GLSL en lugar de HLSL

```csharp
public class ShaderMaterial : Material
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ShaderMaterial](shadermaterial/#constructor)() | Inicializa una nueva instancia de la clase `ShaderMaterial`. |
| [ShaderMaterial](shadermaterial/#constructor_1)(string) | Inicializa una nueva instancia de la clase `ShaderMaterial`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques/) { get; } | Obtiene todas las técnicas disponibles definidas en este material. |

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


