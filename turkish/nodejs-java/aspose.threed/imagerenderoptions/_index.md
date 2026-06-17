---
title: "ImageRenderOptions"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/imagerenderoptions/
---
## ImageRenderOptions class

Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) ve Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions) için seçenekler


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | ImageRenderOptions bir örneğini başlat |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| Ad | Açıklama |
| --- | --- |
| getBackgroundColor() | Render sonucunun arka plan rengi. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| Ad | Açıklama |
| --- | --- |
| setBackgroundColor(value) | Render sonucunun arka plan rengi. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Ad | Açıklama |
| --- | --- |
| getAssetDirectories() | Harici varlıkları (örneğin dokuları) depolayan dizinler |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Ad | Açıklama |
| --- | --- |
| getEnableShadows() | Gölge render edilip edilmeyeceği alınır veya ayarlanır. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Ad | Açıklama |
| --- | --- |
| setEnableShadows(value) | Gölge render edilip edilmeyeceği alınır veya ayarlanır. |

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



