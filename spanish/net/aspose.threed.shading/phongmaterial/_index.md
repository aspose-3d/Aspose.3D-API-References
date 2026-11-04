---
title: "Clase PhongMaterial"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Shading.PhongMaterial class. Material para el modelo de sombreado blinnphong"
type: docs
weight: 2570
url: /es/net/aspose.threed.shading/phongmaterial/
---
## PhongMaterial class

Material para el modelo de sombreado Blinn-Phong.

```csharp
public class PhongMaterial : LambertMaterial
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PhongMaterial](phongmaterial/#constructor)() | Inicializa una nueva instancia de la clase `PhongMaterial`. |
| [PhongMaterial](phongmaterial/#constructor_1)(string) | Inicializa una nueva instancia de la clase `PhongMaterial`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor/) { get; set; } | Obtiene o establece el color ambiental |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor/) { get; set; } | Obtiene o establece el color difuso |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor/) { get; set; } | Obtiene o establece el color emisivo |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [ReflectionColor](../../aspose.threed.shading/phongmaterial/reflectioncolor/) { get; set; } | Obtiene o establece el color de reflexión. |
| [ReflectionFactor](../../aspose.threed.shading/phongmaterial/reflectionfactor/) { get; set; } | Obtiene o establece la atenuación del color de reflexión. |
| [Shininess](../../aspose.threed.shading/phongmaterial/shininess/) { get; set; } | Obtiene o establece el brillo, esto controla el tamaño del reflejo especular. La fórmula del especular: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [SpecularColor](../../aspose.threed.shading/phongmaterial/specularcolor/) { get; set; } | Obtiene o establece el color especular. |
| [SpecularFactor](../../aspose.threed.shading/phongmaterial/specularfactor/) { get; set; } | Obtiene o establece el factor especular. La fórmula del especular: SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
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

* class [LambertMaterial](../lambertmaterial/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


