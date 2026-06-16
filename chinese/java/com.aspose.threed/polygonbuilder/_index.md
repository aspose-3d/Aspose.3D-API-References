---
title: "PolygonBuilder"
second_title: "Aspose.3D for Java API 参考"
description: "用于构建多边形的帮助类，适用于 Example。"
type: docs
weight: 133
url: /zh/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

用于为 [Mesh](../../com.aspose.threed/mesh) 构建多边形的辅助类 **示例:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

等于：

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

如果所有索引都已准备好使用，首选 [Mesh](../../com.aspose.threed/mesh)，否则 [PolygonBuilder](../../com.aspose.threed/polygonbuilder) 将是更好的选择。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | 初始化 [PolygonBuilder](../../com.aspose.threed/polygonbuilder) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | 向多边形添加顶点索引 |
| [begin()](#begin--) | 开始添加新多边形 |
| [end()](#end--) | 完成多边形创建 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonBuilder(Mesh mesh) {#PolygonBuilder-com.aspose.threed.Mesh-}
```
public PolygonBuilder(Mesh mesh)
```


初始化 [PolygonBuilder](../../com.aspose.threed/polygonbuilder) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | 在何种网格上构建多边形。 |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


向多边形添加顶点索引

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int |  |

### begin() {#begin--}
```
public void begin()
```


开始添加新多边形

### end() {#end--}
```
public void end()
```


完成多边形创建

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

