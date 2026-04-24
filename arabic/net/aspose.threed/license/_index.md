---
title: الفئة License
second_title: مرجع API Aspose.3D لـ .NET
description: الفئة Aspose.ThreeD.License. توفر طرقًا لترخيص المكوّن
type: docs
weight: 1610
url: /ar/net/aspose.threed/license/
---
## License class

يوفر طرقًا لترخيص المكوّن.

```csharp
public class License
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [License](license/)() | يقوم بتهيئة نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense)(Stream) | يرخص المكوّن. |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense_1)(string) | يرخص المكوّن. |

## Examples

في هذا المثال، سيتم محاولة العثور على ملف ترخيص اسمه MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المدمجة للتجميع المستدعي.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

the component jar file:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### انظر أيضًا

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


