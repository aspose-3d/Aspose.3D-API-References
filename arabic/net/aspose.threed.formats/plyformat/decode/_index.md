---
title: "PlyFormat.Decode"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة PlyFormat. فك تشفير سحابة نقاط أو شبكة من الدفق المحدد"
type: docs
weight: 10
url: /ar/net/aspose.threed.formats/plyformat/decode/
---
## Decode(string) {#decode_2}

فك تشفير سحابة نقطية أو شبكة من الدفق المحدد.

```csharp
public Geometry Decode(string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | دفق الإدخال |

### قيمة الإرجاع

مثال [`Mesh`](../../../aspose.threed.entities/mesh/) أو [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## أمثلة

الكود التالي يوضح كيفية فك تشفير شبكة من ملف PLY:

```csharp
//إنشاء ملف اختبار للفك
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//فك تشفير الملف
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### انظر أيضًا

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(string, PlyLoadOptions) {#decode_3}

فك تشفير سحابة نقطية أو شبكة من الدفق المحدد.

```csharp
public Geometry Decode(string fileName, PlyLoadOptions opt)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | سلسلة | دفق الإدخال |
| opt | PlyLoadOptions | خيار التحميل لتنسيق PLY |

### قيمة الإرجاع

مثال [`Mesh`](../../../aspose.threed.entities/mesh/) أو [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## أمثلة

الكود التالي يوضح كيفية فك تشفير شبكة من ملف PLY:

```csharp
//إنشاء ملف اختبار للفك
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//فك تشفير الملف
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### انظر أيضًا

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream) {#decode}

فك تشفير سحابة نقطية أو شبكة من الدفق المحدد.

```csharp
public Geometry Decode(Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق الإدخال |

### قيمة الإرجاع

مثال [`Mesh`](../../../aspose.threed.entities/mesh/) أو [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## أمثلة

الكود التالي يوضح كيفية فك تشفير شبكة من ملف PLY:

```csharp
//إنشاء ملف اختبار للفك
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//فك تشفير الملف
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### انظر أيضًا

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream, PlyLoadOptions) {#decode_1}

فك تشفير سحابة نقطية أو شبكة من الدفق المحدد.

```csharp
public Geometry Decode(Stream stream, PlyLoadOptions opt)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق الإدخال |
| opt | PlyLoadOptions | خيار التحميل لتنسيق PLY |

### قيمة الإرجاع

مثال [`Mesh`](../../../aspose.threed.entities/mesh/) أو [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## أمثلة

الكود التالي يوضح كيفية فك تشفير شبكة من ملف PLY:

```csharp
//إنشاء ملف اختبار للفك
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//فك تشفير الملف
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### انظر أيضًا

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


