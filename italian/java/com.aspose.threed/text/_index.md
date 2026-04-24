---
title: Testo
second_title: Aspose.3D for Java API Reference
description: Profilo di testo questo profilo descrive i contorni usando font e testo.
type: docs
weight: 183
url: /it/java/com.aspose.threed/text/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile)
```
public class Text extends Profile
```

Profilo di testo, questo profilo descrive i contorni usando font e testo. **Esempio:** Il codice seguente mostra come creare una mesh 3D dal testo usando il file font specificato.

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Text()](#Text--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | Contenuto del testo |
| [getEntityRendererKey()](#getEntityRendererKey--) | Ottiene la chiave del renderer dell'entità registrata nel renderer |
| [getExcluded()](#getExcluded--) | Ottiene se escludere questa entità durante l'esportazione. |
| [getFont()](#getFont--) | Il font del testo. |
| [getFontSize()](#getFontSize--) | Scala della dimensione del font. |
| [getName()](#getName--) | Ottiene il nome. |
| [getParentNode()](#getParentNode--) | Ottiene il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [getParentNodes()](#getParentNodes--) | Ottiene tutti i nodi genitore; un'entità può essere collegata a più nodi genitore per l'instancing della geometria. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setContent(String value)](#setContent-java.lang.String-) | Contenuto del testo |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Imposta se escludere questa entità durante l'esportazione. |
| [setFont(FontFile value)](#setFont-com.aspose.threed.FontFile-) | Il font del testo. |
| [setFontSize(float value)](#setFontSize-float-) | Scala della dimensione del font. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Imposta il primo nodo genitore; se impostato, questa entità verrà staccata dagli altri nodi genitori. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Text() {#Text--}
```
public Text()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContent() {#getContent--}
```
public String getContent()
```


Contenuto del testo

**Returns:**
java.lang.String - Contenuto del testo **Esempio:** Il codice seguente mostra come creare una mesh 3D dal testo usando il file font specificato.

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
```
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Ottiene la chiave del renderer dell'entità registrata nel renderer

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Ottiene se escludere questa entità durante l'esportazione.

**Returns:**
boolean - se escludere questa entità durante l'esportazione.
### getFont() {#getFont--}
```
public FontFile getFont()
```


Il font del testo.

**Returns:**
[FontFile](../../com.aspose.threed/fontfile) - The font of the text. **Example:** The following code shows how to create a 3D mesh from text using specified font file.

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
```
### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


Scala della dimensione del font.

**Returns:**
float - Scala della dimensione del font. **Esempio:** Il codice seguente mostra come creare una mesh 3D dal testo usando il file font specificato.

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
```
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Ottiene la scena a cui appartiene questo oggetto

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
### setContent(String value) {#setContent-java.lang.String-}
```
public void setContent(String value)
```


Contenuto del testo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Nuovo valore **Esempio:** Il codice seguente mostra come creare una mesh 3D dal testo usando il file font specificato. |

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
``` |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Imposta se escludere questa entità durante l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setFont(FontFile value) {#setFont-com.aspose.threed.FontFile-}
```
public void setFont(FontFile value)
```


Il font del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [FontFile](../../com.aspose.threed/fontfile) | Nuovo valore **Esempio:** Il codice seguente mostra come creare una mesh 3D dal testo usando il file font specificato. |

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
``` |

### setFontSize(float value) {#setFontSize-float-}
```
public void setFontSize(float value)
```


Scala della dimensione del font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | float | Nuovo valore **Esempio:** Il codice seguente mostra come creare una mesh 3D dal testo usando il file font specificato. |

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
``` |

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

