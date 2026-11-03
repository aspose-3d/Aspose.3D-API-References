---
title: "Structure Quaternion"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Structure Aspose.ThreeD.Utilities.Quaternion. Le quaternion est généralement utilisé pour effectuer des rotations en infographie"
type: docs
weight: 2810
url: /fr/net/aspose.threed.utilities/quaternion/
---
## Quaternion structure

Le quaternion est généralement utilisé pour effectuer des rotations en infographie.

```csharp
public struct Quaternion
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Quaternion](quaternion/)(double, double, double, double) | Initialise une nouvelle instance de la classe `Quaternion`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Length](../../aspose.threed.utilities/quaternion/length/) { get; } | Obtient la longueur du quaternion |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromAngleAxis](../../aspose.threed.utilities/quaternion/fromangleaxis/)(double, Vector3) | Crée un quaternion autour d'un axe donné et le fait pivoter dans le sens horaire |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle)(Vector3) | Crée un quaternion à partir d'un angle d'Euler donné |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle_1)(double, double, double) | Crée un quaternion à partir d'un angle d'Euler donné |
| static [FromRotation](../../aspose.threed.utilities/quaternion/fromrotation/)(Vector3, Vector3) | Crée un quaternion qui tourne de la direction d'origine à la direction de destination |
| static [Interpolate](../../aspose.threed.utilities/quaternion/interpolate/)(float, Quaternion, Quaternion) | Remplit ce quaternion avec la valeur interpolée entre les arguments quaternion fournis pour un t compris entre le départ et l'arrivée. |
| static [Slerp](../../aspose.threed.utilities/quaternion/slerp/)(double, Quaternion, Quaternion) | Effectue une interpolation sphérique linéaire entre deux valeurs |
| [Concat](../../aspose.threed.utilities/quaternion/concat/)(Quaternion) | Concatène deux quaternions |
| [Conjugate](../../aspose.threed.utilities/quaternion/conjugate/)() | Renvoie le quaternion conjugué du quaternion actuel |
| [Dot](../../aspose.threed.utilities/quaternion/dot/)(Quaternion) | Produit scalaire |
| override [Equals](../../aspose.threed.utilities/quaternion/equals/)(object) | Vérifie si deux quaternions sont égaux |
| [EulerAngles](../../aspose.threed.utilities/quaternion/eulerangles/)() | Convertit le quaternion en rotation représentée par des angles d'Euler. Tous les composants sont en radians |
| override [GetHashCode](../../aspose.threed.utilities/quaternion/gethashcode/)() | Obtient le code de hachage du Quaternion |
| [Inverse](../../aspose.threed.utilities/quaternion/inverse/)() | Renvoie un quaternion inverse du quaternion actuel |
| [Normalize](../../aspose.threed.utilities/quaternion/normalize/)() | Normalise le quaternion |
| [ToAngleAxis](../../aspose.threed.utilities/quaternion/toangleaxis/)(out double, out Vector3) |  |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix)() | Convertit la rotation présentée par le quaternion en matrice de transformation. |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix_1)(Vector3) | Convertit la rotation présentée par le quaternion en matrice de transformation. |
| override [ToString](../../aspose.threed.utilities/quaternion/tostring/)() | Obtient la représentation du quaternion sous forme de chaîne |
| [operator +](../../aspose.threed.utilities/quaternion/op_addition/) | Surcharge d'opérateur pour + |
| [operator /](../../aspose.threed.utilities/quaternion/op_division/) | Surcharge de l'opérateur / |
| [operator ==](../../aspose.threed.utilities/quaternion/op_equality/) | Opérateur d'égalité pour le quaternion |
| [operator !=](../../aspose.threed.utilities/quaternion/op_inequality/) | Opérateur de différence pour le quaternion |
| [operator *](../../aspose.threed.utilities/quaternion/op_multiply/#op_multiply_1) | Surcharge de l'opérateur * (5 opérateurs) |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Identity](../../aspose.threed.utilities/quaternion/identity/) | Le quaternion identité. |
| [W](../../aspose.threed.utilities/quaternion/w/) | Le composant w. |
| [X](../../aspose.threed.utilities/quaternion/x/) | La composante x. |
| [Y](../../aspose.threed.utilities/quaternion/y/) | La composante y. |
| [Z](../../aspose.threed.utilities/quaternion/z/) | La composante z. |

### Voir aussi

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


