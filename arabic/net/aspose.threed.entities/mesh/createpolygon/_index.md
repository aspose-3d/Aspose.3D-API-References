---
title: "Mesh.CreatePolygon"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Mesh. تنشئ مضلعًا جديدًا بجميع الرؤوس المعرفة في الفهارس. لإنشاء المضلع رأسًا برأس يرجى استخدام PolygonBuilder"
type: docs
weight: 60
url: /ar/net/aspose.threed.entities/mesh/createpolygon/
---
## CreatePolygon(int[], int, int) {#createpolygon_3}

ينشئ مضلعًا جديدًا بجميع الرؤوس المعرفة في *indices*. لإنشاء المضلع رأسًا برأس، يرجى استخدام [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices, int offset, int length)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| indices | Int32[] | مصفوفة فهارس المضلع، كل فهرس يشير إلى نقطة تحكم تشكل المضلع. |
| offset | Int32 | الإزاحة للفهارس الأول للمضلع |
| الطول | Int32 | طول الفهارس |

## أمثلة

الكود التالي يوضح كيفية إنشاء مضلع جديد باستخدام فهارس نقاط التحكم.

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

ينشئ مضلعًا جديدًا بجميع الرؤوس المعرفة في *indices*. لإنشاء المضلع رأسًا برأس، يرجى استخدام [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| indices | Int32[] | مصفوفة فهارس المضلع، كل فهرس يشير إلى نقطة تحكم تشكل المضلع. |

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

إنشاء مضلع بأربعة رؤوس(quad)

```csharp
public void CreatePolygon(int v1, int v2, int v3, int v4)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| v1 | Int32 | فهرس الرأسة الأولى |
| v2 | Int32 | فهرس الرأسة الثانية |
| v3 | Int32 | فهرس الرأسة الثالثة |
| v4 | Int32 | فهرس الرأسة الرابعة |

## أمثلة

الكود التالي يوضح كيفية إنشاء مضلع جديد باستخدام فهارس نقاط التحكم.

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

إنشاء مضلع بثلاث رؤوس(مثلث)

```csharp
public void CreatePolygon(int v1, int v2, int v3)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| v1 | Int32 | فهرس الرأسة الأولى |
| v2 | Int32 | فهرس الرأسة الثانية |
| v3 | Int32 | فهرس الرأسة الثالثة |

## أمثلة

الكود التالي يوضح كيفية إنشاء مضلع جديد باستخدام فهارس نقاط التحكم.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2);
```

### انظر أيضًا

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


