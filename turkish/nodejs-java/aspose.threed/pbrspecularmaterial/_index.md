---
title: "PbrSpecularMaterial"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Difüz renk/yansıma/parlaklığa dayalı fiziksel tabanlı renderleme için malzeme


## Properties

| Ad | Açıklama |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | Speküler parlaklık için doku haritası |

## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | PbrSpecularMaterial yapıcısı |

 **Result:**



---


### getTransparency{#getTransparency}

| Ad | Açıklama |
| --- | --- |
| getTransparency() | Şeffaflık faktörünü alır veya ayarlar. Faktör 0(0%, tamamen opak) ile 1(100%, tamamen şeffaf) arasında olmalıdır. Geçersiz bir faktör değeri sınırlanacaktır. Şeffaflık faktörü. |

 **Result:**



---


### setTransparency{#setTransparency}

| Ad | Açıklama |
| --- | --- |
| setTransparency(value) | Şeffaflık faktörünü alır veya ayarlar. Faktör 0(0%, tamamen opak) ile 1(100%, tamamen şeffaf) arasında olmalıdır. Geçersiz bir faktör değeri sınırlanacaktır. Şeffaflık faktörü. |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| Ad | Açıklama |
| --- | --- |
| getNormalTexture() | Normal haritalamanın dokusunu alır veya ayarlar |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| Ad | Açıklama |
| --- | --- |
| setNormalTexture(value) | Normal haritalamanın dokusunu alır veya ayarlar |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| Ad | Açıklama |
| --- | --- |
| getSpecularGlossinessTexture() | Speküler renk için dokuyu alır veya ayarlar, RGB kanalı speküler rengi, A kanalı ise parlaklığı depolar. |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| Ad | Açıklama |
| --- | --- |
| setSpecularGlossinessTexture(value) | Speküler renk için dokuyu alır veya ayarlar, RGB kanalı speküler rengi, A kanalı ise parlaklığı depolar. |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| Ad | Açıklama |
| --- | --- |
| getGlossinessFactor() | Malzemenin parlaklığını (pürüzsüzlüğünü) alır veya ayarlar, 1 tamamen pürüzsüz, 0 tamamen pürüzlü anlamına gelir, varsayılan değer 1'dir, aralık [0, 1]'dir. |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| Ad | Açıklama |
| --- | --- |
| setGlossinessFactor(value) | Malzemenin parlaklığını (pürüzsüzlüğünü) alır veya ayarlar, 1 tamamen pürüzsüz, 0 tamamen pürüzlü anlamına gelir, varsayılan değer 1'dir, aralık [0, 1]'dir. |

 **Result:**



---


### getSpecular{#getSpecular}

| Ad | Açıklama |
| --- | --- |
| getSpecular() | Malzemenin speküler rengini alır veya ayarlar, varsayılan değer (1, 1, 1)'dir. |

 **Result:**



---


### setSpecular{#setSpecular}

| Ad | Açıklama |
| --- | --- |
| setSpecular(value) | Malzemenin speküler rengini alır veya ayarlar, varsayılan değer (1, 1, 1)'dir. |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| Ad | Açıklama |
| --- | --- |
| getDiffuseTexture() | Difüz için dokuyu alır veya ayarlar |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| Ad | Açıklama |
| --- | --- |
| setDiffuseTexture(value) | Difüz için dokuyu alır veya ayarlar |

 **Result:**



---


### getDiffuse{#getDiffuse}

| Ad | Açıklama |
| --- | --- |
| getDiffuse() | Malzemenin difüz rengini alır veya ayarlar, varsayılan değer (1, 1, 1)'dir. |

 **Result:**



---


### setDiffuse{#setDiffuse}

| Ad | Açıklama |
| --- | --- |
| setDiffuse(value) | Malzemenin difüz rengini alır veya ayarlar, varsayılan değer (1, 1, 1)'dir. |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| Ad | Açıklama |
| --- | --- |
| getEmissiveTexture() | Emisyon için dokuyu alır veya ayarlar |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| Ad | Açıklama |
| --- | --- |
| setEmissiveTexture(value) | Emisyon için dokuyu alır veya ayarlar |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Ad | Açıklama |
| --- | --- |
| getEmissiveColor() | Emisyon rengini alır veya ayarlar, varsayılan değer (0, 0, 0)'dır. |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Ad | Açıklama |
| --- | --- |
| setEmissiveColor(value) | Emisyon rengini alır veya ayarlar, varsayılan değer (0, 0, 0)'dır. |

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



