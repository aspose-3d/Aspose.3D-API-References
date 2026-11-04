---
title: "Mesh.Triangulate"
second_title: "Aspose.3D for .NET API 참조"
description: "Mesh 메서드. 삼각형으로 분할된 메시를 반환합니다"
type: docs
weight: 120
url: /ko/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

삼각형으로 분할된 메시를 반환합니다

```csharp
public Mesh Triangulate()
```

### 반환 값

현재 메시가 이미 삼각형으로 분할된 경우 현재 메시를 반환하고, 그렇지 않으면 새로운 삼각형으로 분할된 메시를 계산하여 반환합니다

## 예제

다음 코드는 메시를 삼각형으로 분할하는 방법을 보여줍니다:

```csharp
//평면 메시에는 4개의 제어점을 가진 다각형이 하나만 있습니다
var mesh = (new Plane()).ToMesh();
//삼각형으로 분할된 후, 새로운 메시의 사각형은 2개의 삼각형이 됩니다.
var triangulated = mesh.Triangulate();
```

### 또 보기

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


