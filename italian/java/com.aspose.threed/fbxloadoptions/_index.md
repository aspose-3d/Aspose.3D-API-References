---
title: FbxLoadOptions
second_title: Aspose.3D for Java API Reference
description: Opzioni di caricamento per il formato Fbx.
type: docs
weight: 62
url: /it/java/com.aspose.threed/fbxloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class FbxLoadOptions extends LoadOptions
```

Opzioni di caricamento per il formato Fbx.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FbxLoadOptions(FileFormat format)](#FbxLoadOptions-com.aspose.threed.FileFormat-) | Costruttore di [FbxLoadOptions](../../com.aspose.threed/fbxloadoptions) |
| [FbxLoadOptions()](#FbxLoadOptions--) | Costruttore di [FbxLoadOptions](../../com.aspose.threed/fbxloadoptions) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompatibleMode()](#getCompatibleMode--) | Ottiene se abilitare la modalità compatibile. |
| [getEncoding()](#getEncoding--) | Restituisce la codifica predefinita per i file di testo. |
| [getFileFormat()](#getFileFormat--) | Restituisce il formato file specificato nell'opzione Salva/Carica corrente. |
| [getFileName()](#getFileName--) | Il nome file della scena di esportazione/importazione. |
| [getFileSystem()](#getFileSystem--) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Restituisce la classe factory per FileSystem. |
| [getKeepBuiltinGlobalSettings()](#getKeepBuiltinGlobalSettings--) | Ottiene se mantenere le proprietà integrate in GlobalSettings che hanno una sostituzione di proprietà nativa in [AssetInfo](../../com.aspose.threed/assetinfo). |
| [getLookupPaths()](#getLookupPaths--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompatibleMode(boolean value)](#setCompatibleMode-boolean-) | Imposta se abilitare la modalità compatibile. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Imposta la codifica predefinita per i file di testo. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Il nome file della scena di esportazione/importazione. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Imposta la classe factory per FileSystem. |
| [setKeepBuiltinGlobalSettings(boolean value)](#setKeepBuiltinGlobalSettings-boolean-) | Imposta se mantenere le proprietà integrate in GlobalSettings che hanno una sostituzione di proprietà nativa in [AssetInfo](../../com.aspose.threed/assetinfo). |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxLoadOptions(FileFormat format) {#FbxLoadOptions-com.aspose.threed.FileFormat-}
```
public FbxLoadOptions(FileFormat format)
```


Costruttore di [FbxLoadOptions](../../com.aspose.threed/fbxloadoptions)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Istanza di [getFileFormat](../../com.aspose.threed/fbxloadoptions\#getFileFormat), dovrebbe essere un formato FBX valido. |

### FbxLoadOptions() {#FbxLoadOptions--}
```
public FbxLoadOptions()
```


Costruttore di [FbxLoadOptions](../../com.aspose.threed/fbxloadoptions)

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
### getCompatibleMode() {#getCompatibleMode--}
```
public boolean getCompatibleMode()
```


Ottiene se abilitare la modalità compatibile. La modalità compatibile cercherà di supportare definizioni FBX non standard come i materiali PBR esportati da Blender. Il valore predefinito è false.

**Returns:**
boolean - se abilitare la modalità compatibile. La modalità compatibile cercherà di supportare definizioni FBX non standard come i materiali PBR esportati da Blender. Il valore predefinito è false.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Restituisce la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.

**Returns:**
java.nio.charset.Charset - la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.
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
### getKeepBuiltinGlobalSettings() {#getKeepBuiltinGlobalSettings--}
```
public boolean getKeepBuiltinGlobalSettings()
```


Ottiene se mantenere le proprietà integrate in GlobalSettings che hanno una sostituzione di proprietà nativa in [AssetInfo](../../com.aspose.threed/assetinfo). Imposta questo su true se desideri le proprietà complete in GlobalSettings. Il valore predefinito è false

**Returns:**
boolean - se mantenere le proprietà integrate in GlobalSettings che hanno una sostituzione di proprietà nativa in [AssetInfo](../../com.aspose.threed/assetinfo). Imposta questo su true se desideri le proprietà complete in GlobalSettings. Il valore predefinito è false
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




### setCompatibleMode(boolean value) {#setCompatibleMode-boolean-}
```
public void setCompatibleMode(boolean value)
```


Imposta se abilitare la modalità compatibile. La modalità compatibile cercherà di supportare definizioni FBX non standard come i materiali PBR esportati da Blender. Il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Imposta la codifica predefinita per i file basati su testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset | Nuovo valore |

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

### setKeepBuiltinGlobalSettings(boolean value) {#setKeepBuiltinGlobalSettings-boolean-}
```
public void setKeepBuiltinGlobalSettings(boolean value)
```


Imposta se mantenere le proprietà integrate in GlobalSettings che hanno una sostituzione di proprietà nativa in [AssetInfo](../../com.aspose.threed/assetinfo). Imposta questo su true se desideri le proprietà complete in GlobalSettings. Il valore predefinito è false

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

