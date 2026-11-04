---
title: "Mesh.op_BitwiseOr"
second_title: "Aspose.3D for .NET API 참조"
description: "Mesh 메서드. 두 메시의 합집합을 계산합니다"
type: docs
weight: 140
url: /ko/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

두 메시의 합집합을 계산합니다

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | Mesh | 첫 번째 메시 |
| b | Mesh | 두 번째 메시 |

### 반환 값

결과 메시

## 예제

다음 코드는 두 메시를 하나의 메시로 합치는 방법을 보여줍니다:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### 또 보기

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


