---
title: "Discreet3dsSaveOptions"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Options d'enregistrement pour le fichier 3DS."
type: docs
weight: 44
url: /fr/java/com.aspose.threed/discreet3dssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Discreet3dsSaveOptions extends SaveOptions
```

Options d'enregistrement pour le fichier 3DS.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Discreet3dsSaveOptions()](#Discreet3dsSaveOptions--) | Constructeur de [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDuplicatedNameCounterBase()](#getDuplicatedNameCounterBase--) | Le compteur utilisé pour générer un nouveau nom pour les noms dupliqués, la valeur par défaut est 2. |
| [getDuplicatedNameCounterFormat()](#getDuplicatedNameCounterFormat--) | Le format du compteur dupliqué, la valeur par défaut est une chaîne vide. |
| [getDuplicatedNameSeparator()](#getDuplicatedNameSeparator--) | Le séparateur entre le nom de l'objet et le compteur dupliqué, la valeur par défaut est "\_". |
| [getEncoding()](#getEncoding--) | Obtient le codage par défaut pour les fichiers texte. |
| [getExportCamera()](#getExportCamera--) | Obtient si toutes les caméras sont exportées dans la scène. |
| [getExportLight()](#getExportLight--) | Obtient si toutes les lumières sont exportées dans la scène. |
| [getExportTextures()](#getExportTextures--) | Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [getFileFormat()](#getFileFormat--) | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [getFileName()](#getFileName--) | Le nom de fichier de la scène d'exportation/importation. |
| [getFileSystem()](#getFileSystem--) | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Obtient la classe de fabrique pour FileSystem. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | Obtient le retournement du système de coordonnées des points de contrôle/normales lors de l'importation/exportation. |
| [getGammaCorrectedColor()](#getGammaCorrectedColor--) | Un fichier 3ds peut contenir la couleur originale et la couleur corrigée gamma pour le même attribut. Mettre cela à true utilisera la couleur corrigée gamma si possible, sinon Aspose.3D essaiera d'utiliser la couleur originale. |
| [getHighPreciseColor()](#getHighPreciseColor--) | Si c'est true, le fichier 3ds généré utilisera une couleur haute précision, ce qui signifie que chaque canal rouge/vert/bleu est en virgule flottante 32 bits. |
| [getLookupPaths()](#getLookupPaths--) | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |
| [getMasterScale()](#getMasterScale--) | Obtient l'échelle principale utilisée lors de l'exportation. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDuplicatedNameCounterBase(int value)](#setDuplicatedNameCounterBase-int-) | Le compteur utilisé pour générer un nouveau nom pour les noms dupliqués, la valeur par défaut est 2. |
| [setDuplicatedNameCounterFormat(String value)](#setDuplicatedNameCounterFormat-java.lang.String-) | Le format du compteur dupliqué, la valeur par défaut est une chaîne vide. |
| [setDuplicatedNameSeparator(String value)](#setDuplicatedNameSeparator-java.lang.String-) | Le séparateur entre le nom de l'objet et le compteur dupliqué, la valeur par défaut est "\_". |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Définit le codage par défaut pour les fichiers texte. |
| [setExportCamera(boolean value)](#setExportCamera-boolean-) | Définit si toutes les caméras sont exportées dans la scène. |
| [setExportLight(boolean value)](#setExportLight-boolean-) | Définit si toutes les lumières sont exportées dans la scène. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Le nom de fichier de la scène d'exportation/importation. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Définit la classe de fabrique pour FileSystem. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | Définit le retournement du système de coordonnées des points de contrôle/normales lors de l'importation/exportation. |
| [setGammaCorrectedColor(boolean value)](#setGammaCorrectedColor-boolean-) | Un fichier 3ds peut contenir la couleur originale et la couleur corrigée gamma pour le même attribut. Mettre cela à true utilisera la couleur corrigée gamma si possible, sinon Aspose.3D essaiera d'utiliser la couleur originale. |
| [setHighPreciseColor(boolean value)](#setHighPreciseColor-boolean-) | Si c'est true, le fichier 3ds généré utilisera une couleur haute précision, ce qui signifie que chaque canal rouge/vert/bleu est en virgule flottante 32 bits. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |
| [setMasterScale(double value)](#setMasterScale-double-) | Définit l'échelle principale utilisée lors de l'exportation. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Discreet3dsSaveOptions() {#Discreet3dsSaveOptions--}
```
public Discreet3dsSaveOptions()
```


Constructeur de [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions)

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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


Le compteur utilisé pour générer un nouveau nom pour les noms dupliqués, la valeur par défaut est 2.

**Returns:**
int - Le compteur utilisé pour générer un nouveau nom pour les noms dupliqués, la valeur par défaut est 2.
### getDuplicatedNameCounterFormat() {#getDuplicatedNameCounterFormat--}
```
public String getDuplicatedNameCounterFormat()
```


Le format du compteur dupliqué, la valeur par défaut est une chaîne vide.

**Returns:**
java.lang.String - Le format du compteur dupliqué, la valeur par défaut est une chaîne vide.
### getDuplicatedNameSeparator() {#getDuplicatedNameSeparator--}
```
public String getDuplicatedNameSeparator()
```


Le séparateur entre le nom de l'objet et le compteur dupliqué, la valeur par défaut est "\\_". Lorsque la scène contient des objets qui utilisent le même nom, l'exportateur 3DS d'Aspose.3D générera un nom différent pour l'objet. Par exemple, il y a deux nœuds nommés "Box", le premier nœud aura le nom "Box", et le deuxième nœud recevra un nouveau nom "Box\\_2" en utilisant la configuration par défaut.

**Returns:**
Le séparateur entre le nom de l'objet et le compteur dupliqué, la valeur par défaut est "\\_". Lorsque la scène contient des objets qui utilisent le même nom, l'exportateur 3DS d'Aspose.3D générera un nom différent pour l'objet. Par exemple, il y a deux nœuds nommés "Box", le premier nœud aura le nom "Box", et le deuxième nœud recevra un nouveau nom "Box\\_2" en utilisant la configuration par défaut.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Obtient le codage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera du codage à utiliser.

**Returns:**
java.nio.charset.Charset - le codage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera du codage à utiliser.
### getExportCamera() {#getExportCamera--}
```
public boolean getExportCamera()
```


Obtient si toutes les caméras sont exportées dans la scène.

**Returns:**
boolean - si toutes les caméras sont exportées dans la scène.
### getExportLight() {#getExportLight--}
```
public boolean getExportLight()
```


Obtient si toutes les lumières sont exportées dans la scène.

**Returns:**
boolean - si toutes les lumières sont exportées dans la scène.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie.

**Returns:**
boolean - Tente de copier les textures utilisées dans la scène vers le répertoire de sortie.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ.

**Returns:**
java.lang.String - Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Et vous pouvez également utiliser votre propre implémentation.

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


Obtient la classe de fabrique pour FileSystem. La fabrique par défaut créera com.aspose.threed.LocalFileSystem qui n'est pas adaptée à un environnement serveur.

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


Obtient le retournement du système de coordonnées des points de contrôle/normales lors de l'importation/exportation.

**Returns:**
boolean - inverser le système de coordonnées des points de contrôle/normales lors de l'importation/exportation.
### getGammaCorrectedColor() {#getGammaCorrectedColor--}
```
public boolean getGammaCorrectedColor()
```


Un fichier 3ds peut contenir la couleur originale et la couleur corrigée gamma pour le même attribut. Mettre cela à true utilisera la couleur corrigée gamma si possible, sinon Aspose.3D essaiera d'utiliser la couleur originale.

**Returns:**
boolean - Un fichier 3ds peut contenir la couleur originale et la couleur corrigée gamma pour le même attribut. Mettre cela à true utilisera la couleur corrigée gamma si possible, sinon Aspose.3D essaiera d'utiliser la couleur originale.
### getHighPreciseColor() {#getHighPreciseColor--}
```
public boolean getHighPreciseColor()
```


Si cette valeur est true, le fichier 3ds généré utilisera une couleur haute précision, ce qui signifie que chaque canal rouge/vert/bleu est en virgule flottante 32 bits. Sinon, le fichier généré utilisera une couleur 24 bits, chaque canal utilisant un octet de 8 bits. La valeur par défaut est false, car toutes les applications ne supportent pas la couleur haute précision.

**Returns:**
Si cette valeur est true, le fichier 3ds généré utilisera une couleur haute précision, ce qui signifie que chaque canal rouge/vert/bleu est en virgule flottante 32 bits. Sinon, le fichier généré utilisera une couleur 24 bits, chaque canal utilisant un octet de 8 bits. La valeur par défaut est false, car toutes les applications ne supportent pas la couleur haute précision.
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger.

**Returns:**
java.util.ArrayList<java.lang.String> - Certains fichiers comme OBJ dépendent de fichiers externes, les chemins de recherche permettront à Aspose.3D de rechercher les fichiers externes à charger. **Example:** Le code suivant montre comment spécifier manuellement les textures de recherche, afin que l'importateur puisse les trouver

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


Obtient l'échelle principale utilisée lors de l'exportation.

**Returns:**
double - l'échelle principale utilisée lors de l'exportation.
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


Le compteur utilisé pour générer un nouveau nom pour les noms dupliqués, la valeur par défaut est 2.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setDuplicatedNameCounterFormat(String value) {#setDuplicatedNameCounterFormat-java.lang.String-}
```
public void setDuplicatedNameCounterFormat(String value)
```


Le format du compteur dupliqué, la valeur par défaut est une chaîne vide.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setDuplicatedNameSeparator(String value) {#setDuplicatedNameSeparator-java.lang.String-}
```
public void setDuplicatedNameSeparator(String value)
```


Le séparateur entre le nom de l'objet et le compteur dupliqué, la valeur par défaut est "\\_". Lorsque la scène contient des objets qui utilisent le même nom, l'exportateur 3DS d'Aspose.3D générera un nom différent pour l'objet. Par exemple, il y a deux nœuds nommés "Box", le premier nœud aura le nom "Box", et le deuxième nœud recevra un nouveau nom "Box\\_2" en utilisant la configuration par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset | Nouvelle valeur |

### setExportCamera(boolean value) {#setExportCamera-boolean-}
```
public void setExportCamera(boolean value)
```


Définit si toutes les caméras sont exportées dans la scène.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setExportLight(boolean value) {#setExportLight-boolean-}
```
public void setExportLight(boolean value)
```


Définit si toutes les lumières sont exportées dans la scène.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Nouvelle valeur **Example:** Le système de fichiers par défaut est LocalFileSystem, il n'est pas sûr dans un environnement côté serveur, mais vous pouvez remplacer l'accès au système de fichiers en spécifiant une implémentation différente. Aspose.3D fournit différentes implémentations de FileSystem comme : |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Et vous pouvez également utiliser votre propre implémentation.

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


Définit la classe de fabrique pour FileSystem. La fabrique par défaut créera com.aspose.threed.LocalFileSystem qui n'est pas adaptée à un environnement serveur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Nouvelle valeur **Example:** Le système de fichiers par défaut dans SaveOptions/LoadOptions est un système de fichiers basé sur les répertoires, vous pouvez remplacer l'implémentation par défaut en le spécifiant via IOConfig.FileSystemFactory : |

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


Définit le retournement du système de coordonnées des points de contrôle/normales lors de l'importation/exportation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setGammaCorrectedColor(boolean value) {#setGammaCorrectedColor-boolean-}
```
public void setGammaCorrectedColor(boolean value)
```


Un fichier 3ds peut contenir la couleur originale et la couleur corrigée gamma pour le même attribut. Mettre cela à true utilisera la couleur corrigée gamma si possible, sinon Aspose.3D essaiera d'utiliser la couleur originale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setHighPreciseColor(boolean value) {#setHighPreciseColor-boolean-}
```
public void setHighPreciseColor(boolean value)
```


Si cette valeur est true, le fichier 3ds généré utilisera une couleur haute précision, ce qui signifie que chaque canal rouge/vert/bleu est en virgule flottante 32 bits. Sinon, le fichier généré utilisera une couleur 24 bits, chaque canal utilisant un octet de 8 bits. La valeur par défaut est false, car toutes les applications ne supportent pas la couleur haute précision.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.util.ArrayList<java.lang.String> | Nouvelle valeur **Example:** Le code suivant montre comment spécifier manuellement les textures de recherche, afin que l'importateur puisse les trouver |

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


Définit l'échelle principale utilisée lors de l'exportation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

