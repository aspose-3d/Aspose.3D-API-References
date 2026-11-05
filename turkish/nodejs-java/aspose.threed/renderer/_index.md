---
title: "Renderer"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/renderer/
---
## Renderer class

Renderlayıcı hakkında bağlam.  @hideconstructor


## Yöntemler

### getShaderSet{#getShaderSet}

| Ad | Açıklama |
| --- | --- |
| getShaderSet() | Sahneyi renderlamak için kullanılan shader setini alır veya ayarlar |

 **Result:**



---


### setShaderSet{#setShaderSet}

| Ad | Açıklama |
| --- | --- |
| setShaderSet(value) | Sahneyi renderlamak için kullanılan shader setini alır veya ayarlar |

 **Result:**



---


### getVariables{#getVariables}

| Ad | Açıklama |
| --- | --- |
| getVariables() | Renderlama için kullanılan dahili değişkenlere erişim |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| Ad | Açıklama |
| --- | --- |
| getPresetShaders() | Ön ayarlı shader setini alır veya ayarlar. Özelliğin değeri PresetShaders tam sayı sabitidir. |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| Ad | Açıklama |
| --- | --- |
| setPresetShaders(value) | Ön ayarlı shader setini alır veya ayarlar. Özelliğin değeri PresetShaders tam sayı sabitidir. |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| Ad | Açıklama |
| --- | --- |
| getRenderFactory() | Render ile ilgili nesneleri oluşturmak için fabrikayı alır. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Ad | Açıklama |
| --- | --- |
| getAssetDirectories() | Harici varlıkların saklandığı dizinler |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| Ad | Açıklama |
| --- | --- |
| getPostProcessings() | Aktif post‑işleme zinciri |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Ad | Açıklama |
| --- | --- |
| getEnableShadows() | Gölge etkinleştirme durumunu alır veya ayarlar. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Ad | Açıklama |
| --- | --- |
| setEnableShadows(value) | Gölge etkinleştirme durumunu alır veya ayarlar. |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| Ad | Açıklama |
| --- | --- |
| getRenderTarget() | Aşağıdaki render işlemlerinin gerçekleştirileceği render hedefini belirtin. |

 **Result:**



---


### getNode{#getNode}

| Ad | Açıklama |
| --- | --- |
| getNode() | Dünya dönüşüm matrisini sağlamak için kullanılan Node örneğini alır veya ayarlar. |

 **Result:**



---


### setNode{#setNode}

| Ad | Açıklama |
| --- | --- |
| setNode(value) | Dünya dönüşüm matrisini sağlamak için kullanılan Node örneğini alır veya ayarlar. |

 **Result:**



---


### getFrustum{#getFrustum}

| Ad | Açıklama |
| --- | --- |
| getFrustum() | Görünüm matrisini sağlamak için kullanılan frustum'u alır veya ayarlar. |

 **Result:**



---


### setFrustum{#setFrustum}

| Ad | Açıklama |
| --- | --- |
| setFrustum(value) | Görünüm matrisini sağlamak için kullanılan frustum'u alır veya ayarlar. |

 **Result:**



---


### getRenderStage{#getRenderStage}

| Ad | Açıklama |
| --- | --- |
| getRenderStage() | Mevcut render aşamasını alır. Özelliğin değeri RenderStage tam sayı sabitidir. |

 **Result:**



---


### getMaterial{#getMaterial}

| Ad | Açıklama |
| --- | --- |
| getMaterial() | Gölgelendiriciler tarafından kullanılan malzeme bilgilerini sağlamak için kullanılan malzemeyi alır veya ayarlar. |

 **Result:**



---


### setMaterial{#setMaterial}

| Ad | Açıklama |
| --- | --- |
| setMaterial(value) | Gölgelendiriciler tarafından kullanılan malzeme bilgilerini sağlamak için kullanılan malzemeyi alır veya ayarlar. |

 **Result:**



---


### getShader{#getShader}

| Ad | Açıklama |
| --- | --- |
| getShader() | Geometriyi renderlemek için kullanılan gölgelendirici örneğini alır veya ayarlar. |

 **Result:**



---


### setShader{#setShader}

| Ad | Açıklama |
| --- | --- |
| setShader(value) | Geometriyi renderlemek için kullanılan gölgelendirici örneğini alır veya ayarlar. |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| Ad | Açıklama |
| --- | --- |
| getFallbackEntityRenderer() | Varlık için özel bir renderlayıcı tanımlı olmadığında yedek varlık renderlayıcısını alır veya ayarlar. |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| Ad | Açıklama |
| --- | --- |
| setFallbackEntityRenderer(value) | Varlık için özel bir renderlayıcı tanımlı olmadığında yedek varlık renderlayıcısını alır veya ayarlar. |

 **Result:**



---


### clearCache{#clearCache}

| Ad | Açıklama |
| --- | --- |
| clearCache() | Önbelleği manuel olarak temizleyin. Aspose.3D, malzemeler/geometriler gibi bazı nesneleri render boru hattıyla uyumlu iç tiplerde önbelleğe alır. Sahne büyük değişiklikler geçirdiğinde bu manuel olarak çağrılmalıdır. |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| Ad | Açıklama |
| --- | --- |
| getPostProcessing(name) | Render tarafından desteklenen yerleşik bir post-işlemci alır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| nam | String | null |

 **Result:**
PostProcessing


---


### execute{#execute}

| Ad | Açıklama |
| --- | --- |
| execute(postProcessing, result) | Belirtilen render hedefi üzerinde bir post-işlem yürütür. |

 **Result:**
PostProcessing


---


### createRenderer{#createRenderer}

| Ad | Açıklama |
| --- | --- |
| createRenderer() | Varsayılan profil ile yeni bir Renderer oluşturur. |

 **Result:**
Renderer


---


### registerEntityRenderer{#registerEntityRenderer}

| Ad | Açıklama |
| --- | --- |
| registerEntityRenderer(renderer) | Belirtilen varlık için varlık renderleyicisini kaydeder. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
Renderer


---


### render{#render}

| Ad | Açıklama |
| --- | --- |
| render(renderTarget) | Belirtilen hedefi renderlar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
Renderer


---



