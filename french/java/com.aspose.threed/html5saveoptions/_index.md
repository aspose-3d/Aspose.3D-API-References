---
title: "Html5SaveOptions"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Options d'enregistrement pour HTML5"
type: docs
weight: 80
url: /fr/java/com.aspose.threed/html5saveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Html5SaveOptions extends SaveOptions
```

Options d'enregistrement pour HTML5
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Html5SaveOptions()](#Html5SaveOptions--) | Constructeur de [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) avec tous les paramètres par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Obtient la position initiale de la caméra, la valeur par défaut est (10, 10, 10) |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Obtient le codage par défaut pour les fichiers texte. |
| [getExportTextures()](#getExportTextures--) | Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [getFarPlane()](#getFarPlane--) | Obtient le plan lointain de la caméra, la valeur par défaut est 1000. |
| [getFieldOfView()](#getFieldOfView--) | Obtient le champ de vision, la valeur par défaut est 45, mesurée en degrés. |
| [getFileFormat()](#getFileFormat--) | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [getFileName()](#getFileName--) | Le nom de fichier de la scène d'exportation/importation. |
| [getFileSystem()](#getFileSystem--) | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Obtient la classe de fabrique pour FileSystem. |
| [getLookAt()](#getLookAt--) | Obtient la position de regard par défaut, la valeur par défaut est (0, 0, 0) |
| [getLookupPaths()](#getLookupPaths--) | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |
| [getNearPlane()](#getNearPlane--) | Obtient le plan proche de la caméra, la valeur par défaut est 1 |
| [getOrientationBox()](#getOrientationBox--) | Affiche une boîte d'orientation. |
| [getShowGrid()](#getShowGrid--) | Affiche une grille dans la scène. |
| [getShowRulers()](#getShowRulers--) | Affiche des règles des axes x/y/z dans la scène pour mesurer le modèle. |
| [getShowUI()](#getShowUI--) | Affiche une interface utilisateur simple dans la scène. |
| [getUpVector()](#getUpVector--) | Obtient le vecteur up, la valeur peut être "x"/"y"/"z", la valeur par défaut est "y" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(Vector3 value)](#setCameraPosition-com.aspose.threed.Vector3-) | Définit la position initiale de la caméra, la valeur par défaut est (10, 10, 10) |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Définit le codage par défaut pour les fichiers texte. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [setFarPlane(double value)](#setFarPlane-double-) | Définit le plan lointain de la caméra, la valeur par défaut est 1000. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Définit le champ de la vue, la valeur par défaut est 45, mesurée en degrés. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Le nom de fichier de la scène d'exportation/importation. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Définit la classe de fabrique pour FileSystem. |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Définit la position de regard par défaut, la valeur par défaut est (0, 0, 0) |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |
| [setNearPlane(double value)](#setNearPlane-double-) | Définit le plan proche de la caméra, la valeur par défaut est 1 |
| [setOrientationBox(boolean value)](#setOrientationBox-boolean-) | Affiche une boîte d'orientation. |
| [setShowGrid(boolean value)](#setShowGrid-boolean-) | Affiche une grille dans la scène. |
| [setShowRulers(boolean value)](#setShowRulers-boolean-) | Affiche des règles des axes x/y/z dans la scène pour mesurer le modèle. |
| [setShowUI(boolean value)](#setShowUI-boolean-) | Affiche une interface utilisateur simple dans la scène. |
| [setUpVector(String value)](#setUpVector-java.lang.String-) | Définit le vecteur up, la valeur peut être "x"/"y"/"z", la valeur par défaut est "y" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Html5SaveOptions() {#Html5SaveOptions--}
```
public Html5SaveOptions()
```


Constructeur de [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) avec tous les paramètres par défaut.

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
### getCameraPosition() {#getCameraPosition--}
```
public Vector3 getCameraPosition()
```


Obtient la position initiale de la caméra, la valeur par défaut est (10, 10, 10)

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


Obtient le codage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera du codage à utiliser.

**Returns:**
java.nio.charset.Charset - le codage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera du codage à utiliser.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie.

**Returns:**
boolean - Tente de copier les textures utilisées dans la scène vers le répertoire de sortie.
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Obtient le plan lointain de la caméra, la valeur par défaut est 1000.

**Returns:**
double - le plan lointain de la caméra, la valeur par défaut est 1000.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Obtient le champ de vision, la valeur par défaut est 45, mesurée en degrés.

**Returns:**
double - le champ de la vue, la valeur par défaut est 45, mesurée en degrés.
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
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Obtient la position de regard par défaut, la valeur par défaut est (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the default look at position, default value is (0, 0, 0)
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
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Obtient le plan proche de la caméra, la valeur par défaut est 1

**Returns:**
double - le plan proche de la caméra, la valeur par défaut est 1
### getOrientationBox() {#getOrientationBox--}
```
public boolean getOrientationBox()
```


Affiche une boîte d'orientation. La valeur par défaut est true.

**Returns:**
boolean - Affiche une boîte d'orientation. La valeur par défaut est true.
### getShowGrid() {#getShowGrid--}
```
public boolean getShowGrid()
```


Affiche une grille dans la scène. La valeur par défaut est true.

**Returns:**
boolean - Affiche une grille dans la scène. La valeur par défaut est true.
### getShowRulers() {#getShowRulers--}
```
public boolean getShowRulers()
```


Affiche des règles des axes x/y/z dans la scène pour mesurer le modèle. La valeur par défaut est false.

**Returns:**
boolean - Affiche des règles des axes x/y/z dans la scène pour mesurer le modèle. La valeur par défaut est false.
### getShowUI() {#getShowUI--}
```
public boolean getShowUI()
```


Affiche une interface utilisateur simple dans la scène. La valeur par défaut est true.

**Returns:**
boolean - Affiche une interface utilisateur simple dans la scène. La valeur par défaut est true.
### getUpVector() {#getUpVector--}
```
public String getUpVector()
```


Obtient le vecteur up, la valeur peut être "x"/"y"/"z", la valeur par défaut est "y"

**Returns:**
java.lang.String - le vecteur up, la valeur peut être "x"/"y"/"z", la valeur par défaut est "y"
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


Définit la position initiale de la caméra, la valeur par défaut est (10, 10, 10)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset | Nouvelle valeur |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Définit le plan lointain de la caméra, la valeur par défaut est 1000.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Définit le champ de la vue, la valeur par défaut est 45, mesurée en degrés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

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

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Définit la position de regard par défaut, la valeur par défaut est (0, 0, 0)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

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

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Définit le plan proche de la caméra, la valeur par défaut est 1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setOrientationBox(boolean value) {#setOrientationBox-boolean-}
```
public void setOrientationBox(boolean value)
```


Affiche une boîte d'orientation. La valeur par défaut est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setShowGrid(boolean value) {#setShowGrid-boolean-}
```
public void setShowGrid(boolean value)
```


Affiche une grille dans la scène. La valeur par défaut est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setShowRulers(boolean value) {#setShowRulers-boolean-}
```
public void setShowRulers(boolean value)
```


Affiche des règles des axes x/y/z dans la scène pour mesurer le modèle. La valeur par défaut est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setShowUI(boolean value) {#setShowUI-boolean-}
```
public void setShowUI(boolean value)
```


Affiche une interface utilisateur simple dans la scène. La valeur par défaut est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setUpVector(String value) {#setUpVector-java.lang.String-}
```
public void setUpVector(String value)
```


Définit le vecteur up, la valeur peut être "x"/"y"/"z", la valeur par défaut est "y"

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

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

