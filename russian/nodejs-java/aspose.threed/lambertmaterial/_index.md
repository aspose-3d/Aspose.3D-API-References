---
title: "LambertMaterial"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/lambertmaterial/
---
## LambertMaterial class

Материал для ламбертовой модели затенения


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр класса LambertMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(name) | Инициализирует новый экземпляр класса LambertMaterial. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя |

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


### getAmbientColor{#getAmbientColor}

| Имя | Описание |
| --- | --- |
| getAmbientColor() | Получает или задает окружающий цвет. Пример: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| Имя | Описание |
| --- | --- |
| setAmbientColor(value) | Получает или задает окружающий цвет. Пример: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| Имя | Описание |
| --- | --- |
| getDiffuseColor() | Получает или задает диффузный цвет Пример: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); диффузный. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| Имя | Описание |
| --- | --- |
| setDiffuseColor(value) | Получает или задает диффузный цвет Пример: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); диффузный. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| Имя | Описание |
| --- | --- |
| getTransparentColor() | Получает или задает прозрачный цвет. Пример: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); цвет прозрачного. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| Имя | Описание |
| --- | --- |
| setTransparentColor(value) | Получает или задает прозрачный цвет. Пример: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); цвет прозрачного. |

 **Result:**



---


### getTransparency{#getTransparency}

| Имя | Описание |
| --- | --- |
| getTransparency() | Получает или задает коэффициент прозрачности. Коэффициент должен находиться в диапазоне от 0 (0 %, полностью непрозрачно) до 1 (100 %, полностью прозрачно). Любое недопустимое значение коэффициента будет ограничено. Пример: var mat = new LambertMaterial(); mat.Transparency = 0.3; коэффициент прозрачности. |

 **Result:**



---


### setTransparency{#setTransparency}

| Имя | Описание |
| --- | --- |
| setTransparency(value) | Получает или задает коэффициент прозрачности. Коэффициент должен находиться в диапазоне от 0 (0 %, полностью непрозрачно) до 1 (100 %, полностью прозрачно). Любое недопустимое значение коэффициента будет ограничено. Пример: var mat = new LambertMaterial(); mat.Transparency = 0.3; коэффициент прозрачности. |

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



