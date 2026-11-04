---
title: "Mesh.op_Subtraction"
second_title: "Aspose.3D for .NET API 참조"
description: "Mesh 메서드. 두 메쉬의 차이를 계산합니다"
type: docs
weight: 150
url: /ko/net/aspose.threed.entities/mesh/op_subtraction/
---
## Mesh Subtraction operator

두 메쉬의 차이를 계산합니다

```csharp
public static Mesh operator -(Mesh a, Mesh b)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | Mesh | 첫 번째 메시 |
| b | Mesh | 두 번째 메시 |

### 반환 값

결과 메시

## 예제

다음 코드는 두 메쉬의 차이를 계산하는 방법을 보여줍니다:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 - box2;
```

### 또 보기

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


