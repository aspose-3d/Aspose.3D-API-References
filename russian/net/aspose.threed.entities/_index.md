---
title: "Aspose.ThreeD.Entities"
second_title: "Справочник API Aspose.3D для .NET"
description: "Все геометрические объекты и сущности определены в этом пространстве имён"
type: docs
weight: 40
url: /ru/net/aspose.threed.entities/
---
Все геометрические объекты и сущности определены в этом пространстве имён

## Классы

| Класс | Описание |
| --- | --- |
| [BooleanOperand](./booleanoperand/) | Этот класс инкапсулирует преобразованную сетку как операнд булевой операции. |
| [BooleanOperator](./booleanoperator/) | Булевый оператор позволяет применять булеву операцию к двум экземплярам [`IMeshConvertible`](../aspose.threed.entities/imeshconvertible/). |
| [Box](./box/) | Коробка. |
| [Camera](./camera/) | Камера описывает точку взгляда наблюдателя, смотрящего на сцену. |
| [Circle](./circle/) | Кривая [`Circle`](../aspose.threed.entities/circle/) состоит из набора точек на границе формы круга. |
| [CompositeCurve](./compositecurve/) | [`CompositeCurve`](../aspose.threed.entities/compositecurve/) состоит из нескольких сегментов кривой. |
| [Curve](./curve/) | Базовый класс всех реализаций кривых. |
| [Cylinder](./cylinder/) | Параметрический цилиндр. Его также можно использовать для представления конуса, когда один из параметров radiusTop/radiusBottom равен нулю. |
| [Dish](./dish/) | Параметрическая тарелка. |
| [Ellipse](./ellipse/) | [`Ellipse`](../aspose.threed.entities/ellipse/) определяет набор точек, образующих форму эллипса. |
| [Frustum](./frustum/) | Базовый класс [`Camera`](../aspose.threed.entities/camera/) и [`Light`](../aspose.threed.entities/light/) |
| [Geometry](./geometry/) | Базовый класс всех визуализируемых геометрических объектов (например, [`Mesh`](../aspose.threed.entities/mesh/), [`NurbsSurface`](../aspose.threed.entities/nurbssurface/), [`Patch`](../aspose.threed.entities/patch/) и т.д.). |
| [HalfSpace](./halfspace/) | [`HalfSpace`](../aspose.threed.entities/halfspace/) представляет бесконечное пространство, разделённое плоскостью; его можно использовать с [`BooleanOperator`](../aspose.threed.entities/booleanoperator/). |
| [Light](./light/) | Свет освещает сцену. |
| [Line](./line/) | Полилиния — это путь, определяемый набором точек с [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/), и соединённый с помощью [`Segments`](../aspose.threed.entities/line/segments/), что означает, что она также может быть набором соединённых отрезков. Линия обычно является линейным объектом, что значит, что её нельзя использовать для представления кривой; для представления кривой используется [`NurbsCurve`](../aspose.threed.entities/nurbscurve/). |
| [LinearExtrusion](./linearextrusion/) | Линейная экструзия принимает 2D-форму в качестве входных данных и расширяет её в третьем измерении. |
| [Mesh](./mesh/) | Сетка состоит из множества n-угольных полигонов. |
| [NurbsCurve](./nurbscurve/) | [NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) — это кривая, представленная NURBS (Non-uniform rational basis spline). Кривая NURBS определяется её [`Order`](../aspose.threed.entities/nurbscurve/order/), набором взвешенных [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/) и [`KnotVectors`](../aspose.threed.entities/nurbscurve/knotvectors/). Компонент w в контрольной точке используется как вес контрольной точки, независимо от того, является ли она двумерной или трёхмерной. |
| [NurbsDirection](./nurbsdirection/) | 3D‑поверхность [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) имеет два направления: [`U`](../aspose.threed.entities/nurbssurface/u/) и [`V`](../aspose.threed.entities/nurbssurface/v/), а [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/) определяет данные для каждого направления. Направление фактически является кривой NURBS, что означает, что оно также определяется своим [`Order`](../aspose.threed.entities/nurbsdirection/order/), [`KnotVectors`](../aspose.threed.entities/nurbsdirection/knotvectors/) и набором взвешенных контрольных точек (определённых в [`NurbsSurface`](../aspose.threed.entities/nurbssurface/)). |
| [NurbsSurface](./nurbssurface/) | [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) — это поверхность, представленная [NURBS(Non-uniform rational basis spline)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline). [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) определяется двумя [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/)[`U`](../aspose.threed.entities/nurbssurface/u/) и [`V`](../aspose.threed.entities/nurbssurface/v/). Компонент w в контрольной точке используется как вес контрольной точки, независимо от того, является ли тип направления двумерным или трёхмерным. |
| [Patch](./patch/) | [`Patch`](../aspose.threed.entities/patch/) — это параметрическая моделирующая поверхность, похожая на [`NurbsSurface`](../aspose.threed.entities/nurbssurface/), она также определяется двумя [`PatchDirection`](../aspose.threed.entities/patchdirection/), [`U`](../aspose.threed.entities/patch/u/) и [`V`](../aspose.threed.entities/patch/v/). Но отличие [`Patch`](../aspose.threed.entities/patch/) от [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) заключается в том, что кривая [`PatchDirection`](../aspose.threed.entities/patchdirection/) может быть одной из: Bezier, QuadraticBezier, BasisSpline, CardinalSpline и Linear. |
| [PatchDirection](./patchdirection/) | Направления U и V патча. |
| [Plane](./plane/) | Параметрическая плоскость. |
| [PointCloud](./pointcloud/) | Облако точек не содержит информации о топологии, а только контрольные точки и элементы вершин. |
| [PolygonBuilder](./polygonbuilder/) | Вспомогательный класс для построения полигонов для [`Mesh`](../aspose.threed.entities/mesh/). |
| [PolygonModifier](./polygonmodifier/) | Утилиты для изменения полигонов. |
| [Primitive](./primitive/) | Базовый класс для всех примитивов. |
| [Pyramid](./pyramid/) | Параметрическая пирамида. |
| [RectangularTorus](./rectangulartorus/) | Параметрический прямоугольный тор. |
| [RevolvedAreaSolid](./revolvedareasolid/) | Этот класс представляет твёрдую модель путем вращения поперечного сечения, заданного профилем, вокруг оси. |
| [Shape](./shape/) | Форма описывает деформацию набора контрольных точек, что аналогично кластерному деформеру в Maya. Например, мы можем добавить форму к созданной геометрии. При этом форма и геометрия имеют одинаковую топологическую информацию, но различаются положением контрольных точек. При различном уровне влияния геометрия осуществляет эффект деформации. |
| [Skeleton](./skeleton/) | Этот [`Skeleton`](../aspose.threed.entities/skeleton/) в основном используется CAD‑программами, чтобы помочь дизайнеру управлять преобразованием скелетной структуры; обычно он бесполезен вне CAD‑программ. Чтобы иерархия скелета вела себя как один объект в CAD‑программе, необходимо пометить верхний узел [`Skeleton`](../aspose.threed.entities/skeleton/) как корневой, установив [`Type`](../aspose.threed.entities/skeleton/type/) в значение Skeleton, а все дочерние — в Bone. |
| [Sphere](./sphere/) | Параметризованная сфера. |
| [SweptAreaSolid](./sweptareasolid/) | Объект [`SweptAreaSolid`](../aspose.threed.entities/sweptareasolid/) создает геометрию, вытягивая профиль вдоль дирекрисы. |
| [Torus](./torus/) | Параметризованный тор. |
| [TransformedCurve](./transformedcurve/) | Объект [`TransformedCurve`](../aspose.threed.entities/transformedcurve/) задает расположение кривой с помощью матрицы преобразования. Это позволяет выполнить преобразование внутри [`TrimmedCurve`](../aspose.threed.entities/trimmedcurve/) или [`CompositeCurve`](../aspose.threed.entities/compositecurve/). |
| [TriMesh](./trimesh/) | TriMesh содержит необработанные данные, которые могут использоваться GPU напрямую. Этот класс — утилита, помогающая создавать сетку, содержащую только данные для каждой вершины. |
| [TriMesh&lt;T&gt;](./trimesh-1/) | Обобщённая версия [`TriMesh`](../aspose.threed.entities/trimesh/) для пользовательского статически определённого типа вершины. |
| [TrimmedCurve](./trimmedcurve/) | Ограниченная кривая, обрезающая базовую кривую с обеих сторон. |
| [VertexElement](./vertexelement/) | Базовый класс элементов вершины. Тип элемента вершины определяется VertexElementType. VertexElement описывает, как элемент вершины отображается на поверхность геометрии и как информация о отображении размещается в памяти. VertexElement содержит нормали, UV‑координаты или другие виды информации. |
| [VertexElementBinormal](./vertexelementbinormal/) | Определяет бинормальные векторы для указанных компонентов. |
| [VertexElementDoublesTemplate](./vertexelementdoublestemplate/) | Вспомогательный класс для определения конкретных реализаций [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementEdgeCrease](./vertexelementedgecrease/) | Определяет сгиб ребра для указанных компонентов. |
| [VertexElementHole](./vertexelementhole/) | Определяет, является ли указанный полигон отверстием. |
| [VertexElementIntsTemplate](./vertexelementintstemplate/) | Вспомогательный класс для определения конкретных реализаций [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementMaterial](./vertexelementmaterial/) | Определяет индекс материала для указанных компонентов. Узел может иметь несколько материалов, [`VertexElementMaterial`](../aspose.threed.entities/vertexelementmaterial/) используется для отображения разных частей геометрии разными материалами. |
| [VertexElementNormal](./vertexelementnormal/) | Определяет нормальные векторы для указанных компонентов. |
| [VertexElementPolygonGroup](./vertexelementpolygongroup/) | Определяет группу полигонов для указанных компонентов, чтобы объединять связанные полигоны. |
| [VertexElementSmoothingGroup](./vertexelementsmoothinggroup/) | Группа сглаживания — это набор полигонов в полигональной сетке, которые должны выглядеть как гладкая поверхность. Некоторые ранние 3D‑моделирующие программы, такие как 3D Studio Max для DOS, использовали группы сглаживания, чтобы избежать хранения нормального вектора для каждой вершины сетки. |
| [VertexElementSpecular](./vertexelementspecular/) | Определяет зеркальный цвет для указанных компонентов. |
| [VertexElementTangent](./vertexelementtangent/) | Определяет касательные векторы для указанных компонентов. |
| [VertexElementTemplate&lt;T&gt;](./vertexelementtemplate-1/) | Вспомогательный класс для определения конкретных реализаций [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementUserData](./vertexelementuserdata/) | Определяет пользовательские данные для указанных компонентов. Обычно это данные, специфичные для приложения, предназначенные для особых целей. |
| [VertexElementUV](./vertexelementuv/) | Определяет UV‑координаты для указанных компонентов. Геометрия может иметь несколько элементов [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/), каждый из которых имеет разные [`TextureMapping`](../aspose.threed.entities/texturemapping/). |
| [VertexElementVector4](./vertexelementvector4/) | Вспомогательный класс для определения конкретных реализаций [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementVertexColor](./vertexelementvertexcolor/) | Определяет цвет вершины для указанных компонентов. |
| [VertexElementVertexCrease](./vertexelementvertexcrease/) | Определяет сгиб вершины для указанных компонентов. |
| [VertexElementVisibility](./vertexelementvisibility/) | Определяет, видимы ли указанные компоненты. |
| [VertexElementWeight](./vertexelementweight/) | Определяет вес смешивания для указанных компонентов. |
## Structures

| Структура | Описание |
| --- | --- |
| [EndPoint](./endpoint/) | Конечная точка для обрезки кривой может быть значением параметра или декартовой точкой. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IIndexedVertexElement](./iindexedvertexelement/) | VertexElement с данными индексов. |
| [IMeshConvertible](./imeshconvertible/) | Сущности, реализующие этот интерфейс, могут быть преобразованы в [`Mesh`](../aspose.threed.entities/mesh/) |
| [IOrientable](./iorientable/) | Ориентируемые сущности должны реализовать этот интерфейс. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [ApertureMode](./aperturemode/) | Режимы диафрагмы камеры. Режим диафрагмы определяет, какие значения управляют диафрагмой камеры. Если режим диафрагмы — HorizAndVert, Horizontal или Vertical, используется поле зрения. Если режим диафрагмы — FocalLength, используется фокусное расстояние. |
| [BooleanOperation](./booleanoperation/) | Булева операция Mesh |
| [CurveDimension](./curvedimension/) | Размерность кривых. |
| [LightType](./lighttype/) | Типы света. |
| [MappingMode](./mappingmode/) | Определяет, как элемент отображается на поверхность. [`MappingMode`](../aspose.threed.entities/mappingmode/) определяет, как [`VertexElement`](../aspose.threed.entities/vertexelement/) отображается на поверхность геометрии. |
| [NurbsType](./nurbstype/) | Типы NURBS. |
| [PatchDirectionType](./patchdirectiontype/) | Типы направлений патча. |
| [ProjectionType](./projectiontype/) | Типы проекций камеры. |
| [ReferenceMode](./referencemode/) | [`ReferenceMode`](../aspose.threed.entities/referencemode/) определяет, как информация о отображении хранится и на неё ссылаются. |
| [RotationMode](./rotationmode/) | Режим вращения фрустума |
| [SkeletonType](./skeletontype/) | Типы [`Skeleton`](../aspose.threed.entities/skeleton/) |
| [SplitMeshPolicy](./splitmeshpolicy/) | Общий доступ к данным вершин/контрольных точек между субмешами или каждый субмеш имеет собственные сжатые данные. |
| [TextureMapping](./texturemapping/) | Тип текстурного отображения для [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/) описывает, какой тип текстурного отображения используется. |
| [VertexElementType](./vertexelementtype/) | Тип элемента вершины, определяющий, как он будет использоваться в моделировании. |


