---
title: "RenderFactory"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory создаёт все ресурсы, представленные в конвейере рендеринга.  @hideconstructor


## Методы

### createRenderTexture{#createRenderTexture}

| Имя | Описание |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | Создать цель рендеринга, которая рендерит в текстуру |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| параметры | RenderParameters | Параметры рендеринга для создания текстуры рендеринга |
| цели | Number | Сколько цветовых целей вывода |
| ширина | Number | Ширина текстуры рендеринга |
| height | Number | Высота текстуры рендеринга |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Имя | Описание |
| --- | --- |
| createRenderTexture(parameters, width, height) | Создать цель рендеринга, содержащую 1 цель, которая рендерит в текстуру |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| параметры | RenderParameters | Параметры рендеринга для создания текстуры рендеринга |
| ширина | Number | Ширина текстуры рендеринга |
| height | Number | Высота текстуры рендеринга |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Имя | Описание |
| --- | --- |
| createDescriptorSet(shader) | Создать набор дескрипторов для указанной программы шейдера. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| шейдер | ShaderProgram | Программа шейдера |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Имя | Описание |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | Создать цель рендеринга, содержащую 1 кубическую текстуру |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| параметры | RenderParameters | Параметры рендеринга для создания текстуры рендеринга |
| ширина | Number | Ширина текстуры рендеринга |
| height | Number | Высота текстуры рендеринга |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Имя | Описание |
| --- | --- |
| createRenderWindow(parameters, handle) | Создать цель рендеринга, которая рендерит в нативное окно. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| параметры | RenderParameters | Параметры рендеринга для создания окна рендеринга |
| дескриптор | WindowHandle | Дескриптор окна для рендеринга |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| Имя | Описание |
| --- | --- |
| createVertexBuffer(declaration) | Создайте экземпляр com.aspose.threed.IVertexBuffer для хранения информации о вершинах многоугольника. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| Имя | Описание |
| --- | --- |
| createIndexBuffer() | Создайте экземпляр com.aspose.threed.IIndexBuffer для хранения информации о гранях многоугольника. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| Имя | Описание |
| --- | --- |
| createTextureUnit(textureType) | Создайте текстурный юнит, к которому может обращаться шейдер. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| Имя | Описание |
| --- | --- |
| createTextureUnit() | Создайте 2D текстурный юнит, к которому может обращаться шейдер. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| Имя | Описание |
| --- | --- |
| createShaderProgram(shaderSource) | Создайте объект ShaderProgram |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| shaderSource | ShaderSource | Исходный код шейдера |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| Имя | Описание |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Создайте предварительно настроенный графический конвейер с предварительно настроенными шейдером/состоянием рендеринга/объявлением вершин и операциями отрисовки. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| шейдер | ShaderProgram | Шейдер, используемый при рендеринге |
| renderState | RenderState | Состояние рендеринга, используемое при рендеринге |
| vertexDeclaration | VertexDeclaration | Объявление вершин входных данных |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Имя | Описание |
| --- | --- |
| createUniformBuffer(size) | Создайте новый униформный буфер на стороне GPU с предварительно выделенным размером. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| size | Number | Размер униформного буфера |

 **Result:**
IBuffer


---



