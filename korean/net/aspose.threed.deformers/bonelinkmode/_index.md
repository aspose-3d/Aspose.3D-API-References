---
title: "BoneLinkMode 열거형"
second_title: "Aspose.3D for .NET API 참조"
description: "Aspose.ThreeD.Deformers.BoneLinkMode 열거형. 뼈 연결 모드는 계층 구조 내에서 뼈가 상위 뼈에 연결되거나 연결되는 방식을 나타냅니다."
type: docs
weight: 200
url: /ko/net/aspose.threed.deformers/bonelinkmode/
---
## BoneLinkMode enumeration

뼈의 연결 모드는 계층 구조 내에서 뼈가 상위 뼈에 연결되거나 연결되는 방식을 나타냅니다.

```csharp
public enum BoneLinkMode
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Normalize | `0` | 이 모드에서는 자식 뼈대의 변환이 부모 뼈대의 변환에 대해 정규화됩니다. |
| Additive | `1` | 가산 모드는 자식 뼈대의 변환을 자체 로컬 변환을 부모 뼈대의 변환에 더하여 계산합니다. |
| TotalOne | `2` | Total One은 부모와 자식 뼈대의 결합 변환이 전체 길이가 한 단위가 되도록 스케일되는 결합 변환을 보장합니다. |

### 또 보기

* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


