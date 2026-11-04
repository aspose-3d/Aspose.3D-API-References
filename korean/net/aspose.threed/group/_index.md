---
title: "그룹 클래스"
second_title: "Aspose.3D for .NET API 참조"
description: "Aspose.ThreeD.Group 클래스. 그룹은 Node의 논리적 관계를 나타냅니다"
type: docs
weight: 1570
url: /ko/net/aspose.threed/group/
---
## Group class

`Group`은 [`Node`](../node/)의 논리적 관계를 나타냅니다.

```csharp
public class Group : A3DObject
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Group](group/)(string) | `Group`의 새 인스턴스를 생성합니다 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | 하위 그룹 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 이름을 가져오거나 설정합니다. |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | 이 그룹의 노드들 |
| [Parent](../../aspose.threed/group/parent/) { get; } | 현재 그룹의 상위 그룹 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 모든 속성의 컬렉션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 속성을 찾습니다. 이는 동적 속성(CreateDynamicProperty/SetProperty로 생성) 또는 네이티브 속성(이름으로 식별)일 수 있습니다. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 지정된 속성의 값을 가져옵니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 동적 속성을 제거합니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 이름으로 식별된 지정된 속성을 제거합니다. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 지정된 속성의 값을 설정합니다 |
| override [ToString](../../aspose.threed/group/tostring/)() | `Group`의 문자열 표현을 가져옵니다 |

### 또 보기

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


