---
title: Escena
second_title: Referencia de API de Aspose.3D para Java
description: 
type: docs
weight: 161
url: /es/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | Inicializa una nueva instancia de la clase [Scene](../../com.aspose.threed/scene) con una entidad adjunta a un nuevo nodo. |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | Inicializa una nueva instancia de la clase [Scene](../../com.aspose.threed/scene) como una subescena. |
| [Scene()](#Scene--) | Inicializa una nueva instancia de la clase [Scene](../../com.aspose.threed/scene). |
## Campos

| Campo | Descripción |
| --- | --- |
| [VERSION](#VERSION) | Obtiene la versión de lanzamiento actual |
## Métodos

| Método | Descripción |
| --- | --- |
| [clear()](#clear--) | Borra el contenido de la escena y restaura la configuración predeterminada. |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | Una función abreviada para crear y registrar el [AnimationClip](../../com.aspose.threed/animationclip). El primer [AnimationClip](../../com.aspose.threed/animationclip) se asignará a [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Busca la propiedad. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Abre la escena desde la ruta especificada |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | Abre la escena desde la ruta especificada |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | Abre la escena desde la ruta especificada usando el formato de archivo indicado. |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Abre la escena desde la ruta especificada usando el formato de archivo indicado. |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | Abre la escena desde la ruta especificada usando el formato de archivo indicado. |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Abre la escena desde la ruta especificada usando el formato de archivo indicado. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Abre la escena desde el flujo proporcionado |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Abre la escena desde el flujo proporcionado usando el formato de archivo especificado. |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado usando el formato de archivo especificado. |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada. |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Abre la escena desde el flujo proporcionado |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | Abre la escena desde el flujo proporcionado usando el formato de archivo especificado. |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado usando el formato de archivo especificado. |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada. |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada. |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | Obtiene un [AnimationClip](../../com.aspose.threed/animationclip) con nombre |
| [getAnimationClips()](#getAnimationClips--) | Obtiene todos los [AnimationClip](../../com.aspose.threed/animationclip) definidos en la escena. |
| [getAssetInfo()](#getAssetInfo--) | Obtiene la información de los recursos de nivel superior |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | Obtiene el [AnimationClip](../../com.aspose.threed/animationclip) activo |
| [getLibrary()](#getLibrary--) | Los objetos que no se usan directamente en la jerarquía de la escena pueden definirse en la Biblioteca. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getPoses()](#getPoses--) | Obtiene todas las [Pose](../../com.aspose.threed/pose) usadas en esta escena. |
| [getProperties()](#getProperties--) | Obtiene la colección de todas las propiedades. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtiene el valor de la propiedad especificada |
| [getRootNode()](#getRootNode--) | Obtiene el nodo raíz de la escena. |
| [getScene()](#getScene--) | Obtiene la escena a la que pertenece este objeto. |
| [getSubScenes()](#getSubScenes--) | Obtiene todas las subescenas |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | Abre la escena desde el flujo proporcionado |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Abre la escena desde el flujo proporcionado usando el formato de archivo especificado. |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado usando el formato de archivo especificado. |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada. |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada. |
| [open(InputStream stream)](#open-java.io.InputStream-) | Abre la escena desde el flujo proporcionado |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | Abre la escena desde el flujo proporcionado usando el formato de archivo especificado. |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado usando el formato de archivo especificado. |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada. |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada. |
| [open(String fileName)](#open-java.lang.String-) | Abre la escena desde la ruta especificada |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | Abre la escena desde la ruta especificada |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | Abre la escena desde la ruta especificada usando el formato de archivo indicado. |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Abre la escena desde la ruta especificada usando el formato de archivo indicado. |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | Abre la escena desde la ruta especificada usando el formato de archivo indicado. |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Abre la escena desde la ruta especificada usando el formato de archivo indicado. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Elimina una propiedad dinámica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Elimina la propiedad especificada identificada por nombre. |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | Renderiza la escena en un mapa de bits desde la perspectiva de la cámara especificada. |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | Renderiza la escena en un mapa de bits desde la perspectiva de la cámara especificada. |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | Renderiza la escena en un archivo externo desde la perspectiva de la cámara especificada. |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | Renderiza la escena en un archivo externo desde la perspectiva de la cámara especificada. |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | Renderiza la escena en un archivo externo desde la perspectiva de la cámara especificada. |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Guarda la escena en un flujo usando el formato de archivo especificado. |
| [save(String fileName)](#save-java.lang.String-) | Guarda la escena en la ruta especificada usando el formato de archivo especificado. |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | Guarda la escena en la ruta especificada usando el formato de archivo especificado. |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Guarda la escena en la ruta especificada usando el formato de archivo especificado. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | Guarda la escena en la ruta especificada usando el formato de archivo especificado. |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Guarda la escena en la ruta especificada usando el formato de archivo especificado. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Establece la información del activo de nivel superior |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | Establece el [AnimationClip](../../com.aspose.threed/animationclip) activo |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Establece el valor de la propiedad especificada. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


Inicializa una nueva instancia de la clase [Scene](../../com.aspose.threed/scene) con una entidad adjunta a un nuevo nodo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | La entidad inicial que se adjunta a la escena **Ejemplo:** El siguiente código muestra cómo crear un [getScene](../../com.aspose.threed/scene\#getScene) directamente desde una [Entity](../../com.aspose.threed/entity): |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


Inicializa una nueva instancia de la clase [Scene](../../com.aspose.threed/scene) como una subescena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | La escena padre. |
| nombre | java.lang.String | Nombre de la escena. |

### Scene() {#Scene--}
```
public Scene()
```


Inicializa una nueva instancia de la clase [Scene](../../com.aspose.threed/scene).

### VERSION {#VERSION}
```
public static final String VERSION
```


Obtiene la versión de lanzamiento actual

### clear() {#clear--}
```
public void clear()
```


Borra el contenido de la escena y restaura la configuración predeterminada.

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


Una función abreviada para crear y registrar el [AnimationClip](../../com.aspose.threed/animationclip). El primer [AnimationClip](../../com.aspose.threed/animationclip) se asignará a [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | Nombre del clip de animación |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Busca la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyName | java.lang.String | Nombre de la propiedad. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


Abre la escena desde la ruta especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


Abre la escena desde la ruta especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


Abre la escena desde la ruta especificada usando el formato de archivo indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


Abre la escena desde la ruta especificada usando el formato de archivo indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


Abre la escena desde la ruta especificada usando el formato de archivo indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Abre la escena desde la ruta especificada usando el formato de archivo indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


Abre la escena desde el flujo proporcionado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


Abre la escena desde el flujo proporcionado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


Abre la escena desde el flujo proporcionado usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Abre la escena desde el flujo proporcionado usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


Abre la escena desde el flujo proporcionado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. **Ejemplo:** El siguiente código muestra cómo crear una escena a partir de un flujo con una fuente de token de cancelación |

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


Abre la escena desde el flujo proporcionado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga **Ejemplo:** El siguiente código muestra cómo crear una escena a partir de un flujo con una fuente de token de cancelación |

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


Abre la escena desde el flujo proporcionado usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. **Ejemplo:** El siguiente código muestra cómo crear una escena a partir de un flujo |

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


Abre la escena desde el flujo proporcionado usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga **Ejemplo:** El siguiente código muestra cómo crear una escena a partir de un flujo |

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


Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. **Ejemplo:** El siguiente código muestra cómo crear una escena a partir de un flujo con opciones de carga |

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


Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga **Ejemplo:** El siguiente código muestra cómo crear una escena a partir de un flujo con opciones de carga |

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


Obtiene un [AnimationClip](../../com.aspose.threed/animationclip) con nombre

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre del [AnimationClip](../../com.aspose.threed/animationclip) a buscar |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


Obtiene todos los [AnimationClip](../../com.aspose.threed/animationclip) definidos en la escena.

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - todos los [AnimationClip](../../com.aspose.threed/animationclip) definidos en la escena.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Obtiene la información de los recursos de nivel superior

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


Obtiene el [AnimationClip](../../com.aspose.threed/animationclip) activo

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


Los objetos que no se usan directamente en la jerarquía de la escena pueden definirse en la Biblioteca. Esto es útil cuando utilizas sub-escenas y colocas componentes reutilizables bajo sub-escenas.

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - Los objetos que no se usan directamente en la jerarquía de la escena pueden definirse en la Biblioteca. Esto es útil cuando utilizas sub-escenas y colocas componentes reutilizables bajo sub-escenas.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


Obtiene todas las [Pose](../../com.aspose.threed/pose) usadas en esta escena.

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - todos los [Pose](../../com.aspose.threed/pose) usados en esta escena.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtiene la colección de todas las propiedades.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtiene el valor de la propiedad especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Nombre de la propiedad |

**Returns:**
java.lang.Object - El valor de la propiedad encontrada
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


Obtiene el nodo raíz de la escena.

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


Obtiene la escena a la que pertenece este objeto.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


Obtiene todas las subescenas

**Returns:**
java.util.List<com.aspose.threed.Scene> - todas las sub-escenas
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


Abre la escena desde el flujo proporcionado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


Abre la escena desde el flujo proporcionado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


Abre la escena desde el flujo proporcionado usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Abre la escena desde el flujo proporcionado usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


Abre la escena desde el flujo proporcionado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. **Ejemplo:** El siguiente código muestra cómo abrir una escena desde un flujo |

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


Abre la escena desde el flujo proporcionado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga **Ejemplo:** El siguiente código muestra cómo abrir una escena desde un flujo con un token de cancelación |

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


Abre la escena desde el flujo proporcionado usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. **Ejemplo:** El siguiente código muestra cómo abrir una escena desde un flujo |

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


Abre la escena desde el flujo proporcionado usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga **Ejemplo:** El siguiente código muestra cómo abrir una escena desde un flujo |

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


Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. **Ejemplo:** El siguiente código muestra cómo abrir una escena desde un flujo con opciones de carga adicionales |

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


Abre la escena desde el flujo proporcionado usando la configuración de E/S especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga **Ejemplo:** El siguiente código muestra cómo abrir una escena desde un flujo con opciones de carga adicionales |

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


Abre la escena desde la ruta especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


Abre la escena desde la ruta especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


Abre la escena desde la ruta especificada usando el formato de archivo indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


Abre la escena desde la ruta especificada usando el formato de archivo indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato de archivo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


Abre la escena desde la ruta especificada usando el formato de archivo indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Abre la escena desde la ruta especificada usando el formato de archivo indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Configuración más detallada para abrir el flujo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de carga |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Elimina una propiedad dinámica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Qué propiedad eliminar |

**Returns:**
boolean - verdadero si la propiedad se elimina correctamente
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Elimina la propiedad especificada identificada por nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Qué propiedad eliminar |

**Returns:**
boolean - verdadero si la propiedad se elimina correctamente
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


Renderiza la escena en un mapa de bits desde la perspectiva de la cámara especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Desde la perspectiva de qué cámara renderizar la escena |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Objetivo del resultado renderizado |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


Renderiza la escena en un mapa de bits desde la perspectiva de la cámara especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Desde la perspectiva de qué cámara renderizar la escena |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Objetivo del resultado renderizado |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | La opción para personalizar algunos ajustes internos. |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


Renderiza la escena en un archivo externo desde la perspectiva de la cámara dada. El tamaño de salida predeterminado es 1024x768 y el formato de salida es png

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Desde la perspectiva de qué cámara renderizar la escena |
| fileName | java.lang.String | El nombre de archivo del archivo de salida |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


Renderiza la escena en un archivo externo desde la perspectiva de la cámara especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Desde la perspectiva de qué cámara renderizar la escena |
| fileName | java.lang.String | El nombre de archivo del archivo de salida |
| size | [Vector2](../../com.aspose.threed/vector2) | El tamaño de la imagen renderizada final |
| formato | java.lang.String | El formato de imagen del archivo de salida |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


Renderiza la escena en un archivo externo desde la perspectiva de la cámara especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Desde la perspectiva de qué cámara renderizar la escena |
| fileName | java.lang.String | El nombre de archivo del archivo de salida |
| size | [Vector2](../../com.aspose.threed/vector2) | El tamaño de la imagen renderizada final |
| formato | java.lang.String | El formato de imagen del archivo de salida |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | La opción para personalizar algunos ajustes internos. |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


Guarda la escena en un flujo usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Guarda la escena en un flujo usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de guardado |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


Guarda la escena en un flujo usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuración más detallada para guardar el flujo. |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


Guarda la escena en un flujo usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuración más detallada para guardar el flujo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de guardado |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


Guarda la escena en un flujo usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. **Ejemplo:** El siguiente código muestra cómo guardar la escena |

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


Guarda la escena en un flujo usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de guardado **Ejemplo:** El siguiente código muestra cómo guardar la escena |

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


Guarda la escena en un flujo usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuración más detallada para guardar el flujo. **Ejemplo:** El siguiente código muestra cómo guardar la escena |

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


Guarda la escena en un flujo usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | Flujo de entrada, el usuario es responsable de cerrar el flujo. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuración más detallada para guardar el flujo. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de guardado **Ejemplo:** El siguiente código muestra cómo guardar la escena |

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


Guarda la escena en la ruta especificada usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


Guarda la escena en la ruta especificada usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


Guarda la escena en la ruta especificada usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formato. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de guardado |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Guarda la escena en la ruta especificada usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuración más detallada para guardar el flujo. |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


Guarda la escena en la ruta especificada usando el formato de archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | Nombre del archivo. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Configuración más detallada para guardar el flujo. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Token de cancelación para la tarea de guardado |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Establece la información del activo de nivel superior

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nuevo valor **Ejemplo:** El siguiente código muestra cómo leer la información de la aplicación desde un archivo FBX: |

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


Establece el [AnimationClip](../../com.aspose.threed/animationclip) activo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | Nuevo valor |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Establece el valor de la propiedad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | Nombre de la propiedad |
| valor | java.lang.Object | El valor de la propiedad |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

