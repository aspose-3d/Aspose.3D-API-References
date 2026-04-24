---
title: PointCloud
second_title: Referencia de API de Aspose.3D para Java
description: La nube de puntos no contiene información de topología, solo los puntos de control y los elementos de vértice.
type: docs
weight: 132
url: /es/java/com.aspose.threed/pointcloud/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)
```
public class PointCloud extends Geometry
```

La nube de puntos no contiene información de topología, solo los puntos de control y los elementos de vértice.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PointCloud(String name)](#PointCloud-java.lang.String-) | Constructor de [PointCloud](../../com.aspose.threed/pointcloud) |
| [PointCloud()](#PointCloud--) | Constructor de [PointCloud](../../com.aspose.threed/pointcloud) |
## Métodos

| Método | Descripción |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Obtiene todos los deformadores con los tipos de deformador especificados |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Agrega un elemento de vértice existente a la geometría actual |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con el tipo de mapeado de textura dado. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con el tipo de mapeado de textura dado. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [fromGeometry(Geometry g)](#fromGeometry-com.aspose.threed.Geometry-) | Crear una nueva instancia de PointCloud a partir de un objeto de geometría |
| [fromGeometry(Geometry g, int density)](#fromGeometry-com.aspose.threed.Geometry-int-) | Crear una nueva instancia de nube de puntos a partir de un objeto de geometría. |
| [getBoundingBox()](#getBoundingBox--) | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| [getCastShadows()](#getCastShadows--) | Obtiene si esta geometría puede proyectar sombra |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Obtiene todos los puntos de control |
| [getDeformers()](#getDeformers--) | Obtiene todos los deformadores asociados a esta geometría. |
| [getDimension()](#getDimension--) | Si se presenta un valor de dimensión para la nube de puntos, indica una nube de puntos organizada. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Obtiene un elemento de vértice con el tipo especificado |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [getExcluded()](#getExcluded--) | Obtiene si se debe excluir esta entidad durante la exportación. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getParentNode()](#getParentNode--) | Obtiene el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [getParentNodes()](#getParentNodes--) | Obtiene todos los nodos padres; una entidad puede estar adjunta a varios nodos padres para instanciación de geometría. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getReceiveShadows()](#getReceiveShadows--) | Obtiene si esta geometría puede recibir sombra. |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Obtiene una instancia de [VertexElementUV](../../com.aspose.threed/vertexelementuv) con el tipo de mapeado de textura dado |
| [getVertexElements()](#getVertexElements--) | Obtiene todos los elementos de vértice |
| [getVisible()](#getVisible--) | Obtiene si la geometría es visible |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Establece si esta geometría puede proyectar sombra |
| [setDimension(Vector2 value)](#setDimension-com.aspose.threed.Vector2-) | Si se presenta un valor de dimensión para la nube de puntos, indica una nube de puntos organizada. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Establece si se debe excluir esta entidad durante la exportación. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Establece si esta geometría puede recibir sombra. |
| [setVisible(boolean value)](#setVisible-boolean-) | Establece si la geometría es visible |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointCloud(String name) {#PointCloud-java.lang.String-}
```
public PointCloud(String name)
```


Constructor de [PointCloud](../../com.aspose.threed/pointcloud)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre de esta entidad |

### PointCloud() {#PointCloud--}
```
public PointCloud()
```


Constructor de [PointCloud](../../com.aspose.threed/pointcloud)

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Obtiene todos los deformadores con los tipos de deformador especificados

**Returns:**
java.util.Collection<T> - colección Deformer
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Agrega un elemento de vértice existente a la geometría actual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | El elemento de vértice a agregar |

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
### fromGeometry(Geometry g) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static PointCloud fromGeometry(Geometry g)
```


Crear una nueva instancia de PointCloud a partir de un objeto de geometría

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g | [Geometry](../../com.aspose.threed/geometry) |  |

**Returns:**
[PointCloud](../../com.aspose.threed/pointcloud)
### fromGeometry(Geometry g, int density) {#fromGeometry-com.aspose.threed.Geometry-int-}
```
public static PointCloud fromGeometry(Geometry g, int density)
```


Crear una nueva instancia de nube de puntos a partir de un objeto de geometría. La densidad es el número de puntos por triángulo unidad (El triángulo unidad es el triángulo con la mayor superficie de la malla)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g | [Geometry](../../com.aspose.threed/geometry) | Malla u otra instancia de geometría |
| densidad | int | Número de puntos por triángulo unidad |

**Returns:**
[PointCloud](../../com.aspose.threed/pointcloud)
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
### getDimension() {#getDimension--}
```
public Vector2 getDimension()
```


Si se presenta un valor de dimensión para la nube de puntos, indica una nube de puntos organizada. Sin un tamaño especificado, se considera una nube de puntos desorganizada. Una nube de puntos organizada significa que tiene una estructura similar a una imagen.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - If a dimension value is present for the point cloud, it indicates an organized point cloud. Without a specified size, it is considered an unorganized point cloud. Organized point cloud means it has an image-like structure.
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
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Establece si esta geometría puede proyectar sombra

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setDimension(Vector2 value) {#setDimension-com.aspose.threed.Vector2-}
```
public void setDimension(Vector2 value)
```


Si se presenta un valor de dimensión para la nube de puntos, indica una nube de puntos organizada. Sin un tamaño especificado, se considera una nube de puntos desorganizada. Una nube de puntos organizada significa que tiene una estructura similar a una imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuevo valor |

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

