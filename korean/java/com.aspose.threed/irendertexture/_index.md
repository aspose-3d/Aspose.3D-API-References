---
title: IRenderTexture
second_title: Aspose.3D for Java API 레퍼런스
description: 렌더 텍스처의 인터페이스
type: docs
weight: 250
url: /ko/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

렌더 텍스처의 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | 깊이 버퍼 텍스처 |
| [getTargets()](#getTargets--) | 색상 출력 대상. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


깊이 버퍼 텍스처

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


색상 출력 대상.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - 색상 출력 대상.
