---
title: "Node.SelectObjects"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Node. حدد عدة كائنات تحت العقدة الحالية باستخدام صيغة استعلام شبيهة بـ XPath"
type: docs
weight: 230
url: /ar/net/aspose.threed/node/selectobjects/
---
## Node.SelectObjects method

اختيار عدة كائنات تحت العقدة الحالية باستخدام صياغة استعلام شبيهة بـ XPath.

```csharp
public List<object> SelectObjects(string path)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| path | سلسلة | استعلام XPath-like |

### قيمة الإرجاع

تطابق عدة كائنات مع استعلام شبيه بـ XPath.

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
//حدد الكائنات التي نوعها Camera أو اسمها 'light' بغض النظر عن موقعها.
var objects = s.RootNode.SelectObjects("//*[(@Type = 'Camera') or (@Name = 'light')]");
```

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


