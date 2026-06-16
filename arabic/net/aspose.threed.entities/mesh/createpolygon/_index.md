---
title: "Mesh.CreatePolygon"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Mesh. تنشئ مضلعًا جديدًا بجميع الرؤوس المحددة في المؤشرات. لإنشاء المضلع رأسًا برأس، يرجى استخدام PolygonBuilder"
type: docs
weight: 60
url: /ar/net/aspose.threed.entities/mesh/createpolygon/
---
## CreatePolygon(int[], int, int) {#createpolygon_3}

ينشئ مضلعًا جديدًا بجميع الرؤوس المحددة في *indices*. لإنشاء المضلع رأسًا برأس، يرجى استخدام [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices, int offset, int length)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المؤشرات | Int32[] | مصفوفة مؤشرات المضلع، كل مؤشر يشير إلى نقطة تحكم تُكوّن المضلع. |
| الإزاحة | Int32 | إزاحة المؤشر الأول للمضلع |
| الطول | Int32 | طول المؤشرات |

## أمثلة

الكود التالي يوضح كيفية إنشاء مضلع جديد باستخدام مؤشرات نقاط التحكم.

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int[]) {#createpolygon_2}

ينشئ مضلعًا جديدًا بجميع الرؤوس المحددة في *indices*. لإنشاء المضلع رأسًا برأس، يرجى استخدام [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المؤشرات | Int32[] | مصفوفة مؤشرات المضلع، كل مؤشر يشير إلى نقطة تحكم تُكوّن المضلع. |

## أمثلة

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int, int) {#createpolygon_1}

إنشاء مضلع بـ 4 رؤوس (رباعي)

```csharp
public void CreatePolygon(int v1, int v2, int v3, int v4)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| v1 | Int32 | مؤشر الرأس الأول |
| v2 | Int32 | مؤشر الرأس الثاني |
| v3 | Int32 | مؤشر الرأس الثالث |
| v4 | Int32 | مؤشر الرأس الرابع |

## أمثلة

الكود التالي يوضح كيفية إنشاء مضلع جديد باستخدام مؤشرات نقاط التحكم.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2, 3);
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int) {#createpolygon}

إنشاء مضلع بـ 3 رؤوس (مثلث)

```csharp
public void CreatePolygon(int v1, int v2, int v3)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| v1 | Int32 | مؤشر الرأس الأول |
| v2 | Int32 | مؤشر الرأس الثاني |
| v3 | Int32 | مؤشر الرأس الثالث |

## أمثلة

الكود التالي يوضح كيفية إنشاء مضلع جديد باستخدام مؤشرات نقاط التحكم.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2);
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


