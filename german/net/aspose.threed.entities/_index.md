---
title: "Aspose.ThreeD.Entities"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Alle Geometrie‑ und Entitätsklassen sind in diesem Namensraum definiert"
type: docs
weight: 40
url: /de/net/aspose.threed.entities/
---
Alle Geometrie‑ und Entitätsklassen sind in diesem Namensraum definiert

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [BooleanOperand](./booleanoperand/) | Diese Klasse kapselt das transformierte Mesh als Operand einer Booleschen Operation. |
| [BooleanOperator](./booleanoperator/) | Der Boolesche Operator ermöglicht es, eine Boolesche Operation auf zwei [`IMeshConvertible`](../aspose.threed.entities/imeshconvertible/) Instanzen anzuwenden. |
| [Box](./box/) | Box. |
| [Camera](./camera/) | Die Kamera beschreibt den Blickpunkt des Betrachters, der die Szene betrachtet. |
| [Circle](./circle/) | Eine [`Circle`](../aspose.threed.entities/circle/) Kurve besteht aus einer Menge von Punkten am Rand der Kreisform. |
| [CompositeCurve](./compositecurve/) | Eine [`CompositeCurve`](../aspose.threed.entities/compositecurve/) besteht aus mehreren Kurvensegmenten. |
| [Curve](./curve/) | Die Basisklasse aller Kurvenimplementierungen. |
| [Cylinder](./cylinder/) | Parametrisierter Zylinder. Er kann auch verwendet werden, um den Kegel darzustellen, wenn einer der Werte radiusTop/radiusBottom null ist. |
| [Dish](./dish/) | Parametrisierte Schale. |
| [Ellipse](./ellipse/) | Ein [`Ellipse`](../aspose.threed.entities/ellipse/) definiert eine Menge von Punkten, die die Form einer Ellipse bilden. |
| [Frustum](./frustum/) | Die Basisklasse von [`Camera`](../aspose.threed.entities/camera/) und [`Light`](../aspose.threed.entities/light/) |
| [Geometry](./geometry/) | Die Basisklasse aller renderbaren geometrischen Objekte (wie [`Mesh`](../aspose.threed.entities/mesh/), [`NurbsSurface`](../aspose.threed.entities/nurbssurface/), [`Patch`](../aspose.threed.entities/patch/) und etc.). |
| [HalfSpace](./halfspace/) | [`HalfSpace`](../aspose.threed.entities/halfspace/) repräsentiert einen unendlichen Raum, der durch eine Ebene geteilt wird; dies kann mit [`BooleanOperator`](../aspose.threed.entities/booleanoperator/) verwendet werden. |
| [Light](./light/) | Das Licht beleuchtet die Szene. |
| [Line](./line/) | Eine Polylinie ist ein Pfad, der durch eine Menge von Punkten mit [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/) definiert wird und durch [`Segments`](../aspose.threed.entities/line/segments/) verbunden ist, was bedeutet, dass es auch eine Menge verbundener Liniensegmente sein kann. Die Linie ist normalerweise ein lineares Objekt, was bedeutet, dass sie nicht verwendet werden kann, um eine Kurve darzustellen; um eine Kurve darzustellen, verwendet man [`NurbsCurve`](../aspose.threed.entities/nurbscurve/). |
| [LinearExtrusion](./linearextrusion/) | Lineare Extrusion nimmt eine 2D-Form als Eingabe und erweitert die Form in die dritte Dimension. |
| [Mesh](./mesh/) | Ein Mesh besteht aus vielen n-seitigen Polygonen. |
| [NurbsCurve](./nurbscurve/) | [NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) ist eine Kurve, die durch NURBS (Non-uniform rational basis spline) dargestellt wird. Eine NURBS-Kurve wird durch ihr [`Order`](../aspose.threed.entities/nurbscurve/order/), eine Menge gewichteter [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/) und ein [`KnotVectors`](../aspose.threed.entities/nurbscurve/knotvectors/) definiert. Die w-Komponente im Kontrollpunkt wird als Gewicht des Kontrollpunkts verwendet, unabhängig davon, ob es sich um eine zweidimensionale oder dreidimensionale handelt. |
| [NurbsDirection](./nurbsdirection/) | Eine 3D-[`NurbsSurface`](../aspose.threed.entities/nurbssurface/) hat zwei Richtungen, das [`U`](../aspose.threed.entities/nurbssurface/u/) und das [`V`](../aspose.threed.entities/nurbssurface/v/); das [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/) definiert Daten für jede Richtung. Eine Richtung ist tatsächlich eine NURBS-Kurve, das bedeutet, sie wird ebenfalls durch ihr [`Order`](../aspose.threed.entities/nurbsdirection/order/), ein [`KnotVectors`](../aspose.threed.entities/nurbsdirection/knotvectors/) und eine Menge gewichteter Kontrollpunkte (definiert in [`NurbsSurface`](../aspose.threed.entities/nurbssurface/)) definiert. |
| [NurbsSurface](./nurbssurface/) | [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) ist eine Oberfläche, die durch [NURBS (Non-uniform rational basis spline)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) dargestellt wird. Eine [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) wird durch zwei [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/)[`U`](../aspose.threed.entities/nurbssurface/u/) und [`V`](../aspose.threed.entities/nurbssurface/v/) definiert. Die w-Komponente im Kontrollpunkt wird als Gewicht des Kontrollpunkts verwendet, unabhängig davon, ob der Richtungstyp zweidimensional oder dreidimensional ist. |
| [Patch](./patch/) | Ein [`Patch`](../aspose.threed.entities/patch/) ist eine parametrische Modellierungsoberfläche, ähnlich wie [`NurbsSurface`](../aspose.threed.entities/nurbssurface/); sie wird ebenfalls durch zwei [`PatchDirection`](../aspose.threed.entities/patchdirection/), das [`U`](../aspose.threed.entities/patch/u/) und das [`V`](../aspose.threed.entities/patch/v/), definiert. Der Unterschied zwischen [`Patch`](../aspose.threed.entities/patch/) und [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) besteht darin, dass die [`PatchDirection`](../aspose.threed.entities/patchdirection/) Kurve eine von Bezier, QuadraticBezier, BasisSpline, CardinalSpline und Linear sein kann. |
| [PatchDirection](./patchdirection/) | U- und V-Richtung des Patches. |
| [Plane](./plane/) | Parametrisierte Ebene. |
| [PointCloud](./pointcloud/) | Die Punktwolke enthält keine Topologieinformationen, sondern nur die Kontrollpunkte und die Vertex-Elemente. |
| [PolygonBuilder](./polygonbuilder/) | Eine Hilfsklasse zum Erstellen eines Polygons für [`Mesh`](../aspose.threed.entities/mesh/) |
| [PolygonModifier](./polygonmodifier/) | Hilfsprogramme zum Ändern von Polygonen |
| [Primitive](./primitive/) | Basisklasse für alle Primitive |
| [Pyramid](./pyramid/) | Parametrisierte Pyramide. |
| [RectangularTorus](./rectangulartorus/) | Parametrisierter rechteckiger Torus. |
| [RevolvedAreaSolid](./revolvedareasolid/) | Diese Klasse stellt ein Festkörpermodell dar, indem ein Querschnitt, der durch ein Profil bereitgestellt wird, um eine Achse rotiert wird. |
| [Shape](./shape/) | Die Form beschreibt die Deformation eines Satzes von Kontrollpunkten, was dem Cluster-Deformer in Maya ähnelt. Zum Beispiel können wir einer erstellten Geometrie eine Form hinzufügen. Und die Form und die Geometrie besitzen dieselben topologischen Informationen, jedoch unterschiedliche Positionen der Kontrollpunkte. Mit variierenden Einflussstärken erzeugt die Geometrie einen Deformationseffekt. |
| [Skeleton](./skeleton/) | Das [`Skeleton`](../aspose.threed.entities/skeleton/) wird hauptsächlich von CAD‑Software verwendet, um dem Designer zu ermöglichen, die Transformation der Skelettstruktur zu manipulieren; außerhalb von CAD‑Software ist es meist nutzlos. Damit die Skelett‑Hierarchie in CAD‑Software wie ein einzelnes Objekt wirkt, muss der oberste [`Skeleton`](../aspose.threed.entities/skeleton/)‑Knoten als Wurzel gekennzeichnet werden, indem [`Type`](../aspose.threed.entities/skeleton/type/) auf Skeleton gesetzt wird, und alle Kindknoten auf Bone gesetzt werden. |
| [Sphere](./sphere/) | Parametrisierte Kugel. |
| [SweptAreaSolid](./sweptareasolid/) | Ein [`SweptAreaSolid`](../aspose.threed.entities/sweptareasolid/) erzeugt eine Geometrie, indem ein Profil entlang einer Direktrix bewegt wird. |
| [Torus](./torus/) | Parametrisierter Torus. |
| [TransformedCurve](./transformedcurve/) | Ein [`TransformedCurve`](../aspose.threed.entities/transformedcurve/) gibt einer Kurve eine Platzierung mittels einer Transformationsmatrix. Dies ermöglicht es, eine Transformation innerhalb eines [`TrimmedCurve`](../aspose.threed.entities/trimmedcurve/) oder [`CompositeCurve`](../aspose.threed.entities/compositecurve/) durchzuführen. |
| [TriMesh](./trimesh/) | Ein TriMesh enthält Rohdaten, die direkt von der GPU verwendet werden können. Diese Klasse ist ein Hilfswerkzeug, um ein Mesh zu erstellen, das nur pro-Vertex‑Daten enthält. |
| [TriMesh&lt;T&gt;](./trimesh-1/) | Generische Version von [`TriMesh`](../aspose.threed.entities/trimesh/) für vom Benutzer statisch definierten Vertex‑Typ |
| [TrimmedCurve](./trimmedcurve/) | Eine begrenzte Kurve, die die Basis­kurve an beiden Enden abschneidet. |
| [VertexElement](./vertexelement/) | Basisklasse für Vertex‑Elemente. Ein Vertex‑Elementtyp wird durch VertexElementType identifiziert. Ein VertexElement beschreibt, wie das Vertex‑Element auf eine Geometrieoberfläche abgebildet wird und wie die Abbildungsinformationen im Speicher angeordnet sind. Ein VertexElement enthält Normalen, UVs oder andere Arten von Informationen. |
| [VertexElementBinormal](./vertexelementbinormal/) | Definiert die Binormalvektoren für die angegebenen Komponenten. |
| [VertexElementDoublesTemplate](./vertexelementdoublestemplate/) | Eine Hilfsklasse zur Definition konkreter [`VertexElement`](../aspose.threed.entities/vertexelement/)‑Implementierungen. |
| [VertexElementEdgeCrease](./vertexelementedgecrease/) | Definiert die Kantenkante (edge crease) für die angegebenen Komponenten. |
| [VertexElementHole](./vertexelementhole/) | Definiert, ob das angegebene Polygon ein Loch ist |
| [VertexElementIntsTemplate](./vertexelementintstemplate/) | Eine Hilfsklasse zur Definition konkreter [`VertexElement`](../aspose.threed.entities/vertexelement/)‑Implementierungen. |
| [VertexElementMaterial](./vertexelementmaterial/) | Definiert den Materialindex für die angegebenen Komponenten. Ein Knoten kann mehrere Materialien haben, das [`VertexElementMaterial`](../aspose.threed.entities/vertexelementmaterial/) wird verwendet, um verschiedene Teile der Geometrie mit unterschiedlichen Materialien zu rendern. |
| [VertexElementNormal](./vertexelementnormal/) | Definiert Normalenvektoren für die angegebenen Komponenten. |
| [VertexElementPolygonGroup](./vertexelementpolygongroup/) | Definiert Polygongruppen für die angegebenen Komponenten, um zusammengehörige Polygone zu gruppieren. |
| [VertexElementSmoothingGroup](./vertexelementsmoothinggroup/) | Eine Glättungsgruppe ist eine Gruppe von Polygonen in einem Polygonnetz, die eine glatte Oberfläche bilden sollen. Einige frühe 3D‑Modellierungsprogramme wie 3D Studio Max für DOS verwendeten Glättungsgruppen, um das Speichern von Normalenvektoren für jeden Netz‑Scheitelpunkt zu vermeiden. |
| [VertexElementSpecular](./vertexelementspecular/) | Definiert die Spiegelungsfarbe für die angegebenen Komponenten. |
| [VertexElementTangent](./vertexelementtangent/) | Definiert Tangentialvektoren für die angegebenen Komponenten. |
| [VertexElementTemplate&lt;T&gt;](./vertexelementtemplate-1/) | Eine Hilfsklasse zur Definition konkreter [`VertexElement`](../aspose.threed.entities/vertexelement/)‑Implementierungen. |
| [VertexElementUserData](./vertexelementuserdata/) | Definiert benutzerdefinierte Benutzerdaten für die angegebenen Komponenten. In der Regel handelt es sich um anwendungspezifische Daten für einen speziellen Zweck. |
| [VertexElementUV](./vertexelementuv/) | Definiert die UV‑Koordinaten für die angegebenen Komponenten. Eine Geometrie kann mehrere [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/)‑Elemente besitzen, und jedes hat unterschiedliche [`TextureMapping`](../aspose.threed.entities/texturemapping/)s. |
| [VertexElementVector4](./vertexelementvector4/) | Eine Hilfsklasse zur Definition konkreter [`VertexElement`](../aspose.threed.entities/vertexelement/)‑Implementierungen. |
| [VertexElementVertexColor](./vertexelementvertexcolor/) | Definiert die Scheitelpunktfarbe für die angegebenen Komponenten |
| [VertexElementVertexCrease](./vertexelementvertexcrease/) | Definiert die Scheitelkantenfalte für die angegebenen Komponenten |
| [VertexElementVisibility](./vertexelementvisibility/) | Definiert, ob die angegebenen Komponenten sichtbar sind |
| [VertexElementWeight](./vertexelementweight/) | Definiert das Blendgewicht für die angegebenen Komponenten. |
## Structures

| Struktur | Beschreibung |
| --- | --- |
| [EndPoint](./endpoint/) | Der Endpunkt zum Beschneiden der Kurve, kann ein Parameterwert oder ein kartesischer Punkt sein. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IIndexedVertexElement](./iindexedvertexelement/) | VertexElement mit Indexdaten. |
| [IMeshConvertible](./imeshconvertible/) | Entitäten, die dieses Interface implementiert haben, können in [`Mesh`](../aspose.threed.entities/mesh/) konvertiert werden |
| [IOrientable](./iorientable/) | Orientierbare Entitäten müssen dieses Interface implementieren. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [ApertureMode](./aperturemode/) | Kamera‑Blendenmodi. Der Blendenmodus bestimmt, welche Werte die Kamerablende steuern. Wenn der Blendenmodus HorizAndVert, Horizontal oder Vertikal ist, wird das Sichtfeld verwendet. Wenn der Blendenmodus FocalLength ist, wird die Brennweite verwendet. |
| [BooleanOperation](./booleanoperation/) | Boolesche Operation des Mesh |
| [CurveDimension](./curvedimension/) | Die Dimension der Kurven. |
| [LightType](./lighttype/) | Lichttypen. |
| [MappingMode](./mappingmode/) | Bestimmt, wie das Element auf eine Oberfläche abgebildet wird. Der [`MappingMode`](../aspose.threed.entities/mappingmode/) definiert, wie [`VertexElement`](../aspose.threed.entities/vertexelement/) auf die Oberfläche der Geometrie abgebildet wird. |
| [NurbsType](./nurbstype/) | NURBS‑Typen. |
| [PatchDirectionType](./patchdirectiontype/) | Typen der Patch‑Richtung. |
| [ProjectionType](./projectiontype/) | Projektionstypen der Kamera. |
| [ReferenceMode](./referencemode/) | [`ReferenceMode`](../aspose.threed.entities/referencemode/) definiert, wie Mapping‑Informationen gespeichert und referenziert werden. |
| [RotationMode](./rotationmode/) | Der Rotationsmodus des Frustums |
| [SkeletonType](./skeletontype/) | [`Skeleton`](../aspose.threed.entities/skeleton/)-Typen. |
| [SplitMeshPolicy](./splitmeshpolicy/) | Gemeinsame Nutzung von Scheitel‑/Kontrollpunktdaten zwischen Sub‑Meshes oder jedes Sub‑Mesh hat eigene komprimierte Daten. |
| [TextureMapping](./texturemapping/) | Der Texturzuordnungstyp für [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/) beschreibt, welche Art von Texturzuordnung verwendet wird. |
| [VertexElementType](./vertexelementtype/) | Der Typ des Vertex-Elements definiert, wie er beim Modellieren verwendet wird. |


