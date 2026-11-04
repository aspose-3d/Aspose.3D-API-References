---
title: "Mesh.Optimize"
second_title: "Aspose.3D for .NET API 참조"
description: "Mesh 메서드. 중복된 제어점을 제거하여 meshs의 메모리 사용량을 최적화합니다"
type: docs
weight: 100
url: /ko/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

중복된 제어점을 제거하여 메시의 메모리 사용량을 최적화합니다

```csharp
public Mesh Optimize(bool vertexElements)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vertexElements | Boolean | 중복된 정점 요소 데이터 최적화 |

### 반환 값

컴팩트한 메모리 사용량을 가진 새로운 메시 인스턴스

## 예제

다음 코드는 최적화되지 않은 메시에서 중복된 제어점을 제거하는 방법을 보여줍니다:

```csharp
//Sphere.ToMesh는 117개의 제어점을 생성합니다
var mesh = (new Sphere()).ToMesh();
//최적화 후에는 86개의 제어점만 남으며, 폴리곤 인덱스도 다시 매핑됩니다.
var optimized = mesh.Optimize(true);
```

### 또 보기

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

중복된 제어점을 제거하여 메시의 메모리 사용량을 최적화합니다

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vertexElements | Boolean | 중복된 정점 요소 데이터 최적화 |
| toleranceControlPoint | 단일 | 제어점에 대한 허용오차, 기본값은 1e-9입니다 |
| toleranceNormal | 단일 | 노멀/탄젠트/바이노멀에 대한 허용오차, 기본값은 1e-9입니다 |
| toleranceUV | 단일 | UV에 대한 허용오차, 기본값은 1e-9입니다 |

### 반환 값

컴팩트한 메모리 사용량을 가진 새로운 메시 인스턴스

### 또 보기

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


