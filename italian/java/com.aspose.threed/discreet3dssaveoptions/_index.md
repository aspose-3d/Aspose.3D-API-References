---
title: Discreet3dsSaveOptions
second_title: Aspose.3D for Java API Reference
description: Opzioni di salvataggio per file 3DS.
type: docs
weight: 44
url: /it/java/com.aspose.threed/discreet3dssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Discreet3dsSaveOptions extends SaveOptions
```

Opzioni di salvataggio per file 3DS.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Discreet3dsSaveOptions()](#Discreet3dsSaveOptions--) | Costruttore di [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDuplicatedNameCounterBase()](#getDuplicatedNameCounterBase--) | Il contatore usato per generare nuovi nomi per i nomi duplicati, il valore predefinito è 2. |
| [getDuplicatedNameCounterFormat()](#getDuplicatedNameCounterFormat--) | Il formato del contatore duplicato, il valore predefinito è una stringa vuota. |
| [getDuplicatedNameSeparator()](#getDuplicatedNameSeparator--) | Il separatore tra il nome dell'oggetto e il contatore duplicato, il valore predefinito è "\_". |
| [getEncoding()](#getEncoding--) | Restituisce la codifica predefinita per i file di testo. |
| [getExportCamera()](#getExportCamera--) | Restituisce se esportare tutte le telecamere nella scena. |
| [getExportLight()](#getExportLight--) | Restituisce se esportare tutte le luci nella scena. |
| [getExportTextures()](#getExportTextures--) | Prova a copiare le texture usate nella scena nella directory di output. |
| [getFileFormat()](#getFileFormat--) | Restituisce il formato file specificato nell'opzione Salva/Carica corrente. |
| [getFileName()](#getFileName--) | Il nome file della scena di esportazione/importazione. |
| [getFileSystem()](#getFileSystem--) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Restituisce la classe factory per FileSystem. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | Restituisce l'inversione del sistema di coordinate dei punti di controllo/normali durante l'importazione/esportazione. |
| [getGammaCorrectedColor()](#getGammaCorrectedColor--) | Un file 3ds può contenere il colore originale e il colore corretto gamma per lo stesso attributo; impostando questo su true verrà usato il colore corretto gamma se possibile, altrimenti Aspose.3D proverà a usare il colore originale. |
| [getHighPreciseColor()](#getHighPreciseColor--) | Se impostato su true, il file 3ds generato utilizzerà colori ad alta precisione, il che significa che ogni canale rosso/verde/blu è in float a 32 bit. |
| [getLookupPaths()](#getLookupPaths--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [getMasterScale()](#getMasterScale--) | Restituisce la scala master usata durante l'esportazione. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDuplicatedNameCounterBase(int value)](#setDuplicatedNameCounterBase-int-) | Il contatore usato per generare nuovi nomi per i nomi duplicati, il valore predefinito è 2. |
| [setDuplicatedNameCounterFormat(String value)](#setDuplicatedNameCounterFormat-java.lang.String-) | Il formato del contatore duplicato, il valore predefinito è una stringa vuota. |
| [setDuplicatedNameSeparator(String value)](#setDuplicatedNameSeparator-java.lang.String-) | Il separatore tra il nome dell'oggetto e il contatore duplicato, il valore predefinito è "\_". |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Imposta la codifica predefinita per i file di testo. |
| [setExportCamera(boolean value)](#setExportCamera-boolean-) | Imposta se esportare tutte le telecamere nella scena. |
| [setExportLight(boolean value)](#setExportLight-boolean-) | Imposta se esportare tutte le luci nella scena. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Prova a copiare le texture usate nella scena nella directory di output. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Il nome file della scena di esportazione/importazione. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Imposta la classe factory per FileSystem. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | Imposta l'inversione del sistema di coordinate dei punti di controllo/normali durante l'importazione/esportazione. |
| [setGammaCorrectedColor(boolean value)](#setGammaCorrectedColor-boolean-) | Un file 3ds può contenere il colore originale e il colore corretto gamma per lo stesso attributo; impostando questo su true verrà usato il colore corretto gamma se possibile, altrimenti Aspose.3D proverà a usare il colore originale. |
| [setHighPreciseColor(boolean value)](#setHighPreciseColor-boolean-) | Se impostato su true, il file 3ds generato utilizzerà colori ad alta precisione, il che significa che ogni canale rosso/verde/blu è in float a 32 bit. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [setMasterScale(double value)](#setMasterScale-double-) | Imposta la scala principale utilizzata durante l'esportazione. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Discreet3dsSaveOptions() {#Discreet3dsSaveOptions--}
```
public Discreet3dsSaveOptions()
```


Costruttore di [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions)

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDuplicatedNameCounterBase() {#getDuplicatedNameCounterBase--}
```
public int getDuplicatedNameCounterBase()
```


Il contatore usato per generare nuovi nomi per i nomi duplicati, il valore predefinito è 2.

**Returns:**
int - Il contatore usato per generare un nuovo nome per i nomi duplicati, il valore predefinito è 2.
### getDuplicatedNameCounterFormat() {#getDuplicatedNameCounterFormat--}
```
public String getDuplicatedNameCounterFormat()
```


Il formato del contatore duplicato, il valore predefinito è una stringa vuota.

**Returns:**
java.lang.String - Il formato del contatore duplicato, il valore predefinito è una stringa vuota.
### getDuplicatedNameSeparator() {#getDuplicatedNameSeparator--}
```
public String getDuplicatedNameSeparator()
```


Il separatore tra il nome dell'oggetto e il contatore duplicato, il valore predefinito è "\_". Quando la scena contiene oggetti che utilizzano lo stesso nome, l'esportatore 3DS di Aspose.3D genererà un nome diverso per l'oggetto. Ad esempio, ci sono due nodi chiamati "Box", il primo nodo avrà il nome "Box", e il secondo otterrà un nuovo nome "Box\_2" usando la configurazione predefinita.

**Returns:**
Il separatore tra il nome dell'oggetto e il contatore duplicato, il valore predefinito è "\_". Quando la scena contiene oggetti che utilizzano lo stesso nome, l'esportatore 3DS di Aspose.3D genererà un nome diverso per l'oggetto. Ad esempio, ci sono due nodi chiamati "Box", il primo nodo avrà il nome "Box", e il secondo otterrà un nuovo nome "Box\_2" usando la configurazione predefinita.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Restituisce la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.

**Returns:**
java.nio.charset.Charset - la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.
### getExportCamera() {#getExportCamera--}
```
public boolean getExportCamera()
```


Restituisce se esportare tutte le telecamere nella scena.

**Returns:**
boolean - se esportare tutte le telecamere nella scena.
### getExportLight() {#getExportLight--}
```
public boolean getExportLight()
```


Restituisce se esportare tutte le luci nella scena.

**Returns:**
boolean - se esportare tutte le luci nella scena.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Prova a copiare le texture usate nella scena nella directory di output.

**Returns:**
boolean - Prova a copiare le texture usate nella scena nella directory di output.
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


Restituisce l'inversione del sistema di coordinate dei punti di controllo/normali durante l'importazione/esportazione.

**Returns:**
boolean - inverte il sistema di coordinate dei punti di controllo/normali durante l'importazione/esportazione.
### getGammaCorrectedColor() {#getGammaCorrectedColor--}
```
public boolean getGammaCorrectedColor()
```


Un file 3ds può contenere il colore originale e il colore corretto gamma per lo stesso attributo; impostando questo su true verrà usato il colore corretto gamma se possibile, altrimenti Aspose.3D proverà a usare il colore originale.

**Returns:**
boolean - Un file 3ds può contenere il colore originale e il colore corretto per gamma per lo stesso attributo; impostare questo su true utilizzerà il colore corretto per gamma se possibile, altrimenti Aspose.3D proverà a usare il colore originale.
### getHighPreciseColor() {#getHighPreciseColor--}
```
public boolean getHighPreciseColor()
```


Se questo è true, il file 3ds generato utilizzerà colori ad alta precisione, il che significa che ogni canale rosso/verde/blu è in float a 32 bit. Altrimenti il file generato utilizzerà colori a 24 bit, ogni canale usa un byte a 8 bit. Il valore predefinito è false, perché non tutte le applicazioni supportano i colori ad alta precisione.

**Returns:**
boolean - Se questo è true, il file 3ds generato utilizzerà colori ad alta precisione, il che significa che ogni canale rosso/verde/blu è in float a 32 bit. Altrimenti il file generato utilizzerà colori a 24 bit, ogni canale usa un byte a 8 bit. Il valore predefinito è false, perché non tutte le applicazioni supportano i colori ad alta precisione.
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
### getMasterScale() {#getMasterScale--}
```
public double getMasterScale()
```


Restituisce la scala master usata durante l'esportazione.

**Returns:**
double - la scala principale utilizzata nell'esportazione.
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




### setDuplicatedNameCounterBase(int value) {#setDuplicatedNameCounterBase-int-}
```
public void setDuplicatedNameCounterBase(int value)
```


Il contatore usato per generare nuovi nomi per i nomi duplicati, il valore predefinito è 2.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setDuplicatedNameCounterFormat(String value) {#setDuplicatedNameCounterFormat-java.lang.String-}
```
public void setDuplicatedNameCounterFormat(String value)
```


Il formato del contatore duplicato, il valore predefinito è una stringa vuota.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setDuplicatedNameSeparator(String value) {#setDuplicatedNameSeparator-java.lang.String-}
```
public void setDuplicatedNameSeparator(String value)
```


Il separatore tra il nome dell'oggetto e il contatore duplicato, il valore predefinito è "\_". Quando la scena contiene oggetti che utilizzano lo stesso nome, l'esportatore 3DS di Aspose.3D genererà un nome diverso per l'oggetto. Ad esempio, ci sono due nodi chiamati "Box", il primo nodo avrà il nome "Box", e il secondo otterrà un nuovo nome "Box\_2" usando la configurazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Imposta la codifica predefinita per i file basati su testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset | Nuovo valore |

### setExportCamera(boolean value) {#setExportCamera-boolean-}
```
public void setExportCamera(boolean value)
```


Imposta se esportare tutte le telecamere nella scena.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setExportLight(boolean value) {#setExportLight-boolean-}
```
public void setExportLight(boolean value)
```


Imposta se esportare tutte le luci nella scena.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Prova a copiare le texture usate nella scena nella directory di output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


Imposta l'inversione del sistema di coordinate dei punti di controllo/normali durante l'importazione/esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setGammaCorrectedColor(boolean value) {#setGammaCorrectedColor-boolean-}
```
public void setGammaCorrectedColor(boolean value)
```


Un file 3ds può contenere il colore originale e il colore corretto gamma per lo stesso attributo; impostando questo su true verrà usato il colore corretto gamma se possibile, altrimenti Aspose.3D proverà a usare il colore originale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setHighPreciseColor(boolean value) {#setHighPreciseColor-boolean-}
```
public void setHighPreciseColor(boolean value)
```


Se questo è true, il file 3ds generato utilizzerà colori ad alta precisione, il che significa che ogni canale rosso/verde/blu è in float a 32 bit. Altrimenti il file generato utilizzerà colori a 24 bit, ogni canale usa un byte a 8 bit. Il valore predefinito è false, perché non tutte le applicazioni supportano i colori ad alta precisione.

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

### setMasterScale(double value) {#setMasterScale-double-}
```
public void setMasterScale(double value)
```


Imposta la scala principale utilizzata durante l'esportazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

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

