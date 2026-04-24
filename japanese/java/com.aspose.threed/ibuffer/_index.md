---
title: IBuffer
second_title: Aspose.3D for Java API リファレンス
description: レンダリングで使用されるすべての管理バッファの基本インターフェイス
type: docs
weight: 239
url: /ja/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

レンダリングで使用されるすべての管理バッファの基本インターフェイス
## Methods

| Method | 説明 |
| --- | --- |
| [getSize()](#getSize--) | このバッファのサイズ（バイト単位） |
| [loadData(byte[] data)](#loadData-byte---) | データを現在のバッファにロードします |
### getSize() {#getSize--}
```
public abstract int getSize()
```


このバッファのサイズ（バイト単位）

**Returns:**
int - このバッファのサイズ（バイト単位）
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


データを現在のバッファにロードします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| データ | byte[] |  |

