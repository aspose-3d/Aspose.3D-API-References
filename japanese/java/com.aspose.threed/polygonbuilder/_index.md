---
title: PolygonBuilder
second_title: Aspose.3D for Java API リファレンス
description: Example 用にポリゴンを構築するヘルパークラスです
type: docs
weight: 133
url: /ja/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

ポリゴンを構築するためのヘルパークラスです [Mesh](../../com.aspose.threed/mesh) **Example:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

等しい :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

すべてのインデックスが使用可能な場合は、[Mesh](../../com.aspose.threed/mesh) が推奨されます。そうでなければ、[PolygonBuilder](../../com.aspose.threed/polygonbuilder) の方が適しています。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | 新しい [PolygonBuilder](../../com.aspose.threed/polygonbuilder) クラスのインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | ポリゴンに頂点インデックスを追加します |
| [begin()](#begin--) | 新しいポリゴンの追加を開始します |
| [end()](#end--) | ポリゴンの作成を完了します |
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


新しい [PolygonBuilder](../../com.aspose.threed/polygonbuilder) クラスのインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | ポリゴンを構築するメッシュです。 |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


ポリゴンに頂点インデックスを追加します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| インデックス | int |  |

### begin() {#begin--}
```
public void begin()
```


新しいポリゴンの追加を開始します

### end() {#end--}
```
public void end()
```


ポリゴンの作成を完了します

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

