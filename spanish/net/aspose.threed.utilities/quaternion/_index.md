---
title: "Estructura Quaternion"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Estructura Aspose.ThreeD.Utilities.Quaternion. El cuaternión se usa normalmente para realizar rotaciones en gráficos por computadora"
type: docs
weight: 2810
url: /es/net/aspose.threed.utilities/quaternion/
---
## Quaternion structure

El cuaternión se usa normalmente para realizar rotaciones en gráficos por computadora.

```csharp
public struct Quaternion
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Quaternion](quaternion/)(double, double, double, double) | Inicializa una nueva instancia de la clase `Quaternion`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Length](../../aspose.threed.utilities/quaternion/length/) { get; } | Obtiene la longitud del cuaternión |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromAngleAxis](../../aspose.threed.utilities/quaternion/fromangleaxis/)(double, Vector3) | Crea un cuaternión alrededor del eje dado y lo rota en sentido horario |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle)(Vector3) | Crea un cuaternión a partir del ángulo de Euler dado |
| static [FromEulerAngle](../../aspose.threed.utilities/quaternion/fromeulerangle/#fromeulerangle_1)(double, double, double) | Crea un cuaternión a partir del ángulo de Euler dado |
| static [FromRotation](../../aspose.threed.utilities/quaternion/fromrotation/)(Vector3, Vector3) | Crea un cuaternión que rota de la dirección original a la de destino |
| static [Interpolate](../../aspose.threed.utilities/quaternion/interpolate/)(float, Quaternion, Quaternion) | Puebla este cuaternión con el valor interpolado entre los argumentos de cuaternión dados para un t entre from y to. |
| static [Slerp](../../aspose.threed.utilities/quaternion/slerp/)(double, Quaternion, Quaternion) | Realiza una interpolación lineal esférica entre dos valores |
| [Concat](../../aspose.threed.utilities/quaternion/concat/)(Quaternion) | Concatena dos cuaterniones |
| [Conjugate](../../aspose.threed.utilities/quaternion/conjugate/)() | Devuelve un cuaternión conjugado del cuaternión actual |
| [Dot](../../aspose.threed.utilities/quaternion/dot/)(Quaternion) | Producto punto |
| override [Equals](../../aspose.threed.utilities/quaternion/equals/)(object) | Comprueba si dos cuaterniones son iguales |
| [EulerAngles](../../aspose.threed.utilities/quaternion/eulerangles/)() | Convierte el cuaternión a una rotación representada por ángulos de Euler. Todos los componentes están en radianes |
| override [GetHashCode](../../aspose.threed.utilities/quaternion/gethashcode/)() | Obtiene el código hash del cuaternión |
| [Inverse](../../aspose.threed.utilities/quaternion/inverse/)() | Devuelve un cuaternión inverso del cuaternión actual |
| [Normalize](../../aspose.threed.utilities/quaternion/normalize/)() | Normaliza el cuaternión |
| [ToAngleAxis](../../aspose.threed.utilities/quaternion/toangleaxis/)(out double, out Vector3) |  |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix)() | Convierte la rotación presentada por el cuaternión a una matriz de transformación. |
| [ToMatrix](../../aspose.threed.utilities/quaternion/tomatrix/#tomatrix_1)(Vector3) | Convierte la rotación presentada por el cuaternión a una matriz de transformación. |
| override [ToString](../../aspose.threed.utilities/quaternion/tostring/)() | Obtiene la representación del cuaternión en cadena |
| [operator +](../../aspose.threed.utilities/quaternion/op_addition/) | Sobrecarga de operador para + |
| [operator /](../../aspose.threed.utilities/quaternion/op_division/) | Sobrecarga del operador para / |
| [operator ==](../../aspose.threed.utilities/quaternion/op_equality/) | Operador de igualdad para cuaternión |
| [operator !=](../../aspose.threed.utilities/quaternion/op_inequality/) | Operador de desigualdad para cuaternión |
| [operator *](../../aspose.threed.utilities/quaternion/op_multiply/#op_multiply_1) | Sobrecarga del operador para * (5 operadores) |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Identity](../../aspose.threed.utilities/quaternion/identity/) | El cuaternión de identidad. |
| [W](../../aspose.threed.utilities/quaternion/w/) | El componente w. |
| [X](../../aspose.threed.utilities/quaternion/x/) | El componente x. |
| [Y](../../aspose.threed.utilities/quaternion/y/) | El componente y. |
| [Z](../../aspose.threed.utilities/quaternion/z/) | El componente z. |

### Ver también

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


