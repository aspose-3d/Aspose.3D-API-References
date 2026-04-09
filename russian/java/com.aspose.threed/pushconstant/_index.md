---
title: PushConstant
second_title: Справочник API Aspose.3D для Java
description: Утилита для передачи данных в шейдер через push‑константу.
type: docs
weight: 141
url: /ru/java/com.aspose.threed/pushconstant/
---

**Inheritance:**
java.lang.Object
```
public class PushConstant
```

Утилита для передачи данных в шейдер через push‑константу.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PushConstant()](#PushConstant--) | Конструктор класса [PushConstant](../../com.aspose.threed/pushconstant) |
## Методы

| Метод | Описание |
| --- | --- |
| [commit(int stage, ICommandList commandList)](#commit-int-com.aspose.threed.ICommandList-) | Фиксирует подготовленные данные в графический конвейер. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(FMatrix4 mat)](#write-com.aspose.threed.FMatrix4-) | Записать матрицу в константу |
| [write(FVector3 vec)](#write-com.aspose.threed.FVector3-) | Записать 3‑компонентный вектор в константу |
| [write(FVector4 vec)](#write-com.aspose.threed.FVector4-) | Записать 4‑компонентный вектор в константу |
| [write(float f)](#write-float-) | Записать значение типа float в константу |
| [write(float x, float y, float z, float w)](#write-float-float-float-float-) | Записать 4‑компонентный вектор в константу |
| [write(int n)](#write-int-) | Записать значение типа int в константу |
### PushConstant() {#PushConstant--}
```
public PushConstant()
```


Конструктор класса [PushConstant](../../com.aspose.threed/pushconstant)

### commit(int stage, ICommandList commandList) {#commit-int-com.aspose.threed.ICommandList-}
```
public PushConstant commit(int stage, ICommandList commandList)
```


Фиксирует подготовленные данные в графический конвейер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| этап | int |  |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(FMatrix4 mat) {#write-com.aspose.threed.FMatrix4-}
```
public PushConstant write(FMatrix4 mat)
```


Записать матрицу в константу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mat | [FMatrix4](../../com.aspose.threed/fmatrix4) | Матрица для записи |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector3 vec) {#write-com.aspose.threed.FVector3-}
```
public PushConstant write(FVector3 vec)
```


Записать 3‑компонентный вектор в константу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(FVector4 vec) {#write-com.aspose.threed.FVector4-}
```
public PushConstant write(FVector4 vec)
```


Записать 4‑компонентный вектор в константу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float f) {#write-float-}
```
public PushConstant write(float f)
```


Записать значение типа float в константу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| f | float |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
### write(float x, float y, float z, float w) {#write-float-float-float-float-}
```
public PushConstant write(float x, float y, float z, float w)
```


Записать 4‑компонентный вектор в константу

**Parameters:**
| Параметр | Тип | Описание |
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


Записать значение типа int в константу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| n | int |  |

**Returns:**
[PushConstant](../../com.aspose.threed/pushconstant)
