---
title: StencilState
second_title: Справочник API Aspose.3D для Java
description: Состояния трафарета для каждой грани.
type: docs
weight: 175
url: /ru/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

Состояния трафарета для каждой грани.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли данный экземпляр указанному объекту. |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | Получает функцию сравнения, используемую в тесте трафарета |
| [getDepthFailAction()](#getDepthFailAction--) | Получает действие трафарета, когда тест трафарета проходит, а тест глубины не проходит. |
| [getFailAction()](#getFailAction--) | Получает действие трафарета, когда тест трафарета не проходит. |
| [getPassAction()](#getPassAction--) | Получает действие трафарета, когда оба теста — трафарета и глубины — проходят. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для данного экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | Устанавливает функцию сравнения, используемую в тесте трафарета |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | Устанавливает действие трафарета, когда тест трафарета проходит, а тест глубины не проходит. |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | Устанавливает действие трафарета, когда тест трафарета не проходит. |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | Устанавливает действие трафарета, когда оба теста — трафарета и глубины — проходят. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли данный экземпляр указанному объекту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompare() {#getCompare--}
```
public CompareFunction getCompare()
```


Получает функцию сравнения, используемую в тесте трафарета

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


Получает действие трафарета, когда тест трафарета проходит, а тест глубины не проходит.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


Получает действие трафарета, когда тест трафарета не проходит.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


Получает действие трафарета, когда оба теста — трафарета и глубины — проходят.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для данного экземпляра.

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




### setCompare(CompareFunction value) {#setCompare-com.aspose.threed.CompareFunction-}
```
public void setCompare(CompareFunction value)
```


Устанавливает функцию сравнения, используемую в тесте трафарета

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Новое значение |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


Устанавливает действие трафарета, когда тест трафарета проходит, а тест глубины не проходит.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Новое значение |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


Устанавливает действие трафарета, когда тест трафарета не проходит.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Новое значение |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


Устанавливает действие трафарета, когда оба теста — трафарета и глубины — проходят.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Новое значение |

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

