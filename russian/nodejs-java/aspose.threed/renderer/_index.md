---
title: "Renderer"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/renderer/
---
## Renderer class

Контекст о рендерере.  @hideconstructor


## Методы

### getShaderSet{#getShaderSet}

| Имя | Описание |
| --- | --- |
| getShaderSet() | Получает или задает набор шейдеров, используемый для рендеринга сцены. |

 **Result:**



---


### setShaderSet{#setShaderSet}

| Имя | Описание |
| --- | --- |
| setShaderSet(value) | Получает или задает набор шейдеров, используемый для рендеринга сцены. |

 **Result:**



---


### getVariables{#getVariables}

| Имя | Описание |
| --- | --- |
| getVariables() | Доступ к внутренним переменным, используемым для рендеринга. |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| Имя | Описание |
| --- | --- |
| getPresetShaders() | Получает или задает набор предустановленных шейдеров. Значение свойства — целочисленная константа PresetShaders. |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| Имя | Описание |
| --- | --- |
| setPresetShaders(value) | Получает или задает набор предустановленных шейдеров. Значение свойства — целочисленная константа PresetShaders. |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| Имя | Описание |
| --- | --- |
| getRenderFactory() | Получает фабрику для создания объектов, связанных с рендерингом. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Имя | Описание |
| --- | --- |
| getAssetDirectories() | Каталоги, в которых хранятся внешние ресурсы. |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| Имя | Описание |
| --- | --- |
| getPostProcessings() | Активная цепочка постобработки. |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Имя | Описание |
| --- | --- |
| getEnableShadows() | Получает или задает, включены ли тени. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Имя | Описание |
| --- | --- |
| setEnableShadows(value) | Получает или задает, включены ли тени. |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| Имя | Описание |
| --- | --- |
| getRenderTarget() | Укажите целевой объект рендеринга, на котором будут выполняться последующие операции рендеринга. |

 **Result:**



---


### getNode{#getNode}

| Имя | Описание |
| --- | --- |
| getNode() | Получает или задает экземпляр Node, используемый для предоставления матрицы мирового преобразования. |

 **Result:**



---


### setNode{#setNode}

| Имя | Описание |
| --- | --- |
| setNode(value) | Получает или задает экземпляр Node, используемый для предоставления матрицы мирового преобразования. |

 **Result:**



---


### getFrustum{#getFrustum}

| Имя | Описание |
| --- | --- |
| getFrustum() | Получает или задает фрустум, используемый для предоставления матрицы вида. |

 **Result:**



---


### setFrustum{#setFrustum}

| Имя | Описание |
| --- | --- |
| setFrustum(value) | Получает или задает фрустум, используемый для предоставления матрицы вида. |

 **Result:**



---


### getRenderStage{#getRenderStage}

| Имя | Описание |
| --- | --- |
| getRenderStage() | Получает текущий этап рендеринга. Значение свойства — целочисленная константа RenderStage. |

 **Result:**



---


### getMaterial{#getMaterial}

| Имя | Описание |
| --- | --- |
| getMaterial() | Получает или задает материал, используемый для предоставления информации о материале, используемой шейдерами. |

 **Result:**



---


### setMaterial{#setMaterial}

| Имя | Описание |
| --- | --- |
| setMaterial(value) | Получает или задает материал, используемый для предоставления информации о материале, используемой шейдерами. |

 **Result:**



---


### getShader{#getShader}

| Имя | Описание |
| --- | --- |
| getShader() | Получает или задает экземпляр шейдера, используемый для рендеринга геометрии. |

 **Result:**



---


### setShader{#setShader}

| Имя | Описание |
| --- | --- |
| setShader(value) | Получает или задает экземпляр шейдера, используемый для рендеринга геометрии. |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| Имя | Описание |
| --- | --- |
| getFallbackEntityRenderer() | Получает или задает резервный рендерер сущностей, когда у сущности не определён специальный рендерер. |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| Имя | Описание |
| --- | --- |
| setFallbackEntityRenderer(value) | Получает или задает резервный рендерер сущностей, когда у сущности не определён специальный рендерер. |

 **Result:**



---


### clearCache{#clearCache}

| Имя | Описание |
| --- | --- |
| clearCache() | Вручную очищает кэш. Aspose.3D кэширует некоторые объекты, такие как материалы/геометрии, во внутренние типы, совместимые с конвейером рендеринга. Это следует вызывать вручную, когда сцена претерпевает значительные изменения. |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| Имя | Описание |
| --- | --- |
| getPostProcessing(name) | Получает встроенный постпроцессор, поддерживаемый рендерером. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| nam | String | null |

 **Result:**
PostProcessing


---


### execute{#execute}

| Имя | Описание |
| --- | --- |
| execute(postProcessing, result) | Выполняет постобработку на указанном целевом объекте рендеринга. |

 **Result:**
PostProcessing


---


### createRenderer{#createRenderer}

| Имя | Описание |
| --- | --- |
| createRenderer() | Создает новый Renderer с профилем по умолчанию. |

 **Result:**
Renderer


---


### registerEntityRenderer{#registerEntityRenderer}

| Имя | Описание |
| --- | --- |
| registerEntityRenderer(renderer) | Зарегистрировать рендерер сущности для указанной сущности |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
Renderer


---


### render{#render}

| Имя | Описание |
| --- | --- |
| render(renderTarget) | Отобразить указанную цель |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
Renderer


---



