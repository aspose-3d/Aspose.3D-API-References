---
title: "Aspose.ThreeD.Entities"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Todas las geometrías y entidades se definen en este espacio de nombres"
type: docs
weight: 40
url: /es/net/aspose.threed.entities/
---
Todas las geometrías y entidades se definen en este espacio de nombres

## Clases

| Clase | Descripción |
| --- | --- |
| [BooleanOperand](./booleanoperand/) | Esta clase encapsula la malla transformada como operando de la operación Booleana. |
| [BooleanOperator](./booleanoperator/) | El operador booleano le permite aplicar una operación Booleana a dos instancias de [`IMeshConvertible`](../aspose.threed.entities/imeshconvertible/). |
| [Box](./box/) | Caja. |
| [Camera](./camera/) | La cámara describe el punto de vista del observador que mira la escena. |
| [Circle](./circle/) | Una curva [`Circle`](../aspose.threed.entities/circle/) consiste en un conjunto de puntos en el borde de la forma circular. |
| [CompositeCurve](./compositecurve/) | Una [`CompositeCurve`](../aspose.threed.entities/compositecurve/) está compuesta por varios segmentos de curva. |
| [Curve](./curve/) | La clase base de todas las implementaciones de curvas. |
| [Cylinder](./cylinder/) | Cilindro parametrizado. También puede usarse para representar el cono cuando uno de radiusTop/radiusBottom es cero. |
| [Dish](./dish/) | Plato parametrizado. |
| [Ellipse](./ellipse/) | Una [`Ellipse`](../aspose.threed.entities/ellipse/) define un conjunto de puntos que forman la forma de una elipse. |
| [Frustum](./frustum/) | La clase base de [`Camera`](../aspose.threed.entities/camera/) y [`Light`](../aspose.threed.entities/light/) |
| [Geometry](./geometry/) | La clase base de todos los objetos geométricos renderizables (como [`Mesh`](../aspose.threed.entities/mesh/), [`NurbsSurface`](../aspose.threed.entities/nurbssurface/), [`Patch`](../aspose.threed.entities/patch/) y etc.). |
| [HalfSpace](./halfspace/) | [`HalfSpace`](../aspose.threed.entities/halfspace/) representa un espacio infinito que se divide por un plano, esto puede usarse con [`BooleanOperator`](../aspose.threed.entities/booleanoperator/) |
| [Light](./light/) | La luz ilumina la escena. |
| [Line](./line/) | Una polilínea es una ruta definida por un conjunto de puntos con [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/), y conectada por [`Segments`](../aspose.threed.entities/line/segments/), lo que significa que también puede ser un conjunto de segmentos de línea conectados. La línea suele ser un objeto lineal, lo que implica que no puede usarse para representar una curva; para representar una curva, se utiliza [`NurbsCurve`](../aspose.threed.entities/nurbscurve/). |
| [LinearExtrusion](./linearextrusion/) | La extrusión lineal toma una forma 2D como entrada y extiende la forma en la tercera dimensión. |
| [Mesh](./mesh/) | Una malla está compuesta por muchos polígonos de n lados. |
| [NurbsCurve](./nurbscurve/) | [NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) es una curva representada por NURBS (Non-uniform rational basis spline). Una curva NURBS se define por su [`Order`](../aspose.threed.entities/nurbscurve/order/), un conjunto de [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/) ponderados y un [`KnotVectors`](../aspose.threed.entities/nurbscurve/knotvectors/). El componente w en el punto de control se usa como peso del punto de control, sea que sea bidimensional o tridimensional. |
| [NurbsDirection](./nurbsdirection/) | Una [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) 3D tiene dos direcciones, la [`U`](../aspose.threed.entities/nurbssurface/u/) y la [`V`](../aspose.threed.entities/nurbssurface/v/), el [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/) define los datos para cada dirección. Una dirección es en realidad una curva NURBS, lo que significa que también se define por su [`Order`](../aspose.threed.entities/nurbsdirection/order/), un [`KnotVectors`](../aspose.threed.entities/nurbsdirection/knotvectors/), y un conjunto de puntos de control ponderados (definidos en [`NurbsSurface`](../aspose.threed.entities/nurbssurface/)). |
| [NurbsSurface](./nurbssurface/) | [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) es una superficie representada por [NURBS(Non-uniform rational basis spline)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline), una [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) se define por dos [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/)[`U`](../aspose.threed.entities/nurbssurface/u/) y [`V`](../aspose.threed.entities/nurbssurface/v/). El componente w en el punto de control se usa como peso del punto de control, sea que el tipo de dirección sea bidimensional o tridimensional. |
| [Patch](./patch/) | Un [`Patch`](../aspose.threed.entities/patch/) es una superficie de modelado paramétrico, similar a [`NurbsSurface`](../aspose.threed.entities/nurbssurface/), también se define por dos [`PatchDirection`](../aspose.threed.entities/patchdirection/), la [`U`](../aspose.threed.entities/patch/u/) y la [`V`](../aspose.threed.entities/patch/v/). Pero la diferencia entre [`Patch`](../aspose.threed.entities/patch/) y [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) es que la curva [`PatchDirection`](../aspose.threed.entities/patchdirection/) puede ser una de Bezier, QuadraticBezier, BasisSpline, CardinalSpline y Linear. |
| [PatchDirection](./patchdirection/) | Dirección U y V del Patch. |
| [Plane](./plane/) | Plano parametrizado. |
| [PointCloud](./pointcloud/) | La nube de puntos no contiene información de topología, solo los puntos de control y los elementos de vértice. |
| [PolygonBuilder](./polygonbuilder/) | Una clase auxiliar para construir polígonos para [`Mesh`](../aspose.threed.entities/mesh/). |
| [PolygonModifier](./polygonmodifier/) | Utilidades para modificar polígonos. |
| [Primitive](./primitive/) | Clase base para todas las primitivas. |
| [Pyramid](./pyramid/) | Pirámide parametrizada. |
| [RectangularTorus](./rectangulartorus/) | Toro rectangular parametrizado. |
| [RevolvedAreaSolid](./revolvedareasolid/) | Esta clase representa un modelo sólido al girar una sección transversal proporcionada por un perfil alrededor de un eje. |
| [Shape](./shape/) | La forma describe la deformación en un conjunto de puntos de control, lo que es similar al deformador de clúster en Maya. Por ejemplo, podemos añadir una forma a una geometría creada. Y la forma y la geometría tienen la misma información topológica pero una posición diferente de los puntos de control. Con diferentes niveles de influencia, la geometría produce un efecto de deformación. |
| [Skeleton](./skeleton/) | El [`Skeleton`](../aspose.threed.entities/skeleton/) se usa principalmente en software CAD para ayudar al diseñador a manipular la transformación de la estructura esquelética, suele ser inútil fuera de los softwares CAD. Para que la jerarquía del esqueleto actúe como un solo objeto en el software CAD, es necesario marcar el nodo superior [`Skeleton`](../aspose.threed.entities/skeleton/) como raíz estableciendo [`Type`](../aspose.threed.entities/skeleton/type/) a Skeleton, y todos los hijos a Bone |
| [Sphere](./sphere/) | Esfera parametrizada. |
| [SweptAreaSolid](./sweptareasolid/) | Un [`SweptAreaSolid`](../aspose.threed.entities/sweptareasolid/) construye una geometría barrendo un perfil a lo largo de una directriz. |
| [Torus](./torus/) | Toro parametrizado. |
| [TransformedCurve](./transformedcurve/) | Un [`TransformedCurve`](../aspose.threed.entities/transformedcurve/) asigna una posición a una curva mediante una matriz de transformación. Esto permite realizar una transformación dentro de un [`TrimmedCurve`](../aspose.threed.entities/trimmedcurve/) o [`CompositeCurve`](../aspose.threed.entities/compositecurve/). |
| [TriMesh](./trimesh/) | Un TriMesh contiene datos crudos que pueden ser usados directamente por la GPU. Esta clase es una utilidad para ayudar a construir una malla que solo contiene datos por vértice. |
| [TriMesh&lt;T&gt;](./trimesh-1/) | Versión genérica de [`TriMesh`](../aspose.threed.entities/trimesh/) para el tipo de vértice estático definido por el usuario |
| [TrimmedCurve](./trimmedcurve/) | Una curva limitada que recorta la curva base en ambos extremos. |
| [VertexElement](./vertexelement/) | Clase base de elementos de vértice. Un tipo de elemento de vértice se identifica mediante VertexElementType. Un VertexElement describe cómo se asigna el elemento de vértice a una superficie geométrica y cómo se organiza la información de asignación en la memoria. Un VertexElement contiene Normales, UVs u otro tipo de información. |
| [VertexElementBinormal](./vertexelementbinormal/) | Define los vectores binormales para los componentes especificados. |
| [VertexElementDoublesTemplate](./vertexelementdoublestemplate/) | Una clase auxiliar para definir implementaciones concretas de [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementEdgeCrease](./vertexelementedgecrease/) | Define el pliegue del borde para los componentes especificados |
| [VertexElementHole](./vertexelementhole/) | Define si el polígono especificado es un agujero |
| [VertexElementIntsTemplate](./vertexelementintstemplate/) | Una clase auxiliar para definir implementaciones concretas de [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementMaterial](./vertexelementmaterial/) | Define el índice de material para los componentes especificados. Un nodo puede tener múltiples materiales, el [`VertexElementMaterial`](../aspose.threed.entities/vertexelementmaterial/) se usa para renderizar diferentes partes de la geometría con distintos materiales. |
| [VertexElementNormal](./vertexelementnormal/) | Define los vectores normales para los componentes especificados. |
| [VertexElementPolygonGroup](./vertexelementpolygongroup/) | Define el grupo de polígonos para los componentes especificados para agrupar polígonos relacionados. |
| [VertexElementSmoothingGroup](./vertexelementsmoothinggroup/) | Un grupo de suavizado es un conjunto de polígonos en una malla de polígonos que debe aparecer como una superficie lisa. Algunos softwares de modelado 3D tempranos como 3D Studio Max para DOS usaban grupos de suavizado para evitar almacenar el vector normal de cada vértice de la malla. |
| [VertexElementSpecular](./vertexelementspecular/) | Define el color especular para los componentes especificados. |
| [VertexElementTangent](./vertexelementtangent/) | Define los vectores tangentes para los componentes especificados. |
| [VertexElementTemplate&lt;T&gt;](./vertexelementtemplate-1/) | Una clase auxiliar para definir implementaciones concretas de [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementUserData](./vertexelementuserdata/) | Define datos de usuario personalizados para los componentes especificados. Usualmente son datos específicos de la aplicación para un propósito especial. |
| [VertexElementUV](./vertexelementuv/) | Define las coordenadas UV para los componentes especificados. Una geometría puede tener múltiples elementos [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/), y cada uno tiene diferentes [`TextureMapping`](../aspose.threed.entities/texturemapping/). |
| [VertexElementVector4](./vertexelementvector4/) | Una clase auxiliar para definir implementaciones concretas de [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementVertexColor](./vertexelementvertexcolor/) | Define el color del vértice para los componentes especificados |
| [VertexElementVertexCrease](./vertexelementvertexcrease/) | Define el pliegue del vértice para los componentes especificados |
| [VertexElementVisibility](./vertexelementvisibility/) | Define si los componentes especificados son visibles |
| [VertexElementWeight](./vertexelementweight/) | Define el peso de mezcla para los componentes especificados. |
## Structures

| Estructura | Descripción |
| --- | --- |
| [EndPoint](./endpoint/) | El punto final para recortar la curva, puede ser un valor de parámetro o un punto cartesiano. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IIndexedVertexElement](./iindexedvertexelement/) | VertexElement con datos de índices. |
| [IMeshConvertible](./imeshconvertible/) | Las entidades que implementaron esta interfaz pueden convertirse a [`Mesh`](../aspose.threed.entities/mesh/) |
| [IOrientable](./iorientable/) | Las entidades orientables deberán implementar esta interfaz. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [ApertureMode](./aperturemode/) | Modos de apertura de cámara. El modo de apertura determina qué valores controlan la apertura de la cámara. Si el modo de apertura es HorizAndVert, Horizontal o Vertical, se utiliza el campo de visión. Si el modo de apertura es FocalLength, se utiliza la distancia focal. |
| [BooleanOperation](./booleanoperation/) | Operación booleana de Mesh |
| [CurveDimension](./curvedimension/) | La dimensión de las curvas. |
| [LightType](./lighttype/) | Tipos de luz. |
| [MappingMode](./mappingmode/) | Determina cómo se asigna el elemento a una superficie. El [`MappingMode`](../aspose.threed.entities/mappingmode/) define cómo se asigna el [`VertexElement`](../aspose.threed.entities/vertexelement/) a la superficie de la geometría. |
| [NurbsType](./nurbstype/) | Tipos de NURBS. |
| [PatchDirectionType](./patchdirectiontype/) | Tipos de dirección de parche. |
| [ProjectionType](./projectiontype/) | Tipos de proyección de la cámara. |
| [ReferenceMode](./referencemode/) | [`ReferenceMode`](../aspose.threed.entities/referencemode/) define cómo se almacena y referencia la información de mapeo. |
| [RotationMode](./rotationmode/) | El modo de rotación del frustum |
| [SkeletonType](./skeletontype/) | Tipos de [`Skeleton`](../aspose.threed.entities/skeleton/). |
| [SplitMeshPolicy](./splitmeshpolicy/) | Compartir datos de vértices/puntos de control entre submallas o que cada submalla tenga sus propios datos compactados. |
| [TextureMapping](./texturemapping/) | El tipo de mapeo de textura para [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/) describe qué tipo de mapeo de textura se utiliza. |
| [VertexElementType](./vertexelementtype/) | El tipo del elemento de vértice, define cómo se utilizará en el modelado. |


