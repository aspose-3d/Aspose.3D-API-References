---
title: "Estructura BoundingBox"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Estructura Aspose.ThreeD.Utilities.BoundingBox. La caja delimitadora alineada a los ejes"
type: docs
weight: 2670
url: /es/net/aspose.threed.utilities/boundingbox/
---
## BoundingBox structure

El cuadro delimitador alineado a los ejes

```csharp
public struct BoundingBox
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BoundingBox](boundingbox/#constructor)(Vector3, Vector3) | Inicializar una caja delimitadora finita con la esquina mínima y máxima dadas |
| [BoundingBox](boundingbox/#constructor_1)(double, double, double, double, double, double) | Inicializar una caja delimitadora finita con la esquina mínima y máxima dadas |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Infinite](../../aspose.threed.utilities/boundingbox/infinite/) { get; } | La caja delimitadora infinita |
| static [Null](../../aspose.threed.utilities/boundingbox/null/) { get; } | La caja delimitadora nula |
| [Center](../../aspose.threed.utilities/boundingbox/center/) { get; } | El centro de la caja delimitadora. |
| [Extent](../../aspose.threed.utilities/boundingbox/extent/) { get; } | Obtiene la extensión de la caja delimitadora. |
| [Maximum](../../aspose.threed.utilities/boundingbox/maximum/) { get; } | La esquina máxima de la caja delimitadora |
| [Minimum](../../aspose.threed.utilities/boundingbox/minimum/) { get; } | La esquina mínima de la caja delimitadora |
| [Size](../../aspose.threed.utilities/boundingbox/size/) { get; } | El tamaño de la caja delimitadora |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/boundingbox/fromgeometry/)(Geometry) | Construir una caja delimitadora a partir de la geometría dada |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains)(BoundingBox) | La caja delimitadora para comprobar si está dentro de la caja delimitadora actual. |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains_1)(Vector3) | Comprobar si el punto p está dentro de la caja delimitadora |
| override [Equals](../../aspose.threed.utilities/boundingbox/equals/)(object) | Determina si dos objetos son iguales |
| override [GetHashCode](../../aspose.threed.utilities/boundingbox/gethashcode/)() | Devuelve el código hash de esta instancia |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge)(BoundingBox) | Fusiona la nueva caja con la caja delimitadora actual. |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_1)(Vector3) | Combinar la caja delimitadora actual con el punto dado |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_2)(Vector4) | Combinar la caja delimitadora actual con el punto dado |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_3)(double, double, double) | Combinar la caja delimitadora actual con el punto dado |
| [OverlapsWith](../../aspose.threed.utilities/boundingbox/overlapswith/)(BoundingBox) | Verifique si el cuadro delimitador actual se superpone con el cuadro delimitador especificado. |
| [Scale](../../aspose.threed.utilities/boundingbox/scale/)() | Calcula el valor absoluto más grande de coordenada de cualquier punto contenido. |
| override [ToString](../../aspose.threed.utilities/boundingbox/tostring/)() | Obtiene la representación en cadena de la caja delimitadora. |
| [operator *](../../aspose.threed.utilities/boundingbox/op_multiply/) | Sobrecarga de operador para multiplicar, la esquina mínima y máxima del nuevo cuadro delimitador serán transformadas por la matriz. |

## Ejemplos

El siguiente código muestra cómo obtener un cuadro delimitador de una instancia de Entity.

```csharp
var sphere = new Sphere();
var boundingBox = sphere.GetBoundingBox();
Console.WriteLine("Bounding box = " + boundingBox);
```

### Ver también

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


