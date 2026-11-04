---
title: "Aspose.ThreeD.Utilities"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Todas las clases de utilidad están definidas en este espacio de nombres"
type: docs
weight: 100
url: /es/net/aspose.threed.utilities/
---
Todas las clases de utilidad se definen en este espacio de nombres.

## Clases

| Clase | Descripción |
| --- | --- |
| [FileSystem](./filesystem/) | Encapsulación del sistema de archivos. Aspose.3D usará esto para leer/escribir dependencias. |
| [IOExtension](./ioextension/) | Utilidades para escribir matrices/vectores en un escritor binario |
| [MathUtils](./mathutils/) | Un conjunto de utilidades matemáticas útiles. |
| [ParseException](./parseexception/) | Excepción cuando Aspose.3D no pudo analizar la entrada. |
| [SemanticAttribute](./semanticattribute/) | Permitir al usuario usar su propia estructura para la declaración estática de [`VertexDeclaration`](../aspose.threed.utilities/vertexdeclaration/) |
| [TransformBuilder](./transformbuilder/) | El [`TransformBuilder`](../aspose.threed.utilities/transformbuilder/) se usa para construir una matriz de transformación mediante una cadena de transformaciones. |
| [Vertex](./vertex/) | Referencia de vértice, utilizada para acceder al vértice crudo en [`TriMesh`](../aspose.threed.entities/trimesh/). |
| [VertexDeclaration](./vertexdeclaration/) | La declaración de la estructura de un vértice definido de forma personalizada |
| [VertexField](./vertexfield/) | Descripción del diseño de memoria de los campos del vértice. |
| [Watermark](./watermark/) | Utilidad para codificar/decodificar marca de agua ciega hacia/desde una malla. |
## Structures

| Estructura | Descripción |
| --- | --- |
| [BoundingBox](./boundingbox/) | El cuadro delimitador alineado a los ejes |
| [BoundingBox2D](./boundingbox2d/) | El cuadro delimitador alineado a los ejes para [`Vector2`](../aspose.threed.utilities/vector2/) |
| [FMatrix4](./fmatrix4/) | Matriz 4x4 con todos los componentes de tipo flotante |
| [FVector2](./fvector2/) | Un vector flotante con dos componentes. |
| [FVector3](./fvector3/) | Un vector flotante con tres componentes. |
| [FVector4](./fvector4/) | Un vector flotante con cuatro componentes. |
| [Matrix4](./matrix4/) | Implementación de matriz 4x4. |
| [Quaternion](./quaternion/) | El cuaternión se usa normalmente para realizar rotaciones en gráficos por computadora. |
| [Rect](./rect/) | Una clase para representar el rectángulo |
| [RelativeRectangle](./relativerectangle/) | Rectángulo relativo La fórmula entre el componente relativo y el valor absoluto es: Escala * (Ancho de referencia) + desplazamiento. Así que si queremos que represente un valor absoluto, deje todos los campos de escala en cero y use los campos de desplazamiento en su lugar. |
| [Vector2](./vector2/) | Un vector con dos componentes. |
| [Vector3](./vector3/) | Un vector con tres componentes. |
| [Vector4](./vector4/) | Un vector con cuatro componentes. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IArrayList&lt;T&gt;](./iarraylist-1/) | Aspose.3D tiene su propia implementación altamente optimizada de List para un mejor rendimiento de carga/guardado. Sólo esta interfaz se expone al usuario con compatibilidad IList y interfaces similares. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [BoundingBoxExtent](./boundingboxextent/) | La extensión del cuadro delimitador |
| [ComposeOrder](./composeorder/) | El orden para componer la matriz de transformación |
| [RotationOrder](./rotationorder/) | El orden controla qué rx ry rz se aplican en la matriz de transformación. |
| [VertexFieldDataType](./vertexfielddatatype/) | Tipo de datos del campo de vértice |
| [VertexFieldSemantic](./vertexfieldsemantic/) | La semántica del campo de vértice |


