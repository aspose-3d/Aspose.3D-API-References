---
title: Cylinder
second_title: .NET API 참조용 Aspose.3D
description: Parameterized Cylinder. radiusTop/radiusBottom 중 하나가 0일 때 원뿔을 나타내는 데 사용할 수도 있습니다.
type: docs
weight: 310
url: /ko/net/aspose.threed.entities/cylinder/
---
## Cylinder class

Parameterized Cylinder. radiusTop/radiusBottom 중 하나가 0일 때 원뿔을 나타내는 데 사용할 수도 있습니다.

```csharp
public class Cylinder : Primitive
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Cylinder](cylinder/#constructor)() | 의 새 인스턴스를 초기화합니다.`Cylinder` 클래스. |
| [Cylinder](cylinder/#constructor_1)(double, double) | 의 새 인스턴스를 초기화합니다.`Cylinder` 클래스. |
| [Cylinder](cylinder/#constructor_2)(double, double, double) | 의 새 인스턴스를 초기화합니다.`Cylinder` 클래스. |
| [Cylinder](cylinder/#constructor_3)(double, double, double, int, int, bool) | 의 새 인스턴스를 초기화합니다.`Cylinder` 클래스. |
| [Cylinder](cylinder/#constructor_4)(string, double, double, double, int, int, bool, double, double) | 의 새 인스턴스를 초기화합니다.`Cylinder` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | 이 지오메트리가 shadow 를 투사할 수 있는지 여부를 가져오거나 설정합니다. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 내보내는 동안 이 엔터티를 제외할지 여부를 가져오거나 설정합니다. |
| [GenerateFanCylinder](../../aspose.threed.entities/cylinder/generatefancylinder/) { get; set; } | ThetaLength가 2*PI보다 작을 때 팬 스타일 실린더를 생성할지 여부를 가져오거나 설정합니다. 그렇지 않으면 모델이 절단되지 않습니다. |
| [Height](../../aspose.threed.entities/cylinder/height/) { get; set; } | 실린더의 높이를 가져오거나 설정합니다. |
| [HeightSegments](../../aspose.threed.entities/cylinder/heightsegments/) { get; set; } | 높이 세그먼트를 가져오거나 설정합니다. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 이름을 가져오거나 설정합니다. |
| [OffsetBottom](../../aspose.threed.entities/cylinder/offsetbottom/) { get; set; } | 아래쪽의 정점 변환 오프셋을 가져오거나 설정합니다. |
| [OffsetTop](../../aspose.threed.entities/cylinder/offsettop/) { get; set; } | 위쪽 면의 정점 변환 오프셋을 가져오거나 설정합니다. |
| [OpenEnded](../../aspose.threed.entities/cylinder/openended/) { get; set; } | 이 여부를 나타내는 값을 가져오거나 설정합니다.`Cylinder` 개방 종료. 기본값은 false입니다. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 첫 번째 부모 노드를 가져오거나 설정합니다. 첫 번째 부모 노드를 설정하면 이 엔터티는 다른 부모 노드에서 분리됩니다. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 모든 부모 노드 가져오기 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 모든 속성의 컬렉션을 가져옵니다. |
| [RadialSegments](../../aspose.threed.entities/cylinder/radialsegments/) { get; set; } | 방사형 세그먼트를 가져오거나 설정합니다. |
| [RadiusBottom](../../aspose.threed.entities/cylinder/radiusbottom/) { get; set; } | 실린더 하단 캡의 반지름을 가져오거나 설정합니다. |
| [RadiusTop](../../aspose.threed.entities/cylinder/radiustop/) { get; set; } | 실린더 상단 캡의 반지름을 가져오거나 설정합니다. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | 이 지오메트리가 그림자를 받을 수 있는지 여부를 가져오거나 설정합니다. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 이 개체가 속한 장면을 가져옵니다 |
| [ShearBottom](../../aspose.threed.entities/cylinder/shearbottom/) { get; set; } | 바닥면의 전단 변환을 가져오거나 설정합니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장합니다. 기본값은 (0, 0) 입니다. |
| [ShearTop](../../aspose.threed.entities/cylinder/sheartop/) { get; set; } | 위쪽의 전단 변환을 가져오거나 설정합니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장합니다. 기본값은 (0, 0) 입니다. |
| [ThetaLength](../../aspose.threed.entities/cylinder/thetalength/) { get; set; } | 세타의 길이를 가져오거나 설정합니다. 기본값은 2π입니다. |
| [ThetaStart](../../aspose.threed.entities/cylinder/thetastart/) { get; set; } | 세타 시작을 가져오거나 설정합니다. 기본값은 0입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 속성을 찾습니다. 동적 속성(CreateDynamicProperty/SetProperty에 의해 생성됨) 또는 고유 속성(이름으로 식별됨) 일 수 있습니다. |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 오브젝트 공간 좌표계에서 현재 엔티티의 경계 상자를 가져옵니다. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | 렌더러 에 등록된 엔티티 렌더러의 키를 가져옵니다. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 지정된 property 의 값을 가져옵니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 동적 속성을 제거합니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name 로 식별되는 지정된 속성을 제거합니다. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 지정된 property 의 값을 설정합니다. |
| override [ToMesh](../../aspose.threed.entities/cylinder/tomesh/)() | 현재 개체를 mesh 로 변환 |

### 또한보십시오

* class [Primitive](../primitive/)
* 네임스페이스 [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* 집회 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->