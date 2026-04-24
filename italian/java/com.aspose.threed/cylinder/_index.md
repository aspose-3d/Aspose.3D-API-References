---
title: Cylinder
second_title: Aspose.3D for Java API Reference
description: Cilindro parametrizzato.
type: docs
weight: 40
url: /it/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

Cilindro parametrizzato. Può anche essere usato per rappresentare il cono quando uno dei valori radiusTop/radiusBottom è zero.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Cylinder()](#Cylinder--) | Inizializza una nuova istanza della classe [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | Inizializza una nuova istanza della classe [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | Inizializza una nuova istanza della classe [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | Inizializza una nuova istanza della classe [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | Inizializza una nuova istanza della classe [Cylinder](../../com.aspose.threed/cylinder). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| [getCastShadows()](#getCastShadows--) | Restituisce se questa geometria può proiettare ombra |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questa entità durante l'esportazione. |
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | Restituisce se generare il cilindro a ventaglio quando ThetaLength è inferiore a 2\*PI, altrimenti il modello non verrà tagliato. |
| [getHeight()](#getHeight--) | Restituisce l'altezza del cilindro. |
| [getHeightSegments()](#getHeightSegments--) | Restituisce i segmenti di altezza. |
| [getName()](#getName--) | Ottiene il nome. |
| [getOffsetBottom()](#getOffsetBottom--) | Restituisce l'offset di trasformazione dei vertici del lato inferiore. |
| [getOffsetTop()](#getOffsetTop--) | Restituisce l'offset di trasformazione dei vertici del lato superiore. |
| [getOpenEnded()](#getOpenEnded--) | Restituisce un valore che indica se questo [Cylinder](../../com.aspose.threed/cylinder) è aperto alle estremità. |
| [getParentNode()](#getParentNode--) | Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [getParentNodes()](#getParentNodes--) | Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getRadialSegments()](#getRadialSegments--) | Restituisce i segmenti radiali. |
| [getRadiusBottom()](#getRadiusBottom--) | Restituisce il raggio del cappuccio inferiore del cilindro. |
| [getRadiusTop()](#getRadiusTop--) | Ottiene il raggio del cappuccio superiore del cilindro. |
| [getReceiveShadows()](#getReceiveShadows--) | Restituisce se questa geometria può ricevere ombra. |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getShearBottom()](#getShearBottom--) | Ottiene la trasformazione di taglio del lato inferiore, il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0) |
| [getShearTop()](#getShearTop--) | Ottiene la trasformazione di taglio del lato superiore, il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0) |
| [getThetaLength()](#getThetaLength--) | Restituisce la lunghezza di theta. |
| [getThetaStart()](#getThetaStart--) | Restituisce l'inizio di theta. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Imposta se questa geometria può proiettare ombra |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questa entità durante l'esportazione. |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | Imposta se generare il cilindro in stile ventaglio quando ThetaLength è inferiore a 2\*PI, altrimenti il modello non verrà tagliato. |
| [setHeight(double value)](#setHeight-double-) | Imposta l'altezza del cilindro. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | Imposta i segmenti di altezza. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | Imposta lo spostamento di trasformazione dei vertici del lato inferiore. |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | Imposta lo spostamento di trasformazione dei vertici del lato superiore. |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | Imposta un valore che indica se questo [Cylinder](../../com.aspose.threed/cylinder) è aperto alle estremità. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setRadialSegments(int value)](#setRadialSegments-int-) | Imposta i segmenti radiali. |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | Imposta il raggio del cappuccio inferiore del cilindro. |
| [setRadiusTop(double value)](#setRadiusTop-double-) | Imposta il raggio del cappuccio superiore del cilindro. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | Imposta se questa geometria può ricevere ombra. |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | Imposta la trasformazione di taglio del lato inferiore, il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0) |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | Imposta la trasformazione di taglio del lato superiore, il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0) |
| [setThetaLength(double value)](#setThetaLength-double-) | Imposta la lunghezza di theta. |
| [setThetaStart(double value)](#setThetaStart-double-) | Imposta l'inizio di theta. |
| [toMesh()](#toMesh--) | Converti l'oggetto corrente in mesh |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


Inizializza una nuova istanza della classe [Cylinder](../../com.aspose.threed/cylinder).

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


Inizializza una nuova istanza della classe [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radius | double | Raggio del cappuccio superiore e inferiore. |
| altezza | double | Altezza. |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


Inizializza una nuova istanza della classe [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radiusTop | double | Raggio superiore. |
| radiusBottom | double | Raggio inferiore. |
| altezza | double | Altezza. |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


Inizializza una nuova istanza della classe [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radiusTop | double | Raggio del cappuccio superiore del cilindro. |
| radiusBottom | double | Raggio del cappuccio inferiore del cilindro. |
| altezza | double | Altezza del cilindro. |
| radialSegments | int | Segmenti radiali di entrambi i cerchi superiore e inferiore.. |
| heightSegments | int | Segmenti di altezza. |
| openEnded | boolean | Se impostato su  true  il cilindro non avrà tappi superiore/inferiore.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


Inizializza una nuova istanza della classe [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome di questo oggetto |
| radiusTop | double | Raggio del cappuccio superiore del cilindro. |
| radiusBottom | double | Raggio del cappuccio inferiore del cilindro. |
| altezza | double | Altezza del cilindro. |
| radialSegments | int | Segmenti radiali di entrambi i cerchi superiore e inferiore.. |
| heightSegments | int | Segmenti di altezza. |
| openEnded | boolean | Se impostato su  true  il cilindro non avrà tappi superiore/inferiore.. |
| thetaStart | double | Inizio theta. |
| thetaLength | double | Lunghezza theta. |

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
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


Restituisce se generare il cilindro a ventaglio quando ThetaLength è inferiore a 2\*PI, altrimenti il modello non verrà tagliato.

**Returns:**
boolean - se generare il cilindro a ventaglio quando ThetaLength è inferiore a 2\*PI, altrimenti il modello non verrà tagliato.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Restituisce l'altezza del cilindro.

**Returns:**
double - l'altezza del cilindro.
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


Restituisce i segmenti di altezza.

**Returns:**
int - i segmenti di altezza.
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


Restituisce l'offset di trasformazione dei vertici del lato inferiore.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


Restituisce l'offset di trasformazione dei vertici del lato superiore.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


Restituisce un valore che indica se questo [Cylinder](../../com.aspose.threed/cylinder) è aperto. Il valore predefinito è false.

**Returns:**
boolean - un valore che indica se questo [Cylinder](../../com.aspose.threed/cylinder) è aperto. Il valore predefinito è false.
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


Restituisce i segmenti radiali.

**Returns:**
int - i segmenti radiali.
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


Restituisce il raggio del cappuccio inferiore del cilindro.

**Returns:**
double - il raggio del tappo inferiore del cilindro.
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


Ottiene il raggio del cappuccio superiore del cilindro.

**Returns:**
double - il raggio del tappo superiore del cilindro.
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
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


Ottiene la trasformazione di taglio del lato inferiore, il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


Ottiene la trasformazione di taglio del lato superiore, il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


Restituisce la lunghezza di theta. Il valore predefinito è 2\\u03c0.

**Returns:**
double - la lunghezza di theta. Il valore predefinito è 2\\u03c0.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


Restituisce l'inizio di theta. Il valore predefinito è 0.

**Returns:**
double - l'inizio di theta. Il valore predefinito è 0.
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

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


Imposta se generare il cilindro in stile ventaglio quando ThetaLength è inferiore a 2\*PI, altrimenti il modello non verrà tagliato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Imposta l'altezza del cilindro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


Imposta i segmenti di altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


Imposta lo spostamento di trasformazione dei vertici del lato inferiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


Imposta lo spostamento di trasformazione dei vertici del lato superiore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


Imposta un valore che indica se questo [Cylinder](../../com.aspose.threed/cylinder) è aperto. Il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


Imposta i segmenti radiali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


Imposta il raggio del cappuccio inferiore del cilindro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


Imposta il raggio del cappuccio superiore del cilindro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


Imposta se questa geometria può ricevere ombra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


Imposta la trasformazione di taglio del lato inferiore, il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuovo valore |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


Imposta la trasformazione di taglio del lato superiore, il vettore memorizza il valore di taglio (asse x, asse z) misurato in radianti, il valore predefinito è (0, 0)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuovo valore |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


Imposta la lunghezza di theta. Il valore predefinito è 2\\u03c0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


Imposta l'inizio di theta. Il valore predefinito è 0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Converti l'oggetto corrente in mesh

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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

