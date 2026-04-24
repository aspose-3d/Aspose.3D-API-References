---
title: Mesh
second_title: Aspose.3D for Java API Reference
description: Una mesh è composta da molti poligoni a n lati.
type: docs
weight: 102
url: /it/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

Una mesh è composta da molti poligoni a n lati. **Example:** Per aggiungere un poligono nella mesh:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Scorri tutti i poligoni nella mesh:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Mesh()](#Mesh--) | Inizializza una nuova istanza della classe [Mesh](../../com.aspose.threed/mesh). |
| [Mesh(String name)](#Mesh-java.lang.String-) | Inizializza una nuova istanza della classe [Mesh](../../com.aspose.threed/mesh). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Ottiene tutti i deformatori con i tipi di deformatore specificati |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Aggiungi un nuovo punto di controllo alla mesh, è più efficiente. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Aggiungi un nuovo punto di controllo alla mesh, è più efficiente. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Aggiunge un elemento vertice esistente alla geometria corrente |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Crea un elemento vertice con il tipo specificato e lo aggiunge alla geometria. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crea un elemento vertice con il tipo specificato e lo aggiunge alla geometria. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con il tipo di mappatura texture fornito. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Crea un [VertexElementUV](../../com.aspose.threed/vertexelementuv) con il tipo di mappatura texture fornito. |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | Crea un poligono con 3 vertici(triangolo) |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | Crea un poligono con 4 vertici(quad) |
| [createPolygon(int[] indices)](#createPolygon-int---) | Crea un nuovo poligono con tutti i vertici definiti in `indices`. |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | Crea un nuovo poligono con tutti i vertici definiti in `indices`. |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Calcola la differenza tra due mesh |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | Esegui un'operazione booleana su due mesh |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| [getCastShadows()](#getCastShadows--) | Restituisce se questa geometria può proiettare ombra |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | Restituisce tutti i punti di controllo |
| [getDeformers()](#getDeformers--) | Restituisce tutti i deformatori associati a questa geometria. |
| [getEdges()](#getEdges--) | Restituisce i bordi della Mesh. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | Restituisce un elemento di vertice con il tipo specificato |
| [getEntityRendererKey()](#getEntityRendererKey--) | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questa entità durante l'esportazione. |
| [getName()](#getName--) | Ottiene il nome. |
| [getParentNode()](#getParentNode--) | Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [getParentNodes()](#getParentNodes--) | Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria. |
| [getPolygonCount()](#getPolygonCount--) | Restituisce il conteggio dei poligoni |
| [getPolygonSize(int index)](#getPolygonSize-int-) | Restituisce il conteggio dei vertici del poligono specificato. |
| [getPolygons()](#getPolygons--) | Restituisce la definizione dei poligoni della mesh |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getReceiveShadows()](#getReceiveShadows--) | Restituisce se questa geometria può ricevere ombra. |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | Restituisce un'istanza di [VertexElementUV](../../com.aspose.threed/vertexelementuv) con il tipo di mappatura texture fornito |
| [getVertexElements()](#getVertexElements--) | Restituisce tutti gli elementi di vertice |
| [getVisible()](#getVisible--) | Restituisce se la geometria è visibile |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Calcola l'intersezione di due mesh |
| [isManifold()](#isManifold--) | Verifica se la mesh corrente è una mesh manifold. |
| [iterator()](#iterator--) | Restituisce l'enumeratore per ciascun poligono interno. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Imposta se questa geometria può proiettare ombra |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questa entità durante l'esportazione. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Imposta se questa geometria può ricevere ombra. |
| [setVisible(boolean value)](#setVisible-boolean-) | Imposta se la geometria è visibile |
| [toMesh()](#toMesh--) | Ottiene l'istanza Mesh dall'entità corrente. |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | Restituisce la mesh triangolata |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | Calcola l'unione di due mesh |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Inizializza una nuova istanza della classe [Mesh](../../com.aspose.threed/mesh).

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Inizializza una nuova istanza della classe [Mesh](../../com.aspose.threed/mesh).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Ottiene tutti i deformatori con i tipi di deformatore specificati

**Returns:**
java.util.Collection<T> - Collezione di Deformer
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Aggiungi un nuovo punto di controllo alla mesh, è più efficiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | double | La componente x del punto di controllo |
| y | double | La componente y del punto di controllo |
| z | double | La componente z del punto di controllo |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Aggiungi un nuovo punto di controllo alla mesh, è più efficiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | double | La componente x del punto di controllo |
| y | double | La componente y del punto di controllo |
| z | double | La componente z del punto di controllo |
| w | double | La componente w del punto di controllo |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Aggiunge un elemento vertice esistente alla geometria corrente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | L'elemento vertice da aggiungere |

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
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


Crea un poligono con 3 vertici(triangolo)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v1 | int | Indice del primo vertice |
| v2 | int | Indice del secondo vertice |
|  | v3 | int | Indice del terzo vertice **Esempio:** Il codice seguente mostra come creare un nuovo poligono con gli indici del punto di controllo. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


Crea un poligono con 4 vertici(quad)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v1 | int | Indice del primo vertice |
| v2 | int | Indice del secondo vertice |
| v3 | int | Indice del terzo vertice |
|  | v4 | int | Indice del quarto vertice **Esempio:** Il codice seguente mostra come creare un nuovo poligono con gli indici del punto di controllo. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


Crea un nuovo poligono con tutti i vertici definiti in `indices`. Per creare il poligono vertice per vertice, si prega di utilizzare [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | indici | int[] | Array degli indici del poligono, ogni indice punta a un punto di controllo che forma il poligono. **Esempio:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


Crea un nuovo poligono con tutti i vertici definiti in `indices`. Per creare il poligono vertice per vertice, si prega di utilizzare [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indici | int[] | Array degli indici del poligono, ogni indice punta a un punto di controllo che forma il poligono. |
| offset | int | L'offset del primo indice del poligono |
|  | lunghezza | int | La lunghezza degli indici **Esempio:** Il codice seguente mostra come creare un nuovo poligono con gli indici dei punti di controllo. |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


Calcola la differenza tra due mesh

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Prima mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Seconda mesh |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


Esegui un'operazione booleana su due mesh

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Il tipo di operazione Boolean. |
| a | [Mesh](../../com.aspose.threed/mesh) | Prima mesh su cui operare. |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | Matrice di trasformazione della prima mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Seconda mesh su cui operare |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | Matrice di trasformazione della seconda mesh |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
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
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


Ottiene i bordi della Mesh. Il bordo è opzionale nella mesh, quindi può essere vuoto.

**Returns:**
java.util.List<java.lang.Integer> - bordi della Mesh. Il bordo è opzionale nella mesh, quindi può essere vuoto.
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
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


Restituisce il conteggio dei poligoni

**Returns:**
int - il conteggio dei poligoni **Esempio:** Il codice seguente mostra come ottenere il numero di poligoni della mesh.

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


Restituisce il conteggio dei vertici del poligono specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | Indice. |

**Returns:**
int - La dimensione del poligono.
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


Restituisce la definizione dei poligoni della mesh

**Returns:**
java.util.List<int[]> - la definizione dei poligoni della mesh
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
### intersect(Mesh a, Mesh b) {#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh intersect(Mesh a, Mesh b)
```


Calcola l'intersezione di due mesh

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Prima mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Seconda mesh |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


Verifica se la mesh corrente è una mesh manifold. Questa funzione non memorizzerà nella cache il risultato del calcolo manifold.

**Returns:**
boolean - vero se la mesh è una mesh manifold.
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


Restituisce l'enumeratore per ciascun poligono interno.

**Returns:**
java.util.Iterator<int[]> - L'enumeratore.
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


Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vertexElements | boolean | Ottimizza i dati degli elementi del vertice duplicati |

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


Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vertexElements | boolean | Ottimizza i dati degli elementi del vertice duplicati |
| toleranceControlPoint | float | La tolleranza per il punto di controllo, il valore predefinito è 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vertexElements | boolean | Ottimizza i dati degli elementi del vertice duplicati |
| toleranceControlPoint | float | La tolleranza per il punto di controllo, il valore predefinito è 1e-9 |
| toleranceNormal | float | La tolleranza per normale/tangente/binormale, il valore predefinito è 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vertexElements | boolean | Ottimizza i dati degli elementi del vertice duplicati |
| toleranceControlPoint | float | La tolleranza per il punto di controllo, il valore predefinito è 1e-9 |
| toleranceNormal | float | La tolleranza per normale/tangente/binormale, il valore predefinito è 1e-9 |
| toleranceUV | float | La tolleranza per uv, il valore predefinito è 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


Ottimizza l'uso della memoria della mesh eliminando i punti di controllo duplicati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vertexElements | boolean | Ottimizza i dati degli elementi del vertice duplicati |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
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

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Ottiene l'istanza Mesh dall'entità corrente.

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


Restituisce la mesh triangolata

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


Calcola l'unione di due mesh

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | Prima mesh |
| b | [Mesh](../../com.aspose.threed/mesh) | Seconda mesh |

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

