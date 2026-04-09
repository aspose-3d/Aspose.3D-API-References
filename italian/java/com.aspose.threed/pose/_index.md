---
title: Pose
second_title: Aspose.3D for Java API Reference
description: La pose è usata per memorizzare la matrice di trasformazione quando la geometria è skinata.
type: docs
weight: 135
url: /it/java/com.aspose.threed/pose/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Pose extends A3DObject
```

La pose è usata per memorizzare la matrice di trasformazione quando la geometria è skinned. La pose è un insieme di [BonePose](../../com.aspose.threed/bonepose), ogni [BonePose](../../com.aspose.threed/bonepose) salva le informazioni concrete di trasformazione del nodo osso.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Pose(String name)](#Pose-java.lang.String-) | Inizializza una nuova istanza della classe [Pose](../../com.aspose.threed/pose). |
| [Pose()](#Pose--) | Inizializza una nuova istanza della classe [Pose](../../com.aspose.threed/pose). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addBonePose(Node node, Matrix4 matrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | Salva la matrice di trasformazione della pose per il nodo osso specificato. |
| [addBonePose(Node node, Matrix4 matrix, boolean localMatrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-) | Salva la matrice di trasformazione della pose per il nodo osso specificato. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getBonePoses()](#getBonePoses--) | Ottiene tutti i [BonePose](../../com.aspose.threed/bonepose). |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Ottiene il nome. |
| [getPoseType()](#getPoseType--) | Ottiene il tipo della pose. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setPoseType(PoseType value)](#setPoseType-com.aspose.threed.PoseType-) | Imposta il tipo della pose. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pose(String name) {#Pose-java.lang.String-}
```
public Pose(String name)
```


Inizializza una nuova istanza della classe [Pose](../../com.aspose.threed/pose).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome |

### Pose() {#Pose--}
```
public Pose()
```


Inizializza una nuova istanza della classe [Pose](../../com.aspose.threed/pose).

### addBonePose(Node node, Matrix4 matrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public void addBonePose(Node node, Matrix4 matrix)
```


Salva la matrice di trasformazione della posa per il nodo osso specificato. La matrice di trasformazione globale è implicita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Nodo osso. |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | Matrice di trasformazione. |

### addBonePose(Node node, Matrix4 matrix, boolean localMatrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-}
```
public void addBonePose(Node node, Matrix4 matrix, boolean localMatrix)
```


Salva la matrice di trasformazione della pose per il nodo osso specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Nodo osso. |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | Matrice di trasformazione. |
| localMatrix | boolean | Se impostato su  true  significa utilizzare la matrice locale, altrimenti significa la matrice globale. |

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
### getBonePoses() {#getBonePoses--}
```
public List<BonePose> getBonePoses()
```


Ottiene tutti i [BonePose](../../com.aspose.threed/bonepose).

**Returns:**
java.util.List<com.aspose.threed.BonePose> - tutti i [BonePose](../../com.aspose.threed/bonepose).
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getPoseType() {#getPoseType--}
```
public PoseType getPoseType()
```


Ottiene il tipo della pose.

**Returns:**
[PoseType](../../com.aspose.threed/posetype) - the type of the pose.
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
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setPoseType(PoseType value) {#setPoseType-com.aspose.threed.PoseType-}
```
public void setPoseType(PoseType value)
```


Imposta il tipo della pose.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PoseType](../../com.aspose.threed/posetype) | Nuovo valore |

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

