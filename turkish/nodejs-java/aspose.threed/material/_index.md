---
title: "Malzeme"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/material/
---
## Material class

Material, geometrinin görsel görünümü için gerekli parametreleri tanımlar.  Aspose.3D, LambertMaterial, PhongMaterial ve ShaderMaterial için gölgelendirme modeli sağlar  @hideconstructor


## Properties

| Ad | Açıklama |
| --- | --- |
| MAP_SPECULAR | setTexture(java.lang.String, com.aspose.threed.TextureBase) içinde speküler doku eşlemesi atamak için kullanılır. |
| MAP_DIFFUSE | setTexture(java.lang.String, com.aspose.threed.TextureBase) içinde difüz doku eşlemesi atamak için kullanılır. |
| MAP_EMISSIVE | setTexture(java.lang.String, com.aspose.threed.TextureBase) içinde emisyon doku eşlemesi atamak için kullanılır. |
| MAP_AMBIENT | setTexture(java.lang.String, com.aspose.threed.TextureBase) içinde ortam doku eşlemesi atamak için kullanılır. |
| MAP_NORMAL | setTexture(java.lang.String, com.aspose.threed.TextureBase) içinde normal doku eşlemesi atamak için kullanılır. |

## Yöntemler

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



