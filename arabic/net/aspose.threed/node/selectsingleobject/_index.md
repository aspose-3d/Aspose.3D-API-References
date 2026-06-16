---
title: "Node.SelectSingleObject"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Node. اختر كائنًا واحدًا تحت العقدة الحالية باستخدام صياغة استعلام شبيهة بـ XPath"
type: docs
weight: 240
url: /ar/net/aspose.threed/node/selectsingleobject/
---
## Node.SelectSingleObject method

اختيار كائن واحد تحت العقدة الحالية باستخدام صياغة استعلام شبيهة بـ XPath.

```csharp
public object SelectSingleObject(string path)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| path | سلسلة | استعلام XPath-like |

### قيمة الإرجاع

الكائن الموجود بواسطة استعلام شبيه بـ XPath.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [ParseException](../../../aspose.threed.utilities/parseexception/) | سيتم إلقاء استثناء ParseException إذا كان المسار يحتوي على استعلام غير صالح. |

## أمثلة

حدد عقدة واحدة باستخدام تعبير شبيه بـ XPath

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
//حدد كائن الكاميرا الفردي تحت العقد الفرعية للعقدة المسماة 'c' تحت العقدة الجذرية
var c1 = s.RootNode.SelectSingleObject("/c/*/<Camera>");
// حدد العقدة المسماة 'a1' تحت العقدة الجذرية، حتى إذا لم تكن 'a1' عقدة فرعية مباشرة لل
var obj = s.RootNode.SelectSingleObject("a1");
//حدد العقدة نفسها، لأن '/' يتم اختياره مباشرةً على العقدة الجذرية، وبالتالي يتم اختيار العقدة الجذرية.
obj = s.RootNode.SelectSingleObject("/");
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


