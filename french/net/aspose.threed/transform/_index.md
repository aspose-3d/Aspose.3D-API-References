---
title: "Classe Transform"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Transform classe. Un transform contient des informations qui permettent d'accéder aux objets de translation/échelle/rotation ou à la matrice de transformation à coût minimal. Ceci est utilisé par la transformation locale."
type: docs
weight: 2650
url: /fr/net/aspose.threed/transform/
---
## Transform class

Une transformation contient des informations permettant d'accéder à la translation/échelle/rotation de l'objet ou à sa matrice de transformation avec un coût minimal. Elle est utilisée par la transformation locale.

```csharp
public class Transform : A3DObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [EulerAngles](../../aspose.threed/transform/eulerangles/) { get; set; } | Obtient ou définit la rotation représentée en angles d'Euler, mesurée en degrés |
| [GeometricRotation](../../aspose.threed/transform/geometricrotation/) { get; set; } | Obtient ou définit la rotation géométrique d'Euler (mesurée en degrés). La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |
| [GeometricScaling](../../aspose.threed/transform/geometricscaling/) { get; set; } | Obtient ou définit l'échelle géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |
| [GeometricTranslation](../../aspose.threed/transform/geometrictranslation/) { get; set; } | Obtient ou définit la translation géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [PostRotation](../../aspose.threed/transform/postrotation/) { get; set; } | Obtient ou définit la post-rotation représentée en degrés |
| [PreRotation](../../aspose.threed/transform/prerotation/) { get; set; } | Obtient ou définit la pré-rotation représentée en degrés |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Rotation](../../aspose.threed/transform/rotation/) { get; set; } | Obtient ou définit la rotation représentée en quaternion. |
| [RotationOffset](../../aspose.threed/transform/rotationoffset/) { get; set; } | Obtient ou définit le décalage de rotation |
| [RotationPivot](../../aspose.threed/transform/rotationpivot/) { get; set; } | Obtient ou définit le pivot de rotation |
| [Scaling](../../aspose.threed/transform/scaling/) { get; set; } | Obtient ou définit l'échelle |
| [ScalingOffset](../../aspose.threed/transform/scalingoffset/) { get; set; } | Obtient ou définit le décalage d'échelle |
| [ScalingPivot](../../aspose.threed/transform/scalingpivot/) { get; set; } | Obtient ou définit le pivot d'échelle |
| [TransformMatrix](../../aspose.threed/transform/transformmatrix/) { get; set; } | Obtient ou définit la matrice de transformation. |
| [Translation](../../aspose.threed/transform/translation/) { get; set; } | Obtient ou définit la translation |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetEulerAngles](../../aspose.threed/transform/seteulerangles/)(double, double, double) | Définit les angles d'Euler en degrés de la transformation actuelle. |
| [SetGeometricRotation](../../aspose.threed/transform/setgeometricrotation/)(double, double, double) | Définit la rotation géométrique d'Euler (mesurée en degrés). La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |
| [SetGeometricScaling](../../aspose.threed/transform/setgeometricscaling/)(double, double, double) | Définit l'échelle géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |
| [SetGeometricTranslation](../../aspose.threed/transform/setgeometrictranslation/)(double, double, double) | Définit la translation géométrique. La transformation géométrique n'affecte que les entités attachées et laisse les nœuds enfants inchangés. Elle sera fusionnée en tant que transformation locale lors de l'exportation de la transformation géométrique vers des types de fichiers qui ne la prennent pas en charge. |
| [SetPostRotation](../../aspose.threed/transform/setpostrotation/)(double, double, double) | Définit la post-rotation représentée en degrés |
| [SetPreRotation](../../aspose.threed/transform/setprerotation/)(double, double, double) | Définit la pré-rotation représentée en degrés |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| [SetRotation](../../aspose.threed/transform/setrotation/)(double, double, double, double) | Définit la rotation (en tant que composants quaternion) de la transformation actuelle. |
| [SetScale](../../aspose.threed/transform/setscale/)(double, double, double) | Définit l'échelle de la transformation actuelle. |
| [SetTranslation](../../aspose.threed/transform/settranslation/)(double, double, double) | Définit la translation de la transformation actuelle. |

## Exemples

Le code suivant montre comment modifier la transformation du nœud :

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//placez la boîte à (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### Voir aussi

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


