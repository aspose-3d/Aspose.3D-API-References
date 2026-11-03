---
title: "Node.SelectSingleObject"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Node. اختر كائنًا واحدًا تحت العقدة الحالية باستخدام صيغة استعلام شبيهة بـ XPath"
type: docs
weight: 240
url: /ar/net/aspose.threed/node/selectsingleobject/
---
## Node.SelectSingleObject method

اختر كائنًا واحدًا تحت العقدة الحالية باستخدام صيغة استعلام شبيهة بـ XPath.

```csharp
public object SelectSingleObject(string path)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المسار | String | استعلام شبيه بـ XPath |

### قيمة الإرجاع

الكائن المحدد بواسطة استعلام شبيه بـ XPath.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [ParseException](../../../aspose.threed.utilities/parseexception/) | سيتم رمي استثناء ParseException إذا كان المسار يحتوي على استعلام غير صالح. |

## أمثلة

اختر عقدة واحدة باستخدام تعبير شبيه بـ XPath

```csharp
//إنشاء مشهد للاختبار
Scene s = new Scene();
var a = s.RootNode.CreateChildNode("a");
a.CreateChildNode("a1");
a.CreateChildNode("a2");
s.RootNode.CreateChildNode("b");
var c = s.RootNode.CreateChildNode("c");
c.CreateChildNode("c1").AddEntity(new Camera("cam"));
c.CreateChildNode("c2").AddEntity(new Light("light"));
//اختر كائن كاميرا واحد تحت العقد الفرعية للعقدة المسماة 'c' تحت العقدة الجذرية
var c1 = s.RootNode.SelectSingleObject("/c/*/<Camera>");
// اختر العقدة المسماة 'a1' تحت العقدة الجذرية، حتى إذا لم تكن 'a1' عقدة فرعية مباشرة لـ
var obj = s.RootNode.SelectSingleObject("a1");
//اختر العقدة نفسها، لأن '/' يتم اختياره مباشرةً على العقدة الجذرية، لذا يتم اختيار العقدة الجذرية.
obj = s.RootNode.SelectSingleObject("/");
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


