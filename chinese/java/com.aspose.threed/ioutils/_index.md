---
title: "IOUtils"
second_title: "Aspose.3D for Java API 参考"
description: "将矩阵/向量写入二进制写入器的实用工具。"
type: docs
weight: 77
url: /zh/java/com.aspose.threed/ioutils/
---

**Inheritance:**
java.lang.Object
```
public class IOUtils
```

将矩阵/向量写入二进制写入器的实用工具。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [IOUtils()](#IOUtils--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(BinaryWriter writer, FMatrix4 mat)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FMatrix4-) | 将矩阵写入二进制写入器 |
| [write(BinaryWriter writer, FVector2 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector2-) | 将向量写入二进制写入器 |
| [write(BinaryWriter writer, FVector3 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector3-) | 将向量写入二进制写入器 |
| [write(BinaryWriter writer, FVector4 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector4-) | 将向量写入二进制写入器 |
| [write(BinaryWriter writer, Matrix4 mat)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Matrix4-) | 将矩阵写入二进制写入器 |
| [write(BinaryWriter writer, Vector2 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector2-) | 将向量写入二进制写入器 |
| [write(BinaryWriter writer, Vector3 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector3-) | 将向量写入二进制写入器 |
| [write(BinaryWriter writer, Vector4 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector4-) | 将向量写入二进制写入器 |
### IOUtils() {#IOUtils--}
```
public IOUtils()
```


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

### write(BinaryWriter writer, FMatrix4 mat) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FMatrix4-}
```
public static void write(BinaryWriter writer, FMatrix4 mat)
```


将矩阵写入二进制写入器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 写入器 | com.aspose.csporter.helpers.BinaryWriter | 目标二进制写入器 |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | 待写入的矩阵 |

### write(BinaryWriter writer, FVector2 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector2-}
```
public static void write(BinaryWriter writer, FVector2 v)
```


将向量写入二进制写入器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 写入器 | com.aspose.csporter.helpers.BinaryWriter | 目标二进制写入器 |
| v | [FVector2](../../com.aspose.threed/fvector2) | 待写入的向量 |

### write(BinaryWriter writer, FVector3 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector3-}
```
public static void write(BinaryWriter writer, FVector3 v)
```


将向量写入二进制写入器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 写入器 | com.aspose.csporter.helpers.BinaryWriter | 目标二进制写入器 |
| v | [FVector3](../../com.aspose.threed/fvector3) | 待写入的向量 |

### write(BinaryWriter writer, FVector4 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector4-}
```
public static void write(BinaryWriter writer, FVector4 v)
```


将向量写入二进制写入器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 写入器 | com.aspose.csporter.helpers.BinaryWriter | 目标二进制写入器 |
| v | [FVector4](../../com.aspose.threed/fvector4) | 待写入的向量 |

### write(BinaryWriter writer, Matrix4 mat) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Matrix4-}
```
public static void write(BinaryWriter writer, Matrix4 mat)
```


将矩阵写入二进制写入器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 写入器 | com.aspose.csporter.helpers.BinaryWriter | 目标二进制写入器 |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | 待写入的矩阵 |

### write(BinaryWriter writer, Vector2 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector2-}
```
public static void write(BinaryWriter writer, Vector2 v)
```


将向量写入二进制写入器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 写入器 | com.aspose.csporter.helpers.BinaryWriter | 目标二进制写入器 |
| v | [Vector2](../../com.aspose.threed/vector2) | 待写入的向量 |

### write(BinaryWriter writer, Vector3 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector3-}
```
public static void write(BinaryWriter writer, Vector3 v)
```


将向量写入二进制写入器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 写入器 | com.aspose.csporter.helpers.BinaryWriter | 目标二进制写入器 |
| v | [Vector3](../../com.aspose.threed/vector3) | 待写入的向量 |

### write(BinaryWriter writer, Vector4 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector4-}
```
public static void write(BinaryWriter writer, Vector4 v)
```


将向量写入二进制写入器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 写入器 | com.aspose.csporter.helpers.BinaryWriter | 目标二进制写入器 |
| v | [Vector4](../../com.aspose.threed/vector4) | 待写入的向量 |

