---
title: ITextureEncoder
second_title: Aspose.3D for Java API 레퍼런스
description: 외부 텍스처 인코더는 인코딩을 위해 이 인터페이스를 구현해야 합니다.
type: docs
weight: 257
url: /ko/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

외부 텍스처 인코더는 인코딩을 위해 이 인터페이스를 구현해야 합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | 텍스처 데이터를 스트림에 인코딩합니다. |
| [getFileExtension()](#getFileExtension--) | 이 인코더의 파일 확장자 이름(점 없이) |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


텍스처 데이터를 스트림에 인코딩합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | 인코딩될 텍스처 데이터 |
| stream | [Stream](../../com.aspose.threed/stream) | 출력 스트림 |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


이 인코더의 파일 확장자 이름(점 없이)

**Returns:**
java.lang.String - 이 인코더의 파일 확장자 이름(점 없이)
