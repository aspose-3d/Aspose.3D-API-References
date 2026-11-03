---
title: "Aspose.ThreeD.Entities"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Toutes les géométries et entités sont définies dans cet espace de noms"
type: docs
weight: 40
url: /fr/net/aspose.threed.entities/
---
Toutes les géométries et entités sont définies dans cet espace de noms

## Classes

| Classe | Description |
| --- | --- |
| [BooleanOperand](./booleanoperand/) | Cette classe encapsule le maillage transformé en tant qu'opérande d'une opération booléenne. |
| [BooleanOperator](./booleanoperator/) | L'opérateur booléen vous permet d'appliquer une opération booléenne sur deux instances de [`IMeshConvertible`](../aspose.threed.entities/imeshconvertible/). |
| [Box](./box/) | Boîte. |
| [Camera](./camera/) | La caméra décrit le point de vue de l'observateur regardant la scène. |
| [Circle](./circle/) | Une courbe [`Circle`](../aspose.threed.entities/circle/) consiste en un ensemble de points sur le bord de la forme circulaire. |
| [CompositeCurve](./compositecurve/) | Une [`CompositeCurve`](../aspose.threed.entities/compositecurve/) se compose de plusieurs segments de courbe. |
| [Curve](./curve/) | La classe de base de toutes les implémentations de courbe. |
| [Cylinder](./cylinder/) | Cylindre paramétré. Il peut également être utilisé pour représenter le cône lorsque l'un des rayons radiusTop/radiusBottom est nul. |
| [Dish](./dish/) | Plat paramétré. |
| [Ellipse](./ellipse/) | Une [`Ellipse`](../aspose.threed.entities/ellipse/) définit un ensemble de points qui forment la forme d'une ellipse. |
| [Frustum](./frustum/) | La classe de base de [`Camera`](../aspose.threed.entities/camera/) et de [`Light`](../aspose.threed.entities/light/) |
| [Geometry](./geometry/) | La classe de base de tous les objets géométriques rendables (comme [`Mesh`](../aspose.threed.entities/mesh/), [`NurbsSurface`](../aspose.threed.entities/nurbssurface/), [`Patch`](../aspose.threed.entities/patch/) etc.). |
| [HalfSpace](./halfspace/) | [`HalfSpace`](../aspose.threed.entities/halfspace/) représente un espace infini qui est divisé par un plan, cela peut être utilisé avec [`BooleanOperator`](../aspose.threed.entities/booleanoperator/) |
| [Light](./light/) | La lumière éclaire la scène. |
| [Line](./line/) | Une polyline est un chemin défini par un ensemble de points avec [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/), et relié par [`Segments`](../aspose.threed.entities/line/segments/), ce qui signifie qu'elle peut également être un ensemble de segments de ligne connectés. La ligne est généralement un objet linéaire, ce qui signifie qu'elle ne peut pas être utilisée pour représenter une courbe ; pour représenter une courbe, utilisez [`NurbsCurve`](../aspose.threed.entities/nurbscurve/). |
| [LinearExtrusion](./linearextrusion/) | L'extrusion linéaire prend une forme 2D en entrée et étend la forme dans la troisième dimension. |
| [Mesh](./mesh/) | Un maillage est composé de nombreux polygones à n côtés. |
| [NurbsCurve](./nurbscurve/) | [NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) est une courbe représentée par les NURBS (Non-uniform rational basis spline). Une courbe NURBS est définie par son [`Order`](../aspose.threed.entities/nurbscurve/order/), un ensemble de [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/) pondérés et un [`KnotVectors`](../aspose.threed.entities/nurbscurve/knotvectors/). Le composant w dans le point de contrôle est utilisé comme poids du point de contrôle, qu'il soit bidimensionnel ou tridimensionnel. |
| [NurbsDirection](./nurbsdirection/) | Une surface 3D [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) possède deux directions, le [`U`](../aspose.threed.entities/nurbssurface/u/) et le [`V`](../aspose.threed.entities/nurbssurface/v/), le [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/) définit les données pour chaque direction. Une direction est en fait une courbe NURBS, ce qui signifie qu'elle est également définie par son [`Order`](../aspose.threed.entities/nurbsdirection/order/), un [`KnotVectors`](../aspose.threed.entities/nurbsdirection/knotvectors/), et un ensemble de points de contrôle pondérés (définis dans [`NurbsSurface`](../aspose.threed.entities/nurbssurface/)). |
| [NurbsSurface](./nurbssurface/) | [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) est une surface représentée par [NURBS(Non-uniform rational basis spline)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline), une [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) est définie par deux [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/)[`U`](../aspose.threed.entities/nurbssurface/u/) et [`V`](../aspose.threed.entities/nurbssurface/v/). Le composant w dans le point de contrôle est utilisé comme poids du point de contrôle, quel que soit le type de la direction, bidimensionnel ou tridimensionnel. |
| [Patch](./patch/) | Un [`Patch`](../aspose.threed.entities/patch/) est une surface de modélisation paramétrique, similaire à [`NurbsSurface`](../aspose.threed.entities/nurbssurface/), elle est également définie par deux [`PatchDirection`](../aspose.threed.entities/patchdirection/), le [`U`](../aspose.threed.entities/patch/u/) et le [`V`](../aspose.threed.entities/patch/v/). Mais la différence entre [`Patch`](../aspose.threed.entities/patch/) et [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) est que la courbe [`PatchDirection`](../aspose.threed.entities/patchdirection/) peut être l'une des suivantes : Bezier, QuadraticBezier, BasisSpline, CardinalSpline et Linear. |
| [PatchDirection](./patchdirection/) | Direction U et V du Patch. |
| [Plane](./plane/) | Plan paramétré. |
| [PointCloud](./pointcloud/) | Le nuage de points ne contient aucune information de topologie, seulement les points de contrôle et les éléments de sommet. |
| [PolygonBuilder](./polygonbuilder/) | Une classe d'aide pour construire des polygones pour [`Mesh`](../aspose.threed.entities/mesh/) |
| [PolygonModifier](./polygonmodifier/) | Utilitaires pour modifier les polygones |
| [Primitive](./primitive/) | Classe de base pour toutes les primitives |
| [Pyramid](./pyramid/) | Pyramide paramétrée. |
| [RectangularTorus](./rectangulartorus/) | Tore rectangulaire paramétré. |
| [RevolvedAreaSolid](./revolvedareasolid/) | Cette classe représente un modèle solide en faisant tourner une section transversale fournie par un profil autour d'un axe. |
| [Shape](./shape/) | La forme décrit la déformation d'un ensemble de points de contrôle, ce qui est similaire au déformateur de groupe dans Maya. Par exemple, nous pouvons ajouter une forme à une géométrie créée. La forme et la géométrie ont les mêmes informations topologiques mais des positions différentes des points de contrôle. Avec des quantités d'influence variables, la géométrie produit un effet de déformation. |
| [Skeleton](./skeleton/) | Le [`Skeleton`](../aspose.threed.entities/skeleton/) est principalement utilisé par les logiciels CAD pour aider le concepteur à manipuler la transformation de la structure squelettique, il est généralement inutile en dehors des logiciels CAD. Pour que la hiérarchie du squelette se comporte comme un seul objet dans le logiciel CAD, il est nécessaire de marquer le nœud supérieur du [`Skeleton`](../aspose.threed.entities/skeleton/) comme racine en définissant [`Type`](../aspose.threed.entities/skeleton/type/) sur Skeleton, et tous les enfants sur Bone |
| [Sphere](./sphere/) | Sphère paramétrée. |
| [SweptAreaSolid](./sweptareasolid/) | Un [`SweptAreaSolid`](../aspose.threed.entities/sweptareasolid/) construit une géométrie en balayant un profil le long d’une directrice. |
| [Torus](./torus/) | Tore paramétré. |
| [TransformedCurve](./transformedcurve/) | Un [`TransformedCurve`](../aspose.threed.entities/transformedcurve/) donne à une courbe un placement en utilisant une matrice de transformation. Cela permet d’effectuer une transformation à l’intérieur d’un [`TrimmedCurve`](../aspose.threed.entities/trimmedcurve/) ou d’un [`CompositeCurve`](../aspose.threed.entities/compositecurve/). |
| [TriMesh](./trimesh/) | Un TriMesh contient des données brutes qui peuvent être utilisées directement par le GPU. Cette classe est un utilitaire pour aider à construire un maillage ne contenant que des données par sommet. |
| [TriMesh&lt;T&gt;](./trimesh-1/) | Version générique de [`TriMesh`](../aspose.threed.entities/trimesh/) pour le type de sommet défini statiquement par l'utilisateur |
| [TrimmedCurve](./trimmedcurve/) | Une courbe bornée qui coupe la courbe de base aux deux extrémités. |
| [VertexElement](./vertexelement/) | Classe de base des éléments de sommet. Un type d’élément de sommet est identifié par VertexElementType. Un VertexElement décrit comment l’élément de sommet est mappé sur une surface géométrique et comment les informations de mappage sont organisées en mémoire. Un VertexElement contient des normales, des UV ou d’autres types d’informations. |
| [VertexElementBinormal](./vertexelementbinormal/) | Définit les vecteurs binormaux pour les composants spécifiés. |
| [VertexElementDoublesTemplate](./vertexelementdoublestemplate/) | Une classe d’aide pour définir des implémentations concrètes de [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementEdgeCrease](./vertexelementedgecrease/) | Définit le pli de bord pour les composants spécifiés |
| [VertexElementHole](./vertexelementhole/) | Définit si le polygone spécifié est un trou |
| [VertexElementIntsTemplate](./vertexelementintstemplate/) | Une classe d’aide pour définir des implémentations concrètes de [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementMaterial](./vertexelementmaterial/) | Définit l’indice de matériau pour les composants spécifiés. Un nœud peut avoir plusieurs matériaux, le [`VertexElementMaterial`](../aspose.threed.entities/vertexelementmaterial/) est utilisé pour rendre différentes parties de la géométrie avec différents matériaux. |
| [VertexElementNormal](./vertexelementnormal/) | Définit les vecteurs normaux pour les composants spécifiés. |
| [VertexElementPolygonGroup](./vertexelementpolygongroup/) | Définit le groupe de polygones pour les composants spécifiés afin de regrouper les polygones liés ensemble. |
| [VertexElementSmoothingGroup](./vertexelementsmoothinggroup/) | Un groupe de lissage est un groupe de polygones dans un maillage polygonal qui doit apparaître comme une surface lisse. Certains logiciels de modélisation 3D anciens, comme 3D Studio Max pour DOS, utilisaient le groupe de lissage pour éviter de stocker le vecteur normal pour chaque sommet du maillage. |
| [VertexElementSpecular](./vertexelementspecular/) | Définit la couleur spéculaire pour les composants spécifiés. |
| [VertexElementTangent](./vertexelementtangent/) | Définit les vecteurs tangents pour les composants spécifiés. |
| [VertexElementTemplate&lt;T&gt;](./vertexelementtemplate-1/) | Une classe d’aide pour définir des implémentations concrètes de [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementUserData](./vertexelementuserdata/) | Définit les données utilisateur personnalisées pour les composants spécifiés. Il s’agit généralement de données spécifiques à l’application pour un usage particulier. |
| [VertexElementUV](./vertexelementuv/) | Définit les coordonnées UV pour les composants spécifiés. Une géométrie peut avoir plusieurs éléments [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/), et chacun possède différents [`TextureMapping`](../aspose.threed.entities/texturemapping/). |
| [VertexElementVector4](./vertexelementvector4/) | Une classe d’aide pour définir des implémentations concrètes de [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementVertexColor](./vertexelementvertexcolor/) | Définit la couleur du sommet pour les composants spécifiés |
| [VertexElementVertexCrease](./vertexelementvertexcrease/) | Définit le pli du sommet pour les composants spécifiés |
| [VertexElementVisibility](./vertexelementvisibility/) | Définit si les composants spécifiés sont visibles |
| [VertexElementWeight](./vertexelementweight/) | Définit le poids de mélange pour les composants spécifiés. |
## Structures

| Structure | Description |
| --- | --- |
| [EndPoint](./endpoint/) | Le point final pour tronquer la courbe peut être une valeur de paramètre ou un point cartésien. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IIndexedVertexElement](./iindexedvertexelement/) | VertexElement avec des données d'indices. |
| [IMeshConvertible](./imeshconvertible/) | Les entités qui implémentent cette interface peuvent être converties en [`Mesh`](../aspose.threed.entities/mesh/) |
| [IOrientable](./iorientable/) | Les entités orientables doivent implémenter cette interface. |
## Énumération

| Énumération | Description |
| --- | --- |
| [ApertureMode](./aperturemode/) | Modes d'ouverture de la caméra. Le mode d'ouverture détermine quelles valeurs contrôlent l'ouverture de la caméra. Si le mode d'ouverture est HorizAndVert, Horizontal ou Vertical, alors le champ de vision est utilisé. Si le mode d'ouverture est FocalLength, alors la distance focale est utilisée. |
| [BooleanOperation](./booleanoperation/) | Opération booléenne du Mesh |
| [CurveDimension](./curvedimension/) | La dimension des courbes. |
| [LightType](./lighttype/) | Types de lumière. |
| [MappingMode](./mappingmode/) | Détermine comment l'élément est mappé sur une surface. Le [`MappingMode`](../aspose.threed.entities/mappingmode/) définit comment le [`VertexElement`](../aspose.threed.entities/vertexelement/) est mappé sur la surface de la géométrie. |
| [NurbsType](./nurbstype/) | Types de NURBS. |
| [PatchDirectionType](./patchdirectiontype/) | Types de direction de patch. |
| [ProjectionType](./projectiontype/) | Types de projection de la caméra. |
| [ReferenceMode](./referencemode/) | [`ReferenceMode`](../aspose.threed.entities/referencemode/) définit comment les informations de mappage sont stockées et référencées par. |
| [RotationMode](./rotationmode/) | Le mode de rotation du frustum |
| [SkeletonType](./skeletontype/) | Types de [`Skeleton`](../aspose.threed.entities/skeleton/) |
| [SplitMeshPolicy](./splitmeshpolicy/) | Partager les données de sommet/point de contrôle entre les sous-meshes ou chaque sous-mesh possède ses propres données compactées. |
| [TextureMapping](./texturemapping/) | Le type de mappage de texture pour [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/) décrit quel type de mappage de texture est utilisé. |
| [VertexElementType](./vertexelementtype/) | Le type de l'élément de sommet, définit comment il sera utilisé dans la modélisation. |


