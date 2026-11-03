---
title: "License.SetLicense"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة License. ترخص المكوّن"
type: docs
weight: 20
url: /ar/net/aspose.threed/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

يرخص المكوّن.

```csharp
public void SetLicense(string licenseName)
```

## ملاحظات

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.

2. المجلد الذي يحتوي على تجميع مكوّن Aspose.

3. المجلد الذي يحتوي على تجميع استدعاء العميل.

4. المجلد الذي يحتوي على تجميع الدخول (بدء التشغيل).

5. مورد مدمج في تجميع استدعاء العميل.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. مسار صريح.

2. مورد مدمج في تجميع استدعاء العميل.

2. المجلد الذي يحتوي على ملف JAR لمكوّن Aspose.

3. المجلد الذي يحتوي على ملف JAR لاستدعاء العميل.

## أمثلة

في هذا المثال، سيتم محاولة العثور على ملف ترخيص باسم MyLicense.lic في المجلد الذي يحتوي على المكوّن، في المجلد الذي يحتوي على تجميع الاستدعاء، في مجلد تجميع الدخول، ثم في الموارد المدمجة لتجميع الاستدعاء.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

ملف JAR للمكوّن:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

يمكن أن يكون اسم ملف كامل أو مختصر أو اسم مورد مدمج. استخدم سلسلة فارغة للتبديل إلى وضع التقييم.

### انظر أيضًا

* class [License](../)
* namespace [Aspose.ThreeD](../../license/)
* assembly [Aspose.3D](../../../)

---

## SetLicense(Stream) {#setlicense}

يرخص المكوّن.

```csharp
public void SetLicense(Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | دفق يحتوي على الترخيص. |

## ملاحظات

استخدم هذه الطريقة لتحميل ترخيص من دفق.

## أمثلة

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)

License license = new License();
license.setLicense(myStream);
```

### انظر أيضًا

* class [License](../)
* namespace [Aspose.ThreeD](../../license/)
* assembly [Aspose.3D](../../../)


