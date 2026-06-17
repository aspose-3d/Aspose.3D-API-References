---
title: "Renderlayıcı"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/renderer/
---
## Renderer class

Renderleyiciyle ilgili bağlam.  @hideconstructor


## Yöntemler

### getShaderSet{#getShaderSet}

| Ad | Açıklama |
| --- | --- |
| getShaderSet() | Sahneyi renderlamak için kullanılan gölgelendirici setini alır veya ayarlar. |

 **Result:**



---


### setShaderSet{#setShaderSet}

| Ad | Açıklama |
| --- | --- |
| setShaderSet(value) | Sahneyi renderlamak için kullanılan gölgelendirici setini alır veya ayarlar. |

 **Result:**



---


### getVariables{#getVariables}

| Ad | Açıklama |
| --- | --- |
| getVariables() | Renderlama için kullanılan iç değişkenlere erişim |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| Ad | Açıklama |
| --- | --- |
| getPresetShaders() | Önceden ayarlanmış gölgelendirici setini alır veya ayarlar. Özelliğin değeri PresetShaders tam sayı sabitidir. |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| Ad | Açıklama |
| --- | --- |
| setPresetShaders(value) | Önceden ayarlanmış gölgelendirici setini alır veya ayarlar. Özelliğin değeri PresetShaders tam sayı sabitidir. |

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
| getAssetDirectories() | Harici varlıkların depolandığı dizinler |

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
| getMaterial() | Shader'lar tarafından kullanılan malzeme bilgilerini sağlamak için kullanılan materyali alır veya ayarlar. |

 **Result:**



---


### setMaterial{#setMaterial}

| Ad | Açıklama |
| --- | --- |
| setMaterial(value) | Shader'lar tarafından kullanılan malzeme bilgilerini sağlamak için kullanılan materyali alır veya ayarlar. |

 **Result:**



---


### getShader{#getShader}

| Ad | Açıklama |
| --- | --- |
| getShader() | Geometriyi renderlemek için kullanılan shader örneğini alır veya ayarlar. |

 **Result:**



---


### setShader{#setShader}

| Ad | Açıklama |
| --- | --- |
| setShader(value) | Geometriyi renderlemek için kullanılan shader örneğini alır veya ayarlar. |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| Ad | Açıklama |
| --- | --- |
| getFallbackEntityRenderer() | Varlığın özel bir renderer tanımlı olmadığı durumlarda yedek varlık renderer'ını alır veya ayarlar. |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| Ad | Açıklama |
| --- | --- |
| setFallbackEntityRenderer(value) | Varlığın özel bir renderer tanımlı olmadığı durumlarda yedek varlık renderer'ını alır veya ayarlar. |

 **Result:**



---


### clearCache{#clearCache}

| Ad | Açıklama |
| --- | --- |
| clearCache() | Manuel olarak önbelleği temizleyin. Aspose.3D, malzemeler/geometriler gibi bazı nesneleri render boru hattıyla uyumlu iç tiplerde önbelleğe alır. Bu, sahne büyük değişiklikler geçirdiğinde manuel olarak çağrılmalıdır. |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| Ad | Açıklama |
| --- | --- |
| getPostProcessing(name) | Renderer tarafından desteklenen yerleşik bir post-işlemci alır. |

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
| execute(postProcessing, result) | Belirtilen render hedefinde bir post işlem yürüt. |

 **Result:**
PostProcessing


---


### createRenderer{#createRenderer}

| Ad | Açıklama |
| --- | --- |
| createRenderer() | Varsayılan profil ile yeni bir Renderer oluşturur. |

 **Result:**
Renderlayıcı


---


### registerEntityRenderer{#registerEntityRenderer}

| Ad | Açıklama |
| --- | --- |
| registerEntityRenderer(renderer) | Belirtilen varlık için entity renderer'ı kaydet |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
Renderlayıcı


---


### render{#render}

| Ad | Açıklama |
| --- | --- |
| render(renderTarget) | Belirtilen hedefi render et |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
Renderlayıcı


---



