---
title: "RenderState"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/renderstate/
---
## RenderState class

Состояние рендеринга для построения конвейера  Изменения, внесённые в состояние рендеринга, не повлияют на созданные экземпляры конвейера.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Конструктор RenderState |

 **Result:**



---


### getBlend{#getBlend}

| Имя | Описание |
| --- | --- |
| getBlend() | Включает или отключает смешивание фрагментов. |

 **Result:**



---


### setBlend{#setBlend}

| Имя | Описание |
| --- | --- |
| setBlend(value) | Включает или отключает смешивание фрагментов. |

 **Result:**



---


### getBlendColor{#getBlendColor}

| Имя | Описание |
| --- | --- |
| getBlendColor() | Получает или задаёт цвет смешивания, используемый в BlendFactor.CONSTANT_COLOR |

 **Result:**



---


### setBlendColor{#setBlendColor}

| Имя | Описание |
| --- | --- |
| setBlendColor(value) | Получает или задаёт цвет смешивания, используемый в BlendFactor.CONSTANT_COLOR |

 **Result:**



---


### getSourceBlendFactor{#getSourceBlendFactor}

| Имя | Описание |
| --- | --- |
| getSourceBlendFactor() | Получает или задаёт способ смешивания цвета. Значение свойства — целочисленная константа BlendFactor. |

 **Result:**



---


### setSourceBlendFactor{#setSourceBlendFactor}

| Имя | Описание |
| --- | --- |
| setSourceBlendFactor(value) | Получает или задаёт способ смешивания цвета. Значение свойства — целочисленная константа BlendFactor. |

 **Result:**



---


### getDestinationBlendFactor{#getDestinationBlendFactor}

| Имя | Описание |
| --- | --- |
| getDestinationBlendFactor() | Получает или задаёт способ смешивания цвета. Значение свойства — целочисленная константа BlendFactor. |

 **Result:**



---


### setDestinationBlendFactor{#setDestinationBlendFactor}

| Имя | Описание |
| --- | --- |
| setDestinationBlendFactor(value) | Получает или задаёт способ смешивания цвета. Значение свойства — целочисленная константа BlendFactor. |

 **Result:**



---


### getCullFace{#getCullFace}

| Имя | Описание |
| --- | --- |
| getCullFace() | Включает или отключает отбрасывание граней |

 **Result:**



---


### setCullFace{#setCullFace}

| Имя | Описание |
| --- | --- |
| setCullFace(value) | Включает или отключает отбрасывание граней |

 **Result:**



---


### getCullFaceMode{#getCullFaceMode}

| Имя | Описание |
| --- | --- |
| getCullFaceMode() | Получает или задает, какая грань будет отбрасываться. Значение свойства — целочисленная константа CullFaceMode. |

 **Result:**



---


### setCullFaceMode{#setCullFaceMode}

| Имя | Описание |
| --- | --- |
| setCullFaceMode(value) | Получает или задает, какая грань будет отбрасываться. Значение свойства — целочисленная константа CullFaceMode. |

 **Result:**



---


### getFrontFace{#getFrontFace}

| Имя | Описание |
| --- | --- |
| getFrontFace() | Получает или задает, какой порядок считается передней гранью. Значение свойства — целочисленная константа FrontFace. |

 **Result:**



---


### setFrontFace{#setFrontFace}

| Имя | Описание |
| --- | --- |
| setFrontFace(value) | Получает или задает, какой порядок считается передней гранью. Значение свойства — целочисленная константа FrontFace. |

 **Result:**



---


### getDepthTest{#getDepthTest}

| Имя | Описание |
| --- | --- |
| getDepthTest() | Включает или отключает тест глубины. |

 **Result:**



---


### setDepthTest{#setDepthTest}

| Имя | Описание |
| --- | --- |
| setDepthTest(value) | Включает или отключает тест глубины. |

 **Result:**



---


### getDepthMask{#getDepthMask}

| Имя | Описание |
| --- | --- |
| getDepthMask() | Включает или отключает запись глубины. |

 **Result:**



---


### setDepthMask{#setDepthMask}

| Имя | Описание |
| --- | --- |
| setDepthMask(value) | Включает или отключает запись глубины. |

 **Result:**



---


### getDepthFunction{#getDepthFunction}

| Имя | Описание |
| --- | --- |
| getDepthFunction() | Получает или задает функцию сравнения, используемую в тесте глубины. Значение свойства — целочисленная константа CompareFunction. |

 **Result:**



---


### setDepthFunction{#setDepthFunction}

| Имя | Описание |
| --- | --- |
| setDepthFunction(value) | Получает или задает функцию сравнения, используемую в тесте глубины. Значение свойства — целочисленная константа CompareFunction. |

 **Result:**



---


### getStencilTest{#getStencilTest}

| Имя | Описание |
| --- | --- |
| getStencilTest() | Включает или отключает тест трафарета. |

 **Result:**



---


### setStencilTest{#setStencilTest}

| Имя | Описание |
| --- | --- |
| setStencilTest(value) | Включает или отключает тест трафарета. |

 **Result:**



---


### getStencilReference{#getStencilReference}

| Имя | Описание |
| --- | --- |
| getStencilReference() | Получает или задает опорное значение для теста трафарета. |

 **Result:**



---


### setStencilReference{#setStencilReference}

| Имя | Описание |
| --- | --- |
| setStencilReference(value) | Получает или задает опорное значение для теста трафарета. |

 **Result:**



---


### getStencilMask{#getStencilMask}

| Имя | Описание |
| --- | --- |
| getStencilMask() | Получает или задает маску, которая И‑логически объединяется как с опорным, так и с сохранённым значением трафарета при выполнении теста. |

 **Result:**



---


### getStencilFrontFace{#getStencilFrontFace}

| Имя | Описание |
| --- | --- |
| getStencilFrontFace() | Получает состояние трафарета для передней грани. |

 **Result:**



---


### getStencilBackFace{#getStencilBackFace}

| Имя | Описание |
| --- | --- |
| getStencilBackFace() | Получает состояние трафарета для обратной стороны. |

 **Result:**



---


### getScissorTest{#getScissorTest}

| Имя | Описание |
| --- | --- |
| getScissorTest() | Включить или отключить тест обрезки |

 **Result:**



---


### setScissorTest{#setScissorTest}

| Имя | Описание |
| --- | --- |
| setScissorTest(value) | Включить или отключить тест обрезки |

 **Result:**



---


### getPolygonMode{#getPolygonMode}

| Имя | Описание |
| --- | --- |
| getPolygonMode() | Получает или задает режим рендеринга полигона. Значение свойства — целочисленная константа PolygonMode. |

 **Result:**



---


### setPolygonMode{#setPolygonMode}

| Имя | Описание |
| --- | --- |
| setPolygonMode(value) | Получает или задает режим рендеринга полигона. Значение свойства — целочисленная константа PolygonMode. |

 **Result:**



---


### equals{#equals}

| Имя | Описание |
| --- | --- |
| equals(obj) | Возвращает значение, указывающее, равен ли данный экземпляр указанному объекту. |

 **Result:**



---


### hashCode{#hashCode}

| Имя | Описание |
| --- | --- |
| hashCode() | Возвращает хеш‑код для данного экземпляра. |

 **Result:**



---


### compareTo{#compareTo}

| Имя | Описание |
| --- | --- |
| compareTo(other) | Сравнить состояние рендеринга с другим экземпляром |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| othe | RenderState | null |

 **Result:**
Number


---



