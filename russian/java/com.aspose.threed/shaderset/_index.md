---
title: ShaderSet
second_title: Справочник API Aspose.3D для Java
description: Шейдерные программы для каждого типа материалов
type: docs
weight: 166
url: /ru/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

Шейдерные программы для каждого типа материалов
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | Создайте экземпляр [ShaderSet](../../com.aspose.threed/shaderset) |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Освободите этот экземпляр и освободите все программы шейдеров. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Получает резервный шейдер, когда требуемый шейдер недоступен |
| [getLambert()](#getLambert--) | Получает шейдер, используемый для рендеринга ламбертового материала |
| [getPbr()](#getPbr--) | Получает шейдер, используемый для рендеринга PBR-материала |
| [getPhong()](#getPhong--) | Получает шейдер, используемый для рендеринга Phong-материала |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | Устанавливает резервный шейдер, когда требуемый шейдер недоступен |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | Устанавливает шейдер, используемый для рендеринга ламбертового материала |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | Устанавливает шейдер, используемый для рендеринга PBR-материала |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | Устанавливает шейдер, используемый для рендеринга Phong-материала |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


Создайте экземпляр [ShaderSet](../../com.aspose.threed/shaderset)

### close() {#close--}
```
public void close()
```


Освободите этот экземпляр и освободите все программы шейдеров.

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
### getFallback() {#getFallback--}
```
public ShaderProgram getFallback()
```


Получает резервный шейдер, когда требуемый шейдер недоступен

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


Получает шейдер, используемый для рендеринга ламбертового материала

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


Получает шейдер, используемый для рендеринга PBR-материала

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


Получает шейдер, используемый для рендеринга Phong-материала

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


Устанавливает резервный шейдер, когда требуемый шейдер недоступен

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Новое значение |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


Устанавливает шейдер, используемый для рендеринга ламбертового материала

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Новое значение |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


Устанавливает шейдер, используемый для рендеринга PBR-материала

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Новое значение |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


Устанавливает шейдер, используемый для рендеринга Phong-материала

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Новое значение |

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

