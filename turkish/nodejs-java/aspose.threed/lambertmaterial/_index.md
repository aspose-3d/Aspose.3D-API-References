---
title: "LambertMaterial"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/lambertmaterial/
---
## LambertMaterial class

Lambert gölgelendirme modeli için malzeme


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | LambertMaterial sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(name) | LambertMaterial sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Ad | Açıklama |
| --- | --- |
| getEmissiveColor() | Emisyon rengini alır veya ayarlar |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Ad | Açıklama |
| --- | --- |
| setEmissiveColor(value) | Emisyon rengini alır veya ayarlar |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| Ad | Açıklama |
| --- | --- |
| getAmbientColor() | Ambient rengi alır veya ayarlar. Örnek: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| Ad | Açıklama |
| --- | --- |
| setAmbientColor(value) | Ambient rengi alır veya ayarlar. Örnek: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| Ad | Açıklama |
| --- | --- |
| getDiffuseColor() | Dağınık rengi alır veya ayarlar Örnek: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); dağınık. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| Ad | Açıklama |
| --- | --- |
| setDiffuseColor(value) | Dağınık rengi alır veya ayarlar Örnek: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); dağınık. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| Ad | Açıklama |
| --- | --- |
| getTransparentColor() | Şeffaf rengi alır veya ayarlar. Örnek: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); şeffafın rengi. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| Ad | Açıklama |
| --- | --- |
| setTransparentColor(value) | Şeffaf rengi alır veya ayarlar. Örnek: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); şeffafın rengi. |

 **Result:**



---


### getTransparency{#getTransparency}

| Ad | Açıklama |
| --- | --- |
| getTransparency() | Şeffaflık faktörünü alır veya ayarlar. Faktör 0(0%, tamamen opak) ile 1(100%, tamamen şeffaf) arasında olmalıdır. Geçersiz faktör değeri sınırlandırılacaktır. Örnek: var mat = new LambertMaterial(); mat.Transparency = 0.3; şeffaflık faktörü. |

 **Result:**



---


### setTransparency{#setTransparency}

| Ad | Açıklama |
| --- | --- |
| setTransparency(value) | Şeffaflık faktörünü alır veya ayarlar. Faktör 0(0%, tamamen opak) ile 1(100%, tamamen şeffaf) arasında olmalıdır. Geçersiz faktör değeri sınırlandırılacaktır. Örnek: var mat = new LambertMaterial(); mat.Transparency = 0.3; şeffaflık faktörü. |

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


### getTexture{#getTexture}

| Ad | Açıklama |
| --- | --- |
| getTexture(slotName) | Belirtilen slot'tan dokuyu alır, bu bir materyalin özellik adı veya shader'ın parametre adı olabilir |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| slotName | String | Slot adı. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Ad | Açıklama |
| --- | --- |
| setTexture(slotName, texture) | Dokuyu belirtilen slota ayarlar |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| slotName | String | Slot adı. |
| texture | TextureBase | Doku. |

 **Result:**
TextureBase


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Nesneyi dizeye biçimlendir |

 **Result:**
String


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


### iterator{#iterator}

| Ad | Açıklama |
| --- | --- |
| iterator() | Dahili kullanım için ayrılmıştır. |

 **Result:**
Property


---



