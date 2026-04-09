---
title: Watermark
second_title: Справочник API Aspose.3D для Java
description: Утилита для кодирования/декодирования слепого водяного знака в/из сетки.
type: docs
weight: 230
url: /ru/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

Утилита для кодирования/декодирования слепого водяного знака в/из сетки. **Remarks:** Оба [Watermark](../../com.aspose.threed/watermark) и [Watermark](../../com.aspose.threed/watermark) выполняют проверку лицензии. Использование в режиме пробной версии вызовет исключение, вы можете использовать [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) для подавления исключения, но это не снимет ограничение здесь. Для использования этих функций без ограничений требуется действительная лицензия. **Example:** Следующий код показывает, как закодировать слепой водяной знак в сетку и декодировать его.

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## Методы

| Метод | Описание |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | Декодировать водяной знак из сетки |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Декодировать водяной знак из сетки |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Закодировать текст в слепой водяной знак сетки. |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | Закодировать текст в слепой водяной знак сетки. |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | Закодировать текст в слепой водяной знак сетки. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### decodeWatermark(Mesh input) {#decodeWatermark-com.aspose.threed.Mesh-}
```
public static String decodeWatermark(Mesh input)
```


Декодировать водяной знак из сетки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Сетка для извлечения водяного знака |

**Returns:**
java.lang.String - слепой водяной знак или null, если водяной знак не декодирован.
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


Декодировать водяной знак из сетки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Сетка для извлечения водяного знака |
| пароль | java.lang.String | Пароль для расшифровки водяного знака |

**Returns:**
java.lang.String - слепой водяной знак или null, если водяной знак не декодирован.
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


Закодировать текст в слепой водяной знак сетки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Сетка для кодирования слепого водяного знака |
| текст | java.lang.String | Текст для кодирования в сетку |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password)
```


Закодировать текст в слепой водяной знак сетки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Сетка для кодирования слепого водяного знака |
| текст | java.lang.String | Текст для кодирования в сетку |
| пароль | java.lang.String | Пароль для защиты водяного знака, необязательно |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password, boolean permanent) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password, boolean permanent)
```


Закодировать текст в слепой водяной знак сетки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Сетка для кодирования слепого водяного знака |
| текст | java.lang.String | Текст для кодирования в сетку |
| пароль | java.lang.String | Пароль для защиты водяного знака, необязательно |
| постоянный | boolean | Постоянный водяной знак не будет перезаписан или удалён. |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
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

