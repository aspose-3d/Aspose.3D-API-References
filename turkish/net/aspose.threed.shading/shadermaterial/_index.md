---
title: ShaderMaterial
second_title: Aspose.3D for .NET API Referansı
description: Bir gölgelendirici malzemesi malzemenin harici işleme motoru veya gölgelendirici dili ile tanımlanmasına olanak tanır. ShaderMaterial./shadermaterial kullanırShaderTechnique./shadertechniquesomut render detaylarını açıklamak için ve en uygun olanı nihai render platformuna göre kullanılacaktır. ÖrneğinShaderMaterial./shadermaterial örneğin iki tekniğe sahip olabilir biri HLSL tarafından diğeri GLSL tarafından tanımlanır. Penceresiz platformda HLSL yerine GLSL kullanılmalıdır
type: docs
weight: 2330
url: /tr/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

Bir gölgelendirici malzemesi, malzemenin harici işleme motoru veya gölgelendirici dili ile tanımlanmasına olanak tanır. [`ShaderMaterial`](../shadermaterial) kullanır[`ShaderTechnique`](../shadertechnique)somut render detaylarını açıklamak için, ve en uygun olanı nihai render platformuna göre kullanılacaktır. Örneğin,[`ShaderMaterial`](../shadermaterial) örneğin iki tekniğe sahip olabilir, biri HLSL tarafından, diğeri GLSL tarafından tanımlanır. Penceresiz platformda HLSL yerine GLSL kullanılmalıdır

```csharp
public class ShaderMaterial : Material
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ShaderMaterial](shadermaterial#constructor)() | Yeni bir örneğini başlatır[`ShaderMaterial`](../shadermaterial) sınıf. |
| [ShaderMaterial](shadermaterial#constructor_1)(string) | Yeni bir örneğini başlatır[`ShaderMaterial`](../shadermaterial) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Adı alır veya ayarlar. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Tüm özelliklerin koleksiyonunu alır. |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques) { get; } | Bu malzemede tanımlanan mevcut tüm teknikleri alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Özelliği bulur. Dinamik bir özellik olabilir (CreateDynamicProperty/SetProperty tarafından oluşturulmuştur) veya yerel özellik (adıyla tanımlanır) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator)() | Numaralandırıcının dahili doku yuvalarını numaralandırmasını sağlar. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Belirtilen özelliğin değerini alın |
| [GetTexture](../../aspose.threed.shading/material/gettexture)(string) | Belirtilen yuvadan dokuyu alır, malzemenin özellik adı veya gölgelendiricinin parametre adı olabilir |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Dinamik bir özelliği kaldırır. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | name ile tanımlanan belirtilen özelliği kaldırın |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Belirtilen özelliğin değerini ayarlar |
| [SetTexture](../../aspose.threed.shading/material/settexture)(string, TextureBase) | Dokuyu belirtilen slot olarak ayarlar |
| override [ToString](../../aspose.threed.shading/material/tostring)() | Nesneyi string olarak biçimlendirir |

### Ayrıca bakınız

* class [Material](../material)
* ad alanı [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* toplantı [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->