---
title: "Sınıf FontFile"
second_title: "Aspose.3D for .NET API Referansı"
description: "Aspose.ThreeD.Profiles.FontFile sınıfı. Yazı tipi dosyası, glif tanımlarını içerir; bu, metin profili oluşturmak için kullanılır"
type: docs
weight: 1720
url: /tr/net/aspose.threed.profiles/fontfile/
---
## FontFile class

Yazı tipi dosyası glif tanımlarını içerir, bu metin profili oluşturmak için kullanılır.

```csharp
public abstract class FontFile : A3DObject
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Adı alır veya ayarlar. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Tüm özelliklerin koleksiyonunu alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | FontFile'ı dosya adından yükle |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | FontFile'ı baytlardan ayrıştır |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty ile oluşturulan) veya yerel özellik (adıyla tanımlanan) olabilir. |
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

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


