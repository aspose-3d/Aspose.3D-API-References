---
title: "AnimationChannel"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/animationchannel/
---
## AnimationChannel class

Un canal asigna el campo componente de una propiedad a un conjunto de secuencias de fotogramas clave  @hideconstructor


## Métodos

### getComponentType{#getComponentType}

| Nombre | Descripción |
| --- | --- |
| getComponentType() | Obtiene el tipo del campo del componente |

 **Result:**



---


### getName{#getName}

| Nombre | Descripción |
| --- | --- |
| getName() | Obtiene el nombre del canal |

 **Result:**



---


### getDefaultValue{#getDefaultValue}

| Nombre | Descripción |
| --- | --- |
| getDefaultValue() | Obtiene o establece el valor predeterminado del canal. Si un canal no tiene secuencias de fotogramas clave conectadas, el valor predeterminado se utilizará durante la evaluación de la animación. Un escenario real: la animación solo anima la coordenada x de un nodo, las coordenadas y y z no se cambian, entonces el valor predeterminado se usará durante la evaluación completa de la traducción. |

 **Result:**



---


### setDefaultValue{#setDefaultValue}

| Nombre | Descripción |
| --- | --- |
| setDefaultValue(value) | Obtiene o establece el valor predeterminado del canal. Si un canal no tiene secuencias de fotogramas clave conectadas, el valor predeterminado se utilizará durante la evaluación de la animación. Un escenario real: la animación solo anima la coordenada x de un nodo, las coordenadas y y z no se cambian, entonces el valor predeterminado se usará durante la evaluación completa de la traducción. |

 **Result:**



---


### getKeyframeSequences{#getKeyframeSequences}

| Nombre | Descripción |
| --- | --- |
| getKeyframeSequences() | Obtiene todas las secuencias de fotogramas clave dentro de este canal |

 **Result:**



---


### addKeyframeSequence{#addKeyframeSequence}

| Nombre | Descripción |
| --- | --- |
| addKeyframeSequence(sequence) | Agrega una secuencia de fotogramas clave a este canal |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| sequence | KeyframeSequence | La secuencia de fotogramas clave a agregar. |

 **Result:**



---


### iterator{#iterator}

| Nombre | Descripción |
| --- | --- |
| iterator() | Reservado para uso interno. |

 **Result:**



---



