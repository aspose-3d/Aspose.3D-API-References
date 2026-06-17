---
title: "Light"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/light/
---
## Light class

La luz ilumina la escena.  La fórmula para calcular la atenuación total de la luz es:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation)


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de la clase Light. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(name) | Inicializa una nueva instancia de la clase Light. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2(name, type) | Inicializa una nueva instancia de la clase Light. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre |
| type | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| Nombre | Descripción |
| --- | --- |
| getColor() | Obtiene o establece el color de la luz |

 **Result:**



---


### setColor{#setColor}

| Nombre | Descripción |
| --- | --- |
| setColor(value) | Obtiene o establece el color de la luz |

 **Result:**



---


### getLightType{#getLightType}

| Nombre | Descripción |
| --- | --- |
| getLightType() | Obtiene o establece el tipo de la luz. El valor de la propiedad es la constante entera LightType. |

 **Result:**



---


### setLightType{#setLightType}

| Nombre | Descripción |
| --- | --- |
| setLightType(value) | Obtiene o establece el tipo de la luz. El valor de la propiedad es la constante entera LightType. |

 **Result:**



---


### getCastLight{#getCastLight}

| Nombre | Descripción |
| --- | --- |
| getCastLight() | Obtiene o establece si la instancia actual de luz puede iluminar otros objetos. |

 **Result:**



---


### setCastLight{#setCastLight}

| Nombre | Descripción |
| --- | --- |
| setCastLight(value) | Obtiene o establece si la instancia actual de luz puede iluminar otros objetos. |

 **Result:**



---


### getIntensity{#getIntensity}

| Nombre | Descripción |
| --- | --- |
| getIntensity() | Obtiene o establece la intensidad de la luz, el valor predeterminado es 100 |

 **Result:**



---


### setIntensity{#setIntensity}

| Nombre | Descripción |
| --- | --- |
| setIntensity(value) | Obtiene o establece la intensidad de la luz, el valor predeterminado es 100 |

 **Result:**



---


### getHotSpot{#getHotSpot}

| Nombre | Descripción |
| --- | --- |
| getHotSpot() | Obtiene o establece el ángulo del cono del punto caliente(in grados). |

 **Result:**



---


### setHotSpot{#setHotSpot}

| Nombre | Descripción |
| --- | --- |
| setHotSpot(value) | Obtiene o establece el ángulo del cono del punto caliente(in grados). |

 **Result:**



---


### getFalloff{#getFalloff}

| Nombre | Descripción |
| --- | --- |
| getFalloff() | Obtiene o establece el ángulo del cono de atenuación (en grados). |

 **Result:**



---


### setFalloff{#setFalloff}

| Nombre | Descripción |
| --- | --- |
| setFalloff(value) | Obtiene o establece el ángulo del cono de atenuación (en grados). |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| Nombre | Descripción |
| --- | --- |
| getConstantAttenuation() | Obtiene o establece la atenuación constante para calcular la atenuación total de la luz |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| Nombre | Descripción |
| --- | --- |
| setConstantAttenuation(value) | Obtiene o establece la atenuación constante para calcular la atenuación total de la luz |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| Nombre | Descripción |
| --- | --- |
| getLinearAttenuation() | Obtiene o establece la atenuación lineal para calcular la atenuación total de la luz |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| Nombre | Descripción |
| --- | --- |
| setLinearAttenuation(value) | Obtiene o establece la atenuación lineal para calcular la atenuación total de la luz |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| Nombre | Descripción |
| --- | --- |
| getQuadraticAttenuation() | Obtiene o establece la atenuación cuadrática para calcular la atenuación total de la luz |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| Nombre | Descripción |
| --- | --- |
| setQuadraticAttenuation(value) | Obtiene o establece la atenuación cuadrática para calcular la atenuación total de la luz |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nombre | Descripción |
| --- | --- |
| getCastShadows() | Obtiene o establece si la luz puede proyectar sombras sobre otros objetos. |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nombre | Descripción |
| --- | --- |
| setCastShadows(value) | Obtiene o establece si la luz puede proyectar sombras sobre otros objetos. |

 **Result:**



---


### getShadowColor{#getShadowColor}

| Nombre | Descripción |
| --- | --- |
| getShadowColor() | Obtiene o establece el color de la sombra. |

 **Result:**



---


### setShadowColor{#setShadowColor}

| Nombre | Descripción |
| --- | --- |
| setShadowColor(value) | Obtiene o establece el color de la sombra. |

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



