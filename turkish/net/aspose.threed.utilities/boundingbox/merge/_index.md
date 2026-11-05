---
title: "BoundingBox.Merge"
second_title: "Aspose.3D for .NET API Referansı"
description: "BoundingBox yöntemi. Mevcut sınırlama kutusunu verilen nokta ile birleştir."
type: docs
weight: 130
url: /tr/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

Mevcut sınırlama kutusunu verilen nokta ile birleştir

```csharp
public void Merge(Vector4 pt)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | Vector4 | Sınırlama kutusuna birleştirilecek nokta |

## Örnekler

Aşağıdaki kod, bir noktayı sınırlama kutusuna nasıl birleştirileceğini gösterir.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Ayrıca Bakınız

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

Mevcut sınırlama kutusunu verilen nokta ile birleştir

```csharp
public void Merge(Vector3 pt)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | Vector3 | Sınırlama kutusuna birleştirilecek nokta |

## Örnekler

Aşağıdaki kod, bir noktayı sınırlama kutusuna nasıl birleştirileceğini gösterir.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Ayrıca Bakınız

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

Mevcut sınırlama kutusunu verilen nokta ile birleştir

```csharp
public void Merge(double x, double y, double z)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | Double | Sınırlama kutusuna birleştirilecek nokta |
| y | Double | Sınırlama kutusuna birleştirilecek nokta |
| z | Double | Sınırlama kutusuna birleştirilecek nokta |

## Örnekler

Aşağıdaki kod, bir noktayı sınırlama kutusuna nasıl birleştirileceğini gösterir.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Ayrıca Bakınız

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

Yeni kutuyu mevcut sınırlama kutusuna birleştirir.

```csharp
public void Merge(BoundingBox bb)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bb | BoundingBox | Birleştirilecek sınırlama kutusu |

### Ayrıca Bakınız

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


