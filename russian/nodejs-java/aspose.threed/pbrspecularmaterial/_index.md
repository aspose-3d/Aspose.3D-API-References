---
title: "PbrSpecularMaterial"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Материал для физически основанного рендеринга, основанный на диффузном цвете/спекуляре/глянце.


## Свойства

| Имя | Описание |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | Текстурная карта для зеркального блеска |

## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Конструктор класса PbrSpecularMaterial |

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


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| Имя | Описание |
| --- | --- |
| getSpecularGlossinessTexture() | Получает или задает текстуру для зеркального цвета, канал RGB хранит зеркальный цвет, а канал A хранит блеск. |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| Имя | Описание |
| --- | --- |
| setSpecularGlossinessTexture(value) | Получает или задает текстуру для зеркального цвета, канал RGB хранит зеркальный цвет, а канал A хранит блеск. |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| Имя | Описание |
| --- | --- |
| getGlossinessFactor() | Получает или задает степень блеска (гладкости) материала, 1 означает полностью гладко, а 0 — полностью шероховато, значение по умолчанию — 1, диапазон [0, 1]. |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| Имя | Описание |
| --- | --- |
| setGlossinessFactor(value) | Получает или задает степень блеска (гладкости) материала, 1 означает полностью гладко, а 0 — полностью шероховато, значение по умолчанию — 1, диапазон [0, 1]. |

 **Result:**



---


### getSpecular{#getSpecular}

| Имя | Описание |
| --- | --- |
| getSpecular() | Получает или задает зеркальный цвет материала, значение по умолчанию — (1, 1, 1). |

 **Result:**



---


### setSpecular{#setSpecular}

| Имя | Описание |
| --- | --- |
| setSpecular(value) | Получает или задает зеркальный цвет материала, значение по умолчанию — (1, 1, 1). |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| Имя | Описание |
| --- | --- |
| getDiffuseTexture() | Получает или задает текстуру диффузного отражения |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| Имя | Описание |
| --- | --- |
| setDiffuseTexture(value) | Получает или задает текстуру диффузного отражения |

 **Result:**



---


### getDiffuse{#getDiffuse}

| Имя | Описание |
| --- | --- |
| getDiffuse() | Получает или задает диффузный цвет материала, значение по умолчанию — (1, 1, 1). |

 **Result:**



---


### setDiffuse{#setDiffuse}

| Имя | Описание |
| --- | --- |
| setDiffuse(value) | Получает или задает диффузный цвет материала, значение по умолчанию — (1, 1, 1). |

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
| getEmissiveColor() | Получает или задает эмиссионный цвет, значение по умолчанию — (0, 0, 0). |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Имя | Описание |
| --- | --- |
| setEmissiveColor(value) | Получает или задает эмиссионный цвет, значение по умолчанию — (0, 0, 0). |

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



