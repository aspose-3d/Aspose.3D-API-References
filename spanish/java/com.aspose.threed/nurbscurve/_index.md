---
title: NurbsCurve
second_title: Referencia de API de Aspose.3D para Java
description: La curva NURBS es una curva representada por NURBSNon-uniform rational basis spline  Una curva NURBS se define por su  un conjunto de ponderados  y un  El componente w en el punto de control se usa como peso de los puntos de control, sea lo que sea, un  o
type: docs
weight: 112
url: /es/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Constructores

| Constructor | Descripción |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | Inicializa una nueva instancia de la clase [NurbsCurve](../../com.aspose.threed/nurbscurve). |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | Inicializa una nueva instancia de la clase [NurbsCurve](../../com.aspose.threed/nurbscurve). |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | Evaluar la curva NURBS |
| [evaluate(int steps)](#evaluate-int-) | Evaluar la curva NURBS |
| [evaluateAt(double u)](#evaluateAt-double-) | Evaluar el punto de la curva en la posición especificada |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getBoundingBox()](#getBoundingBox--) | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtiene el color de la línea, el valor predeterminado es blanco(1, 1, 1) |
| [getControlPoints()](#getControlPoints--) | Obtiene todos los puntos de control |
| [getCurveType()](#getCurveType--) | Obtiene el tipo de la curva. |
| [getDegree()](#getDegree--) | Obtiene el grado de una curva NURBS, el grado se define como Orden - 1 |
| [getDimension()](#getDimension--) | Obtiene la dimensión de la curva. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [getExcluded()](#getExcluded--) | Obtiene si se debe excluir esta entidad durante la exportación. |
| [getKnotVectors()](#getKnotVectors--) | Obtiene el vector de nudos, es una secuencia de valores de parámetros que determina dónde y cómo los puntos de control afectan a la curva NURBS. |
| [getMultiplicity()](#getMultiplicity--) | Obtiene la multiplicidad. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getOrder()](#getOrder--) | Obtiene el orden de una curva NURBS, define la cantidad de puntos de control cercanos que influyen en cualquier punto de la curva. |
| [getParentNode()](#getParentNode--) | Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [getParentNodes()](#getParentNodes--) | Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getRational()](#getRational--) | Obtiene si es racional, este valor indica si este [NurbsCurve](../../com.aspose.threed/nurbscurve) es una spline racional o una spline no racional. |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Establece el color de la línea, el valor predeterminado es blanco(1, 1, 1) |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | Establece el tipo de la curva. |
| [setDegree(int value)](#setDegree-int-) | Establece el grado de una curva NURBS, el grado se define como Orden - 1 |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | Establece la dimensión de la curva. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Establece si se debe excluir esta entidad durante la exportación. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setOrder(int value)](#setOrder-int-) | Establece el orden de una curva NURBS, define la cantidad de puntos de control cercanos que influyen en cualquier punto de la curva. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setRational(boolean value)](#setRational-boolean-) | Establece si es racional, este valor indica si este [NurbsCurve](../../com.aspose.threed/nurbscurve) es una spline racional o una spline no racional. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


Inicializa una nueva instancia de la clase [NurbsCurve](../../com.aspose.threed/nurbscurve).

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


Inicializa una nueva instancia de la clase [NurbsCurve](../../com.aspose.threed/nurbscurve).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


Evaluar la curva NURBS

**Returns:**
com.aspose.threed.Vector4[] - Puntos en la curva
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


Evaluar la curva NURBS

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pasos | int | La frecuencia de evaluación entre dos nudos vecinos, el valor predeterminado es 20 |

**Returns:**
com.aspose.threed.Vector4[] - Puntos en la curva
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


Evaluar el punto de la curva en la posición especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| u | double | La posición en la curva, entre 0 y 1 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Busca la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyName | java.lang.String | Nombre de la propiedad. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Obtiene el color de la línea, el valor predeterminado es blanco(1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Obtiene todos los puntos de control

**Returns:**
java.util.List<com.aspose.threed.Vector4> - todos los puntos de control
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


Obtiene el tipo de la curva.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Obtiene el grado de una curva NURBS, el grado se define como Orden - 1

**Returns:**
int - el grado de una curva NURBS, el grado se define como Orden - 1
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


Obtiene la dimensión de la curva.

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Obtiene la clave del renderizador de entidad registrado en el renderizador

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Obtiene si se debe excluir esta entidad durante la exportación.

**Returns:**
boolean - si se debe excluir esta entidad durante la exportación.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Obtiene el vector de nudos, es una secuencia de valores de parámetros que determina dónde y cómo los puntos de control afectan a la curva NURBS.

**Returns:**
java.util.List<java.lang.Double> - el vector de nudos, es una secuencia de valores de parámetros que determina dónde y cómo los puntos de control afectan a la curva NURBS.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Obtiene la multiplicidad.

**Returns:**
java.util.List<java.lang.Integer> - la multiplicidad.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Obtiene el orden de una curva NURBS, define la cantidad de puntos de control cercanos que influyen en cualquier punto de la curva.

**Returns:**
int - el orden de una curva NURBS, define el número de puntos de control cercanos que influyen en cualquier punto de la curva.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para instanciación de geometría
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtiene la colección de todas las propiedades.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtiene el valor de la propiedad especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Nombre de la propiedad |

**Returns:**
java.lang.Object - El valor de la propiedad encontrada
### getRational() {#getRational--}
```
public boolean getRational()
```


Obtiene si es racional, este valor indica si este [NurbsCurve](../../com.aspose.threed/nurbscurve) es una spline racional o una spline no racional. La B-spline no racional es un caso especial de B-splines racionales.

**Returns:**
boolean - indica si es racional, este valor indica si este [NurbsCurve](../../com.aspose.threed/nurbscurve) es una spline racional o una spline no racional. La B-spline no racional es un caso especial de B-splines racionales.
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtiene la escena a la que pertenece este objeto.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
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


Elimina una propiedad dinámica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Qué propiedad eliminar |

**Returns:**
boolean - verdadero si la propiedad se elimina correctamente
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Elimina la propiedad especificada identificada por nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Qué propiedad eliminar |

**Returns:**
boolean - verdadero si la propiedad se elimina correctamente
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Establece el color de la línea, el valor predeterminado es blanco(1, 1, 1)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


Establece el tipo de la curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nuevo valor |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Establece el grado de una curva NURBS, el grado se define como Orden - 1

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


Establece la dimensión de la curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | Nuevo valor **Remarks:** Para una curva [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL), el componente z en el punto de control no se usa. |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Establece si se debe excluir esta entidad durante la exportación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Establece el orden de una curva NURBS, define la cantidad de puntos de control cercanos que influyen en cualquier punto de la curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuevo valor |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Establece el valor de la propiedad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Nombre de la propiedad |
| valor | java.lang.Object | El valor de la propiedad |

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


Establece si es racional, este valor indica si este [NurbsCurve](../../com.aspose.threed/nurbscurve) es una spline racional o una spline no racional. La B-spline no racional es un caso especial de B-splines racionales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

