---
title: "클래스 BooleanOperator"
second_title: "Aspose.3D for .NET API 참조"
description: "Aspose.ThreeD.Entities.BooleanOperator class. Boolean 연산자는 두 IMeshConvertible 인스턴스에 Boolean 연산을 적용할 수 있게 합니다"
type: docs
weight: 280
url: /ko/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

Boolean 연산자는 두 [`IMeshConvertible`](../imeshconvertible/) 인스턴스에 Boolean 연산을 적용할 수 있게 합니다.

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | `BooleanOperator` 생성자 |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | 두 피연산자를 사용하여 `BooleanOperator`의 새 인스턴스를 생성합니다 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 내보내기 시 이 엔터티를 제외할지 여부를 가져오거나 설정합니다. |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | Boolean 연산자의 첫 번째 피연산자 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 이름을 가져오거나 설정합니다. |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | 결과 메쉬를 생성하기 위해 연산에 사용되는 Boolean 연산자. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 첫 번째 부모 노드를 가져오거나 설정합니다. 첫 번째 부모 노드를 설정하면 이 엔터티는 다른 부모 노드와 분리됩니다. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 모든 부모 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 부모 노드에 연결될 수 있습니다. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 모든 속성의 컬렉션을 가져옵니다. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 이 객체가 속한 씬을 가져옵니다. |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | Boolean 연산자의 두 번째 피연산자 |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | 두 피연산자에 대해 Boolean 연산을 수행합니다 |

### 또 보기

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


