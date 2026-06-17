---
title: "Материал"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/material/
---
## Material class

Material определяет параметры, необходимые для визуального отображения геометрии. Aspose.3D предоставляет модели затенения для LambertMaterial, PhongMaterial и ShaderMaterial  @hideconstructor


## Свойства

| Имя | Описание |
| --- | --- |
| MAP_SPECULAR | Используется в setTexture(java.lang.String, com.aspose.threed.TextureBase) для назначения спекулярного отображения текстуры. |
| MAP_DIFFUSE | Используется в setTexture(java.lang.String, com.aspose.threed.TextureBase) для назначения диффузного отображения текстуры. |
| MAP_EMISSIVE | Используется в setTexture(java.lang.String, com.aspose.threed.TextureBase) для назначения эмиссивного отображения текстуры. |
| MAP_AMBIENT | Используется в setTexture(java.lang.String, com.aspose.threed.TextureBase) для назначения амбиентного отображения текстуры. |
| MAP_NORMAL | Используется в setTexture(java.lang.String, com.aspose.threed.TextureBase) для назначения нормального отображения текстуры. |

## Методы

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



