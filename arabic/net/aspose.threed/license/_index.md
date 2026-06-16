---
title: "فئة License"
second_title: "مرجع Aspose.3D for .NET API"
description: "فئة Aspose.ThreeD.License. توفر طرقًا لترخيص المكوّن"
type: docs
weight: 1610
url: /ar/net/aspose.threed/license/
---
## License class

يوفر طرقًا لترخيص المكوّن.

```csharp
public class License
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [License](license/)() | يُهيئ نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense)(Stream) | يرخص المكوّن. |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense_1)(string) | يرخص المكوّن. |

## أمثلة

في هذا المثال، سيُجرى محاولة للعثور على ملف ترخيص يُدعى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المدمجة للتجميع المستدعي.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

ملف jar المكوّن:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### انظر أيضًا

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


