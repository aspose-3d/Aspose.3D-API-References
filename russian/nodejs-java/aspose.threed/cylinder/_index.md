---
title: "Цилиндр"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

Параметрический цилиндр. Его также можно использовать для представления конуса, когда один из параметров radiusTop/radiusBottom равен нулю.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр класса Cylinder. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(radius, height) | Инициализирует новый экземпляр класса Cylinder. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| radius | Number | Радиус верхней и нижней крышки. |
| height | Number | Высота. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Инициализирует новый экземпляр класса Cylinder. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| radiusTop | Number | Радиус верхней части. |
| radiusBottom | Number | Радиус нижней части. |
| height | Number | Высота. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Имя | Описание |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Инициализирует новый экземпляр класса Cylinder. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| radiusTop | Number | Радиус верхней крышки цилиндра. |
| radiusBottom | Number | Радиус нижней крышки цилиндра. |
| height | Number | Высота цилиндра. |
| radialSegments | Number | Радиальные сегменты верхних и нижних кругов.. |
| heightSegments | Number | Сегменты высоты. |
| openEnded | boolean | Если установлено в |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Имя | Описание |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Инициализирует новый экземпляр класса Cylinder. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя этого объекта |
| radiusTop | Number | Радиус верхней крышки цилиндра. |
| radiusBottom | Number | Радиус нижней крышки цилиндра. |
| height | Number | Высота цилиндра. |
| radialSegments | Number | Радиальные сегменты верхних и нижних кругов.. |
| heightSegments | Number | Сегменты высоты. |
| openEnded | boolean | Если установлено в |
| thetaStart | Number | Начало theta. |
| thetaLength | Number | Длина theta. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| Имя | Описание |
| --- | --- |
| getOffsetBottom() | Получает или задает смещение трансформации вершин нижней стороны. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| Имя | Описание |
| --- | --- |
| setOffsetBottom(value) | Получает или задает смещение трансформации вершин нижней стороны. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| Имя | Описание |
| --- | --- |
| getOffsetTop() | Получает или задает смещение трансформации вершин верхней стороны. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| Имя | Описание |
| --- | --- |
| setOffsetTop(value) | Получает или задает смещение трансформации вершин верхней стороны. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| Имя | Описание |
| --- | --- |
| getGenerateFanCylinder() | Получает или задает, следует ли генерировать цилиндр в виде вентиля, когда ThetaLength меньше 2PI, иначе модель не будет обрезана. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| Имя | Описание |
| --- | --- |
| setGenerateFanCylinder(value) | Получает или задает, следует ли генерировать цилиндр в виде вентиля, когда ThetaLength меньше 2PI, иначе модель не будет обрезана. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| Имя | Описание |
| --- | --- |
| getShearBottom() | Получает или задает преобразование сдвига нижней стороны, вектор хранит значение сдвига (x-axis, z-axis), измеренное в радианах, значение по умолчанию — (0, 0). |

 **Result:**



---


### setShearBottom{#setShearBottom}

| Имя | Описание |
| --- | --- |
| setShearBottom(value) | Получает или задает преобразование сдвига нижней стороны, вектор хранит значение сдвига (x-axis, z-axis), измеренное в радианах, значение по умолчанию — (0, 0). |

 **Result:**



---


### getShearTop{#getShearTop}

| Имя | Описание |
| --- | --- |
| getShearTop() | Получает или задает преобразование сдвига верхней стороны, вектор хранит значение сдвига (x-axis, z-axis), измеренное в радианах, значение по умолчанию — (0, 0). |

 **Result:**



---


### setShearTop{#setShearTop}

| Имя | Описание |
| --- | --- |
| setShearTop(value) | Получает или задает преобразование сдвига верхней стороны, вектор хранит значение сдвига (x-axis, z-axis), измеренное в радианах, значение по умолчанию — (0, 0). |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| Имя | Описание |
| --- | --- |
| getRadiusTop() | Получает или задает радиус верхней крышки цилиндра. Радиус верхней крышки. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| Имя | Описание |
| --- | --- |
| setRadiusTop(value) | Получает или задает радиус верхней крышки цилиндра. Радиус верхней крышки. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| Имя | Описание |
| --- | --- |
| getRadiusBottom() | Получает или задает радиус нижней крышки цилиндра. Радиус нижней крышки. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| Имя | Описание |
| --- | --- |
| setRadiusBottom(value) | Получает или задает радиус нижней крышки цилиндра. Радиус нижней крышки. |

 **Result:**



---


### getHeight{#getHeight}

| Имя | Описание |
| --- | --- |
| getHeight() | Получает или задает высоту цилиндра. Высота. |

 **Result:**



---


### setHeight{#setHeight}

| Имя | Описание |
| --- | --- |
| setHeight(value) | Получает или задает высоту цилиндра. Высота. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| Имя | Описание |
| --- | --- |
| getRadialSegments() | Получает или задает радиальные сегменты. Радиальные сегменты. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| Имя | Описание |
| --- | --- |
| setRadialSegments(value) | Получает или задает радиальные сегменты. Радиальные сегменты. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Имя | Описание |
| --- | --- |
| getHeightSegments() | Получает или задает сегменты высоты. Сегменты высоты. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Имя | Описание |
| --- | --- |
| setHeightSegments(value) | Получает или задает сегменты высоты. Сегменты высоты. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| Имя | Описание |
| --- | --- |
| getOpenEnded() | Получает или задает значение, указывающее, является ли этот Cylinder открытым. Значение по умолчанию — false. true, если открыт; иначе существуют верхняя/нижняя крышки. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| Имя | Описание |
| --- | --- |
| setOpenEnded(value) | Получает или задает значение, указывающее, является ли этот Cylinder открытым. Значение по умолчанию — false. true, если открыт; иначе существуют верхняя/нижняя крышки. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| Имя | Описание |
| --- | --- |
| getThetaStart() | Получает или задает начальное значение theta. Значение по умолчанию — 0. Начальное значение theta. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| Имя | Описание |
| --- | --- |
| setThetaStart(value) | Получает или задает начальное значение theta. Значение по умолчанию — 0. Начальное значение theta. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| Имя | Описание |
| --- | --- |
| getThetaLength() | Получает или задает длину theta. Значение по умолчанию — 2π. Длина theta. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| Имя | Описание |
| --- | --- |
| setThetaLength(value) | Получает или задает длину theta. Значение по умолчанию — 2π. Длина theta. |

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


### toMesh{#toMesh}

| Имя | Описание |
| --- | --- |
| toMesh() | Преобразовать текущий объект в сетку |

 **Result:**
Сетка


---


### getBoundingBox{#getBoundingBox}

| Имя | Описание |
| --- | --- |
| getBoundingBox() | Получает ограничивающий прямоугольник текущей сущности в её системе координат объектного пространства. |

 **Result:**
Сетка


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



