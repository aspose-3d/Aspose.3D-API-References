---
title: Property
second_title: .NET API 참조용 Aspose.3D
description: 사용자 정의 속성을 보유하는 클래스.
type: docs
weight: 1670
url: /ko/net/aspose.threed/property/
---
## Property class

사용자 정의 속성을 보유하는 클래스.

```csharp
public abstract class Property : A3DObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Name](../../aspose.threed/property/name/) { set; } |  |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 모든 속성의 컬렉션을 가져옵니다. |
| abstract [Value](../../aspose.threed/property/value/) { get; set; } | 값을 가져오거나 설정합니다. |
| abstract [ValueType](../../aspose.threed/property/valuetype/) { get; } | 속성 값의 유형을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 속성을 찾습니다. 동적 속성(CreateDynamicProperty/SetProperty에 의해 생성됨) 또는 고유 속성(이름으로 식별됨) 일 수 있습니다. |
| [GetBindPoint](../../aspose.threed/property/getbindpoint/)(AnimationNode, bool) | 지정된 애니메이션 인스턴스의 속성 바인드 포인트를 가져옵니다. |
| [GetKeyframeSequence](../../aspose.threed/property/getkeyframesequence/)(AnimationNode, bool) | 지정된 애니메이션 인스턴스의 키프레임 시퀀스를 가져옵니다. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 지정된 property 의 값을 가져옵니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 동적 속성을 제거합니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name 로 식별되는 지정된 속성을 제거합니다. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 지정된 property 의 값을 설정합니다. |
| override [ToString](../../aspose.threed/property/tostring/)() | 현재를 나타내는 문자열을 반환합니다.`Property` . |

### 또한보십시오

* class [A3DObject](../a3dobject/)
* 네임스페이스 [Aspose.ThreeD](../../aspose.threed/)
* 집회 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
