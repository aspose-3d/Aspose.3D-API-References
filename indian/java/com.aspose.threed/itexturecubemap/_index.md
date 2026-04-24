---
title: ITextureCubemap
second_title: Aspose.3D for Java API Reference
description: क्यूब मैप टेक्सचर
type: docs
weight: 255
url: /hi/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

क्यूब मैप टेक्सचर
## Methods

| Method | विवरण |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | निर्दिष्ट फेस में डेटा लोड करें |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | निर्दिष्ट [TextureData](../../com.aspose.threed/texturedata) से टेक्सचर सामग्री लोड करें |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | निर्दिष्ट फ़ाइलों से टेक्सचर सामग्री लोड करें |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | निर्दिष्ट साइड को मेमोरी में सहेजें |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | टेक्सचर सामग्री को मेमोरी में सहेजें। |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | क्यूब के साइड्स की टेक्सचर सामग्री को बाहरी फ़ाइलों में सहेजें। |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | Convert the texture unit to [TextureData](../../com.aspose.threed/texturedata) instance |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


निर्दिष्ट फेस में डेटा लोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


निर्दिष्ट [TextureData](../../com.aspose.threed/texturedata) से टेक्सचर सामग्री लोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डेटा | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


निर्दिष्ट फ़ाइलों से टेक्सचर सामग्री लोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


निर्दिष्ट साइड को मेमोरी में सहेजें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


टेक्सचर सामग्री को मेमोरी में सहेजें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | Result bitmap to save. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


क्यूब के साइड्स की टेक्सचर सामग्री को बाहरी फ़ाइलों में सहेजें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| path | com.aspose.threed.CubeFaceData<java.lang.String> | सहेजने के लिए फ़ाइल नाम। |
| format | java.lang.String | Image format |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


Convert the texture unit to [TextureData](../../com.aspose.threed/texturedata) instance

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
