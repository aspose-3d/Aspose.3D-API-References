---
title: "ITextureDecoder.Decode"
second_title: "Aspose.3D for .NET API 참조"
description: "ITextureDecoder 메서드. 스트림에서 텍스처를 디코딩합니다. 디코딩에 실패하면 null을 반환합니다"
type: docs
weight: 10
url: /ko/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

스트림에서 텍스처를 디코딩하고, 디코딩에 실패하면 null을 반환합니다.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 텍스처 데이터 소스 스트림 |
| reverseY | Boolean | 텍스처를 뒤집습니다 |

### 반환 값

디코딩된 텍스처 데이터 또는 지원되지 않을 경우 null

### 예외

| 예외 | 조건 |
| --- | --- |
| IOException | 스트림에서 데이터를 읽는 데 실패했을 때 발생합니다 |

### 또 보기

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


