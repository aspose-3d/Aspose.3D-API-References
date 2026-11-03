---
title: "Aspose.ThreeD"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "L'espace de noms de base d'Aspose.3D"
type: docs
weight: 10
url: /fr/net/aspose.threed/
---
L'espace de noms de base d'Aspose.3D

## Classes

| Classe | Description |
| --- | --- |
| [A3DObject](./a3dobject/) | La classe de base de tous les objets Aspose.ThreeD, toutes les sous‑classes prendront en charge les propriétés dynamiques. |
| [AssetInfo](./assetinfo/) | Informations sur l'actif. Les informations d'actif peuvent être attachées à une [`Scene`](../aspose.threed/scene/). Un [`Scene`](../aspose.threed/scene/) enfant peut avoir son propre [`AssetInfo`](../aspose.threed/assetinfo/) pour remplacer la définition du parent. |
| [AxisSystem](./axissystem/) | Le système d'axes est une combinaison du système de coordonnées, du vecteur ascendant et du vecteur avant. |
| [BonePose](./bonepose/) | Le [`BonePose`](../aspose.threed/bonepose/) contient la matrice de transformation d'un nœud osseux. |
| [CustomObject](./customobject/) | Les métadonnées ou objets personnalisés utilisés dans les fichiers 3D sont gérés par cette classe. Toutes les propriétés personnalisées sont enregistrées en tant que propriétés dynamiques. |
| [Entity](./entity/) | La classe de base de toutes les entités. Une entité représente un objet concret qui est attaché sous un nœud tel que [`Light`](../aspose.threed.entities/light/)/[`Geometry`](../aspose.threed.entities/geometry/). |
| [ExportException](./exportexception/) | Exceptions lorsque Aspose.3D n'a pas pu exporter la scène vers le fichier. |
| [FileFormat](./fileformat/) | Définition du format de fichier. |
| [FileFormatType](./fileformattype/) | Type de format de fichier. |
| [GlobalTransform](./globaltransform/) | La transformation globale est similaire à [`Transform`](../aspose.threed/transform/), mais elle est immuable lorsqu'elle représente la transformation finale évaluée. Le système de coordonnées droit est utilisé lors de l'évaluation de la transformation globale. |
| [Group](./group/) | Un [`Group`](../aspose.threed/group/) représente les relations logiques de [`Node`](../aspose.threed/node/). |
| [ImageRenderOptions](./imagerenderoptions/) | Options pour [`Render`](../aspose.threed/scene/render/) et [`Render`](../aspose.threed/scene/render/). |
| [ImportException](./importexception/) | Exception lorsque Aspose.3D n'a pas pu ouvrir la source spécifiée. |
| [License](./license/) | Fournit des méthodes pour licencier le composant. |
| [Metered](./metered/) | Fournit des méthodes pour définir la clé mesurée. |
| [Node](./node/) | Représente un élément du graphe de scène. Un graphe de scène est un arbre d'objets Node. Les services de gestion de l'arbre sont autonomes dans cette classe. Notez que le SDK Aspose.3D ne teste pas la validité du graphe de scène construit. Il incombe à l'appelant de s'assurer qu'il ne génère pas de graphes cycliques dans la hiérarchie des nœuds. En plus de la gestion de l'arbre, cette classe définit toutes les propriétés nécessaires pour décrire la position de l'objet dans la scène. Ces informations incluent les propriétés de Translation, Rotation et Échelle de base ainsi que les options avancées pour les pivots, limites et attributs des articulations IK tels que la raideur et l'amortissement. Lorsqu'il est créé pour la première fois, l'objet Node est "empty" (c'est‑à‑dire qu'il s'agit d'un objet sans aucune représentation graphique qui ne contient que les informations de position). Dans cet état, il peut être utilisé pour représenter les parents dans la structure arborescente des nœuds mais pas bien plus. L'utilisation normale de ce type d'objets consiste à leur ajouter une entité qui spécialisera le nœud (voir "Entity"). L'entité est un objet en soi et est connectée au Node. Cela signifie également que la même entité peut être partagée entre plusieurs nœuds. Camera, Light, Mesh, etc... sont toutes des entités et toutes dérivent de la classe de base Entity. |
| [NodeVisitor](./nodevisitor/) | Un rappel pour parcourir toute la hiérarchie des nœuds. |
| [Pose](./pose/) | La pose est utilisée pour stocker la matrice de transformation lorsque la géométrie est skinnée. La pose est un ensemble de [`BonePose`](../aspose.threed/bonepose/), chaque [`BonePose`](../aspose.threed/bonepose/) enregistre les informations de transformation concrètes du nœud os. |
| [Property](./property/) | Classe pour contenir des propriétés définies par l'utilisateur. |
| [PropertyCollection](./propertycollection/) | La collection de propriétés. |
| [Scene](./scene/) | Une scène est un objet de niveau supérieur qui contient les nœuds, géométries, matériaux, textures, animations, poses, sous‑scènes, etc. Une scène peut avoir des sous‑scènes, servant de prise en charge multi‑documents dans des fichiers tels que collada/blender/fbx. La hiérarchie des nœuds peut être accédée via [`RootNode`](../aspose.threed/scene/rootnode/). [`Library`](../aspose.threed/scene/library/) est utilisé pour conserver une référence aux objets détachés lors de la sérialisation (comme les métadonnées ou objets personnalisés) afin qu'il puisse être utilisé comme une bibliothèque. |
| [SceneObject](./sceneobject/) | La classe racine des objets qui seront stockés à l'intérieur d'une scène. |
| [Transform](./transform/) | Une transformation contient des informations permettant d'accéder à la translation/échelle/rotation de l'objet ou à sa matrice de transformation avec un coût minimal. Elle est utilisée par la transformation locale. |
| [TrialException](./trialexception/) | Cette exception est levée dans Scene.Open/Scene.Save lorsqu'aucune licence n'est appliquée. Vous pouvez désactiver cette exception en définissant SuppressTrialException sur true. |
## Interfaces

| Interface | Description |
| --- | --- |
| [INamedObject](./inamedobject/) | Objet qui possède un nom. |
## Énumération

| Énumération | Description |
| --- | --- |
| [Axis](./axis/) | L'axe de coordonnées. |
| [CoordinateSystem](./coordinatesystem/) | Le système de coordonnées gaucher ou droitier. |
| [FileContentType](./filecontenttype/) | Type de contenu du fichier |
| [PoseType](./posetype/) | Type de pose. |
| [PropertyFlags](./propertyflags/) | Drapeaux de la propriété |


