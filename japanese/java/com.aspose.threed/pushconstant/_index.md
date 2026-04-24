---
title: PushConstant
second_title: Aspose.3D for Java API リファレンス
description: プッシュ定数を介してシェーダーにデータを提供するユーティリティです。
type: docs
weight: 141
url: /ja/java/com.aspose.threed/pushconstant/
---

**Inheritance:**
java.lang.Object
```
public class PushConstant
```

プッシュ定数を介してシェーダーにデータを提供するユーティリティです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PushConstant()](#PushConstant--) | [PushConstant](../../com.aspose.threed/pushconstant) のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [commit(int stage, ICommandList commandList)](#commit-int-com.aspose.threed.ICommandList-) | 準備されたデータをグラフィックスパイプラインにコミットします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(FMatrix4 mat)](#write-com.aspose.threed.FMatrix4-) | 定数に行列を書き込みます |
| [write(FVector3 vec)](#write-com.aspose.threed.FVector3-) | 定数に3成分ベクトルを書き込みます |
| [write(FVector4 vec)](#write-com.aspose.threed.FVector4-) | 定数に4成分ベクトルを書き込みます |
| [write(float f)](#write-float-) | 定数にfloat値を書き込みます |
| [write(float x, float y, float z, float w)](#write-float-float-float-float-) | 定数に4成分ベクトルを書き込みます |
| [write(int n)](#write-int-) | 定数にint値を書き込みます |
### PushConstant() {#PushConstant--}
```
public PushConstant()
```


[PushConstant](../../com.aspose.threed/pushconstant) のコンストラクタ

### commit(int stage, ICommandList commandList) {#commit-int-com.aspose.threed.ICommandList-}
```
public PushConstant commit(int stage, ICommandList commandList)
```


準備されたデータをグラフィックスパイプラインにコミットします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ステージ | int |  |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
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

### write(FMatrix4 mat) {#write-com.aspose.threed.FMatrix4-}
```
public PushConstant write(FMatrix4 mat)
```


定数に行列を書き込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | 書き込む行列 |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector3 vec) {#write-com.aspose.threed.FVector3-}
```
public PushConstant write(FVector3 vec)
```


定数に3成分ベクトルを書き込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector4 vec) {#write-com.aspose.threed.FVector4-}
```
public PushConstant write(FVector4 vec)
```


定数に4成分ベクトルを書き込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float f) {#write-float-}
```
public PushConstant write(float f)
```


定数にfloat値を書き込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| f | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float x, float y, float z, float w) {#write-float-float-float-float-}
```
public PushConstant write(float x, float y, float z, float w)
```


定数に4成分ベクトルを書き込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| z | float |  |
| w | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(int n) {#write-int-}
```
public PushConstant write(int n)
```


定数にint値を書き込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| n | int |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
