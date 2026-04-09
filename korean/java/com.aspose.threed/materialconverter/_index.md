---
title: MaterialConverter
second_title: Aspose.3D for Java API 레퍼런스
description: 기하학 원본 재질을 GLTF의 PBR 재질로 변환하는 사용자 정의 변환기.
type: docs
weight: 260
url: /ko/java/com.aspose.threed/materialconverter/
---
```
public interface MaterialConverter
```

지오메트리의 원본 머티리얼을 GLTF의 PBR 머티리얼로 변환하는 사용자 정의 변환기입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [call(Material mat)](#call-com.aspose.threed.Material-) | 지오메트리의 원본 머티리얼을 GLTF의 PBR 머티리얼로 변환하는 사용자 정의 변환기입니다. |
### call(Material mat) {#call-com.aspose.threed.Material-}
```
public abstract Material call(Material mat)
```


지오메트리의 원본 머티리얼을 GLTF의 PBR 머티리얼로 변환하는 사용자 정의 변환기입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mat | [Material](../../com.aspose.threed/material) | 이전 재질 인스턴스 |

**Returns:**
[Material](../../com.aspose.threed/material) - New material instance
