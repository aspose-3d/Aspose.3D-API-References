---
title: "Clase PbrSpecularMaterial"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Shading.PbrSpecularMaterial. Material para renderizado basado en física basado en color difuso/especular/brillo"
type: docs
weight: 2560
url: /es/net/aspose.threed.shading/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Material para renderizado basado en física basado en color difuso/especular/brillo.

```csharp
public class PbrSpecularMaterial : Material
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PbrSpecularMaterial](pbrspecularmaterial/)() | Constructor de `PbrSpecularMaterial` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Diffuse](../../aspose.threed.shading/pbrspecularmaterial/diffuse/) { get; set; } | Obtiene o establece el color difuso del material, el valor predeterminado es (1, 1, 1) |
| [DiffuseTexture](../../aspose.threed.shading/pbrspecularmaterial/diffusetexture/) { get; set; } | Obtiene o establece la textura para difusa |
| [EmissiveColor](../../aspose.threed.shading/pbrspecularmaterial/emissivecolor/) { get; set; } | Obtiene o establece el color emisivo, el valor predeterminado es (0, 0, 0) |
| [EmissiveTexture](../../aspose.threed.shading/pbrspecularmaterial/emissivetexture/) { get; set; } | Obtiene o establece la textura para emisiva |
| [GlossinessFactor](../../aspose.threed.shading/pbrspecularmaterial/glossinessfactor/) { get; set; } | Obtiene o establece el brillo (suavidad) del material, 1 significa perfectamente liso y 0 significa perfectamente rugoso, el valor predeterminado es 1, el rango es [0, 1] |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [NormalTexture](../../aspose.threed.shading/pbrspecularmaterial/normaltexture/) { get; set; } | Obtiene o establece la textura del mapeo normal |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Specular](../../aspose.threed.shading/pbrspecularmaterial/specular/) { get; set; } | Obtiene o establece el color especular del material, el valor predeterminado es (1, 1, 1). |
| [SpecularGlossinessTexture](../../aspose.threed.shading/pbrspecularmaterial/specularglossinesstexture/) { get; set; } | Obtiene o establece la textura para el color especular, el canal RGB almacena el color especular y el canal A almacena el brillo. |
| [Transparency](../../aspose.threed.shading/pbrspecularmaterial/transparency/) { get; set; } | Obtiene o establece el factor de transparencia. El factor debe estar en el rango entre 0 (0%, totalmente opaco) y 1 (100%, totalmente transparente). Cualquier valor de factor no válido será limitado. |

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
| const [MapSpecularGlossiness](../../aspose.threed.shading/pbrspecularmaterial/mapspecularglossiness/) | El mapa de textura para el brillo especular |

### Ver también

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


