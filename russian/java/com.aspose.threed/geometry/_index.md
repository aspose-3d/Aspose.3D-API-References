---
title: Geometry
second_title: Справочник API Aspose.3D для Java
description: Базовый класс всех визуализируемых геометрических объектов, таких как    и т.д.
type: docs
weight: 71
url: /ru/java/com.aspose.threed/geometry/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)
```
public class Geometry extends Entity
```

Базовый класс всех визуализируемых геометрических объектов (например, [Mesh](../../com.aspose.threed/mesh), [NurbsSurface](../../com.aspose.threed/nurbssurface), [Patch](../../com.aspose.threed/patch) и т.д.).

Базовый класс [Geometry](../../com.aspose.threed/geometry) поддерживает:

 *  **Control point management**, control points defines the base 3D spatial structure of the geometry, different geometric types has different way to define concrete 3D models.
 *  **Vertex element definition**, vertex elements applies extra information like normals/uv coordinates/vertex colors to the geometry, see [VertexElement](../../com.aspose.threed/vertexelement) for more details.
 *  **Object deforming**, [Deformer](../../com.aspose.threed/deformer) can be bonded to animate geometry's shape.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Geometry(String name)](#Geometry-java.lang.String-) | Инициализирует новый экземпляр класса [Geometry](../../com.aspose.threed/geometry). |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Получает все деформаторы с указанными типами деформаторов |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Добавляет существующий элемент вершины в текущую геометрию |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Создаёт элемент вершины с указанным типом и добавляет его в геометрию. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Создаёт элемент вершины с указанным типом и добавляет его в геометрию. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Создает [VertexElementUV](../../com.aspose.threed/vertexelementuv) с заданным типом отображения текстуры. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Создает [VertexElementUV](../../com.aspose.threed/vertexelementuv) с заданным типом отображения текстуры. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getBoundingBox()](#getBoundingBox--) | Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства. |
| [getCastShadows()](#getCastShadows--) | Получает, может ли эта геометрия отбрасывать тень |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Получает все контрольные точки |
| [getDeformers()](#getDeformers--) | Получает все деформаторы, связанные с этой геометрией. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Получает элемент вершины с указанным типом |
| [getEntityRendererKey()](#getEntityRendererKey--) | Получает ключ рендерера сущности, зарегистрированного в рендерере. |
| [getExcluded()](#getExcluded--) | Получает, следует ли исключать эту сущность при экспорте. |
| [getName()](#getName--) | Получает имя. |
| [getParentNode()](#getParentNode--) | Получает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [getParentNodes()](#getParentNodes--) | Получает все родительские узлы; сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии. |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getReceiveShadows()](#getReceiveShadows--) | Получает, может ли эта геометрия принимать тень. |
| [getScene()](#getScene--) | Получает сцену, к которой принадлежит этот объект |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Получает экземпляр [VertexElementUV](../../com.aspose.threed/vertexelementuv) с заданным типом отображения текстуры |
| [getVertexElements()](#getVertexElements--) | Получает все элементы вершин |
| [getVisible()](#getVisible--) | Получает, видима ли геометрия |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Устанавливает, может ли эта геометрия отбрасывать тень |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Устанавливает, следует ли исключать эту сущность при экспорте. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Устанавливает первый родительский узел; если установить первый родительский узел, эта сущность будет отсоединена от других родительских узлов. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Устанавливает, может ли эта геометрия принимать тень. |
| [setVisible(boolean value)](#setVisible-boolean-) | Устанавливает, видима ли геометрия |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geometry(String name) {#Geometry-java.lang.String-}
```
public Geometry(String name)
```


Инициализирует новый экземпляр класса [Geometry](../../com.aspose.threed/geometry).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Получает все деформаторы с указанными типами деформаторов

**Returns:**
java.util.Collection<T> — коллекция деформеров
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Добавляет существующий элемент вершины в текущую геометрию

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | Элемент вершины для добавления |

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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

