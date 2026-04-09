---
title: Html5SaveOptions
second_title: Aspose.3D for Java API Reference
description: Opzioni di salvataggio per HTML5
type: docs
weight: 80
url: /it/java/com.aspose.threed/html5saveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Html5SaveOptions extends SaveOptions
```

Opzioni di salvataggio per HTML5
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Html5SaveOptions()](#Html5SaveOptions--) | Costruttore di [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) con tutte le impostazioni predefinite. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Ottiene la posizione iniziale della fotocamera, il valore predefinito è (10, 10, 10) |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Restituisce la codifica predefinita per i file di testo. |
| [getExportTextures()](#getExportTextures--) | Prova a copiare le texture usate nella scena nella directory di output. |
| [getFarPlane()](#getFarPlane--) | Ottiene il piano lontano della fotocamera, il valore predefinito è 1000. |
| [getFieldOfView()](#getFieldOfView--) | Ottiene il campo della visuale, il valore predefinito è 45, misurato in gradi. |
| [getFileFormat()](#getFileFormat--) | Restituisce il formato file specificato nell'opzione Salva/Carica corrente. |
| [getFileName()](#getFileName--) | Il nome file della scena di esportazione/importazione. |
| [getFileSystem()](#getFileSystem--) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Restituisce la classe factory per FileSystem. |
| [getLookAt()](#getLookAt--) | Ottiene la posizione di osservazione predefinita, il valore predefinito è (0, 0, 0) |
| [getLookupPaths()](#getLookupPaths--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [getNearPlane()](#getNearPlane--) | Ottiene il piano vicino della fotocamera, il valore predefinito è 1 |
| [getOrientationBox()](#getOrientationBox--) | Visualizza una scatola di orientamento. |
| [getShowGrid()](#getShowGrid--) | Visualizza una griglia nella scena. |
| [getShowRulers()](#getShowRulers--) | Visualizza righelli degli assi x/y/z nella scena per misurare il modello. |
| [getShowUI()](#getShowUI--) | Visualizza un'interfaccia semplice nella scena. |
| [getUpVector()](#getUpVector--) | Ottiene il vettore up, il valore può essere "x"/"y"/"z", il valore predefinito è "y" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(Vector3 value)](#setCameraPosition-com.aspose.threed.Vector3-) | Imposta la posizione iniziale della fotocamera, il valore predefinito è (10, 10, 10) |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Imposta la codifica predefinita per i file di testo. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Prova a copiare le texture usate nella scena nella directory di output. |
| [setFarPlane(double value)](#setFarPlane-double-) | Imposta il piano lontano della fotocamera, il valore predefinito è 1000. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Imposta il campo di visualizzazione, il valore predefinito è 45, misurato in gradi. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Il nome file della scena di esportazione/importazione. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Imposta la classe factory per FileSystem. |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Imposta la posizione di default di look at, il valore predefinito è (0, 0, 0) |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [setNearPlane(double value)](#setNearPlane-double-) | Imposta il piano vicino della fotocamera, il valore predefinito è 1 |
| [setOrientationBox(boolean value)](#setOrientationBox-boolean-) | Visualizza una scatola di orientamento. |
| [setShowGrid(boolean value)](#setShowGrid-boolean-) | Visualizza una griglia nella scena. |
| [setShowRulers(boolean value)](#setShowRulers-boolean-) | Visualizza righelli degli assi x/y/z nella scena per misurare il modello. |
| [setShowUI(boolean value)](#setShowUI-boolean-) | Visualizza un'interfaccia semplice nella scena. |
| [setUpVector(String value)](#setUpVector-java.lang.String-) | Imposta il vettore up, il valore può essere "x"/"y"/"z", il valore predefinito è "y" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Html5SaveOptions() {#Html5SaveOptions--}
```
public Html5SaveOptions()
```


Costruttore di [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) con tutte le impostazioni predefinite.

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
### getCameraPosition() {#getCameraPosition--}
```
public Vector3 getCameraPosition()
```


Ottiene la posizione iniziale della fotocamera, il valore predefinito è (10, 10, 10)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the initial position of the camera, default value is (10, 10, 10)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Restituisce la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.

**Returns:**
java.nio.charset.Charset - la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Prova a copiare le texture usate nella scena nella directory di output.

**Returns:**
boolean - Prova a copiare le texture usate nella scena nella directory di output.
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Ottiene il piano lontano della fotocamera, il valore predefinito è 1000.

**Returns:**
double - il piano lontano della fotocamera, il valore predefinito è 1000.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Ottiene il campo della visuale, il valore predefinito è 45, misurato in gradi.

**Returns:**
double - il campo di visualizzazione, il valore predefinito è 45, misurato in gradi.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Restituisce il formato file specificato nell'opzione Salva/Carica corrente.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ.

**Returns:**
java.lang.String - Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

E puoi anche utilizzare la tua implementazione.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
```
### getFileSystemFactory() {#getFileSystemFactory--}
```
public static FileSystemFactory getFileSystemFactory()
```


Ottiene la classe factory per FileSystem. La factory predefinita creerà com.aspose.threed.LocalFileSystem, che non è adatta per l'ambiente server.

**Returns:**
[FileSystemFactory](../../com.aspose.threed/filesystemfactory) - the factory class for FileSystem. The default factory will create com.aspose.threed.LocalFileSystem which is not suitable for server environment. **Example:** The default FileSystem in SaveOptions/LoadOptions is directory-based file system, You can override the default implementation by specify it through IOConfig.FileSystemFactory:

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
```
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Ottiene la posizione di osservazione predefinita, il valore predefinito è (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the default look at position, default value is (0, 0, 0)
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare.

**Returns:**
java.util.ArrayList<java.lang.String> - Alcuni file come OBJ dipendono da file esterni; i percorsi di ricerca consentiranno ad Aspose.3D di cercare i file esterni da caricare. **Esempio:** Il codice seguente mostra come specificare manualmente le texture di ricerca, così l'importatore può trovarle

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Ottiene il piano vicino della fotocamera, il valore predefinito è 1

**Returns:**
double - il piano vicino della fotocamera, il valore predefinito è 1
### getOrientationBox() {#getOrientationBox--}
```
public boolean getOrientationBox()
```


Visualizza una scatola di orientamento. Il valore predefinito è true.

**Returns:**
boolean - Visualizza una scatola di orientamento. Il valore predefinito è true.
### getShowGrid() {#getShowGrid--}
```
public boolean getShowGrid()
```


Visualizza una griglia nella scena. Il valore predefinito è true.

**Returns:**
boolean - Visualizza una griglia nella scena. Il valore predefinito è true.
### getShowRulers() {#getShowRulers--}
```
public boolean getShowRulers()
```


Visualizza righelli degli assi x/y/z nella scena per misurare il modello. Il valore predefinito è false.

**Returns:**
boolean - Visualizza righelli degli assi x/y/z nella scena per misurare il modello. Il valore predefinito è false.
### getShowUI() {#getShowUI--}
```
public boolean getShowUI()
```


Visualizza una semplice interfaccia utente nella scena. Il valore predefinito è true.

**Returns:**
boolean - Visualizza una semplice interfaccia utente nella scena. Il valore predefinito è true.
### getUpVector() {#getUpVector--}
```
public String getUpVector()
```


Ottiene il vettore up, il valore può essere "x"/"y"/"z", il valore predefinito è "y"

**Returns:**
java.lang.String - il vettore up, il valore può essere "x"/"y"/"z", il valore predefinito è "y"
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




### setCameraPosition(Vector3 value) {#setCameraPosition-com.aspose.threed.Vector3-}
```
public void setCameraPosition(Vector3 value)
```


Imposta la posizione iniziale della fotocamera, il valore predefinito è (10, 10, 10)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Imposta la codifica predefinita per i file basati su testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset | Nuovo valore |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Prova a copiare le texture usate nella scena nella directory di output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Imposta il piano lontano della fotocamera, il valore predefinito è 1000.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Imposta il campo di visualizzazione, il valore predefinito è 45, misurato in gradi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Nuovo valore **Esempio:** Il FileSystem predefinito è LocalFileSystem, non è sicuro in ambienti come il lato server, ma è possibile sovrascrivere l'accesso al file system specificando un'implementazione diversa. Aspose.3D fornisce diverse implementazioni di FileSystem come: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

E puoi anche utilizzare la tua implementazione.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
``` |

### setFileSystemFactory(FileSystemFactory value) {#setFileSystemFactory-com.aspose.threed.FileSystemFactory-}
```
public static void setFileSystemFactory(FileSystemFactory value)
```


Imposta la classe factory per FileSystem. La factory predefinita creerà com.aspose.threed.LocalFileSystem, che non è adatta per l'ambiente server.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Nuovo valore **Esempio:** Il FileSystem predefinito in SaveOptions/LoadOptions è un file system basato su directory; è possibile sovrascrivere l'implementazione predefinita specificandola tramite IOConfig.FileSystemFactory: |

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
``` |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Imposta la posizione di default di look at, il valore predefinito è (0, 0, 0)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.util.ArrayList<java.lang.String> | Nuovo valore **Esempio:** Il codice seguente mostra come specificare manualmente le texture di ricerca, così l'importatore può trovarle |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Imposta il piano vicino della fotocamera, il valore predefinito è 1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setOrientationBox(boolean value) {#setOrientationBox-boolean-}
```
public void setOrientationBox(boolean value)
```


Visualizza una scatola di orientamento. Il valore predefinito è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setShowGrid(boolean value) {#setShowGrid-boolean-}
```
public void setShowGrid(boolean value)
```


Visualizza una griglia nella scena. Il valore predefinito è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setShowRulers(boolean value) {#setShowRulers-boolean-}
```
public void setShowRulers(boolean value)
```


Visualizza righelli degli assi x/y/z nella scena per misurare il modello. Il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setShowUI(boolean value) {#setShowUI-boolean-}
```
public void setShowUI(boolean value)
```


Visualizza una semplice interfaccia utente nella scena. Il valore predefinito è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setUpVector(String value) {#setUpVector-java.lang.String-}
```
public void setUpVector(String value)
```


Imposta il vettore up, il valore può essere "x"/"y"/"z", il valore predefinito è "y"

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

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

