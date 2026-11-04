---
title: "클래스 CenterLineProfile"
second_title: "Aspose.3D for .NET API 참조"
description: "**Aspose.ThreeD.Profiles.CenterLineProfile** 클래스. IFC 호환 중심선 프로필"
type: docs
weight: 1690
url: /ko/net/aspose.threed.profiles/centerlineprofile/
---
## CenterLineProfile class

IFC 호환 중심선 프로필

```csharp
public class CenterLineProfile : Profile
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CenterLineProfile](centerlineprofile/)(Curve, double) | 지정된 곡선을 중심선으로 사용하여 새로운 `CenterLineProfile`을 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Curve](../../aspose.threed.profiles/centerlineprofile/curve/) { get; set; } | 프로파일의 중심선 곡선 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 내보내기 시 이 엔터티를 제외할지 여부를 가져오거나 설정합니다. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 이름을 가져오거나 설정합니다. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 첫 번째 부모 노드를 가져오거나 설정합니다. 첫 번째 부모 노드를 설정하면 이 엔터티는 다른 부모 노드와 분리됩니다. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 모든 부모 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 부모 노드에 연결될 수 있습니다. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 모든 속성의 컬렉션을 가져옵니다. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 이 객체가 속한 씬을 가져옵니다. |
| [Thickness](../../aspose.threed.profiles/centerlineprofile/thickness/) { get; set; } | 중심선을 따라 적용된 두께 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 속성을 찾습니다. 이는 동적 속성(CreateDynamicProperty/SetProperty로 생성) 또는 네이티브 속성(이름으로 식별)일 수 있습니다. |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | 렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 지정된 속성의 값을 가져옵니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 동적 속성을 제거합니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 이름으로 식별된 지정된 속성을 제거합니다. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 지정된 속성의 값을 설정합니다 |

### 또 보기

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


