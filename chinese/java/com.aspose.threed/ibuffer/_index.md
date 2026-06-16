---
title: "IBuffer"
second_title: "Aspose.3D for Java API 参考"
description: "所有渲染中使用的托管缓冲区的基础接口"
type: docs
weight: 239
url: /zh/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

所有渲染中使用的托管缓冲区的基础接口
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSize()](#getSize--) | 此缓冲区的大小（字节） |
| [loadData(byte[] data)](#loadData-byte---) | 将数据加载到当前缓冲区 |
### getSize() {#getSize--}
```
public abstract int getSize()
```


此缓冲区的大小（字节）

**Returns:**
int - 此缓冲区的大小（字节）
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


将数据加载到当前缓冲区

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] |  |

