---
title: IBuffer
second_title: Aspose.3D for Java API Reference
description: रेंडरिंग में उपयोग किए जाने वाले सभी प्रबंधित बफ़र्स का बेस इंटरफ़ेस
type: docs
weight: 239
url: /hi/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

रेंडरिंग में उपयोग किए जाने वाले सभी प्रबंधित बफ़र्स का बेस इंटरफ़ेस
## Methods

| Method | विवरण |
| --- | --- |
| [getSize()](#getSize--) | इस बफ़र का आकार बाइट्स में |
| [loadData(byte[] data)](#loadData-byte---) | डेटा को वर्तमान बफ़र में लोड करें |
### getSize() {#getSize--}
```
public abstract int getSize()
```


इस बफ़र का आकार बाइट्स में

**Returns:**
int - इस बफ़र का आकार बाइट्स में
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


डेटा को वर्तमान बफ़र में लोड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डेटा | byte[] |  |

