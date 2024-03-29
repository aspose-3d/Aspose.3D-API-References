---
title: ShaderMaterial
second_title: Referencia de API de Aspose.3D para .NET
description: Un material de sombreado permite describir el material mediante un motor de renderizado externo o un lenguaje de sombreado. ShaderMaterial./shadermaterial usosShaderTechnique./shadertechniquepara describir los detalles de renderizado concreto se utilizará y el más adecuado de acuerdo con la plataforma de renderizado final. Por ejemplo suShaderMaterial./shadermaterial la instancia puede tener dos técnicas una está definida por HLSL y otra está definida por GLSL En la plataforma que no es de ventana se debe usar GLSL en lugar de HLSL
type: docs
weight: 2330
url: /es/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

Un material de sombreado permite describir el material mediante un motor de renderizado externo o un lenguaje de sombreado. [`ShaderMaterial`](../shadermaterial) usos[`ShaderTechnique`](../shadertechnique)para describir los detalles de renderizado concreto, se utilizará y el más adecuado de acuerdo con la plataforma de renderizado final. Por ejemplo, su[`ShaderMaterial`](../shadermaterial) la instancia puede tener dos técnicas, una está definida por HLSL y otra está definida por GLSL En la plataforma que no es de ventana, se debe usar GLSL en lugar de HLSL

```csharp
public class ShaderMaterial : Material
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ShaderMaterial](shadermaterial#constructor)() | Inicializa una nueva instancia del[`ShaderMaterial`](../shadermaterial) clase. |
| [ShaderMaterial](shadermaterial#constructor_1)(string) | Inicializa una nueva instancia del[`ShaderMaterial`](../shadermaterial) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques) { get; } | Obtiene todas las técnicas disponibles definidas en este material. |

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
