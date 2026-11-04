---
title: "Clase Node"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Node. Representa un elemento en el grafo de escena. Un grafo de escena es un árbol de objetos Node. Los servicios de gestión del árbol están contenidos en esta clase. Nota: el Aspose.3D SDK no verifica la validez del grafo de escena construido. Es responsabilidad del llamador asegurarse de que no genere grafos cíclicos en una jerarquía de nodos. Además de la gestión del árbol, esta clase define todas las propiedades necesarias para describir la posición del objeto en la escena. Esta información incluye las propiedades básicas de Translation, Rotation y Scaling, y las opciones más avanzadas para pivotes, límites y atributos de articulaciones IK, como la rigidez y el amortiguamiento. Cuando se crea por primera vez, el objeto Node está vacío, es decir, es un objeto sin representación gráfica que solo contiene la información de posición. En este estado puede usarse para representar padres en la estructura del árbol de nodos, pero no mucho más. El uso normal de este tipo de objetos es añadirles una entidad que especialice el nodo; vea la Entity. La entidad es un objeto por sí mismo y está conectada al Node. Esto también significa que la misma entidad puede compartirse entre varios nodos. Camera Light Mesh etc... son todas entidades y todas derivan de la clase base Entity"
type: docs
weight: 1630
url: /es/net/aspose.threed/node/
---
## Node class

Representa un elemento en el grafo de escena. Un grafo de escena es un árbol de objetos Node. Los servicios de gestión del árbol están contenidos en esta clase. Tenga en cuenta que el SDK de Aspose.3D no verifica la validez del grafo de escena construido. Es responsabilidad del llamador asegurarse de que no genere grafos cíclicos en una jerarquía de nodos. Además de la gestión del árbol, esta clase define todas las propiedades necesarias para describir la posición del objeto en la escena. Esta información incluye las propiedades básicas de Traslación, Rotación y Escalado, y las opciones más avanzadas para pivotes, límites y atributos de articulaciones IK, como la rigidez y el amortiguamiento. Cuando se crea por primera vez, el objeto Node está "vacío" (es decir, es un objeto sin representación gráfica que solo contiene la información de posición). En este estado, puede usarse para representar padres en la estructura del árbol de nodos, pero no mucho más. El uso normal de este tipo de objetos es añadirles una entidad que especializará el nodo (ver la "Entity"). La entidad es un objeto por sí misma y está conectada al Node. Esto también significa que la misma entidad puede compartirse entre varios nodos. Cámara, Luz, Malla, etc... son todas entidades y todas derivan de la clase base Entity.

```csharp
public class Node : SceneObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Node](node/#constructor)() | Inicializa una nueva instancia de la clase `Node`. |
| [Node](node/#constructor_1)(string) | Inicializa una nueva instancia de la clase `Node`. |
| [Node](node/#constructor_2)(string, Entity) | Inicializa una nueva instancia de la clase `Node`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssetInfo](../../aspose.threed/node/assetinfo/) { get; set; } | Información de activo por nodo |
| [ChildNodes](../../aspose.threed/node/childnodes/) { get; } | Obtiene los nodos hijos. |
| [Entities](../../aspose.threed/node/entities/) { get; } | Obtiene todas las entidades del nodo. |
| [Entity](../../aspose.threed/node/entity/) { get; set; } | Obtiene o establece la primera entidad adjunta a este nodo; si se establece, se eliminarán las demás entidades. |
| [Excluded](../../aspose.threed/node/excluded/) { get; set; } | Obtiene o establece si excluir este nodo y todos los nodos/entidades hijos durante la exportación. |
| [GlobalTransform](../../aspose.threed/node/globaltransform/) { get; } | Obtiene la transformación global. |
| [Material](../../aspose.threed/node/material/) { get; set; } | Obtiene o establece el primer material asociado a este nodo; si se establece, se eliminarán los demás materiales |
| [Materials](../../aspose.threed/node/materials/) { get; } | Obtiene los materiales asociados a este nodo. |
| [MetaDatas](../../aspose.threed/node/metadatas/) { get; } | Obtiene los metadatos definidos en este nodo. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/node/parentnode/) { get; set; } | Obtiene o establece el nodo padre. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Transform](../../aspose.threed/node/transform/) { get; } | Obtiene la transformación local. |
| [Visible](../../aspose.threed/node/visible/) { get; set; } | Obtiene o establece la visualización del nodo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Accept](../../aspose.threed/node/accept/)(NodeVisitor) | Recorre todos los nodos descendientes (incluyendo el nodo actual) y llama al visitante con el nodo. El visitante puede interrumpir el recorrido devolviendo false |
| [AddChildNode](../../aspose.threed/node/addchildnode/)(Node) | Agregar un nodo hijo a este nodo |
| [AddEntity](../../aspose.threed/node/addentity/)(Entity) | Agregar una entidad al nodo. |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode)() | Crea un nodo hijo |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_1)(Entity) | Crear un nuevo nodo hijo con la entidad dada adjunta |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_2)(string) | Crear un nuevo nodo hijo con el nombre de nodo dado |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_3)(string, Entity) | Crear un nuevo nodo hijo con el nombre de nodo dado |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_4)(string, Entity, Material) | Crear un nuevo nodo hijo con el nombre de nodo dado, y adjuntar la entidad especificada y un material |
| [EvaluateGlobalTransform](../../aspose.threed/node/evaluateglobaltransform/)(bool) | Evaluar la transformación global, incluir la transformación geométrica o no. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/node/getboundingbox/)() | Calcular la caja delimitadora del nodo |
| [GetChild](../../aspose.threed/node/getchild/#getchild)(int) | Obtiene el nodo hijo en el índice especificado. |
| [GetChild](../../aspose.threed/node/getchild/#getchild_1)(string) | Obtiene el nodo hijo con el nombre especificado |
| [GetEntity&lt;T&gt;](../../aspose.threed/node/getentity/)() |  |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [Merge](../../aspose.threed/node/merge/)(Node) | Desvincular todo bajo el nodo y adjuntarlo al nodo actual. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SelectObjects](../../aspose.threed/node/selectobjects/)(string) | Seleccionar múltiples objetos bajo el nodo actual usando sintaxis de consulta similar a XPath. |
| [SelectSingleObject](../../aspose.threed/node/selectsingleobject/)(string) | Seleccionar un solo objeto bajo el nodo actual usando sintaxis de consulta similar a XPath. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |
| override [ToString](../../aspose.threed/node/tostring/)() | Obtiene la representación en cadena de este nodo. |

### Ver también

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


