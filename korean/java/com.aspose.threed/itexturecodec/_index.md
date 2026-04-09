---
title: ITextureCodec
second_title: Aspose.3D for Java API 레퍼런스
description: 텍스처 코덱
type: docs
weight: 254
url: /ko/java/com.aspose.threed/itexturecodec/
---
```
public interface ITextureCodec
```

텍스처 코덱
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDecoders()](#getDecoders--) | 지원되는 텍스처 디코더를 가져옵니다. |
| [getEncoders()](#getEncoders--) | 지원되는 텍스처 인코더를 가져옵니다. |
### getDecoders() {#getDecoders--}
```
public abstract ITextureDecoder[] getDecoders()
```


지원되는 텍스처 디코더를 가져옵니다.

**Returns:**
com.aspose.threed.ITextureDecoder[] - 지원되는 텍스처 디코더의 배열
### getEncoders() {#getEncoders--}
```
public abstract ITextureEncoder[] getEncoders()
```


지원되는 텍스처 인코더를 가져옵니다.

**Returns:**
com.aspose.threed.ITextureEncoder[] - 지원되는 텍스처 인코더의 배열
