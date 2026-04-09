---
title: IVertexBuffer
second_title: Aspose.3D for Java API Reference
description: वर्टेक्स बफ़र वह बहुभुज वर्टेक्स डेटा रखता है जिसे रेंडरिंग पाइपलाइन में भेजा जाएगा।
type: docs
weight: 259
url: /hi/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

वर्टेक्स बफ़र वह बहुभुज वर्टेक्स डेटा रखता है जिसे रेंडरिंग पाइपलाइन में भेजा जाएगा।
## Methods

| Method | विवरण |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | शीर्ष घोषणा प्राप्त करता है। |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | [TriMesh](../../com.aspose.threed/trimesh) से शीर्ष डेटा लोड करें |
| [loadData(Object array)](#loadData-java.lang.Object-) | ऐरे से डेटा लोड करें। |
| [loadData(long data, int size)](#loadData-long-int-) | दिए गए स्थान से डेटा लोड करें। |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


शीर्ष घोषणा प्राप्त करता है।

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


[TriMesh](../../com.aspose.threed/trimesh) से शीर्ष डेटा लोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


ऐरे से डेटा लोड करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| एरे | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


दिए गए स्थान से डेटा लोड करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डेटा | long |  |
| आकार | int |  |

