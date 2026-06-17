---
title: "Scene"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/scene/
---
## Scene class

Bir sahne, düğümleri, geometrileri, materyalleri, dokuları, animasyonu, pozları, alt sahneleri vb. içeren üst düzey bir nesnedir.  Sahne alt sahnelere sahip olabilir, collada/blender/fbx gibi dosyalarda çoklu belge desteği sağlar.  Düğüm hiyerarşisine RootNodeLibrary aracılığıyla erişilebilir; bu, serileştirme sırasında bağlanmamış nesnelerin (meta veri veya özel nesneler gibi) bir referansını tutmak için kullanılır, böylece bir kütüphane olarak kullanılabilir.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | Scene sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(entity) | Yeni bir düğüme eklenmiş varlıkla Scene sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| varlık | Varlık | Sahneye eklenen ilk varlık |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Ad | Açıklama |
| --- | --- |
| constructor_overload2(parentScene, name) | Scene sınıfının yeni bir örneğini alt sahne olarak başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| parentScene | Scene | Üst sahne. |
| name | String | Sahnenin adı. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Ad | Açıklama |
| --- | --- |
| constructor_overload3(fileName) | Scene sınıfının yeni bir örneğini başlatır ve dosyayı hemen açar. Bu, kullanımdan kaldırılmış bir yapıcıdır, lütfen #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken) kullanın. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Açılacak dosyanın adı. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| Ad | Açıklama |
| --- | --- |
| getSubScenes() | Tüm alt sahneleri alır |

 **Result:**



---


### getLibrary{#getLibrary}

| Ad | Açıklama |
| --- | --- |
| getLibrary() | Sahne hiyerarşisinde doğrudan kullanılmayan nesneler Library içinde tanımlanabilir. Bu, alt sahneler kullandığınızda ve yeniden kullanılabilir bileşenleri alt sahnelerin altına koyduğunuzda yararlıdır. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| Ad | Açıklama |
| --- | --- |
| getAnimationClips() | Sahnede tanımlanan tüm AnimationClip'leri alır. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| Ad | Açıklama |
| --- | --- |
| getCurrentAnimationClip() | Etkin AnimationClip'i alır veya ayarlar |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| Ad | Açıklama |
| --- | --- |
| setCurrentAnimationClip(value) | Etkin AnimationClip'i alır veya ayarlar |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Ad | Açıklama |
| --- | --- |
| getAssetInfo() | Üst düzey varlık bilgilerini alır veya ayarlar. Belge bilgisi. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Ad | Açıklama |
| --- | --- |
| setAssetInfo(value) | Üst düzey varlık bilgilerini alır veya ayarlar. Belge bilgisi. |

 **Result:**



---


### getPoses{#getPoses}

| Ad | Açıklama |
| --- | --- |
| getPoses() | Bu sahnede kullanılan tüm Pose'ları alır. Pose'lar. |

 **Result:**



---


### getRootNode{#getRootNode}

| Ad | Açıklama |
| --- | --- |
| getRootNode() | Sahnenin kök düğümünü alır. Kök düğüm. |

 **Result:**



---


### getScene{#getScene}

| Ad | Açıklama |
| --- | --- |
| getScene() | Bu nesnenin ait olduğu sahneyi alır. |

 **Result:**



---


### getName{#getName}

| Ad | Açıklama |
| --- | --- |
| getName() | Adı alır veya ayarlar. Ad. |

 **Result:**



---


### setName{#setName}

| Ad | Açıklama |
| --- | --- |
| setName(value) | Adı alır veya ayarlar. Ad. |

 **Result:**



---


### getProperties{#getProperties}

| Ad | Açıklama |
| --- | --- |
| getProperties() | Tüm özelliklerin koleksiyonunu alır. |

 **Result:**



---


### getAnimationClip{#getAnimationClip}

| Ad | Açıklama |
| --- | --- |
| getAnimationClip(name) | Adlandırılmış bir AnimationClip alır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Bu |

 **Result:**
AnimationClip


---


### clear{#clear}

| Ad | Açıklama |
| --- | --- |
| clear() | Sahne içeriğini temizler ve varsayılan ayarları geri yükler. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| Ad | Açıklama |
| --- | --- |
| createAnimationClip(name) | AnimationClip oluşturmak ve kaydetmek için bir kısayol işlevi. İlk AnimationClip, CurrentAnimationClip'e atanacaktır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Animasyon klibinin adı |

 **Result:**
AnimationClip


---


### open{#open}

| Ad | Açıklama |
| --- | --- |
| open(fileName, options) | Belirtilen dosya formatını kullanarak verilen yoldan sahneyi açar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Dosya adı. |
| seçenekler | LoadOptions | Akışı açmak için daha ayrıntılı yapılandırma. |

 **Result:**
AnimationClip


---


### open{#open}

| Ad | Açıklama |
| --- | --- |
| open(fileName) | Sahneyi verilen yoldan açar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Dosya adı. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| Ad | Açıklama |
| --- | --- |
| fromFile(fileName) | Sahneyi verilen yoldan açar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Dosya adı. |

 **Result:**
AnimationClip


---


### save{#save}

| Ad | Açıklama |
| --- | --- |
| save(fileName) | Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Dosya adı. |

 **Result:**
AnimationClip


---


### save{#save}

| Ad | Açıklama |
| --- | --- |
| save(fileName, format) | Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Dosya adı. |
| format | Dosya Biçimi | Format. |

 **Result:**
AnimationClip


---


### save{#save}

| Ad | Açıklama |
| --- | --- |
| save(fileName, options) | Belirtilen dosya formatını kullanarak sahneyi belirtilen yola kaydeder. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | Dosya adı. |
| seçenekler | SaveOptions | Akışı kaydetmek için daha ayrıntılı yapılandırma. |

 **Result:**
AnimationClip


---


### render{#render}

| Ad | Açıklama |
| --- | --- |
| render(camera, fileName) | Sahneyi verilen kameranın perspektifinden dış dosyaya renderlar. Varsayılan çıktı boyutu 1024x768 ve çıktı formatı png'dir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| kamera | Kamera | Sahneyi renderlamak için hangi kameranın perspektifinin kullanılacağı |
| fileName | String | Çıktı dosyasının dosya adı |

 **Result:**
AnimationClip


---


### render{#render}

| Ad | Açıklama |
| --- | --- |
| render(camera, fileName, size, format) | Sahneyi verilen kameranın perspektifinden dış dosyaya renderlar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| kamera | Kamera | Sahneyi renderlamak için hangi kameranın perspektifinin kullanılacağı |
| fileName | String | Çıktı dosyasının dosya adı |
| boyut | Vector2 | Son renderlanmış görüntünün boyutu |
| format | String | Çıktı dosyasının görüntü formatı |

 **Result:**
AnimationClip


---


### render{#render}

| Ad | Açıklama |
| --- | --- |
| render(camera, fileName, size, format, options) | Sahneyi verilen kameranın perspektifinden dış dosyaya renderlar. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| kamera | Kamera | Sahneyi renderlamak için hangi kameranın perspektifinin kullanılacağı |
| fileName | String | Çıktı dosyasının dosya adı |
| boyut | Vector2 | Son renderlanmış görüntünün boyutu |
| format | String | Çıktı dosyasının görüntü formatı |
| seçenekler | ImageRenderOptions | İç ayarların bir kısmını özelleştirmek için seçenek. |

 **Result:**
AnimationClip


---


### render{#render}

| Ad | Açıklama |
| --- | --- |
| render(camera, bitmap) | Verilen kameranın perspektifinden sahneyi bitmap'e render et. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| kamera | Kamera | Sahneyi renderlamak için hangi kameranın perspektifinin kullanılacağı |
| bitmap | TextureData | Render edilmiş sonucun hedefi |

 **Result:**
AnimationClip


---


### render{#render}

| Ad | Açıklama |
| --- | --- |
| render(camera, bitmap, options) | Verilen kameranın perspektifinden sahneyi bitmap'e render et. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| kamera | Kamera | Sahneyi renderlamak için hangi kameranın perspektifinin kullanılacağı |
| bitmap | TextureData | Render edilmiş sonucun hedefi |
| seçenekler | ImageRenderOptions | İç ayarların bir kısmını özelleştirmek için seçenek. |

 **Result:**
AnimationClip


---


### removeProperty{#removeProperty}

| Ad | Açıklama |
| --- | --- |
| removeProperty(property) | Dinamik bir özelliği kaldırır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| property | Property | Hangi özellik kaldırılacak |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Ad | Açıklama |
| --- | --- |
| removeProperty(property) | Adı belirtilen özelliği kaldır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Ad | Açıklama |
| --- | --- |
| getProperty(property) | Belirtilen özelliğin değerini al |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| property | String | Özellik adı |

 **Result:**
Object


---


### setProperty{#setProperty}

| Ad | Açıklama |
| --- | --- |
| setProperty(property, value) | Belirtilen özelliğin değerini ayarlar |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| property | String | Özellik adı |
| değer | Object | Özelliğin değeri |

 **Result:**
Object


---


### findProperty{#findProperty}

| Ad | Açıklama |
| --- | --- |
| findProperty(propertyName) | Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty ile oluşturulan) veya yerel özellik (adıyla tanımlanan) olabilir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| propertyName | String | Özellik adı. |

 **Result:**
Property


---



