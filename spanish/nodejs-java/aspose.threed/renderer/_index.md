---
title: "Renderizador"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/renderer/
---
## Renderer class

El contexto sobre el renderizador.  @hideconstructor


## Métodos

### getShaderSet{#getShaderSet}

| Nombre | Descripción |
| --- | --- |
| getShaderSet() | Obtiene o establece el conjunto de shaders que se usa para renderizar la escena |

 **Result:**



---


### setShaderSet{#setShaderSet}

| Nombre | Descripción |
| --- | --- |
| setShaderSet(value) | Obtiene o establece el conjunto de shaders que se usa para renderizar la escena |

 **Result:**



---


### getVariables{#getVariables}

| Nombre | Descripción |
| --- | --- |
| getVariables() | Acceso a las variables internas usadas para el renderizado |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| Nombre | Descripción |
| --- | --- |
| getPresetShaders() | Obtiene o establece el conjunto de shaders predefinido. El valor de la propiedad es la constante entera PresetShaders. |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| Nombre | Descripción |
| --- | --- |
| setPresetShaders(value) | Obtiene o establece el conjunto de shaders predefinido. El valor de la propiedad es la constante entera PresetShaders. |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| Nombre | Descripción |
| --- | --- |
| getRenderFactory() | Obtiene la fábrica para crear objetos relacionados con el renderizado. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Nombre | Descripción |
| --- | --- |
| getAssetDirectories() | Directorios que almacenan recursos externos |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| Nombre | Descripción |
| --- | --- |
| getPostProcessings() | Cadena de post-procesamiento activa |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Nombre | Descripción |
| --- | --- |
| getEnableShadows() | Obtiene o establece si se habilitan las sombras. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Nombre | Descripción |
| --- | --- |
| setEnableShadows(value) | Obtiene o establece si se habilitan las sombras. |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| Nombre | Descripción |
| --- | --- |
| getRenderTarget() | Especifique el objetivo de renderizado en el que se realizarán las siguientes operaciones de renderizado. |

 **Result:**



---


### getNode{#getNode}

| Nombre | Descripción |
| --- | --- |
| getNode() | Obtiene o establece la instancia Node utilizada para proporcionar la matriz de transformación mundial. |

 **Result:**



---


### setNode{#setNode}

| Nombre | Descripción |
| --- | --- |
| setNode(value) | Obtiene o establece la instancia Node utilizada para proporcionar la matriz de transformación mundial. |

 **Result:**



---


### getFrustum{#getFrustum}

| Nombre | Descripción |
| --- | --- |
| getFrustum() | Obtiene o establece el frustum que se usa para proporcionar la matriz de vista. |

 **Result:**



---


### setFrustum{#setFrustum}

| Nombre | Descripción |
| --- | --- |
| setFrustum(value) | Obtiene o establece el frustum que se usa para proporcionar la matriz de vista. |

 **Result:**



---


### getRenderStage{#getRenderStage}

| Nombre | Descripción |
| --- | --- |
| getRenderStage() | Obtiene la etapa de renderizado actual. El valor de la propiedad es la constante entera RenderStage. |

 **Result:**



---


### getMaterial{#getMaterial}

| Nombre | Descripción |
| --- | --- |
| getMaterial() | Obtiene o establece el material que se usa para proporcionar la información del material utilizada por los shaders. |

 **Result:**



---


### setMaterial{#setMaterial}

| Nombre | Descripción |
| --- | --- |
| setMaterial(value) | Obtiene o establece el material que se usa para proporcionar la información del material utilizada por los shaders. |

 **Result:**



---


### getShader{#getShader}

| Nombre | Descripción |
| --- | --- |
| getShader() | Obtiene o establece la instancia del shader utilizada para renderizar la geometría. |

 **Result:**



---


### setShader{#setShader}

| Nombre | Descripción |
| --- | --- |
| setShader(value) | Obtiene o establece la instancia del shader utilizada para renderizar la geometría. |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| Nombre | Descripción |
| --- | --- |
| getFallbackEntityRenderer() | Obtiene o establece el renderizador de entidad de respaldo cuando la entidad no tiene un renderizador especial definido. |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| Nombre | Descripción |
| --- | --- |
| setFallbackEntityRenderer(value) | Obtiene o establece el renderizador de entidad de respaldo cuando la entidad no tiene un renderizador especial definido. |

 **Result:**



---


### clearCache{#clearCache}

| Nombre | Descripción |
| --- | --- |
| clearCache() | Borre manualmente la caché. Aspose.3D almacenará en caché algunos objetos como materiales/geometrías en tipos internos compatibles con la canalización de renderizado. Esto debe llamarse manualmente cuando la escena tenga cambios importantes. |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| Nombre | Descripción |
| --- | --- |
| getPostProcessing(name) | Obtiene un postprocesador incorporado que es compatible con el renderizador. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| nam | Cadena | null |

 **Result:**
PostProcessing


---


### execute{#execute}

| Nombre | Descripción |
| --- | --- |
| execute(postProcessing, result) | Ejecute un postprocesamiento en el objetivo de renderizado especificado |

 **Result:**
PostProcessing


---


### createRenderer{#createRenderer}

| Nombre | Descripción |
| --- | --- |
| createRenderer() | Crea un nuevo Renderer con el perfil predeterminado. |

 **Result:**
Renderizador


---


### registerEntityRenderer{#registerEntityRenderer}

| Nombre | Descripción |
| --- | --- |
| registerEntityRenderer(renderer) | Registra el renderizador de entidad para la entidad especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
Renderizador


---


### render{#render}

| Nombre | Descripción |
| --- | --- |
| render(renderTarget) | Renderiza el objetivo especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
Renderizador


---



