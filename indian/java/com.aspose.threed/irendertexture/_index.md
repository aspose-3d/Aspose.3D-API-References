---
title: IRenderTexture
second_title: Aspose.3D for Java API Reference
description: रेंडर टेक्सचर का इंटरफ़ेस
type: docs
weight: 250
url: /hi/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

रेंडर टेक्सचर का इंटरफ़ेस
## Methods

| Method | विवरण |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | डेप्थ बफ़र टेक्सचर |
| [getTargets()](#getTargets--) | रंग आउटपुट लक्ष्य। |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


डेप्थ बफ़र टेक्सचर

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


रंग आउटपुट लक्ष्य।

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - रंग आउटपुट लक्ष्य।
