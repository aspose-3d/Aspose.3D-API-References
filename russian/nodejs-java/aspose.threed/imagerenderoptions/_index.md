---
title: "ImageRenderOptions"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/imagerenderoptions/
---
## ImageRenderOptions class

Параметры для Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) и  Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions)


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализировать экземпляр ImageRenderOptions |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| Имя | Описание |
| --- | --- |
| getBackgroundColor() | Цвет фона результата рендеринга. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| Имя | Описание |
| --- | --- |
| setBackgroundColor(value) | Цвет фона результата рендеринга. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Имя | Описание |
| --- | --- |
| getAssetDirectories() | Каталоги, в которых хранятся внешние ресурсы (например, текстуры) |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Имя | Описание |
| --- | --- |
| getEnableShadows() | Получает или задаёт, следует ли рендерить тени. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Имя | Описание |
| --- | --- |
| setEnableShadows(value) | Получает или задаёт, следует ли рендерить тени. |

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



