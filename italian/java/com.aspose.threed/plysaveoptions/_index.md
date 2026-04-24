---
title: PlySaveOptions
second_title: Aspose.3D for Java API Reference
description: Opzioni di salvataggio per esportare la scena come file PLY.
type: docs
weight: 131
url: /it/java/com.aspose.threed/plysaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class PlySaveOptions extends SaveOptions
```

Opzioni di salvataggio per esportare la scena come file PLY.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PlySaveOptions()](#PlySaveOptions--) | Costruttore di [PlySaveOptions](../../com.aspose.threed/plysaveoptions) |
| [PlySaveOptions(FileContentType contentType)](#PlySaveOptions-com.aspose.threed.FileContentType-) | Costruttore di [PlySaveOptions](../../com.aspose.threed/plysaveoptions) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAxisSystem()](#getAxisSystem--) | Ottiene il sistema di assi nel file STL esportato. |
| [getClass()](#getClass--) |  |
| [getColorComponents()](#getColorComponents--) | I nomi dei componenti per il colore del vertice, il valore predefinito è ("red", "green", "blue") |
| [getEncoding()](#getEncoding--) | Restituisce la codifica predefinita per i file di testo. |
| [getExportTextures()](#getExportTextures--) | Prova a copiare le texture usate nella scena nella directory di output. |
| [getFaceElement()](#getFaceElement--) | Il nome dell'elemento per i dati della faccia, il valore predefinito è "face" |
| [getFaceProperty()](#getFaceProperty--) | Il nome della proprietà per i dati della faccia, il valore predefinito è "vertex\_index" |
| [getFileFormat()](#getFileFormat--) | Restituisce il formato file specificato nell'opzione Salva/Carica corrente. |
| [getFileName()](#getFileName--) | Il nome file della scena di esportazione/importazione. |
| [getFileSystem()](#getFileSystem--) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Restituisce la classe factory per FileSystem. |
| [getFlipCoordinate()](#getFlipCoordinate--) | Capovolgi la coordinata durante il salvataggio della scena, il valore predefinito è true |
| [getLookupPaths()](#getLookupPaths--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [getNormalComponents()](#getNormalComponents--) | I nomi dei componenti per i dati normali, il valore predefinito è ("nx", "ny", "nz") |
| [getPointCloud()](#getPointCloud--) | Esporta la scena come nuvola di punti, il valore predefinito è false. |
| [getPositionComponents()](#getPositionComponents--) | I nomi dei componenti per i dati di posizione, il valore predefinito è ("x", "y", "z") |
| [getTextureCoordinateComponents()](#getTextureCoordinateComponents--) | I nomi dei componenti per i dati delle coordinate di texture, il valore predefinito è ("u", "v") |
| [getVertexElement()](#getVertexElement--) | Il nome dell'elemento per i dati del vertice, il valore predefinito è "vertex" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Imposta il sistema di assi nel file STL esportato. |
| [setColorComponents(Tuple_3<String,String,String> value)](#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | I nomi dei componenti per il colore del vertice, il valore predefinito è ("red", "green", "blue") |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Imposta la codifica predefinita per i file di testo. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Prova a copiare le texture usate nella scena nella directory di output. |
| [setFaceElement(String value)](#setFaceElement-java.lang.String-) | Il nome dell'elemento per i dati della faccia, il valore predefinito è "face" |
| [setFaceProperty(String value)](#setFaceProperty-java.lang.String-) | Il nome della proprietà per i dati della faccia, il valore predefinito è "vertex\_index" |
| [setFileName(String value)](#setFileName-java.lang.String-) | Il nome file della scena di esportazione/importazione. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Imposta la classe factory per FileSystem. |
| [setFlipCoordinate(boolean value)](#setFlipCoordinate-boolean-) | Capovolgi la coordinata durante il salvataggio della scena, il valore predefinito è true |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [setNormalComponents(Tuple_3<String,String,String> value)](#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | I nomi dei componenti per i dati normali, il valore predefinito è ("nx", "ny", "nz") |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | Esporta la scena come nuvola di punti, il valore predefinito è false. |
| [setPositionComponents(Tuple_3<String,String,String> value)](#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | I nomi dei componenti per i dati di posizione, il valore predefinito è ("x", "y", "z") |
| [setTextureCoordinateComponents(Tuple_2<String,String> value)](#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--) | I nomi dei componenti per i dati delle coordinate di texture, il valore predefinito è ("u", "v") |
| [setVertexElement(String value)](#setVertexElement-java.lang.String-) | Il nome dell'elemento per i dati del vertice, il valore predefinito è "vertex" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlySaveOptions() {#PlySaveOptions--}
```
public PlySaveOptions()
```


Costruttore di [PlySaveOptions](../../com.aspose.threed/plysaveoptions)

### PlySaveOptions(FileContentType contentType) {#PlySaveOptions-com.aspose.threed.FileContentType-}
```
public PlySaveOptions(FileContentType contentType)
```


Costruttore di [PlySaveOptions](../../com.aspose.threed/plysaveoptions)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

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
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Ottiene il sistema di assi nel file STL esportato.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the axis system in the exported stl file. **Remarks:** FlipCoordinateSystem must be enabled to utilize this feature.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorComponents() {#getColorComponents--}
```
public Tuple_3<String,String,String> getColorComponents()
```


I nomi dei componenti per il colore del vertice, il valore predefinito è ("red", "green", "blue")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - I nomi dei componenti per il colore del vertice, il valore predefinito è ("red", "green", "blue")
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
### getFaceElement() {#getFaceElement--}
```
public String getFaceElement()
```


Il nome dell'elemento per i dati della faccia, il valore predefinito è "face"

**Returns:**
java.lang.String - Il nome dell'elemento per i dati della faccia, il valore predefinito è "face"
### getFaceProperty() {#getFaceProperty--}
```
public String getFaceProperty()
```


Il nome della proprietà per i dati della faccia, il valore predefinito è "vertex\_index"

**Returns:**
java.lang.String - Il nome della proprietà per i dati della faccia, il valore predefinito è "vertex\_index"
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
### getFlipCoordinate() {#getFlipCoordinate--}
```
public boolean getFlipCoordinate()
```


Capovolgi la coordinata durante il salvataggio della scena, il valore predefinito è true

**Returns:**
boolean - Capovolgi la coordinata durante il salvataggio della scena, il valore predefinito è true
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
### getNormalComponents() {#getNormalComponents--}
```
public Tuple_3<String,String,String> getNormalComponents()
```


I nomi dei componenti per i dati normali, il valore predefinito è ("nx", "ny", "nz")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - I nomi dei componenti per i dati normali, il valore predefinito è ("nx", "ny", "nz")
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


Esporta la scena come nuvola di punti, il valore predefinito è false.

**Returns:**
boolean - Esporta la scena come nuvola di punti, il valore predefinito è false.
### getPositionComponents() {#getPositionComponents--}
```
public Tuple_3<String,String,String> getPositionComponents()
```


I nomi dei componenti per i dati di posizione, il valore predefinito è ("x", "y", "z")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - I nomi dei componenti per i dati di posizione, il valore predefinito è ("x", "y", "z")
### getTextureCoordinateComponents() {#getTextureCoordinateComponents--}
```
public Tuple_2<String,String> getTextureCoordinateComponents()
```


I nomi dei componenti per i dati delle coordinate di texture, il valore predefinito è ("u", "v")

**Returns:**
com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> - I nomi dei componenti per i dati delle coordinate di texture, il valore predefinito è ("u", "v")
### getVertexElement() {#getVertexElement--}
```
public String getVertexElement()
```


Il nome dell'elemento per i dati del vertice, il valore predefinito è "vertex"

**Returns:**
java.lang.String - Il nome dell'elemento per i dati del vertice, il valore predefinito è "vertex"
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




### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Imposta il sistema di assi nel file STL esportato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Nuovo valore **Remarks:** FlipCoordinateSystem deve essere abilitato per utilizzare questa funzionalità. |

### setColorComponents(Tuple_3<String,String,String> value) {#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setColorComponents(Tuple_3<String,String,String> value)
```


I nomi dei componenti per il colore del vertice, il valore predefinito è ("red", "green", "blue")

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Nuovo valore |

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

### setFaceElement(String value) {#setFaceElement-java.lang.String-}
```
public void setFaceElement(String value)
```


Il nome dell'elemento per i dati della faccia, il valore predefinito è "face"

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setFaceProperty(String value) {#setFaceProperty-java.lang.String-}
```
public void setFaceProperty(String value)
```


Il nome della proprietà per i dati della faccia, il valore predefinito è "vertex\_index"

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

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

### setFlipCoordinate(boolean value) {#setFlipCoordinate-boolean-}
```
public void setFlipCoordinate(boolean value)
```


Capovolgi la coordinata durante il salvataggio della scena, il valore predefinito è true

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

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

### setNormalComponents(Tuple_3<String,String,String> value) {#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setNormalComponents(Tuple_3<String,String,String> value)
```


I nomi dei componenti per i dati normali, il valore predefinito è ("nx", "ny", "nz")

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Nuovo valore |

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


Esporta la scena come nuvola di punti, il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setPositionComponents(Tuple_3<String,String,String> value) {#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setPositionComponents(Tuple_3<String,String,String> value)
```


I nomi dei componenti per i dati di posizione, il valore predefinito è ("x", "y", "z")

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Nuovo valore |

### setTextureCoordinateComponents(Tuple_2<String,String> value) {#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--}
```
public void setTextureCoordinateComponents(Tuple_2<String,String> value)
```


I nomi dei componenti per i dati delle coordinate di texture, il valore predefinito è ("u", "v")

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> | Nuovo valore |

### setVertexElement(String value) {#setVertexElement-java.lang.String-}
```
public void setVertexElement(String value)
```


Il nome dell'elemento per i dati del vertice, il valore predefinito è "vertex"

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

