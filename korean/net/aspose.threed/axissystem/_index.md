---
title: "클래스 AxisSystem"
second_title: "Aspose.3D for .NET API 참조"
description: "Aspose.ThreeD.AxisSystem 클래스. 축 시스템은 좌표계의 업 벡터와 프론트 벡터의 조합입니다"
type: docs
weight: 150
url: /ko/net/aspose.threed/axissystem/
---
## AxisSystem class

축 시스템은 좌표계, 업 벡터 및 프론트 벡터의 조합입니다.

```csharp
public class AxisSystem
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [AxisSystem](axissystem/#constructor)(Axis, Axis?) |  |
| [AxisSystem](axissystem/#constructor_1)(CoordinateSystem, Axis) | 새 축 시스템을 생성합니다 |
| [AxisSystem](axissystem/#constructor_2)(CoordinateSystem, Axis, Axis) | 새 축 시스템을 생성합니다 |
| [AxisSystem](axissystem/#constructor_3)(CoordinateSystem?, Axis?, Axis?) |  |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CoordinateSystem](../../aspose.threed/axissystem/coordinatesystem/) { get; } | 이 축 시스템의 좌표계를 가져옵니다. |
| [Front](../../aspose.threed/axissystem/front/) { get; } | 이 축 시스템의 프론트 벡터를 가져옵니다 |
| [Up](../../aspose.threed/axissystem/up/) { get; } | 이 축 시스템의 업 벡터를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromAssetInfo](../../aspose.threed/axissystem/fromassetinfo/)(AssetInfo) | [`AssetInfo`](../assetinfo/)에서 `AxisSystem`을 생성합니다 |
| [TransformTo](../../aspose.threed/axissystem/transformto/)(AxisSystem) | 현재 축 시스템에서 대상 축 시스템으로 변환하는 데 사용되는 행렬을 생성합니다. |

### 또 보기

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


