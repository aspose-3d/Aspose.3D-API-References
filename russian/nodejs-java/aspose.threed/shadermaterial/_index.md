---
title: "ShaderMaterial"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

Шейдерный материал позволяет описать материал с помощью внешнего движка рендеринга или языка шейдеров.  ShaderMaterial использует ShaderTechnique для описания конкретных деталей рендеринга, и наиболее подходящий будет выбран в зависимости от конечной платформы рендеринга.  Например, ваш экземпляр ShaderMaterial может иметь две техники: одна определена в HLSL, другая — в GLSL.  На платформах без окна следует использовать GLSL вместо HLSL.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр класса ShaderMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(name) | Инициализирует новый экземпляр класса ShaderMaterial. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя |

 **Result:**



---


### getTechniques{#getTechniques}

| Имя | Описание |
| --- | --- |
| getTechniques() | Получает все доступные техники, определённые в этом материале. |

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



