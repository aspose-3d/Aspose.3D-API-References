---
title: "Cilindro"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

Cilindro parametrizado. También puede usarse para representar el cono cuando uno de radiusTop/radiusBottom es cero.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de la clase Cylinder. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(radius, height) | Inicializa una nueva instancia de la clase Cylinder. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| radius | Número | Radio de la tapa superior e inferior. |
| height | Número | Altura. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Inicializa una nueva instancia de la clase Cylinder. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| radiusTop | Número | Radio superior. |
| radiusBottom | Número | Radio inferior. |
| height | Número | Altura. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nombre | Descripción |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Inicializa una nueva instancia de la clase Cylinder. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| radiusTop | Número | Radio de la tapa superior del cilindro. |
| radiusBottom | Número | Radio de la tapa inferior del cilindro. |
| height | Número | Altura del cilindro. |
| radialSegments | Número | Segmentos radiales de ambos círculos superior e inferior.. |
| heightSegments | Número | Segmentos de altura. |
| openEnded | boolean | Si se establece en |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nombre | Descripción |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Inicializa una nueva instancia de la clase Cylinder. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | El nombre de este objeto |
| radiusTop | Número | Radio de la tapa superior del cilindro. |
| radiusBottom | Número | Radio de la tapa inferior del cilindro. |
| height | Número | Altura del cilindro. |
| radialSegments | Número | Segmentos radiales de ambos círculos superior e inferior.. |
| heightSegments | Número | Segmentos de altura. |
| openEnded | boolean | Si se establece en |
| thetaStart | Número | Inicio de Theta. |
| thetaLength | Número | Longitud de Theta. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| Nombre | Descripción |
| --- | --- |
| getOffsetBottom() | Obtiene o establece el desplazamiento de transformación de los vértices del lado inferior. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| Nombre | Descripción |
| --- | --- |
| setOffsetBottom(value) | Obtiene o establece el desplazamiento de transformación de los vértices del lado inferior. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| Nombre | Descripción |
| --- | --- |
| getOffsetTop() | Obtiene o establece el desplazamiento de transformación de los vértices del lado superior. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| Nombre | Descripción |
| --- | --- |
| setOffsetTop(value) | Obtiene o establece el desplazamiento de transformación de los vértices del lado superior. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| Nombre | Descripción |
| --- | --- |
| getGenerateFanCylinder() | Obtiene o establece si generar el cilindro estilo abanico cuando ThetaLength es menor que 2PI, de lo contrario el modelo no se recortará. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| Nombre | Descripción |
| --- | --- |
| setGenerateFanCylinder(value) | Obtiene o establece si generar el cilindro estilo abanico cuando ThetaLength es menor que 2PI, de lo contrario el modelo no se recortará. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| Nombre | Descripción |
| --- | --- |
| getShearBottom() | Obtiene o establece la transformación de cizallamiento del lado inferior, el vector almacena el valor de cizallamiento (x-axis, z-axis) medido en radianes, el valor predeterminado es (0, 0) |

 **Result:**



---


### setShearBottom{#setShearBottom}

| Nombre | Descripción |
| --- | --- |
| setShearBottom(value) | Obtiene o establece la transformación de cizallamiento del lado inferior, el vector almacena el valor de cizallamiento (x-axis, z-axis) medido en radianes, el valor predeterminado es (0, 0) |

 **Result:**



---


### getShearTop{#getShearTop}

| Nombre | Descripción |
| --- | --- |
| getShearTop() | Obtiene o establece la transformación de cizallamiento del lado superior, el vector almacena el valor de cizallamiento (x-axis, z-axis) medido en radianes, el valor predeterminado es (0, 0) |

 **Result:**



---


### setShearTop{#setShearTop}

| Nombre | Descripción |
| --- | --- |
| setShearTop(value) | Obtiene o establece la transformación de cizallamiento del lado superior, el vector almacena el valor de cizallamiento (x-axis, z-axis) medido en radianes, el valor predeterminado es (0, 0) |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| Nombre | Descripción |
| --- | --- |
| getRadiusTop() | Obtiene o establece el radio de la tapa superior del cilindro. El radio de la tapa superior. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| Nombre | Descripción |
| --- | --- |
| setRadiusTop(value) | Obtiene o establece el radio de la tapa superior del cilindro. El radio de la tapa superior. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| Nombre | Descripción |
| --- | --- |
| getRadiusBottom() | Obtiene o establece el radio de la tapa inferior del cilindro. El radio de la tapa inferior. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| Nombre | Descripción |
| --- | --- |
| setRadiusBottom(value) | Obtiene o establece el radio de la tapa inferior del cilindro. El radio de la tapa inferior. |

 **Result:**



---


### getHeight{#getHeight}

| Nombre | Descripción |
| --- | --- |
| getHeight() | Obtiene o establece la altura del cilindro. La altura. |

 **Result:**



---


### setHeight{#setHeight}

| Nombre | Descripción |
| --- | --- |
| setHeight(value) | Obtiene o establece la altura del cilindro. La altura. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| Nombre | Descripción |
| --- | --- |
| getRadialSegments() | Obtiene o establece los segmentos radiales. Los segmentos radiales. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| Nombre | Descripción |
| --- | --- |
| setRadialSegments(value) | Obtiene o establece los segmentos radiales. Los segmentos radiales. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Nombre | Descripción |
| --- | --- |
| getHeightSegments() | Obtiene o establece los segmentos de altura. Los segmentos de altura. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Nombre | Descripción |
| --- | --- |
| setHeightSegments(value) | Obtiene o establece los segmentos de altura. Los segmentos de altura. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| Nombre | Descripción |
| --- | --- |
| getOpenEnded() | Obtiene o establece un valor que indica si este Cylinder está abierto en los extremos. El valor predeterminado es false. true si está abierto; de lo contrario, existen tapas superior/inferior. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| Nombre | Descripción |
| --- | --- |
| setOpenEnded(value) | Obtiene o establece un valor que indica si este Cylinder está abierto en los extremos. El valor predeterminado es false. true si está abierto; de lo contrario, existen tapas superior/inferior. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| Nombre | Descripción |
| --- | --- |
| getThetaStart() | Obtiene o establece el inicio theta. El valor predeterminado es 0. El inicio theta. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| Nombre | Descripción |
| --- | --- |
| setThetaStart(value) | Obtiene o establece el inicio theta. El valor predeterminado es 0. El inicio theta. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| Nombre | Descripción |
| --- | --- |
| getThetaLength() | Obtiene o establece la longitud de theta. El valor predeterminado es 2π. La longitud de theta. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| Nombre | Descripción |
| --- | --- |
| setThetaLength(value) | Obtiene o establece la longitud de theta. El valor predeterminado es 2π. La longitud de theta. |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nombre | Descripción |
| --- | --- |
| getCastShadows() | Obtiene o establece si esta geometría puede proyectar sombra |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nombre | Descripción |
| --- | --- |
| setCastShadows(value) | Obtiene o establece si esta geometría puede proyectar sombra |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Nombre | Descripción |
| --- | --- |
| getReceiveShadows() | Obtiene o establece si esta geometría puede recibir sombra. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Nombre | Descripción |
| --- | --- |
| setReceiveShadows(value) | Obtiene o establece si esta geometría puede recibir sombra. |

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


### toMesh{#toMesh}

| Nombre | Descripción |
| --- | --- |
| toMesh() | Convertir el objeto actual a malla |

 **Result:**
Malla


---


### getBoundingBox{#getBoundingBox}

| Nombre | Descripción |
| --- | --- |
| getBoundingBox() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |

 **Result:**
Malla


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



