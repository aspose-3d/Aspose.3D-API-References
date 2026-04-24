---
title: IRenderTexture
second_title: Aspose.3D for Java API リファレンス
description: レンダーテクスチャのインターフェイス
type: docs
weight: 250
url: /ja/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

レンダーテクスチャのインターフェイス
## Methods

| Method | 説明 |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | 深度バッファテクスチャ |
| [getTargets()](#getTargets--) | カラ―出力ターゲット。 |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


深度バッファテクスチャ

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


カラ―出力ターゲット。

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - カラ―出力ターゲット。
