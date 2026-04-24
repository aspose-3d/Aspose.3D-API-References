---
title: Трансформ
second_title: Справочник API Aspose.3D для Java
description: Трансформ содержит информацию, позволяющую получать доступ к перемещению/масштабированию/вращению объектов или к матрице трансформации с минимальными затратами. Это используется локальным трансформом.
type: docs
weight: 190
url: /ru/java/com.aspose.threed/transform/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Transform extends A3DObject
```

Трансформ содержит информацию, позволяющую получать доступ к перемещению/масштабированию/вращению объекта или к матрице трансформации с минимальными затратами. Это используется локальным трансформом. **Example:** Следующий код показывает, как изменить трансформ узла:

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | Получает вращение, представленное углами Эйлера, измеренное в градусах |
| [getGeometricRotation()](#getGeometricRotation--) | Получает геометрическое вращение Эйлера (измеряется в градусах). |
| [getGeometricScaling()](#getGeometricScaling--) | Получает геометрическое масштабирование. |
| [getGeometricTranslation()](#getGeometricTranslation--) | Получает геометрический перенос. |
| [getName()](#getName--) | Получает имя. |
| [getPostRotation()](#getPostRotation--) | Получает пост-вращение, представленное в градусах |
| [getPreRotation()](#getPreRotation--) | Получает пре-вращение, представленное в градусах |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [getRotation()](#getRotation--) | Получает вращение, представленное кватернионом. |
| [getRotationOffset()](#getRotationOffset--) | Получает смещение вращения |
| [getRotationPivot()](#getRotationPivot--) | Получает точку вращения |
| [getScaling()](#getScaling--) | Получает масштабирование |
| [getScalingOffset()](#getScalingOffset--) | Получает смещение масштабирования |
| [getScalingPivot()](#getScalingPivot--) | Получает опорную точку масштабирования |
| [getTransformMatrix()](#getTransformMatrix--) | Получает матрицу преобразования. |
| [getTranslation()](#getTranslation--) | Получает трансляцию |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setEulerAngles(Vector3 value)](#setEulerAngles-com.aspose.threed.Vector3-) | Устанавливает вращение, представленное углами Эйлера, измеряемыми в градусах |
| [setEulerAngles(double rx, double ry, double rz)](#setEulerAngles-double-double-double-) | Устанавливает углы Эйлера в градусах текущего преобразования. |
| [setGeometricRotation(Vector3 value)](#setGeometricRotation-com.aspose.threed.Vector3-) | Устанавливает геометрическое вращение Эйлера (измеряемое в градусах). |
| [setGeometricRotation(double rx, double ry, double rz)](#setGeometricRotation-double-double-double-) | Устанавливает геометрическое вращение Эйлера (измеряемое в градусах). |
| [setGeometricScaling(Vector3 value)](#setGeometricScaling-com.aspose.threed.Vector3-) | Устанавливает геометрическое масштабирование. |
| [setGeometricScaling(double sx, double sy, double sz)](#setGeometricScaling-double-double-double-) | Устанавливает геометрическое масштабирование. |
| [setGeometricTranslation(Vector3 value)](#setGeometricTranslation-com.aspose.threed.Vector3-) | Устанавливает геометрический перенос. |
| [setGeometricTranslation(double x, double y, double z)](#setGeometricTranslation-double-double-double-) | Устанавливает геометрический перенос. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setPostRotation(Vector3 value)](#setPostRotation-com.aspose.threed.Vector3-) | Устанавливает пост‑вращение, представленное в градусах |
| [setPostRotation(double rx, double ry, double rz)](#setPostRotation-double-double-double-) | Устанавливает пост‑вращение, представленное в градусах **Example:** |
| [setPreRotation(Vector3 value)](#setPreRotation-com.aspose.threed.Vector3-) | Устанавливает пред‑вращение, представленное в градусах |
| [setPreRotation(double rx, double ry, double rz)](#setPreRotation-double-double-double-) | Устанавливает пред‑вращение, представленное в градусах **Example:** |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [setRotation(Quaternion value)](#setRotation-com.aspose.threed.Quaternion-) | Устанавливает вращение, представленное кватернионом. |
| [setRotation(double rw, double rx, double ry, double rz)](#setRotation-double-double-double-double-) | Устанавливает вращение (как компоненты кватерниона) текущего преобразования. |
| [setRotationOffset(Vector3 value)](#setRotationOffset-com.aspose.threed.Vector3-) | Устанавливает смещение вращения |
| [setRotationPivot(Vector3 value)](#setRotationPivot-com.aspose.threed.Vector3-) | Устанавливает точку вращения |
| [setScale(double sx, double sy, double sz)](#setScale-double-double-double-) | Устанавливает масштаб текущего преобразования. |
| [setScaling(Vector3 value)](#setScaling-com.aspose.threed.Vector3-) | Устанавливает масштабирование |
| [setScalingOffset(Vector3 value)](#setScalingOffset-com.aspose.threed.Vector3-) | Устанавливает смещение масштабирования |
| [setScalingPivot(Vector3 value)](#setScalingPivot-com.aspose.threed.Vector3-) | Устанавливает опорную точку масштабирования |
| [setTransformMatrix(Matrix4 value)](#setTransformMatrix-com.aspose.threed.Matrix4-) | Устанавливает матрицу преобразования. |
| [setTranslation(Vector3 value)](#setTranslation-com.aspose.threed.Vector3-) | Устанавливает перенос |
| [setTranslation(double tx, double ty, double tz)](#setTranslation-double-double-double-) | Устанавливает перенос текущего преобразования. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEulerAngles() {#getEulerAngles--}
```
public Vector3 getEulerAngles()
```


Получает вращение, представленное углами Эйлера, измеренное в градусах

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation represented in Euler angles, measured in degree **Example:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
```
### getGeometricRotation() {#getGeometricRotation--}
```
public Vector3 getGeometricRotation()
```


Получает геометрическое вращение Эйлера (измеряемое в градусах). Геометрическое преобразование влияет только на присоединённые сущности и не затрагивает дочерние узлы. Оно будет объединено как локальное преобразование при экспорте геометрического преобразования в типы файлов, которые его не поддерживают.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.
### getGeometricScaling() {#getGeometricScaling--}
```
public Vector3 getGeometricScaling()
```


Получает геометрическое масштабирование. Геометрическое преобразование влияет только на прикреплённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые его не поддерживают, оно будет объединено как локальное преобразование.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric scaling. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
```
### getGeometricTranslation() {#getGeometricTranslation--}
```
public Vector3 getGeometricTranslation()
```


Получает геометрический перенос. Геометрическое преобразование влияет только на прикреплённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые его не поддерживают, оно будет объединено как локальное преобразование.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric translation. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
```
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getPostRotation() {#getPostRotation--}
```
public Vector3 getPostRotation()
```


Получает пост-вращение, представленное в градусах

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the post-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
```
### getPreRotation() {#getPreRotation--}
```
public Vector3 getPreRotation()
```


Получает пре-вращение, представленное в градусах

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the pre-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
```
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
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


Получает вращение, представленное кватернионом.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - the rotation represented in quaternion. **Example:**

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
```
### getRotationOffset() {#getRotationOffset--}
```
public Vector3 getRotationOffset()
```


Получает смещение вращения

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation offset
### getRotationPivot() {#getRotationPivot--}
```
public Vector3 getRotationPivot()
```


Получает точку вращения

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation pivot
### getScaling() {#getScaling--}
```
public Vector3 getScaling()
```


Получает масштабирование

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling **Example:**

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
```
### getScalingOffset() {#getScalingOffset--}
```
public Vector3 getScalingOffset()
```


Получает смещение масштабирования

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling offset
### getScalingPivot() {#getScalingPivot--}
```
public Vector3 getScalingPivot()
```


Получает опорную точку масштабирования

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling pivot
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


Получает матрицу преобразования.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix. **Remarks:** Assign on this will reset the [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) and [getRotation](../../com.aspose.threed/transform\#getRotation), the [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) and [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) will not be affected. **Example:**

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
```
### getTranslation() {#getTranslation--}
```
public Vector3 getTranslation()
```


Получает трансляцию

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the translation **Example:**

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
```
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
### setEulerAngles(Vector3 value) {#setEulerAngles-com.aspose.threed.Vector3-}
```
public void setEulerAngles(Vector3 value)
```


Устанавливает вращение, представленное углами Эйлера, измеряемыми в градусах

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Новое значение **Пример:** |

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
``` |

### setEulerAngles(double rx, double ry, double rz) {#setEulerAngles-double-double-double-}
```
public Transform setEulerAngles(double rx, double ry, double rz)
```


Устанавливает углы Эйлера в градусах текущего преобразования. **Пример:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(90, 0, 0);
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricRotation(Vector3 value) {#setGeometricRotation-com.aspose.threed.Vector3-}
```
public void setGeometricRotation(Vector3 value)
```


Устанавливает геометрический вращение Эйлера (измеряется в градусах). Геометрическое преобразование влияет только на прикреплённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые его не поддерживают, оно будет объединено как локальное преобразование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setGeometricRotation(double rx, double ry, double rz) {#setGeometricRotation-double-double-double-}
```
public Transform setGeometricRotation(double rx, double ry, double rz)
```


Устанавливает геометрический вращение Эйлера (измеряется в градусах). Геометрическое преобразование влияет только на прикреплённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые его не поддерживают, оно будет объединено как локальное преобразование. **Пример:**

```
Node node = new Node();
     node.getTransform().setGeometricRotation(90, 0, 0);
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricScaling(Vector3 value) {#setGeometricScaling-com.aspose.threed.Vector3-}
```
public void setGeometricScaling(Vector3 value)
```


Устанавливает геометрическое масштабирование. Геометрическое преобразование влияет только на прикреплённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые его не поддерживают, оно будет объединено как локальное преобразование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Новое значение **Пример:** |

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
``` |

### setGeometricScaling(double sx, double sy, double sz) {#setGeometricScaling-double-double-double-}
```
public Transform setGeometricScaling(double sx, double sy, double sz)
```


Устанавливает геометрическое масштабирование. Геометрическое преобразование влияет только на прикреплённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые его не поддерживают, оно будет объединено как локальное преобразование. **Пример:**

```
Node node = new Node();
     node.getTransform().setGeometricScaling(2, 2, 2);
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricTranslation(Vector3 value) {#setGeometricTranslation-com.aspose.threed.Vector3-}
```
public void setGeometricTranslation(Vector3 value)
```


Устанавливает геометрический перенос. Геометрическое преобразование влияет только на прикреплённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые его не поддерживают, оно будет объединено как локальное преобразование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Новое значение **Пример:** |

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
``` |

### setGeometricTranslation(double x, double y, double z) {#setGeometricTranslation-double-double-double-}
```
public Transform setGeometricTranslation(double x, double y, double z)
```


Устанавливает геометрический перенос. Геометрическое преобразование влияет только на прикреплённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые его не поддерживают, оно будет объединено как локальное преобразование. **Пример:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(10, 0, 0);
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setPostRotation(Vector3 value) {#setPostRotation-com.aspose.threed.Vector3-}
```
public void setPostRotation(Vector3 value)
```


Устанавливает пост‑вращение, представленное в градусах

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Новое значение **Пример:** |

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
``` |

### setPostRotation(double rx, double ry, double rz) {#setPostRotation-double-double-double-}
```
public Transform setPostRotation(double rx, double ry, double rz)
```


Устанавливает пост‑вращение, представленное в градусах **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(90, 0, 0);
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setPreRotation(Vector3 value) {#setPreRotation-com.aspose.threed.Vector3-}
```
public void setPreRotation(Vector3 value)
```


Устанавливает пред‑вращение, представленное в градусах

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Новое значение **Пример:** |

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
``` |

### setPreRotation(double rx, double ry, double rz) {#setPreRotation-double-double-double-}
```
public Transform setPreRotation(double rx, double ry, double rz)
```


Устанавливает пред‑вращение, представленное в градусах **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(90, 0, 0);
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

### setRotation(Quaternion value) {#setRotation-com.aspose.threed.Quaternion-}
```
public void setRotation(Quaternion value)
```


Устанавливает вращение, представленное кватернионом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Quaternion](../../com.aspose.threed/quaternion) | Новое значение **Пример:** |

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
``` |

### setRotation(double rw, double rx, double ry, double rz) {#setRotation-double-double-double-double-}
```
public Transform setRotation(double rw, double rx, double ry, double rz)
```


Устанавливает вращение (как компоненты кватерниона) текущего преобразования. **Пример:**

```
Node node = new Node();
     node.getTransform().setRotation(1, 0, 0, 0);
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rw | double |  |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setRotationOffset(Vector3 value) {#setRotationOffset-com.aspose.threed.Vector3-}
```
public void setRotationOffset(Vector3 value)
```


Устанавливает смещение вращения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setRotationPivot(Vector3 value) {#setRotationPivot-com.aspose.threed.Vector3-}
```
public void setRotationPivot(Vector3 value)
```


Устанавливает точку вращения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setScale(double sx, double sy, double sz) {#setScale-double-double-double-}
```
public Transform setScale(double sx, double sy, double sz)
```


Устанавливает масштаб текущего преобразования. **Пример:**

```
Node node = new Node();
     node.getTransform().setScale(2, 2, 2);
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setScaling(Vector3 value) {#setScaling-com.aspose.threed.Vector3-}
```
public void setScaling(Vector3 value)
```


Устанавливает масштабирование

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Новое значение **Пример:** |

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
``` |

### setScalingOffset(Vector3 value) {#setScalingOffset-com.aspose.threed.Vector3-}
```
public void setScalingOffset(Vector3 value)
```


Устанавливает смещение масштабирования

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setScalingPivot(Vector3 value) {#setScalingPivot-com.aspose.threed.Vector3-}
```
public void setScalingPivot(Vector3 value)
```


Устанавливает опорную точку масштабирования

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setTransformMatrix(Matrix4 value) {#setTransformMatrix-com.aspose.threed.Matrix4-}
```
public void setTransformMatrix(Matrix4 value)
```


Устанавливает матрицу преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Matrix4](../../com.aspose.threed/matrix4) | Новое значение **Примечание:** Присвоение этому сбросит [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) и [getRotation](../../com.aspose.threed/transform\#getRotation), а [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) и [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) не будут затронуты. **Пример:** |

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
``` |

### setTranslation(Vector3 value) {#setTranslation-com.aspose.threed.Vector3-}
```
public void setTranslation(Vector3 value)
```


Устанавливает перенос

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Новое значение **Пример:** |

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
``` |

### setTranslation(double tx, double ty, double tz) {#setTranslation-double-double-double-}
```
public Transform setTranslation(double tx, double ty, double tz)
```


Устанавливает перенос текущего преобразования. **Пример:**

```
Node node = new Node();
     node.getTransform().setTranslation(10, 0, 0);
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tx | double |  |
| ty | double |  |
| tz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

