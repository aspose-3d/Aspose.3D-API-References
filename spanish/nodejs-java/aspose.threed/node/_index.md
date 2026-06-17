---
title: "Nodo"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/node/
---
## Node class

Representa un elemento en el grafo de escena. Un grafo de escena es un árbol de objetos Node. Los servicios de gestión del árbol están contenidos en esta clase. Nota: el SDK Aspose.3D no verifica la validez del grafo de escena construido. Es responsabilidad del llamador asegurarse de que no genere grafos cíclicos en una jerarquía de nodos. Además de la gestión del árbol, esta clase define todas las propiedades necesarias para describir la posición del objeto en la escena. Esta información incluye las propiedades básicas de Translación, Rotación y Escalado, y las opciones más avanzadas para pivotes, límites y atributos de articulaciones IK como la rigidez y el amortiguamiento. Cuando se crea por primera vez, el objeto Node está "empty" (es decir, es un objeto sin representación gráfica que solo contiene la información de posición). En este estado, puede usarse para representar padres en la estructura del árbol de nodos pero no mucho más. El uso normal de este tipo de objetos es añadirles una entidad que especializará el nodo (ver "Entity"). La entidad es un objeto por sí misma y está conectada al Node. Esto también significa que la misma entidad puede compartirse entre varios nodos. Cámara, Luz, Malla, etc... son todas entidades y todas derivan de la clase base Entity.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de la clase Node. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(name, entity) | Inicializa una nueva instancia de la clase Node. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre. |
| entidad | Entidad | Entidad predeterminada. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2(name) | Inicializa una nueva instancia de la clase Node. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Nombre | Descripción |
| --- | --- |
| getAssetInfo() | Información de activo por nodo |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Nombre | Descripción |
| --- | --- |
| setAssetInfo(value) | Información de activo por nodo |

 **Result:**



---


### getVisible{#getVisible}

| Nombre | Descripción |
| --- | --- |
| getVisible() | Obtiene o establece si se muestra el nodo |

 **Result:**



---


### setVisible{#setVisible}

| Nombre | Descripción |
| --- | --- |
| setVisible(value) | Obtiene o establece si se muestra el nodo |

 **Result:**



---


### getChildNodes{#getChildNodes}

| Nombre | Descripción |
| --- | --- |
| getChildNodes() | Obtiene los nodos hijos. Los nodos. |

 **Result:**



---


### getEntity{#getEntity}

| Nombre | Descripción |
| --- | --- |
| getEntity() | Obtiene o establece la primera entidad adjunta a este nodo; si se establece, se eliminarán las demás entidades. La entidad del nodo. |

 **Result:**



---


### setEntity{#setEntity}

| Nombre | Descripción |
| --- | --- |
| setEntity(value) | Obtiene o establece la primera entidad adjunta a este nodo; si se establece, se eliminarán las demás entidades. La entidad del nodo. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nombre | Descripción |
| --- | --- |
| getExcluded() | Obtiene o establece si excluir este nodo y todos los nodos/entidades hijos durante la exportación. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nombre | Descripción |
| --- | --- |
| setExcluded(value) | Obtiene o establece si excluir este nodo y todos los nodos/entidades hijos durante la exportación. |

 **Result:**



---


### getEntities{#getEntities}

| Nombre | Descripción |
| --- | --- |
| getEntities() | Obtiene todas las entidades del nodo. Las entidades del nodo. |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| Nombre | Descripción |
| --- | --- |
| getMetaDatas() | Obtiene los metadatos definidos en este nodo. Los metadatos. |

 **Result:**



---


### getMaterials{#getMaterials}

| Nombre | Descripción |
| --- | --- |
| getMaterials() | Obtiene los materiales asociados a este nodo. Los materiales. |

 **Result:**



---


### getMaterial{#getMaterial}

| Nombre | Descripción |
| --- | --- |
| getMaterial() | Obtiene o establece el primer material asociado a este nodo; si se establece, se eliminarán los demás materiales. El material. |

 **Result:**



---


### setMaterial{#setMaterial}

| Nombre | Descripción |
| --- | --- |
| setMaterial(value) | Obtiene o establece el primer material asociado a este nodo; si se establece, se eliminarán los demás materiales. El material. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nombre | Descripción |
| --- | --- |
| getParentNode() | Obtiene o establece el nodo padre. El nodo padre. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nombre | Descripción |
| --- | --- |
| setParentNode(value) | Obtiene o establece el nodo padre. El nodo padre. |

 **Result:**



---


### getTransform{#getTransform}

| Nombre | Descripción |
| --- | --- |
| getTransform() | Obtiene la transformación local. La transformación. |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| Nombre | Descripción |
| --- | --- |
| getGlobalTransform() | Obtiene la transformación global. La transformación global. |

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


### createChildNode{#createChildNode}

| Nombre | Descripción |
| --- | --- |
| createChildNode() | Crea un nodo hijo |

 **Result:**
Nodo


---


### merge{#merge}

| Nombre | Descripción |
| --- | --- |
| merge(node) | Desvincula todo bajo el nodo y adjúntalo al nodo actual. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| asentir | Nodo | null |

 **Result:**
Nodo


---


### createChildNode{#createChildNode}

| Nombre | Descripción |
| --- | --- |
| createChildNode(nodeName) | Crea un nuevo nodo hijo con el nombre de nodo proporcionado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| nodeName | Cadena | El nombre del nuevo nodo hijo |

 **Result:**
Nodo


---


### createChildNode{#createChildNode}

| Nombre | Descripción |
| --- | --- |
| createChildNode(entity) | Crea un nuevo nodo hijo con la entidad proporcionada adjunta |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | Entidad predeterminada adjunta al nodo |

 **Result:**
Nodo


---


### createChildNode{#createChildNode}

| Nombre | Descripción |
| --- | --- |
| createChildNode(nodeName, entity) | Crea un nuevo nodo hijo con el nombre de nodo proporcionado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| nodeName | Cadena | El nombre del nuevo nodo hijo |
| entidad | Entidad | Entidad predeterminada adjunta al nodo |

 **Result:**
Nodo


---


### createChildNode{#createChildNode}

| Nombre | Descripción |
| --- | --- |
| createChildNode(nodeName, entity, material) | Crea un nuevo nodo hijo con el nombre de nodo proporcionado y adjunta la entidad especificada y un material |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| nodeName | Cadena | El nombre del nuevo nodo hijo |
| entidad | Entidad | Entidad predeterminada adjunta al nodo |
| material | Material | El material adjunto al nodo |

 **Result:**
Nodo


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Nombre | Descripción |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Evalúa la transformación global, incluye la transformación geométrica o no. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| withGeometricTransform | boolean | Si se necesita la transformación geométrica. |

 **Result:**
Matrix4


---


### getChild{#getChild}

| Nombre | Descripción |
| --- | --- |
| getChild(index) | Obtiene el nodo hijo en el índice especificado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| index | Número | Índice. |

 **Result:**
Nodo


---


### getChild{#getChild}

| Nombre | Descripción |
| --- | --- |
| getChild(nodeName) | Obtiene el nodo hijo con el nombre especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| nodeName | Cadena | El nombre del hijo a buscar. |

 **Result:**
Nodo


---


### accept{#accept}

| Nombre | Descripción |
| --- | --- |
| accept(visitor) | Recorre todos los nodos descendientes (incluyendo el nodo actual) y llama al visitante con el nodo. El visitante puede interrumpir el recorrido devolviendo false |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| visitor | NodeVisitor | Callback del Visitor para visitar el nodo |

 **Result:**
boolean


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Obtiene la representación en cadena de este nodo. |

 **Result:**
Cadena


---


### getBoundingBox{#getBoundingBox}

| Nombre | Descripción |
| --- | --- |
| getBoundingBox() | Calcula la caja delimitadora del nodo |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| Nombre | Descripción |
| --- | --- |
| addEntity(entity) | Añade una entidad al nodo. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| entidad | Entidad | La entidad que se adjuntará al nodo |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| Nombre | Descripción |
| --- | --- |
| addChildNode(node) | Añade un nodo hijo a este nodo |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| nodo | Nodo | El nodo hijo que se adjuntará |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| Nombre | Descripción |
| --- | --- |
| selectSingleObject(path) | Selecciona un único objeto bajo el nodo actual usando sintaxis de consulta similar a XPath. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| pat | Cadena | null |

 **Result:**
Objeto


---


### selectObjects{#selectObjects}

| Nombre | Descripción |
| --- | --- |
| selectObjects(path) | Selecciona múltiples objetos bajo el nodo actual usando sintaxis de consulta similar a XPath. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| pat | Cadena | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


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



