---
title: Scena
second_title: Aspose.3D for Java API Reference
description: 
type: docs
weight: 161
url: /it/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | Inizializza una nuova istanza della classe [Scene](../../com.aspose.threed/scene) con un'entità collegata a un nuovo nodo. |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | Inizializza una nuova istanza della classe [Scene](../../com.aspose.threed/scene) come sotto-scena. |
| [Scene()](#Scene--) | Inizializza una nuova istanza della classe [Scene](../../com.aspose.threed/scene). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [VERSION](#VERSION) | Restituisce la versione di rilascio corrente |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clear()](#clear--) | Cancella il contenuto della scena e ripristina le impostazioni predefinite. |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | Una funzione abbreviata per creare e registrare il [AnimationClip](../../com.aspose.threed/animationclip). Il primo [AnimationClip](../../com.aspose.threed/animationclip) sarà assegnato a [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Apre la scena dal percorso specificato |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | Apre la scena dal percorso specificato |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | Apre la scena dal percorso specificato usando il formato file specificato. |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Apre la scena dal percorso specificato usando il formato file specificato. |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | Apre la scena dal percorso specificato usando il formato file specificato. |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Apre la scena dal percorso specificato usando il formato file specificato. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Apre la scena dallo stream fornito |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Apre la scena dallo stream fornito usando il formato file specificato. |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito usando il formato file specificato. |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Apre la scena dallo stream fornito usando la configurazione I/O specificata. |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito usando la configurazione I/O specificata. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Apre la scena dallo stream fornito |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | Apre la scena dallo stream fornito usando il formato file specificato. |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito usando il formato file specificato. |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | Apre la scena dallo stream fornito usando la configurazione I/O specificata. |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito usando la configurazione I/O specificata. |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | Restituisce un [AnimationClip](../../com.aspose.threed/animationclip) con nome |
| [getAnimationClips()](#getAnimationClips--) | Restituisce tutti i [AnimationClip](../../com.aspose.threed/animationclip) definiti nella scena. |
| [getAssetInfo()](#getAssetInfo--) | Restituisce le informazioni dell'asset di livello superiore |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | Restituisce il [AnimationClip](../../com.aspose.threed/animationclip) attivo |
| [getLibrary()](#getLibrary--) | Gli oggetti che non sono usati direttamente nella gerarchia della scena possono essere definiti nella Libreria. |
| [getName()](#getName--) | Ottiene il nome. |
| [getPoses()](#getPoses--) | Restituisce tutti i [Pose](../../com.aspose.threed/pose) usati in questa scena. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getRootNode()](#getRootNode--) | Restituisce il nodo radice della scena. |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getSubScenes()](#getSubScenes--) | Restituisce tutte le sotto-scene |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | Apre la scena dallo stream fornito |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Apre la scena dallo stream fornito usando il formato file specificato. |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito usando il formato file specificato. |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Apre la scena dallo stream fornito usando la configurazione I/O specificata. |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito usando la configurazione I/O specificata. |
| [open(InputStream stream)](#open-java.io.InputStream-) | Apre la scena dallo stream fornito |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | Apre la scena dallo stream fornito usando il formato file specificato. |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito usando il formato file specificato. |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | Apre la scena dallo stream fornito usando la configurazione I/O specificata. |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Apre la scena dallo stream fornito usando la configurazione I/O specificata. |
| [open(String fileName)](#open-java.lang.String-) | Apre la scena dal percorso specificato |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | Apre la scena dal percorso specificato |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | Apre la scena dal percorso specificato usando il formato file specificato. |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Apre la scena dal percorso specificato usando il formato file specificato. |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | Apre la scena dal percorso specificato usando il formato file specificato. |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Apre la scena dal percorso specificato usando il formato file specificato. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | Renderizza la scena in bitmap dalla prospettiva della telecamera specificata. |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | Renderizza la scena in bitmap dalla prospettiva della telecamera specificata. |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | Renderizza la scena in un file esterno dalla prospettiva della telecamera specificata. |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | Renderizza la scena in un file esterno dalla prospettiva della telecamera specificata. |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | Renderizza la scena in un file esterno dalla prospettiva della telecamera specificata. |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Salva la scena nello stream usando il formato file specificato. |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Salva la scena nello stream usando il formato file specificato. |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | Salva la scena nello stream usando il formato file specificato. |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Salva la scena nello stream usando il formato file specificato. |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | Salva la scena nello stream usando il formato file specificato. |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Salva la scena nello stream usando il formato file specificato. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | Salva la scena nello stream usando il formato file specificato. |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Salva la scena nello stream usando il formato file specificato. |
| [save(String fileName)](#save-java.lang.String-) | Salva la scena nel percorso specificato utilizzando il formato file specificato. |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | Salva la scena nel percorso specificato utilizzando il formato file specificato. |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Salva la scena nel percorso specificato utilizzando il formato file specificato. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | Salva la scena nel percorso specificato utilizzando il formato file specificato. |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Salva la scena nel percorso specificato utilizzando il formato file specificato. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Imposta le informazioni dell'asset di livello superiore |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | Imposta il [AnimationClip](../../com.aspose.threed/animationclip) attivo |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


Inizializza una nuova istanza della classe [Scene](../../com.aspose.threed/scene) con un'entità collegata a un nuovo nodo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | L'entità iniziale che è stata collegata alla scena **Esempio:** Il codice seguente mostra come creare un [getScene](../../com.aspose.threed/scene\\#getScene) direttamente da un [Entity](../../com.aspose.threed/entity): |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


Inizializza una nuova istanza della classe [Scene](../../com.aspose.threed/scene) come sotto-scena.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | La scena genitore. |
| nome | java.lang.String | Nome della scena. |

### Scene() {#Scene--}
```
public Scene()
```


Inizializza una nuova istanza della classe [Scene](../../com.aspose.threed/scene).

### VERSION {#VERSION}
```
public static final String VERSION
```


Restituisce la versione di rilascio corrente

### clear() {#clear--}
```
public void clear()
```


Cancella il contenuto della scena e ripristina le impostazioni predefinite.

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


Una funzione abbreviata per creare e registrare il [AnimationClip](../../com.aspose.threed/animationclip). Il primo [AnimationClip](../../com.aspose.threed/animationclip) sarà assegnato a [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome della clip di animazione |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
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
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


Apre la scena dal percorso specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


Apre la scena dal percorso specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


Apre la scena dal percorso specificato usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


Apre la scena dal percorso specificato usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


Apre la scena dal percorso specificato usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Apre la scena dal percorso specificato usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


Apre la scena dallo stream fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


Apre la scena dallo stream fornito usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


Apre la scena dallo stream fornito usando la configurazione I/O specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito usando la configurazione I/O specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


Apre la scena dallo stream fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. **Esempio:** Il codice seguente mostra come creare una scena da uno stream con una sorgente di token di cancellazione |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento **Esempio:** Il codice seguente mostra come creare una scena da uno stream con una sorgente di token di cancellazione |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, cts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(InputStream stream, FileFormat format)
```


Apre la scena dallo stream fornito usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. **Esempio:** Il codice seguente mostra come creare una scena da uno stream |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento **Esempio:** Il codice seguente mostra come creare una scena da uno stream |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(InputStream stream, LoadOptions options)
```


Apre la scena dallo stream fornito usando la configurazione I/O specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. **Esempio:** Il codice seguente mostra come creare una scena da uno stream con opzioni di caricamento |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito usando la configurazione I/O specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento **Esempio:** Il codice seguente mostra come creare una scena da uno stream con opzioni di caricamento |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### getAnimationClip(String name) {#getAnimationClip-java.lang.String-}
```
public AnimationClip getAnimationClip(String name)
```


Restituisce un [AnimationClip](../../com.aspose.threed/animationclip) con nome

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome del [AnimationClip](../../com.aspose.threed/animationclip) da cercare |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


Restituisce tutti i [AnimationClip](../../com.aspose.threed/animationclip) definiti nella scena.

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - tutti i [AnimationClip](../../com.aspose.threed/animationclip) definiti nella scena.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Restituisce le informazioni dell'asset di livello superiore

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - the top-level asset information **Example:** The following code shows how to read the application information from a FBX file:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentAnimationClip() {#getCurrentAnimationClip--}
```
public AnimationClip getCurrentAnimationClip()
```


Restituisce il [AnimationClip](../../com.aspose.threed/animationclip) attivo

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


Gli oggetti che non sono utilizzati direttamente nella gerarchia della scena possono essere definiti nella Libreria. Questo è utile quando si utilizzano sotto-scene e si inseriscono componenti riutilizzabili sotto le sotto-scene.

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - Gli oggetti che non sono utilizzati direttamente nella gerarchia della scena possono essere definiti nella Libreria. Questo è utile quando si utilizzano sotto-scene e si inseriscono componenti riutilizzabili sotto le sotto-scene.
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


Restituisce tutti i [Pose](../../com.aspose.threed/pose) usati in questa scena.

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - tutti i [Pose](../../com.aspose.threed/pose) utilizzati in questa scena.
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
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


Restituisce il nodo radice della scena.

**Returns:**
[Node](../../com.aspose.threed/node) - the root node of the scene. **Example:** The following code shows how to create a node with Box entity attached to the root node.

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box());
     scene.save("box.stl");
```
### getScene() {#getScene--}
```
public Scene getScene()
```


Ottiene la scena a cui appartiene questo oggetto

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


Restituisce tutte le sotto-scene

**Returns:**
java.util.List<com.aspose.threed.Scene> - tutte le sotto-scene
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




### open(Stream stream) {#open-com.aspose.threed.Stream-}
```
public void open(Stream stream)
```


Apre la scena dallo stream fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


Apre la scena dallo stream fornito usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


Apre la scena dallo stream fornito usando la configurazione I/O specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito usando la configurazione I/O specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


Apre la scena dallo stream fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. **Esempio:** Il codice seguente mostra come aprire una scena dallo stream |

```
var scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs);    
     }
``` |

### open(InputStream stream, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento **Esempio:** Il codice seguente mostra come aprire una scena dallo stream con un token di cancellazione |

```
var scene = new Scene();    
     Cancellation cts = new Cancellation();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, cts);    
     }
``` |

### open(InputStream stream, FileFormat format) {#open-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public void open(InputStream stream, FileFormat format)
```


Apre la scena dallo stream fornito usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. **Esempio:** Il codice seguente mostra come aprire una scena dallo stream |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, FileFormat format, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento **Esempio:** Il codice seguente mostra come aprire una scena dallo stream |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, LoadOptions options) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public void open(InputStream stream, LoadOptions options)
```


Apre la scena dallo stream fornito usando la configurazione I/O specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. **Esempio:** Il codice seguente mostra come aprire una scena dallo stream con opzioni di caricamento aggiuntive |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


Apre la scena dallo stream fornito usando la configurazione I/O specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento **Esempio:** Il codice seguente mostra come aprire una scena dallo stream con opzioni di caricamento aggiuntive |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(String fileName) {#open-java.lang.String-}
```
public void open(String fileName)
```


Apre la scena dal percorso specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


Apre la scena dal percorso specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


Apre la scena dal percorso specificato usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


Apre la scena dal percorso specificato usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato file. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


Apre la scena dal percorso specificato usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Apre la scena dal percorso specificato usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configurazione più dettagliata per aprire lo stream. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di caricamento |

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
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


Renderizza la scena in bitmap dalla prospettiva della telecamera specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Da quale prospettiva della fotocamera renderizzare la scena |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Obiettivo del risultato renderizzato |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


Renderizza la scena in bitmap dalla prospettiva della telecamera specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Da quale prospettiva della fotocamera renderizzare la scena |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Obiettivo del risultato renderizzato |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | L'opzione per personalizzare alcune impostazioni interne. |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


Renderizza la scena in un file esterno dalla prospettiva della fotocamera specificata. La dimensione di output predefinita è 1024x768 e il formato di output è png

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Da quale prospettiva della fotocamera renderizzare la scena |
| fileName | java.lang.String | Il nome del file di output |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


Renderizza la scena in un file esterno dalla prospettiva della telecamera specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Da quale prospettiva della fotocamera renderizzare la scena |
| fileName | java.lang.String | Il nome del file di output |
| size | [Vector2](../../com.aspose.threed/vector2) | La dimensione dell'immagine renderizzata finale |
| formato | java.lang.String | Il formato immagine del file di output |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


Renderizza la scena in un file esterno dalla prospettiva della telecamera specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Da quale prospettiva della fotocamera renderizzare la scena |
| fileName | java.lang.String | Il nome del file di output |
| size | [Vector2](../../com.aspose.threed/vector2) | La dimensione dell'immagine renderizzata finale |
| formato | java.lang.String | Il formato immagine del file di output |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | L'opzione per personalizzare alcune impostazioni interne. |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


Salva la scena nello stream usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Salva la scena nello stream usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di salvataggio |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


Salva la scena nello stream usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configurazione più dettagliata per salvare lo stream. |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


Salva la scena nello stream usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Stream di input, l'utente è responsabile della chiusura dello stream. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configurazione più dettagliata per salvare lo stream. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di salvataggio |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


Salva la scena nello stream usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. **Esempio:** Il codice seguente mostra come salvare la scena |

```
Scene scene = Scene.fromFile("input.fbx");    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ);    
     }
``` |

### save(OutputStream stream, FileFormat format, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, FileFormat format, Cancellation cancellationToken)
```


Salva la scena nello stream usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di salvataggio **Esempio:** Il codice seguente mostra come salvare la scena |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ, cts);    
     }
``` |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


Salva la scena nello stream usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configurazione più dettagliata per salvare lo stream. **Esempio:** Il codice seguente mostra come salvare la scena |

```
Scene scene = Scene.fromFile("input.fbx");    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt);    
     }
``` |

### save(OutputStream stream, SaveOptions options, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)
```


Salva la scena nello stream usando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | Stream di input, l'utente è responsabile della chiusura dello stream. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configurazione più dettagliata per salvare lo stream. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di salvataggio **Esempio:** Il codice seguente mostra come salvare la scena |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt, cts);    
     }
``` |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Salva la scena nel percorso specificato utilizzando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


Salva la scena nel percorso specificato utilizzando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


Salva la scena nel percorso specificato utilizzando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di salvataggio |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Salva la scena nel percorso specificato utilizzando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configurazione più dettagliata per salvare lo stream. |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


Salva la scena nel percorso specificato utilizzando il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Nome del file. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configurazione più dettagliata per salvare lo stream. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token di cancellazione per l'operazione di salvataggio |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Imposta le informazioni dell'asset di livello superiore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nuovo valore **Esempio:** Il codice seguente mostra come leggere le informazioni dell'applicazione da un file FBX: |

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
``` |

### setCurrentAnimationClip(AnimationClip value) {#setCurrentAnimationClip-com.aspose.threed.AnimationClip-}
```
public void setCurrentAnimationClip(AnimationClip value)
```


Imposta il [AnimationClip](../../com.aspose.threed/animationclip) attivo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | Nuovo valore |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

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

