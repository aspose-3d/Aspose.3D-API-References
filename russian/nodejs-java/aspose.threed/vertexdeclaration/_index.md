---
title: "VertexDeclaration"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

Объявление структуры пользовательской вершины


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getSealed{#getSealed}

| Имя | Описание |
| --- | --- |
| getSealed() | VertexDeclaration будет запечатан, когда его использует com.aspose.threed.TriMesh`1 или TriMesh, дальнейшие изменения не допускаются. |

 **Result:**



---


### getCount{#getCount}

| Имя | Описание |
| --- | --- |
| getCount() | Получает количество всех полей, определённых в этом VertexDeclaration |

 **Result:**



---


### getSize{#getSize}

| Имя | Описание |
| --- | --- |
| getSize() | Размер структуры вершины в байтах. |

 **Result:**



---


### get{#get}

| Имя | Описание |
| --- | --- |
| get(index) |  |

 **Result:**



---


### clear{#clear}

| Имя | Описание |
| --- | --- |
| clear() | Очистить все поля. |

 **Result:**



---


### addField{#addField}

| Имя | Описание |
| --- | --- |
| addField(dataType, semantic, index, alias) | Добавить новое поле вершины |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| dataType | Number | VertexFieldDataType |
| semantic | VertexFieldSemantic | VertexFieldSemantic |
| индекс | Number | Индекс для одинаковой семантики поля, -1 для автоматической генерации |
| alias | String | Псевдоним поля |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Имя | Описание |
| --- | --- |
| fromGeometry(geometry, useFloat) | Создать VertexDeclaration на основе раскладки Geometry. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| geometr | Геометрия | null |
| useFloat | boolean | Использовать тип float вместо double |

 **Result:**
VertexDeclaration


---


### compareTo{#compareTo}

| Имя | Описание |
| --- | --- |
| compareTo(other) | Сравнивает данный экземпляр с указанным объектом и возвращает индикатор их относительных значений. |

 **Result:**
VertexDeclaration


---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### hashCode{#hashCode}

| Имя | Описание |
| --- | --- |
| hashCode() |  |

 **Result:**
Number


---


### equals{#equals}

| Имя | Описание |
| --- | --- |
| equals(obj) | Определяет, имеют ли этот экземпляр и указанный объект, который также должен быть объектом VertexDeclaration, одинаковое значение. |

 **Result:**
Number


---


### iterator{#iterator}

| Имя | Описание |
| --- | --- |
| iterator() | Зарезервировано для внутреннего использования. |

 **Result:**
Number


---



