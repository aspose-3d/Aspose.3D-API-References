---
title: IIndexBuffer
second_title: Aspose.3D for Java API Reference
description: इंडेक्स बफ़र रेंडरिंग पाइपलाइन में उपयोग की गई ज्यामिति का वर्णन करता है।
type: docs
weight: 242
url: /hi/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

इंडेक्स बफ़र रेंडरिंग पाइपलाइन में उपयोग की गई ज्यामिति का वर्णन करता है।
## Methods

| Method | विवरण |
| --- | --- |
| [getCount()](#getCount--) | इस बफ़र में सूचकांक की संख्या प्राप्त करता है। |
| [getIndexDataType()](#getIndexDataType--) | प्रत्येक तत्व का डेटा प्रकार प्राप्त करता है। |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | से [TriMesh](../../com.aspose.threed/trimesh) इंडिस डेटा लोड करें |
| [loadData(int[] indices)](#loadData-int---) | इंडिस डेटा लोड करें |
| [loadData(short[] indices)](#loadData-short---) | इंडिस डेटा लोड करें |
### getCount() {#getCount--}
```
public abstract int getCount()
```


इस बफ़र में सूचकांक की संख्या प्राप्त करता है।

**Returns:**
int - इस बफ़र में सूचकांक की संख्या।
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


प्रत्येक तत्व का डेटा प्रकार प्राप्त करता है।

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


से [TriMesh](../../com.aspose.threed/trimesh) इंडिस डेटा लोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


इंडिस डेटा लोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


इंडिस डेटा लोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | short[] |  |

