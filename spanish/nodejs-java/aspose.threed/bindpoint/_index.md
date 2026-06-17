---
title: "BindPoint"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

Un BindPoint suele crearse en la propiedad de un objeto, algunos tipos de propiedad contienen múltiples campos componentes (como un campo Vector3),  BindPoint generará un canal para cada campo componente y conectará el campo a una o más instancias de secuencia de fotogramas clave a través de los canales.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(scene, prop) | Inicializa una nueva instancia de la clase BindPoint. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| escena | Scene | La escena que contiene la animación. |
| prop | Property | Propiedad. |

 **Result:**



---


### getProperty{#getProperty}

| Nombre | Descripción |
| --- | --- |
| getProperty() | Obtiene la propiedad asociada con CurveMapping |

 **Result:**



---


### setProperty{#setProperty}

| Nombre | Descripción |
| --- | --- |
| setProperty(value) | Obtiene la propiedad asociada con CurveMapping |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Nombre | Descripción |
| --- | --- |
| getChannelsCount() | Obtiene el número total de canales de propiedad definidos en este mapeo de curva de animación. |

 **Result:**
Número


---


### getName{#getName}

| Nombre | Descripción |
| --- | --- |
| getName() | Obtiene o establece el nombre. El nombre. |

 **Result:**
Número


---


### setName{#setName}

| Nombre | Descripción |
| --- | --- |
| setName(value) | Obtiene o establece el nombre. El nombre. |

 **Result:**
Número


---


### getProperties{#getProperties}

| Nombre | Descripción |
| --- | --- |
| getProperties() | Obtiene la colección de todas las propiedades. |

 **Result:**
Número


---


### get{#get}

| Nombre | Descripción |
| --- | --- |
| get(channelName) |  |

 **Result:**
Número


---


### getKeyframeSequence{#getKeyframeSequence}

| Nombre | Descripción |
| --- | --- |
| getKeyframeSequence(channelName) | Obtiene la primera secuencia de fotogramas clave en el canal especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| channelName | Cadena | El nombre del canal a buscar |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| Nombre | Descripción |
| --- | --- |
| getKeyframeSequences(channelName) | Obtiene todas las secuencias de fotogramas clave en el canal especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| channelName | Cadena | El nombre del canal a buscar |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| Nombre | Descripción |
| --- | --- |
| createKeyframeSequence(name) | Crea una nueva curva y la conecta al primer canal del mapeo de curvas |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | El nombre de la nueva secuencia. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Nombre | Descripción |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Vincula la secuencia de fotogramas clave al canal especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| channelName | Cadena | A qué canal se vinculará la secuencia de fotogramas clave |
| sequence | KeyframeSequence | La secuencia de fotogramas clave a vincular |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Nombre | Descripción |
| --- | --- |
| getChannel(channelName) | Obtiene el canal por el nombre dado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| channelName | Cadena | El nombre del canal a buscar |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| Nombre | Descripción |
| --- | --- |
| addChannel(name, value) | Agrega la propiedad de canal especificada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre. |
| valor | Objeto | Valor. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| Nombre | Descripción |
| --- | --- |
| addChannel(name, type, value) | Agrega la propiedad de canal especificada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre. |
| type | Clase | Tipo. |
| valor | Objeto | Valor. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Nombre | Descripción |
| --- | --- |
| resetChannels() | Vacía los canales de propiedades de este mapeo de curvas de animación. |

 **Result:**
boolean


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Formatea el objeto a cadena |

 **Result:**
Cadena


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



