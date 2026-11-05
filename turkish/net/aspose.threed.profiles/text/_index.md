---
title: "Sınıf Text"
second_title: "Aspose.3D for .NET API Referansı"
description: "Aspose.ThreeD.Profiles.Text sınıfı. Metin profili bu profil, yazı tipi ve metin kullanarak konturları tanımlar"
type: docs
weight: 1820
url: /tr/net/aspose.threed.profiles/text/
---
## Text class

Metin profili, bu profil yazı tipi ve metin kullanarak konturları tanımlar.

```csharp
public class Text : Profile
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Text](text/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Content](../../aspose.threed.profiles/text/content/) { get; set; } | Metnin içeriği |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Dışa aktarım sırasında bu varlığın dışlanıp dışlanmayacağını alır veya ayarlar. |
| [Font](../../aspose.threed.profiles/text/font/) { get; set; } | Metnin yazı tipi. |
| [FontSize](../../aspose.threed.profiles/text/fontsize/) { get; set; } | Yazı tipi boyutu ölçeği. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Adı alır veya ayarlar. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | İlk üst düğümü alır veya ayarlar, ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Tüm özelliklerin koleksiyonunu alır. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Bu nesnenin ait olduğu sahneyi alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty ile oluşturulan) veya yerel özellik (adıyla tanımlanan) olabilir. |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Renderer içinde kayıtlı varlık işleyicisinin anahtarını alır. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Belirtilen özelliğin değerini al. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Dinamik bir özelliği kaldırır. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Adı ile tanımlanan belirtilen özelliği kaldır. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Belirtilen özelliğin değerini ayarlar. |

## Örnekler

Aşağıdaki kod, belirtilen yazı tipi dosyasını kullanarak metinden 3B örgü nasıl oluşturulacağını gösterir.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### Ayrıca Bakınız

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


