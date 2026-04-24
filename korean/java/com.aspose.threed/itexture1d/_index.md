---
title: ITexture1D
second_title: Aspose.3D for Java API 레퍼런스
description: 1D 텍스처
type: docs
weight: 252
url: /ko/java/com.aspose.threed/itexture1d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture1D extends ITextureUnit
```

1D 텍스처
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | 지정된 비트맵에서 텍스처 콘텐츠를 로드합니다 |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | 텍스처 콘텐츠를 외부 파일에 저장합니다. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | 텍스처 콘텐츠를 외부 파일에 저장합니다. |
| [toBitmap()](#toBitmap--) | 텍스처 유닛을 [TextureData](../../com.aspose.threed/texturedata) 인스턴스로 변환합니다 |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


지정된 비트맵에서 텍스처 콘텐츠를 로드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


텍스처 콘텐츠를 외부 파일에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | 저장할 결과 비트맵. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


텍스처 콘텐츠를 외부 파일에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 경로 | java.lang.String | 저장할 파일 이름. |
| 형식 | java.lang.String | 이미지 형식 |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


텍스처 유닛을 [TextureData](../../com.aspose.threed/texturedata) 인스턴스로 변환합니다

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
