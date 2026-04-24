---
title: ITextureCubemap
second_title: Aspose.3D for Java API 레퍼런스
description: 큐브맵 텍스처
type: docs
weight: 255
url: /ko/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

큐브맵 텍스처
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | 지정된 면에 데이터를 로드합니다. |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | 지정된 [TextureData](../../com.aspose.threed/texturedata)에서 텍스처 내용을 로드합니다. |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | 지정된 파일에서 텍스처 콘텐츠를 로드합니다. |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | 지정된 면을 메모리에 저장합니다. |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | 텍스처 콘텐츠를 메모리에 저장합니다. |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | 큐브 면의 텍스처 콘텐츠를 외부 파일에 저장합니다. |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | 텍스처 유닛을 [TextureData](../../com.aspose.threed/texturedata) 인스턴스로 변환합니다 |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


지정된 면에 데이터를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


지정된 [TextureData](../../com.aspose.threed/texturedata)에서 텍스처 내용을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


지정된 파일에서 텍스처 콘텐츠를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


지정된 면을 메모리에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


텍스처 콘텐츠를 메모리에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | 저장할 결과 비트맵. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


큐브 면의 텍스처 콘텐츠를 외부 파일에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 경로 | com.aspose.threed.CubeFaceData<java.lang.String> | 저장할 파일 이름. |
| 형식 | java.lang.String | 이미지 형식 |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


텍스처 유닛을 [TextureData](../../com.aspose.threed/texturedata) 인스턴스로 변환합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
