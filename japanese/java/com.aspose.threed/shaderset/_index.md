---
title: ShaderSet
second_title: Aspose.3D for Java API リファレンス
description: 各種マテリアル用のシェーダープログラム
type: docs
weight: 166
url: /ja/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

各種マテリアル用のシェーダープログラム
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | [ShaderSet](../../com.aspose.threed/shaderset) のインスタンスを構築します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [close()](#close--) | このインスタンスを破棄し、すべてのシェーダープログラムを解放します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | 必要なシェーダーが利用できない場合のフォールバックシェーダーを取得します。 |
| [getLambert()](#getLambert--) | lambert マテリアルのレンダリングに使用されるシェーダーを取得します。 |
| [getPbr()](#getPbr--) | PBR マテリアルのレンダリングに使用されるシェーダーを取得します。 |
| [getPhong()](#getPhong--) | phong マテリアルのレンダリングに使用されるシェーダーを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | 必要なシェーダーが利用できない場合のフォールバックシェーダーを設定します。 |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | lambert マテリアルのレンダリングに使用されるシェーダーを設定します。 |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | PBR マテリアルのレンダリングに使用されるシェーダーを設定します。 |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | phong マテリアルのレンダリングに使用されるシェーダーを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


[ShaderSet](../../com.aspose.threed/shaderset) のインスタンスを構築します。

### close() {#close--}
```
public void close()
```


このインスタンスを破棄し、すべてのシェーダープログラムを解放します。

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
### getFallback() {#getFallback--}
```
public ShaderProgram getFallback()
```


必要なシェーダーが利用できない場合のフォールバックシェーダーを取得します。

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


lambert マテリアルのレンダリングに使用されるシェーダーを取得します。

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


PBR マテリアルのレンダリングに使用されるシェーダーを取得します。

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


phong マテリアルのレンダリングに使用されるシェーダーを取得します。

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the phong material
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




### setFallback(ShaderProgram value) {#setFallback-com.aspose.threed.ShaderProgram-}
```
public void setFallback(ShaderProgram value)
```


必要なシェーダーが利用できない場合のフォールバックシェーダーを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 新しい値 |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


lambert マテリアルのレンダリングに使用されるシェーダーを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 新しい値 |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


PBR マテリアルのレンダリングに使用されるシェーダーを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 新しい値 |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


phong マテリアルのレンダリングに使用されるシェーダーを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 新しい値 |

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

