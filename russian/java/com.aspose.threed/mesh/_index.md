---
title: Сетка
second_title: Справочник API Aspose.3D для Java
description: Сетка состоит из множества n-угольных полигонов.
type: docs
weight: 102
url: /ru/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

Сетка состоит из множества n-угольных полигонов. **Пример:** Чтобы добавить полигон в сетку:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Перебрать все полигоны в сетке:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Mesh()](#Mesh--) | Инициализирует новый экземпляр класса [Mesh](../../com.aspose.threed/mesh). |
| [Mesh(String name)](#Mesh-java.lang.String-) | Инициализирует новый экземпляр класса [Mesh](../../com.aspose.threed/mesh). |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Получает все деформаторы с указанными типами деформаторов |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Добавьте новую контрольную точку в сетку, это более эффективно. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Добавьте новую контрольную точку в сетку, это более эффективно. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Добавляет существующий элемент вершины в текущую геометрию |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Создаёт элемент вершины с указанным типом и добавляет его в геометрию. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Создаёт элемент вершины с указанным типом и добавляет его в геометрию. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Создает [VertexElementUV](../../com.aspose.threed/vertexelementuv) с заданным типом отображения текстуры. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Создает [VertexElementUV](../../com.aspose.threed/vertexelementuv) с заданным типом отображения текстуры. |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | Создать полигон с 3 вершинами (треугольник) |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | Создать полигон с 4 вершинами (четырёхугольник) |
| [createPolygon(int[] indices)](#createPolygon-int---) | Создает новый полигон, все вершины которого определены в `indices`. |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | Создает новый полигон, все вершины которого определены в `indices`. |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Вычислить разность двух сеток |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | Выполнить булеву операцию над двумя сетками |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getBoundingBox()](#getBoundingBox--) | Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства. |
| [getCastShadows()](#getCastShadows--) | Получает, может ли эта геометрия отбрасывать тень |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Получает все контрольные точки |
| [getDeformers()](#getDeformers--) | Получает все деформаторы, связанные с этой геометрией. |
| [getEdges()](#getEdges--) | Получает ребра сетки. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Получает элемент вершины с указанным типом |
| [getEntityRendererKey()](#getEntityRendererKey--) | Получает ключ рендерера сущности, зарегистрированного в рендерере. |
| [getExcluded()](#getExcluded--) | Получает, следует ли исключать эту сущность при экспорте. |
| [getName()](#getName--) | Получает имя. |
| [getParentNode()](#getParentNode--) | Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [getParentNodes()](#getParentNodes--) | Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии. |
| [getPolygonCount()](#getPolygonCount--) | Получает количество полигонов |
| [getPolygonSize(int index)](#getPolygonSize-int-) | Получает количество вершин указанного полигона. |
| [getPolygons()](#getPolygons--) | Получает определение полигонов сетки |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getReceiveShadows()](#getReceiveShadows--) | Получает, может ли эта геометрия принимать тень. |
| [getScene()](#getScene--) | Получает сцену, к которой принадлежит этот объект |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Получает экземпляр [VertexElementUV](../../com.aspose.threed/vertexelementuv) с заданным типом отображения текстуры |
| [getVertexElements()](#getVertexElements--) | Получает все элементы вершин |
| [getVisible()](#getVisible--) | Получает, видима ли геометрия |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Вычислить пересечение двух сеток |
| [isManifold()](#isManifold--) | Проверить, является ли текущая сетка многообразной. |
| [iterator()](#iterator--) | Получает перечислитель для каждого внутреннего полигона. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | Оптимизировать использование памяти сеткой, устраняя дублированные контрольные точки |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | Оптимизировать использование памяти сеткой, устраняя дублированные контрольные точки |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | Оптимизировать использование памяти сеткой, устраняя дублированные контрольные точки |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | Оптимизировать использование памяти сеткой, устраняя дублированные контрольные точки |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | Оптимизировать использование памяти сеткой, устраняя дублированные контрольные точки |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Устанавливает, может ли эта геометрия отбрасывать тень |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Устанавливает, следует ли исключать эту сущность при экспорте. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Устанавливает, может ли эта геометрия принимать тень. |
| [setVisible(boolean value)](#setVisible-boolean-) | Устанавливает, видима ли геометрия |
| [toMesh()](#toMesh--) | Получает экземпляр Mesh из текущего объекта. |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | Возвращает триангулированную сетку |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Вычисляет объединение двух сеток |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Инициализирует новый экземпляр класса [Mesh](../../com.aspose.threed/mesh).

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Инициализирует новый экземпляр класса [Mesh](../../com.aspose.threed/mesh).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Получает все деформаторы с указанными типами деформаторов

**Returns:**
java.util.Collection<T> — коллекция деформеров
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Добавьте новую контрольную точку в сетку, это более эффективно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double | Компонента x контрольной точки |
| y | double | Компонента y контрольной точки |
| z | double | Компонента z контрольной точки |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Добавьте новую контрольную точку в сетку, это более эффективно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double | Компонента x контрольной точки |
| y | double | Компонента y контрольной точки |
| z | double | Компонента z контрольной точки |
| w | double | Компонента w контрольной точки |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Добавляет существующий элемент вершины в текущую геометрию

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | Элемент вершины для добавления |

### clone() {#clone--}
```
public Mesh clone()
```




**Returns:**
[Mesh](../../com.aspose.threed/mesh)
### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


Создаёт элемент вершины с указанным типом и добавляет его в геометрию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Тип элемента вершины |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Создаёт элемент вершины с указанным типом и добавляет его в геометрию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Тип элемента вершины |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Режим отображения по умолчанию |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Режим ссылки по умолчанию |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


Создает [VertexElementUV](../../com.aspose.threed/vertexelementuv) с заданным типом отображения текстуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Какой тип текстурного отображения создать |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


Создает [VertexElementUV](../../com.aspose.threed/vertexelementuv) с заданным типом отображения текстуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Какой тип текстурного отображения создать |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Режим отображения по умолчанию |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Режим ссылки по умолчанию |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


Создать полигон с 3 вершинами (треугольник)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v1 | int | Индекс первой вершины |
| v2 | int | Индекс второй вершины |
|  | v3 | int | Индекс третьей вершины **Пример:** Следующий код показывает, как создать новый полигон с индексами контрольных точек. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


Создать полигон с 4 вершинами (четырёхугольник)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| v1 | int | Индекс первой вершины |
| v2 | int | Индекс второй вершины |
| v3 | int | Индекс третьей вершины |
|  | v4 | int | Индекс четвертой вершины **Пример:** Следующий код показывает, как создать новый полигон с индексами контрольных точек. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


Создает новый полигон со всеми вершинами, определенными в `indices`. Чтобы создать полигон вершина за вершиной, пожалуйста, используйте [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | индексы | int[] | Массив индексов полигонов, каждый индекс указывает на контрольную точку, образующую полигон. **Пример:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


Создает новый полигон со всеми вершинами, определенными в `indices`. Чтобы создать полигон вершина за вершиной, пожалуйста, используйте [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индексы | int[] | Массив индексов полигонов, каждый индекс указывает на контрольную точку, образующую полигон. |
| смещение | int | Смещение первого индекса полигона |
|  | длина | int | Длина индексов **Пример:** Следующий код показывает, как создать новый полигон с индексами контрольных точек. |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


Вычислить разность двух сеток

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Первый меш |
| b | [Mesh](../../com.aspose.threed/mesh) | Второй меш |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


Выполнить булеву операцию над двумя сетками

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Тип булевой операции. |
| a | [Mesh](../../com.aspose.threed/mesh) | Первый меш для операции. |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | Матрица преобразования первого меша |
| b | [Mesh](../../com.aspose.threed/mesh) | Второй меш для операции |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | Матрица преобразования второго меша |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Находит свойство. Оно может быть динамическим свойством (созданным с помощью CreateDynamicProperty/SetProperty) или нативным свойством (определяемым по его имени)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyName | java.lang.String | Имя свойства. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Получает, может ли эта геометрия отбрасывать тень

**Returns:**
boolean - может ли эта геометрия отбрасывать тень
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Получает все контрольные точки

**Returns:**
java.util.List<com.aspose.threed.Vector4> - все контрольные точки
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


Получает все деформаторы, связанные с этой геометрией.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - все деформаторы, связанные с этой геометрией.
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


Получает ребра меша. Ребро является необязательным в меше, поэтому может быть пустым.

**Returns:**
java.util.List<java.lang.Integer> - ребра меша. Ребро является необязательным в меше, поэтому может быть пустым.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


Получает элемент вершины с указанным типом

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | какой тип элемента вершины искать |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Получает ключ рендерера сущности, зарегистрированного в рендерере.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Получает, следует ли исключать эту сущность при экспорте.

**Returns:**
boolean — следует ли исключать эту сущность при экспорте.
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - все родительские узлы, объект может быть привязан к нескольким родительским узлам для инстанцирования геометрии
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


Получает количество полигонов

**Returns:**
int - количество полигонов **Пример:** Следующий код показывает, как получить число полигонов меша.

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


Получает количество вершин указанного полигона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс. |

**Returns:**
int - Размер полигона.
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


Получает определение полигонов сетки

**Returns:**
java.util.List<int[]> - определение полигонов сетки
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Получает коллекцию всех свойств.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Получить значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |

**Returns:**
java.lang.Object - Значение найденного свойства
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Получает, может ли эта геометрия принимать тень.

**Returns:**
boolean - может ли эта геометрия принимать тень.
### getScene() {#getScene--}
```
public Scene getScene()
```


Получает сцену, к которой принадлежит этот объект

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


Получает экземпляр [VertexElementUV](../../com.aspose.threed/vertexelementuv) с заданным типом отображения текстуры

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


Получает все элементы вершин

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - все элементы вершин
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Получает, видима ли геометрия

**Returns:**
boolean - видима ли геометрия
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(Mesh a, Mesh b) {#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh intersect(Mesh a, Mesh b)
```


Вычислить пересечение двух сеток

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Первый меш |
| b | [Mesh](../../com.aspose.threed/mesh) | Второй меш |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


Проверьте, является ли текущая сетка многообразной. Эта функция не будет кэшировать результат расчёта многообразия.

**Returns:**
boolean - true, если сетка является многообразной.
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


Получает перечислитель для каждого внутреннего полигона.

**Returns:**
java.util.Iterator<int[]> - Перечислитель.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### optimize(boolean vertexElements) {#optimize-boolean-}
```
public Mesh optimize(boolean vertexElements)
```


Оптимизировать использование памяти сеткой, устраняя дублированные контрольные точки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vertexElements | boolean | Оптимизировать дублированные данные элементов вершин |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage **Example:** The following code shows how to eliminate duplicated control points from an unoptimized mesh:

```
//Sphere.ToMesh generates 117 control points
  Mesh mesh = (new Sphere()).toMesh();
  //After optimized, there're only 86 control points, polygon indices are also remapped.
  Mesh optimized = mesh.optimize(true);
```
### optimize(boolean vertexElements, float toleranceControlPoint) {#optimize-boolean-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint)
```


Оптимизировать использование памяти сеткой, устраняя дублированные контрольные точки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vertexElements | boolean | Оптимизировать дублированные данные элементов вершин |
| toleranceControlPoint | float | Допуск для контрольной точки, значение по умолчанию 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


Оптимизировать использование памяти сеткой, устраняя дублированные контрольные точки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vertexElements | boolean | Оптимизировать дублированные данные элементов вершин |
| toleranceControlPoint | float | Допуск для контрольной точки, значение по умолчанию 1e-9 |
| toleranceNormal | float | Допуск для нормали/касательной/бинормали, значение по умолчанию 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


Оптимизировать использование памяти сеткой, устраняя дублированные контрольные точки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vertexElements | boolean | Оптимизировать дублированные данные элементов вершин |
| toleranceControlPoint | float | Допуск для контрольной точки, значение по умолчанию 1e-9 |
| toleranceNormal | float | Допуск для нормали/касательной/бинормали, значение по умолчанию 1e-9 |
| toleranceUV | float | Допуск для uv, значение по умолчанию 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


Оптимизировать использование памяти сеткой, устраняя дублированные контрольные точки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vertexElements | boolean | Оптимизировать дублированные данные элементов вершин |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Удаляет динамическое свойство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Удалить указанное свойство, определяемое по имени

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Устанавливает, может ли эта геометрия отбрасывать тень

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Устанавливает, следует ли исключать эту сущность при экспорте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Новое значение |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Устанавливает значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |
| значение | java.lang.Object | Значение свойства |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Устанавливает, может ли эта геометрия принимать тень.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Устанавливает, видима ли геометрия

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Получает экземпляр Mesh из текущего объекта.

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Returns current instance.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangulate() {#triangulate--}
```
public Mesh triangulate()
```


Возвращает триангулированную сетку

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Current mesh if current mesh is already triangulated, otherwise a new triangulated mesh will be calculated and returned **Example:** The following code shows how to triangulate a mesh:

```
//The plane mesh has only one polygon with 4 control points
  var mesh = (new Plane()).ToMesh();
  //After triangulated, the new mesh's rectangle will become 2 triangles.
  var triangulated = mesh.Triangulate();
```
### union(Mesh a, Mesh b) {#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh union(Mesh a, Mesh b)
```


Вычисляет объединение двух сеток

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Первый меш |
| b | [Mesh](../../com.aspose.threed/mesh) | Второй меш |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to union two meshes into one mesh:
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

