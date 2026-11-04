---
title: "Aspose.ThreeD"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "El espacio de nombres base de Aspose.3D"
type: docs
weight: 10
url: /es/net/aspose.threed/
---
El espacio de nombres base de Aspose.3D

## Clases

| Clase | Descripción |
| --- | --- |
| [A3DObject](./a3dobject/) | La clase base de todos los objetos Aspose.ThreeD, todas las subclases admitirán propiedades dinámicas. |
| [AssetInfo](./assetinfo/) | Información del activo. La información del activo puede adjuntarse a un [`Scene`](../aspose.threed/scene/). Un [`Scene`](../aspose.threed/scene/) hijo puede tener su propio [`AssetInfo`](../aspose.threed/assetinfo/) para sobrescribir la definición del padre. |
| [AxisSystem](./axissystem/) | El sistema de ejes es una combinación de sistema de coordenadas, vector ascendente y vector frontal. |
| [BonePose](./bonepose/) | El [`BonePose`](../aspose.threed/bonepose/) contiene la matriz de transformación para un nodo óseo. |
| [CustomObject](./customobject/) | Los metadatos o objetos personalizados utilizados en archivos 3D son gestionados por esta clase. Todas las propiedades personalizadas se guardan como propiedades dinámicas. |
| [Entity](./entity/) | La clase base de todas las entidades. La entidad representa un objeto concreto que se adjunta bajo un nodo como [`Light`](../aspose.threed.entities/light/)/[`Geometry`](../aspose.threed.entities/geometry/). |
| [ExportException](./exportexception/) | Excepciones cuando Aspose.3D no pudo exportar la escena a un archivo |
| [FileFormat](./fileformat/) | Definición del formato de archivo |
| [FileFormatType](./fileformattype/) | Tipo de formato de archivo |
| [GlobalTransform](./globaltransform/) | La transformación global es similar a [`Transform`](../aspose.threed/transform/), pero es inmutable mientras representa la transformación final evaluada. Se utiliza un sistema de coordenadas de mano derecha al evaluar la transformación global. |
| [Group](./group/) | Un [`Group`](../aspose.threed/group/) representa las relaciones lógicas de [`Node`](../aspose.threed/node/). |
| [ImageRenderOptions](./imagerenderoptions/) | Opciones para [`Render`](../aspose.threed/scene/render/) y [`Render`](../aspose.threed/scene/render/) |
| [ImportException](./importexception/) | Excepción cuando Aspose.3D no pudo abrir la fuente especificada |
| [License](./license/) | Proporciona métodos para licenciar el componente. |
| [Metered](./metered/) | Proporciona métodos para establecer la clave medida. |
| [Node](./node/) | Representa un elemento en el grafo de escena. Un grafo de escena es un árbol de objetos Node. Los servicios de gestión del árbol están contenidos en esta clase. Tenga en cuenta que el SDK de Aspose.3D no verifica la validez del grafo de escena construido. Es responsabilidad del llamador asegurarse de que no genere grafos cíclicos en una jerarquía de nodos. Además de la gestión del árbol, esta clase define todas las propiedades necesarias para describir la posición del objeto en la escena. Esta información incluye las propiedades básicas de Traslación, Rotación y Escalado, y las opciones más avanzadas para pivotes, límites y atributos de articulaciones IK, como la rigidez y el amortiguamiento. Cuando se crea por primera vez, el objeto Node está "vacío" (es decir, es un objeto sin representación gráfica que solo contiene la información de posición). En este estado, puede usarse para representar padres en la estructura del árbol de nodos, pero no mucho más. El uso normal de este tipo de objetos es añadirles una entidad que especializará el nodo (ver la "Entity"). La entidad es un objeto por sí misma y está conectada al Node. Esto también significa que la misma entidad puede compartirse entre varios nodos. Cámara, Luz, Malla, etc... son todas entidades y todas derivan de la clase base Entity. |
| [NodeVisitor](./nodevisitor/) | Una devolución de llamada para recorrer toda la jerarquía de nodos. |
| [Pose](./pose/) | La pose se utiliza para almacenar la matriz de transformación cuando la geometría está skinada. La pose es un conjunto de [`BonePose`](../aspose.threed/bonepose/), cada [`BonePose`](../aspose.threed/bonepose/) guarda la información concreta de transformación del nodo óseo. |
| [Property](./property/) | Clase para contener propiedades definidas por el usuario. |
| [PropertyCollection](./propertycollection/) | La colección de propiedades |
| [Scene](./scene/) | Una escena es un objeto de nivel superior que contiene los nodos, geometrías, materiales, texturas, animaciones, poses, subescenas, etc. La escena puede tener subescenas y funciona como soporte de varios documentos en archivos como collada/blender/fbx. La jerarquía de nodos puede accederse a través de [`RootNode`](../aspose.threed/scene/rootnode/). [`Library`](../aspose.threed/scene/library/) se utiliza para mantener una referencia de objetos no adjuntos durante la serialización (como metadatos u objetos personalizados) para que pueda usarse como una biblioteca. |
| [SceneObject](./sceneobject/) | La clase raíz de los objetos que se almacenarán dentro de una escena. |
| [Transform](./transform/) | Una transformación contiene información que permite acceder a la traslación/escalado/rotación del objeto o a la matriz de transformación con un coste mínimo. Esto se usa en la transformación local. |
| [TrialException](./trialexception/) | Esto se genera en Scene.Open/Scene.Save cuando no se aplican licencias. Puede desactivar esta excepción configurando SuppressTrialException a true. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [INamedObject](./inamedobject/) | Objeto que tiene un nombre |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [Axis](./axis/) | El eje de coordenadas. |
| [CoordinateSystem](./coordinatesystem/) | El sistema de coordenadas zurdo o diestro. |
| [FileContentType](./filecontenttype/) | Tipo de contenido del archivo |
| [PoseType](./posetype/) | Tipo de pose. |
| [PropertyFlags](./propertyflags/) | Banderas de la propiedad |


