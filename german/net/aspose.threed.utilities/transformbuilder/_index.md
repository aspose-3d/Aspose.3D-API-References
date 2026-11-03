---
title: "Klasse TransformBuilder"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Utilities.TransformBuilder Klasse. Der TransformBuilder wird verwendet, um eine Transformationsmatrix durch eine Kette von Transformationen zu erstellen."
type: docs
weight: 2860
url: /de/net/aspose.threed.utilities/transformbuilder/
---
## TransformBuilder class

Der `TransformBuilder` wird verwendet, um eine Transformationsmatrix durch eine Kette von Transformationen zu erstellen.

```csharp
public class TransformBuilder
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TransformBuilder](transformbuilder/#constructor)(ComposeOrder) | Erstelle einen `TransformBuilder` mit einer anfänglichen Identitäts-Transformationsmatrix und einer angegebenen Zusammensetzungsreihenfolge. |
| [TransformBuilder](transformbuilder/#constructor_1)(Matrix4, ComposeOrder) | Erstelle einen `TransformBuilder` mit einer anfänglichen Transformationsmatrix und einer angegebenen Zusammensetzungsreihenfolge. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ComposeOrder](../../aspose.threed.utilities/transformbuilder/composeorder/) { get; set; } | Liest oder setzt die Zusammensetzungsreihenfolge der Kette. |
| [Matrix](../../aspose.threed.utilities/transformbuilder/matrix/) { get; set; } | Liest oder setzt den aktuellen Matrixwert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Append](../../aspose.threed.utilities/transformbuilder/append/)(Matrix4) | Füge die neue Transformationsmatrix zur Transformationskette hinzu. |
| [Compose](../../aspose.threed.utilities/transformbuilder/compose/)(Matrix4) | Hänge das Argument an die interne Matrix an oder füge es am Anfang ein. |
| [Prepend](../../aspose.threed.utilities/transformbuilder/prepend/)(Matrix4) | Füge die neue Transformationsmatrix am Anfang der Transformationskette ein. |
| [Rearrange](../../aspose.threed.utilities/transformbuilder/rearrange/)(Axis, Axis, Axis) | Ordne das Layout der Achse neu an. |
| [Reset](../../aspose.threed.utilities/transformbuilder/reset/)() | Setze die Transformation auf die Identitätsmatrix zurück. |
| [Rotate](../../aspose.threed.utilities/transformbuilder/rotate/)(Quaternion) | Verkette eine Rotation mittels Quaternion. |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree)(double, Vector3) | Verkette eine Rotations-Transformation in Grad. |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree_1)(Vector3, RotationOrder) | Füge eine Rotation mit angegebener Reihenfolge hinzu. |
| [RotateEulerDegree](../../aspose.threed.utilities/transformbuilder/rotateeulerdegree/)(double, double, double) | Verkette eine Rotation mittels Euler-Winkeln in Grad. |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian)(Vector3) | Verkette eine Rotation mittels Euler-Winkeln in Bogenmaß. |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian_1)(double, double, double) | Verkette eine Rotation mittels Euler-Winkeln in Bogenmaß. |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian)(double, Vector3) | Verkette eine Rotations-Transformation in Bogenmaß. |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian_1)(Vector3, RotationOrder) | Füge eine Rotation mit angegebener Reihenfolge hinzu. |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_1)(double) | Verkette eine Skalierungs-Transformationsmatrix, wobei eine Komponente um s skaliert wird. |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale)(Vector3) | Verkette eine Skalierungs-Transformation. |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_2)(double, double, double) | Verkette eine Skalierungs-Transformationsmatrix. |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate)(Vector3) | Verkette eine Translations-Transformation. |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate_1)(double, double, double) | Verkette eine Translations-Transformation. |

## Beispiele

Der folgende Code zeigt, wie man eine Matrix durch eine Reihe von Operationen erstellt.

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(10, 20, 0);
tb.Scale(10, 10, 10);
tb.RotateEulerDegree(90, 0, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


