---
title: TransformedCurve
second_title: .NET API 참조용 Aspose.3D
description: ATransformedCurve./transformedcurve/ 변환 행렬을 사용하여 곡선에 배치를 제공합니다. 이렇게 하면 내부에서 변환을 수행할 수 있습니다.TrimmedCurve./trimmedcurve/ 또는CompositeCurve./compositecurve/ .
type: docs
weight: 720
url: /ko/net/aspose.threed.entities/transformedcurve/
---
## TransformedCurve class

A`TransformedCurve` 변환 행렬을 사용하여 곡선에 배치를 제공합니다. 이렇게 하면 내부에서 변환을 수행할 수 있습니다.[`TrimmedCurve`](../trimmedcurve/) 또는[`CompositeCurve`](../compositecurve/) .

```csharp
public class TransformedCurve : Curve
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TransformedCurve](transformedcurve/#constructor)() | 의 생성자`TransformedCurve` |
| [TransformedCurve](transformedcurve/#constructor_1)(Curve, Matrix4) | 의 생성자`TransformedCurve` |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/transformedcurve/basiscurve/) { get; set; } | 기본 곡선. |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | 선의 색상을 가져오거나 설정합니다. 기본값은 white(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 내보내는 동안 이 엔터티를 제외할지 여부를 가져오거나 설정합니다. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 이름을 가져오거나 설정합니다. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 첫 번째 부모 노드를 가져오거나 설정합니다. 첫 번째 부모 노드를 설정하면 이 엔터티는 다른 부모 노드에서 분리됩니다. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 모든 부모 노드 가져오기 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 모든 속성의 컬렉션을 가져옵니다. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 이 개체가 속한 장면을 가져옵니다 |
| [TransformMatrix](../../aspose.threed.entities/transformedcurve/transformmatrix/) { get; set; } | 변환 매트릭스. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 속성을 찾습니다. 동적 속성(CreateDynamicProperty/SetProperty에 의해 생성됨) 또는 고유 속성(이름으로 식별됨) 일 수 있습니다. |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 오브젝트 공간 좌표계에서 현재 엔티티의 경계 상자를 가져옵니다. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | 렌더러 에 등록된 엔티티 렌더러의 키를 가져옵니다. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 지정된 property 의 값을 가져옵니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 동적 속성을 제거합니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name 로 식별되는 지정된 속성을 제거합니다. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 지정된 property 의 값을 설정합니다. |

### 또한보십시오

* class [Curve](../curve/)
* 네임스페이스 [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* 집회 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->