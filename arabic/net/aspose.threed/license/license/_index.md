---
title: "License.License"
second_title: "مرجع Aspose.3D for .NET API"
description: "منشئ License. يهيئ نسخة جديدة من هذه الفئة."
type: docs
weight: 10
url: /ar/net/aspose.threed/license/license/
---
## License constructor

يُهيئ نسخة جديدة من هذه الفئة.

```csharp
public License()
```

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

* class [License](../)
* namespace [Aspose.ThreeD](../../license/)
* assembly [Aspose.3D](../../../)


