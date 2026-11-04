---
title: "Clase Transform"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Transform. Un transform contiene información que permite acceder a objetos de traslación/escalado/rotación o a la matriz de transformación con el costo mínimo. Esto se usa en la transformación local."
type: docs
weight: 2650
url: /es/net/aspose.threed/transform/
---
## Transform class

Una transformación contiene información que permite acceder a la traslación/escalado/rotación del objeto o a la matriz de transformación con un coste mínimo. Esto se usa en la transformación local.

```csharp
public class Transform : A3DObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EulerAngles](../../aspose.threed/transform/eulerangles/) { get; set; } | Obtiene o establece la rotación representada en ángulos de Euler, medida en grados |
| [GeometricRotation](../../aspose.threed/transform/geometricrotation/) { get; set; } | Obtiene o establece la rotación geométrica de Euler (medida en grados). La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no lo soportan. |
| [GeometricScaling](../../aspose.threed/transform/geometricscaling/) { get; set; } | Obtiene o establece el escalado geométrico. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no lo soportan. |
| [GeometricTranslation](../../aspose.threed/transform/geometrictranslation/) { get; set; } | Obtiene o establece la traslación geométrica. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no lo soportan. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [PostRotation](../../aspose.threed/transform/postrotation/) { get; set; } | Obtiene o establece la post-rotación representada en grados |
| [PreRotation](../../aspose.threed/transform/prerotation/) { get; set; } | Obtiene o establece la pre-rotación representada en grados |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Rotation](../../aspose.threed/transform/rotation/) { get; set; } | Obtiene o establece la rotación representada en cuaternión. |
| [RotationOffset](../../aspose.threed/transform/rotationoffset/) { get; set; } | Obtiene o establece el desplazamiento de rotación |
| [RotationPivot](../../aspose.threed/transform/rotationpivot/) { get; set; } | Obtiene o establece el punto de pivote de rotación |
| [Scaling](../../aspose.threed/transform/scaling/) { get; set; } | Obtiene o establece el escalado |
| [ScalingOffset](../../aspose.threed/transform/scalingoffset/) { get; set; } | Obtiene o establece el desplazamiento de escalado |
| [ScalingPivot](../../aspose.threed/transform/scalingpivot/) { get; set; } | Obtiene o establece el punto de pivote de escalado |
| [TransformMatrix](../../aspose.threed/transform/transformmatrix/) { get; set; } | Obtiene o establece la matriz de transformación. |
| [Translation](../../aspose.threed/transform/translation/) { get; set; } | Obtiene o establece la traslación |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetEulerAngles](../../aspose.threed/transform/seteulerangles/)(double, double, double) | Establece los ángulos de Euler en grados de la transformación actual. |
| [SetGeometricRotation](../../aspose.threed/transform/setgeometricrotation/)(double, double, double) | Establece la rotación geométrica de Euler (medida en grados). La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no lo soportan. |
| [SetGeometricScaling](../../aspose.threed/transform/setgeometricscaling/)(double, double, double) | Establece el escalado geométrico. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no lo soportan. |
| [SetGeometricTranslation](../../aspose.threed/transform/setgeometrictranslation/)(double, double, double) | Establece la traslación geométrica. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no lo soportan. |
| [SetPostRotation](../../aspose.threed/transform/setpostrotation/)(double, double, double) | Establece la post-rotación representada en grados |
| [SetPreRotation](../../aspose.threed/transform/setprerotation/)(double, double, double) | Establece la pre-rotación representada en grados |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |
| [SetRotation](../../aspose.threed/transform/setrotation/)(double, double, double, double) | Establece la rotación (como componentes de cuaternión) de la transformación actual. |
| [SetScale](../../aspose.threed/transform/setscale/)(double, double, double) | Establece la escala de la transformación actual. |
| [SetTranslation](../../aspose.threed/transform/settranslation/)(double, double, double) | Establece la traslación de la transformación actual. |

## Ejemplos

El siguiente código muestra cómo cambiar la transformación del nodo:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//coloca la caja en (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### Ver también

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


