---
title: "Scene"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/scene/
---
## Scene class

Una escena es un objeto de nivel superior que contiene los nodos, geometrías, materiales, texturas, animaciones, poses, sub-escenas, etc.  La escena puede tener sub-escenas, funciona como soporte de múltiples documentos en archivos como collada/blender/fbx.  La jerarquía de nodos se puede acceder a través de RootNodeLibrary, que se utiliza para mantener una referencia de objetos no adjuntos durante la serialización (como metadatos u objetos personalizados) para que pueda usarse como una biblioteca.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de la clase Scene. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(entity) | Inicializa una nueva instancia de la clase Scene con una entidad adjunta a un nuevo nodo. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad inicial que se adjuntó a la escena |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2(parentScene, name) | Inicializa una nueva instancia de la clase Scene como una subescena. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| parentScene | Scene | La escena padre. |
| name | Cadena | Nombre de la escena. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nombre | Descripción |
| --- | --- |
| constructor_overload3(fileName) | Inicializa una nueva instancia de la clase Scene y abre el archivo inmediatamente. Este es un constructor obsoleto, por favor use #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | Nombre del archivo a abrir. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| Nombre | Descripción |
| --- | --- |
| getSubScenes() | Obtiene todas las subescenas |

 **Result:**



---


### getLibrary{#getLibrary}

| Nombre | Descripción |
| --- | --- |
| getLibrary() | Los objetos que no se usan directamente en la jerarquía de la escena pueden definirse en Library. Esto es útil cuando utilizas subescenas y colocas componentes reutilizables bajo subescenas. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| Nombre | Descripción |
| --- | --- |
| getAnimationClips() | Obtiene todos los AnimationClip definidos en la escena. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| Nombre | Descripción |
| --- | --- |
| getCurrentAnimationClip() | Obtiene o establece el AnimationClip activo |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| Nombre | Descripción |
| --- | --- |
| setCurrentAnimationClip(value) | Obtiene o establece el AnimationClip activo |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Nombre | Descripción |
| --- | --- |
| getAssetInfo() | Obtiene o establece la información del activo de nivel superior, la información del documento. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Nombre | Descripción |
| --- | --- |
| setAssetInfo(value) | Obtiene o establece la información del activo de nivel superior, la información del documento. |

 **Result:**



---


### getPoses{#getPoses}

| Nombre | Descripción |
| --- | --- |
| getPoses() | Obtiene todas las Pose usadas en esta escena. Las poses. |

 **Result:**



---


### getRootNode{#getRootNode}

| Nombre | Descripción |
| --- | --- |
| getRootNode() | Obtiene el nodo raíz de la escena. El nodo raíz. |

 **Result:**



---


### getScene{#getScene}

| Nombre | Descripción |
| --- | --- |
| getScene() | Obtiene la escena a la que pertenece este objeto |

 **Result:**



---


### getName{#getName}

| Nombre | Descripción |
| --- | --- |
| getName() | Obtiene o establece el nombre. El nombre. |

 **Result:**



---


### setName{#setName}

| Nombre | Descripción |
| --- | --- |
| setName(value) | Obtiene o establece el nombre. El nombre. |

 **Result:**



---


### getProperties{#getProperties}

| Nombre | Descripción |
| --- | --- |
| getProperties() | Obtiene la colección de todas las propiedades. |

 **Result:**



---


### getAnimationClip{#getAnimationClip}

| Nombre | Descripción |
| --- | --- |
| getAnimationClip(name) | Obtiene un AnimationClip con nombre |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | El |

 **Result:**
AnimationClip


---


### clear{#clear}

| Nombre | Descripción |
| --- | --- |
| clear() | Borra el contenido de la escena y restaura la configuración predeterminada. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| Nombre | Descripción |
| --- | --- |
| createAnimationClip(name) | Una función abreviada para crear y registrar el AnimationClip. El primer AnimationClip será asignado al CurrentAnimationClip |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre del clip de animación |

 **Result:**
AnimationClip


---


### open{#open}

| Nombre | Descripción |
| --- | --- |
| open(fileName, options) | Abre la escena desde la ruta especificada usando el formato de archivo indicado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | Nombre del archivo. |
| opciones | LoadOptions | Configuración más detallada para abrir el flujo. |

 **Result:**
AnimationClip


---


### open{#open}

| Nombre | Descripción |
| --- | --- |
| open(fileName) | Abre la escena desde la ruta especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | Nombre del archivo. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| Nombre | Descripción |
| --- | --- |
| fromFile(fileName) | Abre la escena desde la ruta especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | Nombre del archivo. |

 **Result:**
AnimationClip


---


### save{#save}

| Nombre | Descripción |
| --- | --- |
| save(fileName) | Guarda la escena en la ruta especificada usando el formato de archivo indicado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | Nombre del archivo. |

 **Result:**
AnimationClip


---


### save{#save}

| Nombre | Descripción |
| --- | --- |
| save(fileName, format) | Guarda la escena en la ruta especificada usando el formato de archivo indicado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | Nombre del archivo. |
| format | FileFormat | Formato. |

 **Result:**
AnimationClip


---


### save{#save}

| Nombre | Descripción |
| --- | --- |
| save(fileName, options) | Guarda la escena en la ruta especificada usando el formato de archivo indicado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| fileName | Cadena | Nombre del archivo. |
| opciones | SaveOptions | Configuración más detallada para guardar el flujo. |

 **Result:**
AnimationClip


---


### render{#render}

| Nombre | Descripción |
| --- | --- |
| render(camera, fileName) | Renderiza la escena a un archivo externo desde la perspectiva de la cámara dada. El tamaño de salida predeterminado es 1024x768 y el formato de salida es png. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| cámara | Cámara | Desde la perspectiva de cuál cámara renderizar la escena |
| fileName | Cadena | El nombre del archivo de salida |

 **Result:**
AnimationClip


---


### render{#render}

| Nombre | Descripción |
| --- | --- |
| render(camera, fileName, size, format) | Renderiza la escena a un archivo externo desde la perspectiva de la cámara dada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| cámara | Cámara | Desde la perspectiva de cuál cámara renderizar la escena |
| fileName | Cadena | El nombre del archivo de salida |
| tamaño | Vector2 | El tamaño de la imagen renderizada final |
| format | Cadena | El formato de imagen del archivo de salida |

 **Result:**
AnimationClip


---


### render{#render}

| Nombre | Descripción |
| --- | --- |
| render(camera, fileName, size, format, options) | Renderiza la escena a un archivo externo desde la perspectiva de la cámara dada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| cámara | Cámara | Desde la perspectiva de cuál cámara renderizar la escena |
| fileName | Cadena | El nombre del archivo de salida |
| tamaño | Vector2 | El tamaño de la imagen renderizada final |
| format | Cadena | El formato de imagen del archivo de salida |
| opciones | ImageRenderOptions | La opción de personalizar algunos ajustes internos. |

 **Result:**
AnimationClip


---


### render{#render}

| Nombre | Descripción |
| --- | --- |
| render(camera, bitmap) | Renderiza la escena en un bitmap desde la perspectiva de la cámara dada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| cámara | Cámara | Desde la perspectiva de cuál cámara renderizar la escena |
| bitmap | TextureData | Objetivo del resultado renderizado |

 **Result:**
AnimationClip


---


### render{#render}

| Nombre | Descripción |
| --- | --- |
| render(camera, bitmap, options) | Renderiza la escena en un bitmap desde la perspectiva de la cámara dada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| cámara | Cámara | Desde la perspectiva de cuál cámara renderizar la escena |
| bitmap | TextureData | Objetivo del resultado renderizado |
| opciones | ImageRenderOptions | La opción de personalizar algunos ajustes internos. |

 **Result:**
AnimationClip


---


### removeProperty{#removeProperty}

| Nombre | Descripción |
| --- | --- |
| removeProperty(property) | Elimina una propiedad dinámica. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Property | Qué propiedad eliminar |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nombre | Descripción |
| --- | --- |
| removeProperty(property) | Eliminar la propiedad especificada identificada por nombre |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| propert | Cadena | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nombre | Descripción |
| --- | --- |
| getProperty(property) | Obtener el valor de la propiedad especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Cadena | Nombre de la propiedad |

 **Result:**
Objeto


---


### setProperty{#setProperty}

| Nombre | Descripción |
| --- | --- |
| setProperty(property, value) | Establece el valor de la propiedad especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Cadena | Nombre de la propiedad |
| valor | Objeto | El valor de la propiedad |

 **Result:**
Objeto


---


### findProperty{#findProperty}

| Nombre | Descripción |
| --- | --- |
| findProperty(propertyName) | Busca la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| propertyName | Cadena | Nombre de la propiedad. |

 **Result:**
Property


---



