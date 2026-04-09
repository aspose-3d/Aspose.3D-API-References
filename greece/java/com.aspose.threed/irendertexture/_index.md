---
title: IRenderTexture
second_title: Aspose.3D for Java API Reference
description: Η διεπαφή της υφής απόδοσης
type: docs
weight: 250
url: /el/java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

Η διεπαφή της υφής απόδοσης
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDepthTexture()](#getDepthTexture--) | Υφή buffer βάθους |
| [getTargets()](#getTargets--) | Στόχοι εξόδου χρώματος. |
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


Υφή buffer βάθους

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - Depth buffer texture
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


Στόχοι εξόδου χρώματος.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit> - Στόχοι εξόδου χρώματος.
