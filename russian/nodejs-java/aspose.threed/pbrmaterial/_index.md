---
title: "PbrMaterial"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/pbrmaterial/
---
## PbrMaterial class

Материал для физически основанного рендеринга, основанный на альбедо‑цвете/металличности/шероховатости.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Создать экземпляр материала PBR по умолчанию |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(albedo) | Создать материал PBR по умолчанию с указанным значением цвета альбедо. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| albedo | Vector3 | Значение цвета альбедо по умолчанию |

 **Result:**



---


### getTransparency{#getTransparency}

| Имя | Описание |
| --- | --- |
| getTransparency() | Получает или задает коэффициент прозрачности. Коэффициент должен находиться в диапазоне от 0 (0 %, полностью непрозрачно) до 1 (100 %, полностью прозрачно). Любое недопустимое значение коэффициента будет ограничено. Коэффициент прозрачности. |

 **Result:**



---


### setTransparency{#setTransparency}

| Имя | Описание |
| --- | --- |
| setTransparency(value) | Получает или задает коэффициент прозрачности. Коэффициент должен находиться в диапазоне от 0 (0 %, полностью непрозрачно) до 1 (100 %, полностью прозрачно). Любое недопустимое значение коэффициента будет ограничено. Коэффициент прозрачности. |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| Имя | Описание |
| --- | --- |
| getNormalTexture() | Получает или задает текстуру нормального отображения |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| Имя | Описание |
| --- | --- |
| setNormalTexture(value) | Получает или задает текстуру нормального отображения |

 **Result:**



---


### getSpecularTexture{#getSpecularTexture}

| Имя | Описание |
| --- | --- |
| getSpecularTexture() | Получает или задает текстуру для зеркального цвета |

 **Result:**



---


### setSpecularTexture{#setSpecularTexture}

| Имя | Описание |
| --- | --- |
| setSpecularTexture(value) | Получает или задает текстуру для зеркального цвета |

 **Result:**



---


### getAlbedoTexture{#getAlbedoTexture}

| Имя | Описание |
| --- | --- |
| getAlbedoTexture() | Получает или задает текстуру альбедо |

 **Result:**



---


### setAlbedoTexture{#setAlbedoTexture}

| Имя | Описание |
| --- | --- |
| setAlbedoTexture(value) | Получает или задает текстуру альбедо |

 **Result:**



---


### getAlbedo{#getAlbedo}

| Имя | Описание |
| --- | --- |
| getAlbedo() | Получает или задает базовый цвет материала |

 **Result:**



---


### setAlbedo{#setAlbedo}

| Имя | Описание |
| --- | --- |
| setAlbedo(value) | Получает или задает базовый цвет материала |

 **Result:**



---


### getOcclusionTexture{#getOcclusionTexture}

| Имя | Описание |
| --- | --- |
| getOcclusionTexture() | Получает или задает текстуру для окклюзии окружающей среды |

 **Result:**



---


### setOcclusionTexture{#setOcclusionTexture}

| Имя | Описание |
| --- | --- |
| setOcclusionTexture(value) | Получает или задает текстуру для окклюзии окружающей среды |

 **Result:**



---


### getOcclusionFactor{#getOcclusionFactor}

| Имя | Описание |
| --- | --- |
| getOcclusionFactor() | Получает или задает коэффициент окклюзии окружающей среды |

 **Result:**



---


### setOcclusionFactor{#setOcclusionFactor}

| Имя | Описание |
| --- | --- |
| setOcclusionFactor(value) | Получает или задает коэффициент окклюзии окружающей среды |

 **Result:**



---


### getMetallicFactor{#getMetallicFactor}

| Имя | Описание |
| --- | --- |
| getMetallicFactor() | Получает или задает металлическость материала, значение 1 означает, что материал является металлом, а значение 0 — диэлектриком. |

 **Result:**



---


### setMetallicFactor{#setMetallicFactor}

| Имя | Описание |
| --- | --- |
| setMetallicFactor(value) | Получает или задает металлическость материала, значение 1 означает, что материал является металлом, а значение 0 — диэлектриком. |

 **Result:**



---


### getRoughnessFactor{#getRoughnessFactor}

| Имя | Описание |
| --- | --- |
| getRoughnessFactor() | Получает или задает шероховатость материала, значение 1 означает полностью шероховатый материал, а значение 0 — полностью гладкий |

 **Result:**



---


### setRoughnessFactor{#setRoughnessFactor}

| Имя | Описание |
| --- | --- |
| setRoughnessFactor(value) | Получает или задает шероховатость материала, значение 1 означает полностью шероховатый материал, а значение 0 — полностью гладкий |

 **Result:**



---


### getMetallicRoughness{#getMetallicRoughness}

| Имя | Описание |
| --- | --- |
| getMetallicRoughness() | Получает или задает текстуру для металлических свойств (в канале R) и шероховатости (в канале G) |

 **Result:**



---


### setMetallicRoughness{#setMetallicRoughness}

| Имя | Описание |
| --- | --- |
| setMetallicRoughness(value) | Получает или задает текстуру для металлических свойств (в канале R) и шероховатости (в канале G) |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| Имя | Описание |
| --- | --- |
| getEmissiveTexture() | Получает или задает текстуру эмиссии |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| Имя | Описание |
| --- | --- |
| setEmissiveTexture(value) | Получает или задает текстуру эмиссии |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Имя | Описание |
| --- | --- |
| getEmissiveColor() | Получает или задает излучающий цвет |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Имя | Описание |
| --- | --- |
| setEmissiveColor(value) | Получает или задает излучающий цвет |

 **Result:**



---


### getName{#getName}

| Имя | Описание |
| --- | --- |
| getName() | Получает или задает имя. Имя. |

 **Result:**



---


### setName{#setName}

| Имя | Описание |
| --- | --- |
| setName(value) | Получает или задает имя. Имя. |

 **Result:**



---


### getProperties{#getProperties}

| Имя | Описание |
| --- | --- |
| getProperties() | Получает коллекцию всех свойств. |

 **Result:**



---


### fromMaterial{#fromMaterial}

| Имя | Описание |
| --- | --- |
| fromMaterial(material) | Разрешить преобразование другого материала в PbrMaterial |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| материя | Материал | null |

 **Result:**
PbrMaterial


---


### getTexture{#getTexture}

| Имя | Описание |
| --- | --- |
| getTexture(slotName) | Получает текстуру из указанного слота, это может быть имя свойства материала или имя параметра шейдера |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| slotName | String | Имя слота. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Имя | Описание |
| --- | --- |
| setTexture(slotName, texture) | Устанавливает текстуру в указанный слот |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| slotName | String | Имя слота. |
| texture | TextureBase | Текстура. |

 **Result:**
TextureBase


---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() | Преобразует объект в строку |

 **Result:**
String


---


### removeProperty{#removeProperty}

| Имя | Описание |
| --- | --- |
| removeProperty(property) | Удаляет динамическое свойство. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | Property | Какое свойство удалить |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Имя | Описание |
| --- | --- |
| removeProperty(property) | Удалить указанное свойство, определённое по имени |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Имя | Описание |
| --- | --- |
| getProperty(property) | Получить значение указанного свойства |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | String | Имя свойства |

 **Result:**
Object


---


### setProperty{#setProperty}

| Имя | Описание |
| --- | --- |
| setProperty(property, value) | Устанавливает значение указанного свойства |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | String | Имя свойства |
| value | Object | Значение свойства |

 **Result:**
Object


---


### findProperty{#findProperty}

| Имя | Описание |
| --- | --- |
| findProperty(propertyName) | Находит свойство. Это может быть динамическое свойство (Created by CreateDynamicProperty/SetProperty) или нативное свойство (Identified by its name) |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| propertyName | String | Имя свойства. |

 **Result:**
Property


---


### iterator{#iterator}

| Имя | Описание |
| --- | --- |
| iterator() | Зарезервировано для внутреннего использования. |

 **Result:**
Property


---



