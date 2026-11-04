---
title: "BoundingBox.Merge"
second_title: "Aspose.3D for .NET API リファレンス"
description: "BoundingBox メソッド。現在のバウンディングボックスを指定された点とマージします"
type: docs
weight: 130
url: /ja/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

現在のバウンディングボックスを指定された点とマージします

```csharp
public void Merge(Vector4 pt)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | Vector4 | バウンディングボックスにマージされる点 |

## 例

以下のコードは、点をバウンディングボックスにマージする方法を示しています。

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### 関連項目

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

現在のバウンディングボックスを指定された点とマージします

```csharp
public void Merge(Vector3 pt)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | Vector3 | バウンディングボックスにマージされる点 |

## 例

以下のコードは、点をバウンディングボックスにマージする方法を示しています。

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### 関連項目

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

現在のバウンディングボックスを指定された点とマージします

```csharp
public void Merge(double x, double y, double z)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | Double | バウンディングボックスにマージされる点 |
| y | Double | バウンディングボックスにマージされる点 |
| z | Double | バウンディングボックスにマージされる点 |

## 例

以下のコードは、点をバウンディングボックスにマージする方法を示しています。

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### 関連項目

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

新しいボックスを現在のバウンディングボックスにマージします。

```csharp
public void Merge(BoundingBox bb)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bb | BoundingBox | マージするバウンディングボックス |

### 関連項目

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


