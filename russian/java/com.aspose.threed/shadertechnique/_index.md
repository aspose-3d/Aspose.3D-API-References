---
title: ShaderTechnique
second_title: Справочник API Aspose.3D для Java
description: Шейдерная техника представляет конкретную реализацию рендеринга.
type: docs
weight: 169
url: /ru/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

Шейдерная техника представляет конкретную реализацию рендеринга.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | Инициализирует новый экземпляр класса [ShaderTechnique](../../com.aspose.threed/shadertechnique). |
## Методы

| Метод | Описание |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | Привязывает динамическое свойство к параметру шейдера |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Получает описание этой техники |
| [getRenderAPI()](#getRenderAPI--) | Получает API рендеринга, используемый этой техникой |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | Получает версию API рендеринга. |
| [getShaderContent()](#getShaderContent--) | Получает содержимое встроенного скрипта шейдера. |
| [getShaderEntry()](#getShaderEntry--) | Получает точку входа шейдера, некоторые шейдеры, такие как HLSL, могут иметь пользовательские точки входа. |
| [getShaderFile()](#getShaderFile--) | Получает имя файла внешнего шейдерного файла. |
| [getShaderLanguage()](#getShaderLanguage--) | Получает язык шейдера, используемый этой техникой. |
| [getShaderParameters()](#getShaderParameters--) | Получает определение параметра шейдера. |
| [getShaderVersion()](#getShaderVersion--) | Получает версию шейдера, используемую этой техникой. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Устанавливает описание этой техники |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | Устанавливает API рендеринга, используемое этой техникой |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | Устанавливает версию API рендеринга. |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | Устанавливает содержимое встроенного скрипта шейдера. |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | Устанавливает точку входа шейдера, некоторые шейдеры, такие как HLSL, могут иметь пользовательские точки входа. |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | Устанавливает имя файла внешнего шейдера. |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | Устанавливает язык шейдера, используемый этой техникой. |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | Устанавливает версию шейдера, используемую этой техникой. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


Инициализирует новый экземпляр класса [ShaderTechnique](../../com.aspose.threed/shadertechnique).

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


Привязывает динамическое свойство к параметру шейдера

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя динамического свойства. |
| shaderParameter | java.lang.String | Имя параметра шейдера. |

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
### getDescription() {#getDescription--}
```
public String getDescription()
```


Получает описание этой техники

**Returns:**
java.lang.String - описание этой техники
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


Получает API рендеринга, используемый этой техникой

**Returns:**
java.lang.String - API рендеринга, используемое этой техникой
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


Получает версию API рендеринга.

**Returns:**
java.lang.String - версия API рендеринга.
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


Получает содержимое встроенного скрипта шейдера. Это может быть исходный файл шейдера HLSL/GLSL.

**Returns:**
byte[] - содержимое встроенного скрипта шейдера. Это может быть исходный файл шейдера HLSL/GLSL.
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


Получает точку входа шейдера, некоторые шейдеры, такие как HLSL, могут иметь пользовательские точки входа.

**Returns:**
java.lang.String - точка входа шейдера, некоторые шейдеры, такие как HLSL, могут иметь пользовательские точки входа.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


Получает имя файла внешнего шейдерного файла.

**Returns:**
java.lang.String - имя файла внешнего шейдера.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


Получает язык шейдера, используемый этой техникой.

**Returns:**
java.lang.String - язык шейдера, используемый этой техникой.
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


Получает определение параметра шейдера. Ключом является имя динамического свойства, а значением — имя параметра шейдера, к которому свойство подключено.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - определение параметра шейдера. Ключом является имя динамического свойства, а значением — имя параметра шейдера, к которому свойство подключено.
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


Получает версию шейдера, используемую этой техникой.

**Returns:**
java.lang.String - версия шейдера, используемая этой техникой.
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




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Устанавливает описание этой техники

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


Устанавливает API рендеринга, используемое этой техникой

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


Устанавливает версию API рендеринга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


Устанавливает содержимое встроенного скрипта шейдера. Это может быть исходный файл шейдера HLSL/GLSL.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] | Новое значение |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


Устанавливает точку входа шейдера, некоторые шейдеры, такие как HLSL, могут иметь пользовательские точки входа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


Устанавливает имя файла внешнего шейдера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


Устанавливает язык шейдера, используемый этой техникой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


Устанавливает версию шейдера, используемую этой техникой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

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

