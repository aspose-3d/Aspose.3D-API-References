---
title: "BindPoint"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

BindPoint обычно создаётся на свойстве объекта, некоторые типы свойств содержат несколько компонентных полей (например, поле Vector3), BindPoint генерирует канал для каждого компонентного поля и соединяет поле с одним или несколькими экземплярами последовательностей ключевых кадров через каналы.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(scene, prop) | Инициализирует новый экземпляр класса BindPoint. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| сцена | Scene | Сцена, содержащая анимацию. |
| prop | Property | Свойство. |

 **Result:**



---


### getProperty{#getProperty}

| Имя | Описание |
| --- | --- |
| getProperty() | Получает свойство, связанное с CurveMapping |

 **Result:**



---


### setProperty{#setProperty}

| Имя | Описание |
| --- | --- |
| setProperty(value) | Получает свойство, связанное с CurveMapping |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Имя | Описание |
| --- | --- |
| getChannelsCount() | Получает общее количество каналов свойств, определённых в этом отображении анимационной кривой. |

 **Result:**
Number


---


### getName{#getName}

| Имя | Описание |
| --- | --- |
| getName() | Получает или задает имя. Имя. |

 **Result:**
Number


---


### setName{#setName}

| Имя | Описание |
| --- | --- |
| setName(value) | Получает или задает имя. Имя. |

 **Result:**
Number


---


### getProperties{#getProperties}

| Имя | Описание |
| --- | --- |
| getProperties() | Получает коллекцию всех свойств. |

 **Result:**
Number


---


### get{#get}

| Имя | Описание |
| --- | --- |
| get(channelName) |  |

 **Result:**
Number


---


### getKeyframeSequence{#getKeyframeSequence}

| Имя | Описание |
| --- | --- |
| getKeyframeSequence(channelName) | Получает первую последовательность ключевых кадров в указанном канале |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| channelName | String | Имя канала для поиска |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| Имя | Описание |
| --- | --- |
| getKeyframeSequences(channelName) | Получает все последовательности ключевых кадров в указанном канале |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| channelName | String | Имя канала для поиска |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| Имя | Описание |
| --- | --- |
| createKeyframeSequence(name) | Создаёт новую кривую и соединяет её с первым каналом отображения кривой |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя новой последовательности. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Имя | Описание |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Привязывает последовательность ключевых кадров к указанному каналу |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| channelName | String | К какому каналу будет привязана последовательность ключевых кадров |
| последовательность | KeyframeSequence | Последовательность ключевых кадров для привязки |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Имя | Описание |
| --- | --- |
| getChannel(channelName) | Получает канал по заданному имени |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| channelName | String | Имя канала для поиска |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| Имя | Описание |
| --- | --- |
| addChannel(name, value) | Добавляет указанное свойство канала. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя. |
| value | Object | Значение. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| Имя | Описание |
| --- | --- |
| addChannel(name, type, value) | Добавляет указанное свойство канала. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя. |
| type | Класс | Тип. |
| value | Object | Значение. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Имя | Описание |
| --- | --- |
| resetChannels() | Очищает каналы свойств этой отображения анимационной кривой. |

 **Result:**
boolean


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



