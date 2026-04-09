---
title: Shape
second_title: Aspose.3D for Java API Reference
description: La forma descrive la deformazione su un insieme di punti di controllo, simile al deformatore a cluster in Maya.
type: docs
weight: 171
url: /it/java/com.aspose.threed/shape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)
```
public class Shape extends Geometry
```

La forma descrive la deformazione su un insieme di punti di controllo, simile al deformatore a cluster in Maya. Ad esempio, possiamo aggiungere una forma a una geometria creata. E la forma e la geometria hanno le stesse informazioni topologiche ma posizioni diverse dei punti di controllo. Con quantità variabili di influenza, la geometria produce un effetto di deformazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Shape()](#Shape--) | Inizializza una nuova istanza della classe [Shape](../../com.aspose.threed/shape). |
| [Shape(String name)](#Shape-java.lang.String-) | Inizializza una nuova istanza della classe [Shape](../../com.aspose.threed/shape). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Ottiene tutti i deformatori con i tipi di deformatore specificati |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Aggiunge un elemento vertice esistente alla geometria corrente |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Crea un elemento vertice con il tipo specificato e lo aggiunge alla geometria. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crea un elemento vertice con il tipo specificato e lo aggiunge alla geometria. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con il tipo di mappatura texture fornito. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con il tipo di mappatura texture fornito. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [fromControlPoints(Vector3[] controlPoints)](#fromControlPoints-com.aspose.threed.Vector3...-) | Crea una forma con punti di controllo specificati e indici predefiniti. |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| [getCastShadows()](#getCastShadows--) | Restituisce se questa geometria può proiettare ombra |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Restituisce tutti i punti di controllo |
| [getDeformers()](#getDeformers--) | Restituisce tutti i deformatori associati a questa geometria. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Restituisce un elemento di vertice con il tipo specificato |
| [getEntityRendererKey()](#getEntityRendererKey--) | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questa entità durante l'esportazione. |
| [getIndices()](#getIndices--) | Restituisce gli indici. |
| [getName()](#getName--) | Ottiene il nome. |
| [getParentNode()](#getParentNode--) | Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [getParentNodes()](#getParentNodes--) | Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getReceiveShadows()](#getReceiveShadows--) | Restituisce se questa geometria può ricevere ombra. |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Restituisce un'istanza di [VertexElementUV](../../com.aspose.threed/vertexelementuv) con il tipo di mappatura texture fornito |
| [getVertexElements()](#getVertexElements--) | Restituisce tutti gli elementi di vertice |
| [getVisible()](#getVisible--) | Restituisce se la geometria è visibile |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Imposta se questa geometria può proiettare ombra |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questa entità durante l'esportazione. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Imposta se questa geometria può ricevere ombra. |
| [setVisible(boolean value)](#setVisible-boolean-) | Imposta se la geometria è visibile |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


Inizializza una nuova istanza della classe [Shape](../../com.aspose.threed/shape).

### Shape(String name) {#Shape-java.lang.String-}
```
public Shape(String name)
```


Inizializza una nuova istanza della classe [Shape](../../com.aspose.threed/shape).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Ottiene tutti i deformatori con i tipi di deformatore specificati

**Returns:**
java.util.Collection<T> - Collezione di Deformer
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Aggiunge un elemento vertice esistente alla geometria corrente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | L'elemento vertice da aggiungere |

### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


Crea un elemento vertice con il tipo specificato e lo aggiunge alla geometria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Tipo di elemento vertice |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Crea un elemento vertice con il tipo specificato e lo aggiunge alla geometria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | Tipo di elemento vertice |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Modalità di mappatura predefinita |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Modalità di riferimento predefinita |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con il tipo di mappatura texture fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Quale tipo di mappatura texture creare |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con il tipo di mappatura texture fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Quale tipo di mappatura texture creare |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | Modalità di mappatura predefinita |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | Modalità di riferimento predefinita |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trova la proprietà. Può essere una proprietà dinamica (creata con CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata per nome).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | java.lang.String | Nome della proprietà. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromControlPoints(Vector3[] controlPoints) {#fromControlPoints-com.aspose.threed.Vector3...-}
```
public static Shape fromControlPoints(Vector3[] controlPoints)
```


Crea una forma con punti di controllo specificati e indici predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| controlPoints | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Shape](../../com.aspose.threed/shape)
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto.

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


Restituisce se questa geometria può proiettare ombra

**Returns:**
boolean - se questa geometria può proiettare ombra
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


Restituisce tutti i punti di controllo

**Returns:**
java.util.List<com.aspose.threed.Vector4> - tutti i punti di controllo
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


Restituisce tutti i deformatori associati a questa geometria.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - tutti i deformatori associati a questa geometria.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


Restituisce un elemento di vertice con il tipo specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | qual è il tipo di elemento vertice da trovare |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Ottiene la chiave del renderer dell'entità registrata nel renderer

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Ottiene se escludere questa entità durante l'esportazione.

**Returns:**
boolean - se escludere questa entità durante l'esportazione.
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


Restituisce gli indici.

**Returns:**
java.util.List<java.lang.Integer> - gli indici.
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - tutti i nodi genitore, un'entità può essere collegata a più nodi genitore per l'instanziazione della geometria
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Ottiene la collezione di tutte le proprietà.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Ottieni il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |

**Returns:**
java.lang.Object - Il valore della proprietà trovata
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


Restituisce se questa geometria può ricevere ombra.

**Returns:**
boolean - se questa geometria può ricevere ombra.
### getScene() {#getScene--}
```
public Scene getScene()
```


Ottiene la scena a cui appartiene questo oggetto

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


Restituisce un'istanza di [VertexElementUV](../../com.aspose.threed/vertexelementuv) con il tipo di mappatura texture fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


Restituisce tutti gli elementi di vertice

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - tutti gli elementi dei vertici
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Restituisce se la geometria è visibile

**Returns:**
boolean - se la geometria è visibile
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


Rimuove una proprietà dinamica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Rimuove la proprietà specificata identificata per nome

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Imposta se questa geometria può proiettare ombra

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Imposta se escludere questa entità durante l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuovo valore |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Imposta il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |
| valore | java.lang.Object | Il valore della proprietà |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Imposta se questa geometria può ricevere ombra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Imposta se la geometria è visibile

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

