---
title: RenderFactory
second_title: Справочник API Aspose.3D для Java
description: RenderFactory создает все ресурсы, представленные в конвейере рендеринга.
type: docs
weight: 148
url: /ru/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactory создает все ресурсы, представленные в конвейере рендеринга.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Создать цель рендеринга, содержащую 1 кубическую текстуру |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | Создать набор дескрипторов для указанной программы шейдера. |
| [createIndexBuffer()](#createIndexBuffer--) | Создать экземпляр [IIndexBuffer](../../com.aspose.threed/iindexbuffer) для хранения информации о гранях полигона. |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | Создать предварительно настроенный графический конвейер с предустановленными шейдером/состоянием рендеринга/объявлением вершин и операциями отрисовки. |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Создать цель рендеринга, содержащую 1 цель, которая выводит в текстуру |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | Создать цель рендеринга, выводящую в текстуру |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | Создать цель рендеринга, выводящую в нативное окно. |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | Создать объект [ShaderProgram](../../com.aspose.threed/shaderprogram) |
| [createTextureUnit()](#createTextureUnit--) | Создать 2D‑юнит текстуры, доступный шейдеру. |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | Создать юнит текстуры, доступный шейдеру. |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | Создать новый униформ‑буфер на стороне GPU с предварительно выделенным размером. |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | Создать экземпляр [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) для хранения информации о вершинах полигона. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderFactory() {#RenderFactory--}
```
public RenderFactory()
```


### createCubeRenderTexture(RenderParameters parameters, int width, int height) {#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createCubeRenderTexture(RenderParameters parameters, int width, int height)
```


Создать цель рендеринга, содержащую 1 кубическую текстуру

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Параметры рендеринга для создания текстуры рендеринга |
| ширина | int | Ширина текстуры рендеринга |
| высота | int | Высота текстуры рендеринга |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


Создать набор дескрипторов для указанной программы шейдера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Шейдерная программа |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


Создать экземпляр [IIndexBuffer](../../com.aspose.threed/iindexbuffer) для хранения информации о гранях полигона.

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


Создать предварительно настроенный графический конвейер с предустановленными шейдером/состоянием рендеринга/объявлением вершин и операциями отрисовки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Шейдер, используемый при рендеринге |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | Состояние рендеринга, используемое при рендеринге |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Объявление вершин входных данных вершин |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | Операция отрисовки |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


Создать цель рендеринга, содержащую 1 цель, которая выводит в текстуру

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Параметры рендеринга для создания текстуры рендеринга |
| ширина | int | Ширина текстуры рендеринга |
| высота | int | Высота текстуры рендеринга |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


Создать цель рендеринга, выводящую в текстуру

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Параметры рендеринга для создания текстуры рендеринга |
| цели | int | Сколько цветовых выходных целей |
| ширина | int | Ширина текстуры рендеринга |
| высота | int | Высота текстуры рендеринга |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


Создать цель рендеринга, выводящую в нативное окно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Параметры рендеринга для создания окна рендеринга |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | Дескриптор окна для рендеринга |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


Создать объект [ShaderProgram](../../com.aspose.threed/shaderprogram)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | Исходный код шейдера |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


Создать 2D‑юнит текстуры, доступный шейдеру.

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


Создать юнит текстуры, доступный шейдеру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | Тип текстуры |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


Создать новый униформ‑буфер на стороне GPU с предварительно выделенным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| размер | int | Размер униформного буфера |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


Создать экземпляр [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) для хранения информации о вершинах полигона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
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

