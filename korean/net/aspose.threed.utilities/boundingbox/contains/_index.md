---
title: "BoundingBox.Contains"
second_title: "Aspose.3D for .NET API 참조"
description: "BoundingBox 메서드. 점 p가 경계 상자 안에 있는지 확인합니다"
type: docs
weight: 100
url: /ko/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

점 p가 경계 상자 안에 있는지 확인합니다

```csharp
public bool Contains(Vector3 p)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| p | Vector3 | 테스트할 점 |

### 반환 값

점이 경계 상자 내부에 있으면 True

## 예제

다음 코드는 점이 경계 상자 내부에 있는지 확인하는 방법을 보여줍니다.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### 또 보기

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

현재 경계 상자 내부에 있는지 확인할 경계 상자.

```csharp
public bool Contains(BoundingBox bbox)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bbox | BoundingBox |  |

### 또 보기

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


