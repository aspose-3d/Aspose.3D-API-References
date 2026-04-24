---
title: ITextureDecoder
second_title: Aspose.3D for Java API 레퍼런스
description: 외부 텍스처 디코더는 디코딩을 위해 이 인터페이스를 구현해야 합니다.
type: docs
weight: 256
url: /ko/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

외부 텍스처 디코더는 디코딩을 위해 이 인터페이스를 구현해야 합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | 스트림에서 텍스처를 디코딩하고, 디코딩에 실패하면 null을 반환합니다. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


스트림에서 텍스처를 디코딩하고, 디코딩에 실패하면 null을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 텍스처 데이터 소스 스트림 |
| reverseY | boolean | 텍스처를 뒤집기 |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
