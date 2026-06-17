---
title: "PointCloud"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/pointcloud/
---
## PointCloud class

Облако точек не содержит информации о топологии, а только контрольные точки и элементы вершин.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(name) | Конструктор PointCloud |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя этой сущности |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload() | Конструктор PointCloud |

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


### getEntityRendererKey{#getEntityRendererKey}

| Имя | Описание |
| --- | --- |
| getEntityRendererKey() | Получает ключ рендерера сущности, зарегистрированного в рендерере. |

 **Result:**
EntityRendererKey


---


### fromGeometry{#fromGeometry}

| Имя | Описание |
| --- | --- |
| fromGeometry(g) | Создать новый экземпляр PointCloud из объекта геометрии |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
|  | Геометрия | null |

 **Result:**
PointCloud


---


### fromGeometry{#fromGeometry}

| Имя | Описание |
| --- | --- |
| fromGeometry(g, density) | Создать новый экземпляр облака точек из объекта геометрии. Плотность — это количество точек на единичный треугольник (единичный треугольник — это треугольник с максимальной площадью из сетки) |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| g | Геометрия | Экземпляр Mesh или другой геометрии |
| плотность | Number | Количество точек на единичный треугольник |

 **Result:**
PointCloud


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



