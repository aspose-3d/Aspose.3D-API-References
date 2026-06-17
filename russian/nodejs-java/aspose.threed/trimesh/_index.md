---
title: "TriMesh"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

TriMesh содержит необработанные данные, которые могут использоваться GPU напрямую.  Этот класс — утилита, помогающая построить сетку, содержащую только данные по вершинам.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(name, declaration) | Инициализировать экземпляр TriMesh |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя этого TriMesh |
| declaration | VertexDeclaration | Объявление вершины |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| Имя | Описание |
| --- | --- |
| getVertexDeclaration() | Разметка вершин TriMesh. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| Имя | Описание |
| --- | --- |
| getVerticesCount() | Количество вершин в этом TriMesh |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| Имя | Описание |
| --- | --- |
| getIndicesCount() | Количество индексов в этом TriMesh |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| Имя | Описание |
| --- | --- |
| getUnmergedVerticesCount() | Количество несъединённых вершин, переданных через beginVertex() и endVertex(). |

 **Result:**



---


### getCapacity{#getCapacity}

| Имя | Описание |
| --- | --- |
| getCapacity() | Ёмкость предварительно выделенных вершин. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| Имя | Описание |
| --- | --- |
| getVerticesSizeInBytes() | Общий размер всех вершин в байтах |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Имя | Описание |
| --- | --- |
| getParentNodes() | Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии. Узлы. |

 **Result:**



---


### getExcluded{#getExcluded}

| Имя | Описание |
| --- | --- |
| getExcluded() | Получает или задает, следует ли исключать эту сущность при экспорте. |

 **Result:**



---


### setExcluded{#setExcluded}

| Имя | Описание |
| --- | --- |
| setExcluded(value) | Получает или задает, следует ли исключать эту сущность при экспорте. |

 **Result:**



---


### getParentNode{#getParentNode}

| Имя | Описание |
| --- | --- |
| getParentNode() | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от других родительских узлов. Родительский узел. |

 **Result:**



---


### setParentNode{#setParentNode}

| Имя | Описание |
| --- | --- |
| setParentNode(value) | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от других родительских узлов. Родительский узел. |

 **Result:**



---


### getScene{#getScene}

| Имя | Описание |
| --- | --- |
| getScene() | Получает сцену, к которой принадлежит этот объект. |

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


### fromMesh{#fromMesh}

| Имя | Описание |
| --- | --- |
| fromMesh(declaration, mesh) | Создать TriMesh из данного объекта mesh с заданным расположением вершин. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |
| mes | Сетка | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| Имя | Описание |
| --- | --- |
| copyFrom(input, vd) | Скопировать TriMesh из input с новым расположением вершин |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| input | TriMesh | Входной TriMesh для копирования |
| vd | VertexDeclaration | Новое объявление вершин выходного TriMesh |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| Имя | Описание |
| --- | --- |
| fromMesh(mesh, useFloat) | Создать TriMesh из данного объекта mesh, объявление вершин основано на структуре входного mesh. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| mes | Сетка | null |
| useFloat | boolean | Использовать тип float вместо double для каждого компонента элемента вершины. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| Имя | Описание |
| --- | --- |
| beginVertex() | Начать добавление вершины |

 **Result:**
Вершина


---


### endVertex{#endVertex}

| Имя | Описание |
| --- | --- |
| endVertex() | Завершить добавление вершины |

 **Result:**
Вершина


---


### verticesToArray{#verticesToArray}

| Имя | Описание |
| --- | --- |
| verticesToArray() | Преобразовать данные вершин в массив байтов |

 **Result:**
byte[]


---


### toString{#toString}

| Имя | Описание |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### fromRawData{#fromRawData}

| Имя | Описание |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | Создать TriMesh из необработанных данных. Возвращаемый TriMesh не будет копировать входной массив байтов для повышения производительности; внешние изменения массива будут отражаться в этом экземпляре. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| vd | VertexDeclaration | Объявление вершины должно содержать хотя бы одно поле. |
| vertices | byte[] | Входные данные вершины, минимальная длина массива вершин должна быть больше или равна размеру объявления вершины. |
| индексы | Number[] | Индексы треугольников |
| generateVertexMapping | boolean | Сгенерировать |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| Имя | Описание |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | Загрузить вершины из байтов, длина массива байтов должна быть целым кратным размеру вершины. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| Имя | Описание |
| --- | --- |
| readVector4(idx, field) | Прочитать поле vector4 |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| idx | Number | Индекс вершины для чтения |
| field | VertexField | Поле с типом данных Vector4/FVector4 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| Имя | Описание |
| --- | --- |
| readFVector4(idx, field) | Прочитать поле vector4 |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| idx | Number | Индекс вершины для чтения |
| field | VertexField | Поле с типом данных Vector4/FVector4 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| Имя | Описание |
| --- | --- |
| readVector3(idx, field) | Прочитать поле vector3 |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| idx | Number | Индекс вершины для чтения |
| field | VertexField | Поле с типом данных Vector3/FVector3 |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| Имя | Описание |
| --- | --- |
| readFVector3(idx, field) | Прочитать поле vector3 |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| idx | Number | Индекс вершины для чтения |
| field | VertexField | Поле с типом данных Vector3/FVector3 |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| Имя | Описание |
| --- | --- |
| readVector2(idx, field) | Прочитать поле vector2 |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| idx | Number | Индекс вершины для чтения |
| field | VertexField | Поле с типом данных Vector2/FVector2 |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| Имя | Описание |
| --- | --- |
| readFVector2(idx, field) | Прочитать поле vector2 |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| idx | Number | Индекс вершины для чтения |
| field | VertexField | Поле с типом данных Vector2/FVector2 |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| Имя | Описание |
| --- | --- |
| readDouble(idx, field) | Прочитать поле double |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| idx | Number | Индекс вершины для чтения |
| field | VertexField | Поле с совместимым типом данных float/double |

 **Result:**
Number


---


### readFloat{#readFloat}

| Имя | Описание |
| --- | --- |
| readFloat(idx, field) | Прочитать поле float |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| idx | Number | Индекс вершины для чтения |
| field | VertexField | Поле с совместимым типом данных float/double |

 **Result:**
Number


---


### getBoundingBox{#getBoundingBox}

| Имя | Описание |
| --- | --- |
| getBoundingBox() | Получает ограничивающий прямоугольник текущей сущности в её системе координат объектного пространства. |

 **Result:**
Number


---


### getEntityRendererKey{#getEntityRendererKey}

| Имя | Описание |
| --- | --- |
| getEntityRendererKey() | Получает ключ рендерера сущности, зарегистрированного в рендерере. |

 **Result:**
EntityRendererKey


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



