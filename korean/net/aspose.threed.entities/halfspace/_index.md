---
title: "HalfSpace 클래스"
second_title: "Aspose.3D for .NET API 참조"
description: "Aspose.ThreeD.Entities.HalfSpace 클래스. HalfSpace는 평면에 의해 분할되는 무한 공간을 나타내며, 이는 BooleanOperator와 함께 사용할 수 있습니다."
type: docs
weight: 420
url: /ko/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace`는 평면에 의해 분할되는 무한 공간을 나타내며, 이는 [`BooleanOperator`](../booleanoperator/)와 함께 사용할 수 있습니다.

```csharp
public class HalfSpace : Entity
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | `HalfSpace`의 새 인스턴스를 생성합니다. |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | 주어진 법선 벡터와 절단 평면상의 위치를 사용하여 `HalfSpace`의 새 인스턴스를 생성합니다; |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 내보내기 시 이 엔터티를 제외할지 여부를 가져오거나 설정합니다. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 이름을 가져오거나 설정합니다. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | 분할 평면의 법선이며, 평면은 N * P + D = 0으로 정의됩니다. 여기서 N은 법선이고 P는 평면상의 임의의 점입니다. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 첫 번째 부모 노드를 가져오거나 설정합니다. 첫 번째 부모 노드를 설정하면 이 엔터티는 다른 부모 노드와 분리됩니다. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 모든 부모 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 부모 노드에 연결될 수 있습니다. |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | 분할 평면상의 임의의 점이며, 평면은 N * P + D = 0으로 정의됩니다. 여기서 N은 법선이고 P는 평면상의 임의의 점입니다. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 모든 속성의 컬렉션을 가져옵니다. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 이 객체가 속한 씬을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 속성을 찾습니다. 이는 동적 속성(CreateDynamicProperty/SetProperty로 생성) 또는 네이티브 속성(이름으로 식별)일 수 있습니다. |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | 렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 지정된 속성의 값을 가져옵니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 동적 속성을 제거합니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 이름으로 식별된 지정된 속성을 제거합니다. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 지정된 속성의 값을 설정합니다 |

### 또 보기

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


