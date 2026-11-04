---
title: "Clase TransformBuilder"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Utilities.TransformBuilder. El TransformBuilder se usa para construir la matriz de transformación mediante una cadena de transformaciones"
type: docs
weight: 2860
url: /es/net/aspose.threed.utilities/transformbuilder/
---
## TransformBuilder class

El `TransformBuilder` se usa para construir la matriz de transformación mediante una cadena de transformaciones.

```csharp
public class TransformBuilder
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TransformBuilder](transformbuilder/#constructor)(ComposeOrder) | Construir un `TransformBuilder` con la matriz de transformación identidad inicial y el orden de composición especificado |
| [TransformBuilder](transformbuilder/#constructor_1)(Matrix4, ComposeOrder) | Construir un `TransformBuilder` con la matriz de transformación inicial y el orden de composición especificado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ComposeOrder](../../aspose.threed.utilities/transformbuilder/composeorder/) { get; set; } | Obtiene o establece el orden de composición de la cadena. |
| [Matrix](../../aspose.threed.utilities/transformbuilder/matrix/) { get; set; } | Obtiene o establece el valor actual de la matriz |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Append](../../aspose.threed.utilities/transformbuilder/append/)(Matrix4) | Agregar la nueva matriz de transformación a la cadena de transformaciones. |
| [Compose](../../aspose.threed.utilities/transformbuilder/compose/)(Matrix4) | Agregar o anteponer el argumento a la matriz interna. |
| [Prepend](../../aspose.threed.utilities/transformbuilder/prepend/)(Matrix4) | Anteponer la nueva matriz de transformación a la cadena de transformaciones. |
| [Rearrange](../../aspose.threed.utilities/transformbuilder/rearrange/)(Axis, Axis, Axis) | Reorganizar la disposición del eje. |
| [Reset](../../aspose.threed.utilities/transformbuilder/reset/)() | Restablecer la transformación a la matriz identidad |
| [Rotate](../../aspose.threed.utilities/transformbuilder/rotate/)(Quaternion) | Encadenar una rotación mediante un cuaternión |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree)(double, Vector3) | Encadenar una transformación de rotación en grados |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree_1)(Vector3, RotationOrder) | Agregar rotación con el orden especificado |
| [RotateEulerDegree](../../aspose.threed.utilities/transformbuilder/rotateeulerdegree/)(double, double, double) | Encadenar una rotación por ángulos de Euler en grados |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian)(Vector3) | Encadenar una rotación por ángulos de Euler en radianes |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian_1)(double, double, double) | Encadenar una rotación por ángulos de Euler en radianes |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian)(double, Vector3) | Encadenar una transformación de rotación en radianes |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian_1)(Vector3, RotationOrder) | Agregar rotación con el orden especificado |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_1)(double) | Encadenar una matriz de transformación de escalado con un componente escalado por s |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale)(Vector3) | Encadenar una transformación de escala |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_2)(double, double, double) | Encadenar una matriz de transformación de escalado |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate)(Vector3) | Encadenar una transformación de traslación |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate_1)(double, double, double) | Encadenar una transformación de traslación |

## Ejemplos

El siguiente código muestra cómo crear una matriz mediante un conjunto de operaciones

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(10, 20, 0);
tb.Scale(10, 10, 10);
tb.RotateEulerDegree(90, 0, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


