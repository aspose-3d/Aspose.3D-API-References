---
title: SceneObject
second_title: .NET API 참조용 Aspose.3D
description: 장면 내부에 저장될 객체의 루트 클래스입니다.
type: docs
weight: 2260
url: /ko/net/aspose.threed/sceneobject/
---
## SceneObject class

장면 내부에 저장될 객체의 루트 클래스입니다.

```csharp
public abstract class SceneObject : A3DObject
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SceneObject](sceneobject/#constructor)() | SceneObject를 초기화합니다. |
| [SceneObject](sceneobject/#constructor_1)(string) | 기본 이름 로 SceneObject 초기화 |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 이름을 가져오거나 설정합니다. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 모든 속성의 컬렉션을 가져옵니다. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 이 개체가 속한 장면을 가져옵니다 |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 속성을 찾습니다. 동적 속성(CreateDynamicProperty/SetProperty에 의해 생성됨) 또는 고유 속성(이름으로 식별됨) 일 수 있습니다. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 지정된 property 의 값을 가져옵니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 동적 속성을 제거합니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name 로 식별되는 지정된 속성을 제거합니다. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 지정된 property 의 값을 설정합니다. |

### 또한보십시오

* class [A3DObject](../a3dobject/)
* 네임스페이스 [Aspose.ThreeD](../../aspose.threed/)
* 집회 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
