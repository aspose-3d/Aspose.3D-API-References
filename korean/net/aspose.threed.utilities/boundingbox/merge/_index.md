---
title: "BoundingBox.Merge"
second_title: "Aspose.3D for .NET API 참조"
description: "BoundingBox 메서드. 현재 경계 상자를 주어진 점과 병합합니다."
type: docs
weight: 130
url: /ko/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

현재 경계 상자를 주어진 점과 병합합니다.

```csharp
public void Merge(Vector4 pt)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pt | Vector4 | 경계 상자에 병합될 점 |

## 예제

다음 코드는 점을 경계 상자에 병합하는 방법을 보여줍니다.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### 또 보기

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

현재 경계 상자를 주어진 점과 병합합니다.

```csharp
public void Merge(Vector3 pt)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pt | Vector3 | 경계 상자에 병합될 점 |

## 예제

다음 코드는 점을 경계 상자에 병합하는 방법을 보여줍니다.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### 또 보기

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

현재 경계 상자를 주어진 점과 병합합니다.

```csharp
public void Merge(double x, double y, double z)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | Double | 경계 상자에 병합될 점 |
| y | Double | 경계 상자에 병합될 점 |
| z | Double | 경계 상자에 병합될 점 |

## 예제

다음 코드는 점을 경계 상자에 병합하는 방법을 보여줍니다.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### 또 보기

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

새 상자를 현재 경계 상자에 병합합니다.

```csharp
public void Merge(BoundingBox bb)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bb | BoundingBox | 병합할 경계 상자 |

### 또 보기

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


