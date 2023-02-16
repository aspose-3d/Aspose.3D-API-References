---
title: LShape
second_title: .NET API 참조용 Aspose.3D
description: 매개변수로 정의된 IFC 호환 L자형 프로파일.
type: docs
weight: 1580
url: /ko/net/aspose.threed.profiles/lshape/
---
## LShape class

매개변수로 정의된 IFC 호환 L자형 프로파일.

```csharp
public class LShape : ParameterizedProfile
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LShape](lshape/)() | 의 생성자`LShape` |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Depth](../../aspose.threed.profiles/lshape/depth/) { get; set; } | 프로필의 깊이를 가져오거나 설정합니다. |
| [EdgeRadius](../../aspose.threed.profiles/lshape/edgeradius/) { get; set; } | 가장자리의 반지름을 가져오거나 설정합니다. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 내보내는 동안 이 엔터티를 제외할지 여부를 가져오거나 설정합니다. |
| [FilletRadius](../../aspose.threed.profiles/lshape/filletradius/) { get; set; } | 필렛의 반지름을 가져오거나 설정합니다. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 이름을 가져오거나 설정합니다. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 첫 번째 부모 노드를 가져오거나 설정합니다. 첫 번째 부모 노드를 설정하면 이 엔터티는 다른 부모 노드에서 분리됩니다. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 모든 부모 노드 가져오기 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 모든 속성의 컬렉션을 가져옵니다. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 이 개체가 속한 장면을 가져옵니다 |
| [Thickness](../../aspose.threed.profiles/lshape/thickness/) { get; set; } | 상수 벽의 두께를 가져오거나 설정합니다. |
| [Width](../../aspose.threed.profiles/lshape/width/) { get; set; } | 프로필의 너비를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 속성을 찾습니다. 동적 속성(CreateDynamicProperty/SetProperty에 의해 생성됨) 또는 고유 속성(이름으로 식별됨) 일 수 있습니다. |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 오브젝트 공간 좌표계에서 현재 엔티티의 경계 상자를 가져옵니다. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | 렌더러 에 등록된 엔티티 렌더러의 키를 가져옵니다. |
| override [GetExtent](../../aspose.threed.profiles/lshape/getextent/)() | x 및 y 차원의 범위를 가져옵니다. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 지정된 property 의 값을 가져옵니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 동적 속성을 제거합니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name 로 식별되는 지정된 속성을 제거합니다. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 지정된 property 의 값을 설정합니다. |

### 또한보십시오

* class [ParameterizedProfile](../parameterizedprofile/)
* 네임스페이스 [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* 집회 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->