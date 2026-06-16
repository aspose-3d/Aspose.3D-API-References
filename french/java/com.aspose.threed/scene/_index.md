---
title: "Scène"
second_title: "Référence d'API Aspose.3D pour Java"
description: 
type: docs
weight: 161
url: /fr/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | Initialise une nouvelle instance de la classe [Scene](../../com.aspose.threed/scene) avec une entité attachée à un nouveau nœud. |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | Initialise une nouvelle instance de la classe [Scene](../../com.aspose.threed/scene) en tant que sous‑scène. |
| [Scene()](#Scene--) | Initialise une nouvelle instance de la classe [Scene](../../com.aspose.threed/scene). |
## Champs

| Champ | Description |
| --- | --- |
| [VERSION](#VERSION) | Obtient la version de publication actuelle |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clear()](#clear--) | Efface le contenu de la scène et restaure les paramètres par défaut. |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | Une fonction raccourcie pour créer et enregistrer le [AnimationClip](../../com.aspose.threed/animationclip). Le premier [AnimationClip](../../com.aspose.threed/animationclip) sera assigné à [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Ouvre la scène depuis le chemin fourni |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le chemin fourni |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié. |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié. |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié. |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Ouvre la scène depuis le flux fourni |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié. |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié. |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée. |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Ouvre la scène depuis le flux fourni |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié. |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié. |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée. |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée. |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | Obtient un [AnimationClip](../../com.aspose.threed/animationclip) nommé |
| [getAnimationClips()](#getAnimationClips--) | Obtient tous les [AnimationClip](../../com.aspose.threed/animationclip) définis dans la scène. |
| [getAssetInfo()](#getAssetInfo--) | Obtient les informations de l’actif de niveau supérieur |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | Obtient le [AnimationClip](../../com.aspose.threed/animationclip) actif |
| [getLibrary()](#getLibrary--) | Les objets qui ne sont pas directement utilisés dans la hiérarchie de la scène peuvent être définis dans la Bibliothèque. |
| [getName()](#getName--) | Obtient le nom. |
| [getPoses()](#getPoses--) | Obtient toutes les [Pose](../../com.aspose.threed/pose) utilisées dans cette scène. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getRootNode()](#getRootNode--) | Obtient le nœud racine de la scène. |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getSubScenes()](#getSubScenes--) | Obtient toutes les sous‑scènes |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | Ouvre la scène depuis le flux fourni |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié. |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié. |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée. |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée. |
| [open(InputStream stream)](#open-java.io.InputStream-) | Ouvre la scène depuis le flux fourni |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié. |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié. |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée. |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée. |
| [open(String fileName)](#open-java.lang.String-) | Ouvre la scène depuis le chemin fourni |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le chemin fourni |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié. |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié. |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié. |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | Rendre la scène en bitmap depuis la perspective de la caméra donnée. |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | Rendre la scène en bitmap depuis la perspective de la caméra donnée. |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | Rendre la scène dans un fichier externe depuis la perspective de la caméra donnée. |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | Rendre la scène dans un fichier externe depuis la perspective de la caméra donnée. |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | Rendre la scène dans un fichier externe depuis la perspective de la caméra donnée. |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [save(String fileName)](#save-java.lang.String-) | Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié. |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié. |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié. |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Définit les informations de l'actif de niveau supérieur |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | Définit le [AnimationClip](../../com.aspose.threed/animationclip) actif |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


Initialise une nouvelle instance de la classe [Scene](../../com.aspose.threed/scene) avec une entité attachée à un nouveau nœud.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | L'entité initiale qui est attachée à la scène **Example:** Le code suivant montre comment créer un [getScene](../../com.aspose.threed/scene\#getScene) directement à partir d'une [Entity](../../com.aspose.threed/entity) : |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


Initialise une nouvelle instance de la classe [Scene](../../com.aspose.threed/scene) en tant que sous‑scène.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | La scène parente. |
| nom | java.lang.String | Nom de la scène. |

### Scene() {#Scene--}
```
public Scene()
```


Initialise une nouvelle instance de la classe [Scene](../../com.aspose.threed/scene).

### VERSION {#VERSION}
```
public static final String VERSION
```


Obtient la version de publication actuelle

### clear() {#clear--}
```
public void clear()
```


Efface le contenu de la scène et restaure les paramètres par défaut.

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


Une fonction raccourcie pour créer et enregistrer le [AnimationClip](../../com.aspose.threed/animationclip). Le premier [AnimationClip](../../com.aspose.threed/animationclip) sera assigné à [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom du clip d'animation |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | Nom de la propriété. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


Ouvre la scène depuis le chemin fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


Ouvre la scène depuis le chemin fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


Ouvre la scène depuis le flux fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


Ouvre la scène depuis le flux fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


Ouvre la scène depuis le flux fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. **Example:** Le code suivant montre comment créer une scène à partir d'un flux avec une source de jeton d'annulation |

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


Ouvre la scène depuis le flux fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement **Example:** Le code suivant montre comment créer une scène à partir d'un flux avec une source de jeton d'annulation |

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


Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. **Example:** Le code suivant montre comment créer une scène à partir d'un flux |

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


Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement **Example:** Le code suivant montre comment créer une scène à partir d'un flux |

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


Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. **Example:** Le code suivant montre comment créer une scène à partir d'un flux avec des options de chargement |

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


Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement **Example:** Le code suivant montre comment créer une scène à partir d'un flux avec des options de chargement |

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


Obtient un [AnimationClip](../../com.aspose.threed/animationclip) nommé

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Le nom du [AnimationClip](../../com.aspose.threed/animationclip) à rechercher |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


Obtient tous les [AnimationClip](../../com.aspose.threed/animationclip) définis dans la scène.

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - tous les [AnimationClip](../../com.aspose.threed/animationclip) définis dans la scène.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Obtient les informations de l’actif de niveau supérieur

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


Obtient le [AnimationClip](../../com.aspose.threed/animationclip) actif

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


Les objets qui ne sont pas directement utilisés dans la hiérarchie de la scène peuvent être définis dans la Bibliothèque. Ceci est utile lorsque vous utilisez des sous‑scènes et placez des composants réutilisables sous les sous‑scènes.

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - Les objets qui ne sont pas directement utilisés dans la hiérarchie de la scène peuvent être définis dans la Bibliothèque. Ceci est utile lorsque vous utilisez des sous‑scènes et placez des composants réutilisables sous les sous‑scènes.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


Obtient toutes les [Pose](../../com.aspose.threed/pose) utilisées dans cette scène.

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - tous les [Pose](../../com.aspose.threed/pose) utilisés dans cette scène.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtient la collection de toutes les propriétés.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtenir la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |

**Returns:**
java.lang.Object - La valeur de la propriété trouvée
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


Obtient le nœud racine de la scène.

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


Obtient la scène à laquelle cet objet appartient

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


Obtient toutes les sous‑scènes

**Returns:**
java.util.List<com.aspose.threed.Scene> - toutes les sous‑scènes
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


Ouvre la scène depuis le flux fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


Ouvre la scène depuis le flux fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


Ouvre la scène depuis le flux fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. **Example:** Le code suivant montre comment ouvrir une scène à partir d'un flux |

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


Ouvre la scène depuis le flux fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement **Exemple :** Le code suivant montre comment ouvrir une scène depuis un flux avec un jeton d'annulation |

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


Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. **Exemple :** Le code suivant montre comment ouvrir une scène depuis un flux |

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


Ouvre la scène depuis le flux fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement **Exemple :** Le code suivant montre comment ouvrir une scène depuis un flux |

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


Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. **Exemple :** Le code suivant montre comment ouvrir une scène depuis un flux avec des options de chargement supplémentaires |

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


Ouvre la scène depuis le flux fourni en utilisant la configuration d'E/S spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement **Exemple :** Le code suivant montre comment ouvrir une scène depuis un flux avec des options de chargement supplémentaires |

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


Ouvre la scène depuis le chemin fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


Ouvre la scène depuis le chemin fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format de fichier. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuration plus détaillée pour ouvrir le flux. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche de chargement |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Supprime une propriété dynamique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Supprime la propriété spécifiée identifiée par son nom

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


Rendre la scène en bitmap depuis la perspective de la caméra donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Depuis quelle perspective de caméra rendre la scène |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Cible du résultat rendu |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


Rendre la scène en bitmap depuis la perspective de la caméra donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Depuis quelle perspective de caméra rendre la scène |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Cible du résultat rendu |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | L'option de personnaliser certains paramètres internes. |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


Rendre la scène dans un fichier externe depuis la perspective de la caméra donnée. La taille de sortie par défaut est 1024x768 et le format de sortie est png

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Depuis quelle perspective de caméra rendre la scène |
| fileName | java.lang.String | Le nom du fichier de sortie |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


Rendre la scène dans un fichier externe depuis la perspective de la caméra donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Depuis quelle perspective de caméra rendre la scène |
| fileName | java.lang.String | Le nom du fichier de sortie |
| size | [Vector2](../../com.aspose.threed/vector2) | La taille de l'image rendue finale |
| format | java.lang.String | Le format d'image du fichier de sortie |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


Rendre la scène dans un fichier externe depuis la perspective de la caméra donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Depuis quelle perspective de caméra rendre la scène |
| fileName | java.lang.String | Le nom du fichier de sortie |
| size | [Vector2](../../com.aspose.threed/vector2) | La taille de l'image rendue finale |
| format | java.lang.String | Le format d'image du fichier de sortie |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | L'option de personnaliser certains paramètres internes. |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche d'enregistrement |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuration plus détaillée pour enregistrer le flux. |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuration plus détaillée pour enregistrer le flux. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche d'enregistrement |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Format. **Exemple :** Le code suivant montre comment enregistrer la scène |

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


Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche d'enregistrement **Exemple :** Le code suivant montre comment enregistrer la scène |

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


Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuration plus détaillée pour enregistrer le flux. **Exemple :** Le code suivant montre comment enregistrer la scène |

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


Enregistre la scène dans le flux en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream | Flux d'entrée, l'utilisateur est responsable de la fermeture du flux. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuration plus détaillée pour enregistrer le flux. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche d'enregistrement **Exemple :** Le code suivant montre comment enregistrer la scène |

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


Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche d'enregistrement |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuration plus détaillée pour enregistrer le flux. |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Nom du fichier. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuration plus détaillée pour enregistrer le flux. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Jeton d'annulation pour la tâche d'enregistrement |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Définit les informations de l'actif de niveau supérieur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nouvelle valeur **Exemple :** Le code suivant montre comment lire les informations de l'application depuis un fichier FBX : |

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


Définit le [AnimationClip](../../com.aspose.threed/animationclip) actif

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Définit la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |
| valeur | java.lang.Object | La valeur de la propriété |

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

