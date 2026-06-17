---
title: "Сетка"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/mesh/
---
## Mesh class

Сетка состоит из множества n-угольных полигонов.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр класса Mesh. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(name) | Инициализирует новый экземпляр класса Mesh. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя. |

 **Result:**



---


### getEdges{#getEdges}

| Имя | Описание |
| --- | --- |
| getEdges() | Получает ребра Mesh. Ребро является необязательным в сетке, поэтому может быть пустым. |

 **Result:**



---


### getPolygonCount{#getPolygonCount}

| Имя | Описание |
| --- | --- |
| getPolygonCount() | Получает количество полигонов. Количество полигонов. |

 **Result:**



---


### getPolygons{#getPolygons}

| Имя | Описание |
| --- | --- |
| getPolygons() | Получает определение полигонов сетки |

 **Result:**



---


### getVisible{#getVisible}

| Имя | Описание |
| --- | --- |
| getVisible() | Получает или задает, видима ли геометрия |

 **Result:**



---


### setVisible{#setVisible}

| Имя | Описание |
| --- | --- |
| setVisible(value) | Получает или задает, видима ли геометрия |

 **Result:**



---


### getDeformers{#getDeformers}

| Имя | Описание |
| --- | --- |
| getDeformers() | Получает все деформаторы, связанные с этой геометрией. Деформаторы. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Имя | Описание |
| --- | --- |
| getControlPoints() | Получает все контрольные точки |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Имя | Описание |
| --- | --- |
| getCastShadows() | Получает или задает, может ли эта геометрия отбрасывать тень |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Имя | Описание |
| --- | --- |
| setCastShadows(value) | Получает или задает, может ли эта геометрия отбрасывать тень |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Имя | Описание |
| --- | --- |
| getReceiveShadows() | Получает или задает, может ли эта геометрия принимать тень. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Имя | Описание |
| --- | --- |
| setReceiveShadows(value) | Получает или задает, может ли эта геометрия принимать тень. |

 **Result:**



---


### getVertexElements{#getVertexElements}

| Имя | Описание |
| --- | --- |
| getVertexElements() | Получает все элементы вершин |

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


### getPolygonSize{#getPolygonSize}

| Имя | Описание |
| --- | --- |
| getPolygonSize(index) | Получает количество вершин указанного многоугольника. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| индекс | Number | Индекс. |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Имя | Описание |
| --- | --- |
| createPolygon(indices, offset, length) | Создает новый многоугольник со всеми вершинами, определенными в indices. Чтобы создавать многоугольник вершина за вершиной, пожалуйста, используйте PolygonBuilder. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| индексы | Number[] | Массив индексов многоугольника, каждый индекс указывает на контрольную точку, образующую многоугольник. |
| смещение | Number | Смещение первого индекса многоугольника |
| длина | Number | Длина индексов |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Имя | Описание |
| --- | --- |
| createPolygon(indices) | Создает новый многоугольник со всеми вершинами, определенными в indices. Чтобы создавать многоугольник вершина за вершиной, пожалуйста, используйте PolygonBuilder. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| индексы | Number[] | Массив индексов многоугольника, каждый индекс указывает на контрольную точку, образующую многоугольник. |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Имя | Описание |
| --- | --- |
| createPolygon(v1, v2, v3, v4) | Создать многоугольник с 4 вершинами (quad) |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| v1 | Number | Индекс первой вершины |
| v2 | Number | Индекс второй вершины |
| v3 | Number | Индекс третьей вершины |
| v4 | Number | Индекс четвертой вершины |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Имя | Описание |
| --- | --- |
| createPolygon(v1, v2, v3) | Создать полигон с 3 вершинами(треугольник) |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| v1 | Number | Индекс первой вершины |
| v2 | Number | Индекс второй вершины |
| v3 | Number | Индекс третьей вершины |

 **Result:**
Number


---


### toMesh{#toMesh}

| Имя | Описание |
| --- | --- |
| toMesh() | Получает экземпляр Mesh из текущей сущности. |

 **Result:**
Сетка


---


### getElement{#getElement}

| Имя | Описание |
| --- | --- |
| getElement(type) | Получает элемент вершины с указанным типом |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| Имя | Описание |
| --- | --- |
| getVertexElementOfUV(textureMapping) | Получает экземпляр VertexElementUV с заданным типом отображения текстуры |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| Имя | Описание |
| --- | --- |
| createElement(type) | Создает элемент вершины с указанным типом и добавляет его в геометрию. Если тип равен VertexElementType.UV, будет создан VertexElementUV с типом отображения текстуры TextureMapping.DIFFUSE. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| Имя | Описание |
| --- | --- |
| addElement(element) | Добавляет существующий элемент вершины в текущую геометрию |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| element | VertexElement | Элемент вершины для добавления |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Имя | Описание |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Создает элемент вершины с указанным типом и добавляет его в геометрию. Если тип равен VertexElementType.UV, будет создан VertexElementUV с типом отображения текстуры TextureMapping.DIFFUSE. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| Имя | Описание |
| --- | --- |
| createElementUV(uvMapping) | Создает VertexElementUV с заданным типом отображения текстуры. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| Имя | Описание |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | Создает VertexElementUV с заданным типом отображения текстуры. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| Имя | Описание |
| --- | --- |
| getBoundingBox() | Получает ограничивающий прямоугольник текущей сущности в её системе координат объектного пространства. |

 **Result:**
VertexElementUV


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



