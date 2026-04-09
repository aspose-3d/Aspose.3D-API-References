---
title: GLSLSource
second_title: Aspose.3D for Java API リファレンス
description: GLSL のシェーダーのソースコードです。
type: docs
weight: 70
url: /ja/java/com.aspose.threed/glslsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.ShaderSource](../../com.aspose.threed/shadersource)
```
public final class GLSLSource extends ShaderSource
```

GLSL のシェーダーのソースコードです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [GLSLSource()](#GLSLSource--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [defineInclude(String fileName, String content)](#defineInclude-java.lang.String-java.lang.String-) | GLSL ソースコード内の \#include 用に仮想ファイルを定義します |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComputeShader()](#getComputeShader--) | コンピュートシェーダーのソースコードを取得します。 |
| [getFragmentShader()](#getFragmentShader--) | フラグメントシェーダーのソースコードを取得します。 |
| [getGeometryShader()](#getGeometryShader--) | ジオメトリシェーダーのソースコードを取得します。 |
| [getVertexShader()](#getVertexShader--) | 頂点シェーダーのソースコードを取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setComputeShader(String value)](#setComputeShader-java.lang.String-) | コンピュートシェーダーのソースコードを設定します。 |
| [setFragmentShader(String value)](#setFragmentShader-java.lang.String-) | フラグメントシェーダーのソースコードを設定します。 |
| [setGeometryShader(String value)](#setGeometryShader-java.lang.String-) | ジオメトリシェーダーのソースコードを設定します。 |
| [setVertexShader(String value)](#setVertexShader-java.lang.String-) | 頂点シェーダーのソースコードを設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GLSLSource() {#GLSLSource--}
```
public GLSLSource()
```


### defineInclude(String fileName, String content) {#defineInclude-java.lang.String-java.lang.String-}
```
public void defineInclude(String fileName, String content)
```


GLSL ソースコード内の \#include 用に仮想ファイルを定義します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | 仮想ファイルのファイル名 |
| コンテンツ | java.lang.String |  |

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
### getComputeShader() {#getComputeShader--}
```
public String getComputeShader()
```


コンピュートシェーダーのソースコードを取得します。

**Returns:**
java.lang.String - コンピュートシェーダーのソースコード。
### getFragmentShader() {#getFragmentShader--}
```
public String getFragmentShader()
```


フラグメントシェーダーのソースコードを取得します。

**Returns:**
java.lang.String - フラグメントシェーダーのソースコード。
### getGeometryShader() {#getGeometryShader--}
```
public String getGeometryShader()
```


ジオメトリシェーダーのソースコードを取得します。

**Returns:**
java.lang.String - ジオメトリシェーダーのソースコード。
### getVertexShader() {#getVertexShader--}
```
public String getVertexShader()
```


頂点シェーダーのソースコードを取得します

**Returns:**
java.lang.String - 頂点シェーダーのソースコード
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




### setComputeShader(String value) {#setComputeShader-java.lang.String-}
```
public void setComputeShader(String value)
```


コンピュートシェーダーのソースコードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setFragmentShader(String value) {#setFragmentShader-java.lang.String-}
```
public void setFragmentShader(String value)
```


フラグメントシェーダーのソースコードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setGeometryShader(String value) {#setGeometryShader-java.lang.String-}
```
public void setGeometryShader(String value)
```


ジオメトリシェーダーのソースコードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setVertexShader(String value) {#setVertexShader-java.lang.String-}
```
public void setVertexShader(String value)
```


頂点シェーダーのソースコードを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

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

