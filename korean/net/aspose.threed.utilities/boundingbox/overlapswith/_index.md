---
title: "BoundingBox.OverlapsWith"
second_title: "Aspose.3D for .NET API 참조"
description: "BoundingBox 메서드. 현재 경계 상자가 지정된 경계 상자와 겹치는지 확인합니다"
type: docs
weight: 140
url: /ko/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

현재 경계 상자가 지정된 경계 상자와 겹치는지 확인합니다.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 상자 | BoundingBox | 테스트할 다른 경계 상자 |

### 반환 값

현재 경계 상자가 주어진 상자와 겹치면 true.

## 예제

다음 코드는 두 경계 상자가 서로 겹치는지 확인하는 방법을 보여줍니다.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### 또 보기

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


