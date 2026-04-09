---
title: IOUtils
second_title: Aspose.3D for Java API 레퍼런스
description: 행렬/벡터를 바이너리 라이터에 쓰기 위한 유틸리티
type: docs
weight: 77
url: /ko/java/com.aspose.threed/ioutils/
---

**Inheritance:**
java.lang.Object
```
public class IOUtils
```

행렬/벡터를 바이너리 라이터에 쓰기 위한 유틸리티
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [IOUtils()](#IOUtils--) |  |
## 메서드

| 메서드 | 설명 |
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
| [write(BinaryWriter writer, FMatrix4 mat)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FMatrix4-) | 행렬을 바이너리 라이터에 씁니다 |
| [write(BinaryWriter writer, FVector2 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector2-) | 벡터를 바이너리 라이터에 씁니다 |
| [write(BinaryWriter writer, FVector3 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector3-) | 벡터를 바이너리 라이터에 씁니다 |
| [write(BinaryWriter writer, FVector4 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector4-) | 벡터를 바이너리 라이터에 씁니다 |
| [write(BinaryWriter writer, Matrix4 mat)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Matrix4-) | 행렬을 바이너리 라이터에 씁니다 |
| [write(BinaryWriter writer, Vector2 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector2-) | 벡터를 바이너리 라이터에 씁니다 |
| [write(BinaryWriter writer, Vector3 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector3-) | 벡터를 바이너리 라이터에 씁니다 |
| [write(BinaryWriter writer, Vector4 v)](#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector4-) | 벡터를 바이너리 라이터에 씁니다 |
### IOUtils() {#IOUtils--}
```
public IOUtils()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(BinaryWriter writer, FMatrix4 mat) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FMatrix4-}
```
public static void write(BinaryWriter writer, FMatrix4 mat)
```


행렬을 바이너리 라이터에 씁니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 라이터 | com.aspose.csporter.helpers.BinaryWriter | 대상 바이너리 라이터 |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | 작성할 행렬 |

### write(BinaryWriter writer, FVector2 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector2-}
```
public static void write(BinaryWriter writer, FVector2 v)
```


벡터를 바이너리 라이터에 씁니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 라이터 | com.aspose.csporter.helpers.BinaryWriter | 대상 바이너리 라이터 |
| v | [FVector2](../../com.aspose.threed/fvector2) | 작성할 벡터 |

### write(BinaryWriter writer, FVector3 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector3-}
```
public static void write(BinaryWriter writer, FVector3 v)
```


벡터를 바이너리 라이터에 씁니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 라이터 | com.aspose.csporter.helpers.BinaryWriter | 대상 바이너리 라이터 |
| v | [FVector3](../../com.aspose.threed/fvector3) | 작성할 벡터 |

### write(BinaryWriter writer, FVector4 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.FVector4-}
```
public static void write(BinaryWriter writer, FVector4 v)
```


벡터를 바이너리 라이터에 씁니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 라이터 | com.aspose.csporter.helpers.BinaryWriter | 대상 바이너리 라이터 |
| v | [FVector4](../../com.aspose.threed/fvector4) | 작성할 벡터 |

### write(BinaryWriter writer, Matrix4 mat) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Matrix4-}
```
public static void write(BinaryWriter writer, Matrix4 mat)
```


행렬을 바이너리 라이터에 씁니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 라이터 | com.aspose.csporter.helpers.BinaryWriter | 대상 바이너리 라이터 |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | 작성할 행렬 |

### write(BinaryWriter writer, Vector2 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector2-}
```
public static void write(BinaryWriter writer, Vector2 v)
```


벡터를 바이너리 라이터에 씁니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 라이터 | com.aspose.csporter.helpers.BinaryWriter | 대상 바이너리 라이터 |
| v | [Vector2](../../com.aspose.threed/vector2) | 작성할 벡터 |

### write(BinaryWriter writer, Vector3 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector3-}
```
public static void write(BinaryWriter writer, Vector3 v)
```


벡터를 바이너리 라이터에 씁니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 라이터 | com.aspose.csporter.helpers.BinaryWriter | 대상 바이너리 라이터 |
| v | [Vector3](../../com.aspose.threed/vector3) | 작성할 벡터 |

### write(BinaryWriter writer, Vector4 v) {#write-com.aspose.csporter.helpers.BinaryWriter-com.aspose.threed.Vector4-}
```
public static void write(BinaryWriter writer, Vector4 v)
```


벡터를 바이너리 라이터에 씁니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 라이터 | com.aspose.csporter.helpers.BinaryWriter | 대상 바이너리 라이터 |
| v | [Vector4](../../com.aspose.threed/vector4) | 작성할 벡터 |

