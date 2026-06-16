---
title: Malla
second_title: Referencia de API de Aspose.3D para Java
description: Una malla está compuesta por muchos polígonos de n lados.
type: docs
weight: 102
url: /es/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

Una malla está compuesta por muchos polígonos de n lados. **Example:** Para agregar un polígono en la malla:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Recorra todos los polígonos de la malla:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Mesh()](#Mesh--) | Inicializa una nueva instancia de la clase [Mesh](../../com.aspose.threed/mesh). |
| [Mesh(String name)](#Mesh-java.lang.String-) | Inicializa una nueva instancia de la clase [Mesh](../../com.aspose.threed/mesh). |
## Métodos

| Método | Descripción |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Obtiene todos los deformadores con los tipos de deformador especificados |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Agrega un nuevo punto de control a la malla, esto es más eficiente. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Agrega un nuevo punto de control a la malla, esto es más eficiente. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Agrega un elemento de vértice existente a la geometría actual |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con el tipo de mapeado de textura dado. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con el tipo de mapeado de textura dado. |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | Crea un polígono con 3 vértices(triángulo) |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | Crea un polígono con 4 vértices(cuadrilátero) |
| [createPolygon(int[] indices)](#createPolygon-int---) | Crea un nuevo polígono con todos los vértices definidos en `indices`. |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | Crea un nuevo polígono con todos los vértices definidos en `indices`. |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Calcula la diferencia de dos mallas |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | Realiza una operación booleana en dos mallas |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [getBoundingBox()](#getBoundingBox--) | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| [getCastShadows()](#getCastShadows--) | Obtiene si esta geometría puede proyectar sombra |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Obtiene todos los puntos de control |
| [getDeformers()](#getDeformers--) | Obtiene todos los deformadores asociados a esta geometría. |
| [getEdges()](#getEdges--) | Obtiene los bordes de la malla. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Obtiene un elemento de vértice con el tipo especificado |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [getExcluded()](#getExcluded--) | Obtiene si se debe excluir esta entidad durante la exportación. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getParentNode()](#getParentNode--) | Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [getParentNodes()](#getParentNodes--) | Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría. |
| [getPolygonCount()](#getPolygonCount--) | Obtiene el recuento de polígonos |
| [getPolygonSize(int index)](#getPolygonSize-int-) | Obtiene el número de vértices del polígono especificado. |
| [getPolygons()](#getPolygons--) | Obtiene la definición de polígonos de la malla |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getReceiveShadows()](#getReceiveShadows--) | Obtiene si esta geometría puede recibir sombra. |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Obtiene una instancia de [VertexElementUV](../../com.aspose.threed/vertexelementuv) con el tipo de mapeado de textura dado |
| [getVertexElements()](#getVertexElements--) | Obtiene todos los elementos de vértice |
| [getVisible()](#getVisible--) | Obtiene si la geometría es visible |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Calcula la intersección de dos mallas |
| [isManifold()](#isManifold--) | Comprueba si la malla actual es una malla manífolda. |
| [iterator()](#iterator--) | Obtiene el enumerador para cada polígono interno. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | Optimiza el uso de memoria de la malla eliminando puntos de control duplicados |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | Optimiza el uso de memoria de la malla eliminando puntos de control duplicados |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | Optimiza el uso de memoria de la malla eliminando puntos de control duplicados |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | Optimiza el uso de memoria de la malla eliminando puntos de control duplicados |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | Optimiza el uso de memoria de la malla eliminando puntos de control duplicados |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Establece si esta geometría puede proyectar sombra |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Establece si se debe excluir esta entidad durante la exportación. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Establece si esta geometría puede recibir sombra. |
| [setVisible(boolean value)](#setVisible-boolean-) | Establece si la geometría es visible |
| [toMesh()](#toMesh--) | Obtiene la instancia Mesh de la entidad actual. |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | Devuelve malla triangulada |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Calcula la unión de dos mallas |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Inicializa una nueva instancia de la clase [Mesh](../../com.aspose.threed/mesh).

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Inicializa una nueva instancia de la clase [Mesh](../../com.aspose.threed/mesh).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Obtiene todos los deformadores con los tipos de deformador especificados

**Returns:**
java.util.Collection<T> - colección Deformer
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Agrega un nuevo punto de control a la malla, esto es más eficiente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | double | El componente x del punto de control |
| y | double | El componente y del punto de control |
| z | double | El componente z del punto de control |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Agrega un nuevo punto de control a la malla, esto es más eficiente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | double | El componente x del punto de control |
| y | double | El componente y del punto de control |
| z | double | El componente z del punto de control |
| w | double | El componente w del punto de control |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Agrega un elemento de vértice existente a la geometría actual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | El elemento de vértice a agregar |

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


Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Tipo de elemento de vértice |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Tipo de elemento de vértice |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Modo de mapeo predeterminado |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Modo de referencia predeterminado |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con el tipo de mapeado de textura dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Qué tipo de mapeo de textura crear |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con el tipo de mapeado de textura dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Qué tipo de mapeo de textura crear |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Modo de mapeo predeterminado |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Modo de referencia predeterminado |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


Crea un polígono con 3 vértices(triángulo)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v1 | int | Índice del primer vértice |
| v2 | int | Índice del segundo vértice |
|  | v3 | int | Índice del tercer vértice **Ejemplo:** El siguiente código muestra cómo crear un nuevo polígono con los índices del punto de control. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


Crea un polígono con 4 vértices(cuadrilátero)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v1 | int | Índice del primer vértice |
| v2 | int | Índice del segundo vértice |
| v3 | int | Índice del tercer vértice |
|  | v4 | int | Índice del cuarto vértice **Ejemplo:** El siguiente código muestra cómo crear un nuevo polígono con los índices del punto de control. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


Crea un nuevo polígono con todos los vértices definidos en `indices`. Para crear el polígono vértice a vértice, por favor use [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | índices | int[] | Matriz de los índices del polígono, cada índice apunta a un punto de control que forma el polígono. **Ejemplo:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


Crea un nuevo polígono con todos los vértices definidos en `indices`. Para crear el polígono vértice a vértice, por favor use [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índices | int[] | Matriz de los índices del polígono, cada índice apunta a un punto de control que forma el polígono. |
| desplazamiento | int | El desplazamiento del primer índice del polígono |
|  | longitud | int | La longitud de los índices **Ejemplo:** El siguiente código muestra cómo crear un nuevo polígono con los índices del punto de control. |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


Calcula la diferencia de dos mallas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Primera malla |
| b | [Mesh](../../com.aspose.threed/mesh) | Segunda malla |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


Realiza una operación booleana en dos mallas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | El tipo de operación Boolean. |
| a | [Mesh](../../com.aspose.threed/mesh) | Primera malla a operar. |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | Matriz de transformación de la primera malla |
| b | [Mesh](../../com.aspose.threed/mesh) | Segunda malla a operar |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | Matriz de transformación de la segunda malla |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Obtiene si esta geometría puede proyectar sombra

**Returns:**
boolean - si esta geometría puede proyectar sombra
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


Obtiene todos los puntos de control

**Returns:**
java.util.List<com.aspose.threed.Vector4> - todos los puntos de control
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


Obtiene todos los deformadores asociados a esta geometría.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - todos los deformadores asociados a esta geometría.
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


Obtiene los bordes de la malla. El borde es opcional en la malla, por lo que puede estar vacío.

**Returns:**
java.util.List<java.lang.Integer> - bordes de la malla. El borde es opcional en la malla, por lo que puede estar vacío.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


Obtiene un elemento de vértice con el tipo especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | qué tipo de elemento de vértice buscar |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Obtiene la clave del renderizador de entidad registrado en el renderizador

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Obtiene si se debe excluir esta entidad durante la exportación.

**Returns:**
boolean - si se debe excluir esta entidad durante la exportación.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
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
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


Obtiene el recuento de polígonos

**Returns:**
int - el recuento de polígonos **Ejemplo:** El siguiente código muestra cómo obtener el número de polígonos de la malla.

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


Obtiene el número de vértices del polígono especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Índice. |

**Returns:**
int - El tamaño del polígono.
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


Obtiene la definición de polígonos de la malla

**Returns:**
java.util.List<int[]> - la definición de polígonos de la malla
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
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Obtiene si esta geometría puede recibir sombra.

**Returns:**
boolean - si esta geometría puede recibir sombra.
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtiene la escena a la que pertenece este objeto.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


Obtiene una instancia de [VertexElementUV](../../com.aspose.threed/vertexelementuv) con el tipo de mapeado de textura dado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


Obtiene todos los elementos de vértice

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - todos los elementos de vértice
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Obtiene si la geometría es visible

**Returns:**
boolean - si la geometría es visible
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


Calcula la intersección de dos mallas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Primera malla |
| b | [Mesh](../../com.aspose.threed/mesh) | Segunda malla |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


Verifique si la malla actual es una malla manifold. Esta función no almacenará en caché el resultado del cálculo manifold.

**Returns:**
boolean - verdadero si la malla es una malla manifold.
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


Obtiene el enumerador para cada polígono interno.

**Returns:**
java.util.Iterator<int[]> - El enumerador.
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


Optimiza el uso de memoria de la malla eliminando puntos de control duplicados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vertexElements | boolean | Optimizar datos de elementos de vértice duplicados |

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


Optimiza el uso de memoria de la malla eliminando puntos de control duplicados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vertexElements | boolean | Optimizar datos de elementos de vértice duplicados |
| toleranceControlPoint | float | La tolerancia para el punto de control, el valor predeterminado es 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


Optimiza el uso de memoria de la malla eliminando puntos de control duplicados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vertexElements | boolean | Optimizar datos de elementos de vértice duplicados |
| toleranceControlPoint | float | La tolerancia para el punto de control, el valor predeterminado es 1e-9 |
| toleranceNormal | float | La tolerancia para normal/tangente/binormal, el valor predeterminado es 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


Optimiza el uso de memoria de la malla eliminando puntos de control duplicados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vertexElements | boolean | Optimizar datos de elementos de vértice duplicados |
| toleranceControlPoint | float | La tolerancia para el punto de control, el valor predeterminado es 1e-9 |
| toleranceNormal | float | La tolerancia para normal/tangente/binormal, el valor predeterminado es 1e-9 |
| toleranceUV | float | La tolerancia para uv, el valor predeterminado es 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


Optimiza el uso de memoria de la malla eliminando puntos de control duplicados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vertexElements | boolean | Optimizar datos de elementos de vértice duplicados |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Establece si esta geometría puede proyectar sombra

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Establece si esta geometría puede recibir sombra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Establece si la geometría es visible

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Obtiene la instancia Mesh de la entidad actual.

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


Devuelve malla triangulada

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


Calcula la unión de dos mallas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Primera malla |
| b | [Mesh](../../com.aspose.threed/mesh) | Segunda malla |

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

