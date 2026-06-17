---
title: "Cámara"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/camera/
---
## Camera class

La cámara describe el punto de vista del observador que mira la escena.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de la clase Camera. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(projectionType) | Inicializa una nueva instancia de la clase Camera. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2(name) | Inicializa una nueva instancia de la clase Camera. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nombre | Descripción |
| --- | --- |
| constructor_overload3(name, projectionType) | Inicializa una nueva instancia de la clase Camera. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre. |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### getApertureMode{#getApertureMode}

| Nombre | Descripción |
| --- | --- |
| getApertureMode() | Obtiene o establece el modo de apertura de la cámara. El valor de la propiedad es la constante entera ApertureMode. |

 **Result:**



---


### setApertureMode{#setApertureMode}

| Nombre | Descripción |
| --- | --- |
| setApertureMode(value) | Obtiene o establece el modo de apertura de la cámara. El valor de la propiedad es la constante entera ApertureMode. |

 **Result:**



---


### getFieldOfView{#getFieldOfView}

| Nombre | Descripción |
| --- | --- |
| getFieldOfView() | Obtiene o establece el campo de visión de la cámara en grados; esta propiedad se usa solo cuando ApertureMode es ApertureMode.HORIZONTAL o ApertureMode.VERTICAL |

 **Result:**



---


### setFieldOfView{#setFieldOfView}

| Nombre | Descripción |
| --- | --- |
| setFieldOfView(value) | Obtiene o establece el campo de visión de la cámara en grados; esta propiedad se usa solo cuando ApertureMode es ApertureMode.HORIZONTAL o ApertureMode.VERTICAL |

 **Result:**



---


### getFieldOfViewX{#getFieldOfViewX}

| Nombre | Descripción |
| --- | --- |
| getFieldOfViewX() | Obtiene o establece el campo de visión horizontal de la cámara en grados; esta propiedad se usa solo cuando ApertureMode es ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### setFieldOfViewX{#setFieldOfViewX}

| Nombre | Descripción |
| --- | --- |
| setFieldOfViewX(value) | Obtiene o establece el campo de visión horizontal de la cámara en grados; esta propiedad se usa solo cuando ApertureMode es ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### getFieldOfViewY{#getFieldOfViewY}

| Nombre | Descripción |
| --- | --- |
| getFieldOfViewY() | Obtiene o establece el campo de visión vertical de la cámara en grados; esta propiedad se usa solo cuando ApertureMode es ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### setFieldOfViewY{#setFieldOfViewY}

| Nombre | Descripción |
| --- | --- |
| setFieldOfViewY(value) | Obtiene o establece el campo de visión vertical de la cámara en grados; esta propiedad se usa solo cuando ApertureMode es ApertureMode.HORIZ_AND_VERT |

 **Result:**



---


### getWidth{#getWidth}

| Nombre | Descripción |
| --- | --- |
| getWidth() | Obtiene o establece el ancho del plano de visión medido en pulgadas. |

 **Result:**



---


### setWidth{#setWidth}

| Nombre | Descripción |
| --- | --- |
| setWidth(value) | Obtiene o establece el ancho del plano de visión medido en pulgadas. |

 **Result:**



---


### getHeight{#getHeight}

| Nombre | Descripción |
| --- | --- |
| getHeight() | Obtiene o establece la altura del plano de visión medido en pulgadas. |

 **Result:**



---


### setHeight{#setHeight}

| Nombre | Descripción |
| --- | --- |
| setHeight(value) | Obtiene o establece la altura del plano de visión medido en pulgadas. |

 **Result:**



---


### getAspectRatio{#getAspectRatio}

| Nombre | Descripción |
| --- | --- |
| getAspectRatio() | Obtiene o establece la relación de aspecto del plano de visión. |

 **Result:**



---


### setAspectRatio{#setAspectRatio}

| Nombre | Descripción |
| --- | --- |
| setAspectRatio(value) | Obtiene o establece la relación de aspecto del plano de visión. |

 **Result:**



---


### getMagnification{#getMagnification}

| Nombre | Descripción |
| --- | --- |
| getMagnification() | Obtiene o establece la ampliación utilizada en la cámara ortográfica. |

 **Result:**



---


### setMagnification{#setMagnification}

| Nombre | Descripción |
| --- | --- |
| setMagnification(value) | Obtiene o establece la ampliación utilizada en la cámara ortográfica. |

 **Result:**



---


### getProjectionType{#getProjectionType}

| Nombre | Descripción |
| --- | --- |
| getProjectionType() | Obtiene o establece el tipo de proyección de la cámara. Por defecto se utiliza la proyección en perspectiva. El valor de la propiedad es la constante entera ProjectionType. |

 **Result:**



---


### setProjectionType{#setProjectionType}

| Nombre | Descripción |
| --- | --- |
| setProjectionType(value) | Obtiene o establece el tipo de proyección de la cámara. Por defecto se utiliza la proyección en perspectiva. El valor de la propiedad es la constante entera ProjectionType. |

 **Result:**



---


### getRotationMode{#getRotationMode}

| Nombre | Descripción |
| --- | --- |
| getRotationMode() | Obtiene o establece el modo de orientación del frustum. Esta propiedad solo funciona cuando Target es nulo. Si el valor es RotationMode.FIXED_TARGET, la dirección siempre se calcula mediante la propiedad LookAt. De lo contrario, LookAt siempre se calcula mediante Direction. El valor de la propiedad es la constante entera RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Nombre | Descripción |
| --- | --- |
| setRotationMode(value) | Obtiene o establece el modo de orientación del frustum. Esta propiedad solo funciona cuando Target es nulo. Si el valor es RotationMode.FIXED_TARGET, la dirección siempre se calcula mediante la propiedad LookAt. De lo contrario, LookAt siempre se calcula mediante Direction. El valor de la propiedad es la constante entera RotationMode. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| Nombre | Descripción |
| --- | --- |
| getNearPlane() | Obtiene o establece la distancia del plano cercano del frustum. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| Nombre | Descripción |
| --- | --- |
| setNearPlane(value) | Obtiene o establece la distancia del plano cercano del frustum. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| Nombre | Descripción |
| --- | --- |
| getFarPlane() | Obtiene o establece la distancia del plano lejano del frustum. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Nombre | Descripción |
| --- | --- |
| setFarPlane(value) | Obtiene o establece la distancia del plano lejano del frustum. |

 **Result:**



---


### getAspect{#getAspect}

| Nombre | Descripción |
| --- | --- |
| getAspect() | Obtiene o establece la relación de aspecto del frustum |

 **Result:**



---


### setAspect{#setAspect}

| Nombre | Descripción |
| --- | --- |
| setAspect(value) | Obtiene o establece la relación de aspecto del frustum |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| Nombre | Descripción |
| --- | --- |
| getOrthoHeight() | Obtiene o establece la altura cuando el frustum está en proyección ortográfica. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Nombre | Descripción |
| --- | --- |
| setOrthoHeight(value) | Obtiene o establece la altura cuando el frustum está en proyección ortográfica. |

 **Result:**



---


### getUp{#getUp}

| Nombre | Descripción |
| --- | --- |
| getUp() | Obtiene o establece la dirección ascendente de la cámara |

 **Result:**



---


### setUp{#setUp}

| Nombre | Descripción |
| --- | --- |
| setUp(value) | Obtiene o establece la dirección ascendente de la cámara |

 **Result:**



---


### getLookAt{#getLookAt}

| Nombre | Descripción |
| --- | --- |
| getLookAt() | Obtiene o establece la posición de interés a la que la cámara está mirando. |

 **Result:**



---


### setLookAt{#setLookAt}

| Nombre | Descripción |
| --- | --- |
| setLookAt(value) | Obtiene o establece la posición de interés a la que la cámara está mirando. |

 **Result:**



---


### getDirection{#getDirection}

| Nombre | Descripción |
| --- | --- |
| getDirection() | Obtiene o establece la dirección a la que la cámara está mirando. Los cambios en esta propiedad también afectarán a LookAt y Target. |

 **Result:**



---


### setDirection{#setDirection}

| Nombre | Descripción |
| --- | --- |
| setDirection(value) | Obtiene o establece la dirección a la que la cámara está mirando. Los cambios en esta propiedad también afectarán a LookAt y Target. |

 **Result:**



---


### getTarget{#getTarget}

| Nombre | Descripción |
| --- | --- |
| getTarget() | Obtiene o establece el objetivo al que la cámara está mirando. Si el usuario admite esta propiedad, debe ser anterior a la propiedad LookAt. |

 **Result:**



---


### setTarget{#setTarget}

| Nombre | Descripción |
| --- | --- |
| setTarget(value) | Obtiene o establece el objetivo al que la cámara está mirando. Si el usuario admite esta propiedad, debe ser anterior a la propiedad LookAt. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nombre | Descripción |
| --- | --- |
| getParentNodes() | Obtiene todos los nodos padre; una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría. Los nodos. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nombre | Descripción |
| --- | --- |
| getExcluded() | Obtiene o establece si excluir esta entidad durante la exportación. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nombre | Descripción |
| --- | --- |
| setExcluded(value) | Obtiene o establece si excluir esta entidad durante la exportación. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nombre | Descripción |
| --- | --- |
| getParentNode() | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. El nodo padre. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nombre | Descripción |
| --- | --- |
| setParentNode(value) | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. El nodo padre. |

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


### moveForward{#moveForward}

| Nombre | Descripción |
| --- | --- |
| moveForward(distance) | Mueve la cámara hacia adelante en su dirección o objetivo. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| distancia | Número | Cuánto tiempo mover hacia adelante |

 **Result:**



---


### getBoundingBox{#getBoundingBox}

| Nombre | Descripción |
| --- | --- |
| getBoundingBox() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |

 **Result:**



---


### getEntityRendererKey{#getEntityRendererKey}

| Nombre | Descripción |
| --- | --- |
| getEntityRendererKey() | Obtiene la clave del renderizador de entidad registrado en el renderizador |

 **Result:**
EntityRendererKey


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



