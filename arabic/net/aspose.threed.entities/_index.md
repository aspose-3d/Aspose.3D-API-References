---
title: "Aspose.ThreeD.Entities"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "جميع الهندسة والكيانات معرفة في هذه المساحة."
type: docs
weight: 40
url: /ar/net/aspose.threed.entities/
---
جميع الهندسة والكيانات معرفة في هذه المساحة.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [BooleanOperand](./booleanoperand/) | هذه الفئة تُغلف الشبكة المُحوّلة كمعامل عملية بوليانية. |
| [BooleanOperator](./booleanoperator/) | مُعامل بولياني يتيح لك تطبيق عملية بوليانية على مثالي [`IMeshConvertible`](../aspose.threed.entities/imeshconvertible/). |
| [Box](./box/) | صندوق. |
| [Camera](./camera/) | الكاميرا تصف نقطة عين المشاهد التي تنظر إلى المشهد. |
| [Circle](./circle/) | منحنى [`Circle`](../aspose.threed.entities/circle/) يتكوّن من مجموعة من النقاط على حافة شكل الدائرة. |
| [CompositeCurve](./compositecurve/) | إن [`CompositeCurve`](../aspose.threed.entities/compositecurve/) يتكوّن من عدة مقاطع من المنحنيات. |
| [Curve](./curve/) | الفئة الأساسية لجميع تطبيقات المنحنيات. |
| [Cylinder](./cylinder/) | اسطوانة مُعلمة. يمكن استخدامها أيضًا لتمثيل المخروط عندما يكون أحد القيم radiusTop/radiusBottom صفرًا. |
| [Dish](./dish/) | طبق مُعَدل. |
| [Ellipse](./ellipse/) | يُعرّف [`Ellipse`](../aspose.threed.entities/ellipse/) مجموعة من النقاط التي تُشكّل شكل القطع الناقص. |
| [Frustum](./frustum/) | الفئة الأساسية لـ [`Camera`](../aspose.threed.entities/camera/) و [`Light`](../aspose.threed.entities/light/). |
| [Geometry](./geometry/) | الفئة الأساسية لجميع الكائنات الهندسية القابلة للتصوير (مثل [`Mesh`](../aspose.threed.entities/mesh/)، [`NurbsSurface`](../aspose.threed.entities/nurbssurface/)، [`Patch`](../aspose.threed.entities/patch/) وغيرها). |
| [HalfSpace](./halfspace/) | يمثّل [`HalfSpace`](../aspose.threed.entities/halfspace/) مساحة لا نهائية تُقسم بواسطة مستوى، ويمكن استخدامه مع [`BooleanOperator`](../aspose.threed.entities/booleanoperator/). |
| [Light](./light/) | الضوء يضيء المشهد. |
| [Line](./line/) | الخط المتعدد هو مسار يُعرّف بمجموعة من النقاط باستخدام [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/)، ومتصلة بواسطة [`Segments`](../aspose.threed.entities/line/segments/)، مما يعني أنه يمكن أن يكون أيضًا مجموعة من القطع الخطية المتصلة. عادةً ما تكون الخط مستقيمًا، مما يعني أنه لا يمكن استخدامه لتمثيل منحنى؛ لتمثيل منحنى، يُستخدم [`NurbsCurve`](../aspose.threed.entities/nurbscurve/). |
| [LinearExtrusion](./linearextrusion/) | الإخراج الخطي يأخذ شكلًا ثنائي الأبعاد كمدخل ويمدد الشكل في البُعد الثالث. |
| [Mesh](./mesh/) | الشبكة تتكون من العديد من المضلعات ذات n أضلاع. |
| [NurbsCurve](./nurbscurve/) | [NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) هو منحنى يُمثَّل بواسطة NURBS (منحنى أساس غير منتظم نسبي). يُعرَّف منحنى NURBS بـ[`Order`](../aspose.threed.entities/nurbscurve/order/)، ومجموعة من [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/) ذات وزن، و[`KnotVectors`](../aspose.threed.entities/nurbscurve/knotvectors/). يُستخدم العنصر w في نقطة التحكم كوزن لنقطة التحكم، سواء كان ذلك في بعد ثنائي أو ثلاثي الأبعاد. |
| [NurbsDirection](./nurbsdirection/) | سطح ثلاثي الأبعاد [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) له اتجاهان، الـ[`U`](../aspose.threed.entities/nurbssurface/u/) والـ[`V`](../aspose.threed.entities/nurbssurface/v/). الـ[`NurbsDirection`](../aspose.threed.entities/nurbsdirection/) يحدد البيانات لكل اتجاه. الاتجاه في الواقع هو منحنى NURBS، مما يعني أنه يُعرَّف أيضًا بـ[`Order`](../aspose.threed.entities/nurbsdirection/order/)، و[`KnotVectors`](../aspose.threed.entities/nurbsdirection/knotvectors/)، ومجموعة من نقاط التحكم ذات وزن (مُعرَّفة في [`NurbsSurface`](../aspose.threed.entities/nurbssurface/)). |
| [NurbsSurface](./nurbssurface/) | [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) هو سطح يُمثَّل بواسطة [NURBS(منحنى أساس غير منتظم نسبي)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline). يُعرَّف [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) بواسطة اتجاهين [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/): الـ[`U`](../aspose.threed.entities/nurbssurface/u/) والـ[`V`](../aspose.threed.entities/nurbssurface/v/). يُستخدم العنصر w في نقطة التحكم كوزن لنقطة التحكم، بغض النظر عن ما إذا كان نوع الاتجاه ثنائي الأبعاد أو ثلاثي الأبعاد. |
| [Patch](./patch/) | `[`Patch`](../aspose.threed.entities/patch/) هو سطح نمذجة باراميتري، مشابه لـ[`NurbsSurface`](../aspose.threed.entities/nurbssurface/)، ويُعرَّف أيضًا بواسطة اتجاهين [`PatchDirection`](../aspose.threed.entities/patchdirection/): الـ[`U`](../aspose.threed.entities/patch/u/) والـ[`V`](../aspose.threed.entities/patch/v/). لكن الفرق بين [`Patch`](../aspose.threed.entities/patch/) و[`NurbsSurface`](../aspose.threed.entities/nurbssurface/) هو أن منحنى [`PatchDirection`](../aspose.threed.entities/patchdirection/) يمكن أن يكون أحد: Bezier، QuadraticBezier، BasisSpline، CardinalSpline وLinear. |
| [PatchDirection](./patchdirection/) | اتجاه الـU والـV للـPatch. |
| [Plane](./plane/) | سطح مُعَدل باراميتريًا. |
| [PointCloud](./pointcloud/) | سحابة النقاط لا تحتوي على معلومات طوبولوجية بل فقط نقاط التحكم وعناصر الرؤوس. |
| [PolygonBuilder](./polygonbuilder/) | فئة مساعدة لبناء مضلع لـ[`Mesh`](../aspose.threed.entities/mesh/). |
| [PolygonModifier](./polygonmodifier/) | أدوات لتعديل المضلعات. |
| [Primitive](./primitive/) | الفئة الأساسية لجميع الكائنات الأولية. |
| [Pyramid](./pyramid/) | هرم مُعَدل باراميتريًا. |
| [RectangularTorus](./rectangulartorus/) | طوق مستطيل مُعَدل باراميتريًا. |
| [RevolvedAreaSolid](./revolvedareasolid/) | هذه الفئة تمثل نموذجًا صلبًا عن طريق تدوير مقطع عرضي مُقدم بواسطة ملف حول محور. |
| [Shape](./shape/) | الشكل يصف التشوه على مجموعة من نقاط التحكم، وهو مشابه لمُشَكِّل التجمع (cluster deformer) في Maya. على سبيل المثال، يمكننا إضافة شكل إلى هندسة مُنشأة. ويكون الشكل والهندسة لهما نفس المعلومات الطوبولوجية لكن مواضع نقاط التحكم مختلفة. مع اختلاف مقدار التأثير، تُجري الهندسة تأثير التشوه. |
| [Skeleton](./skeleton/) | يُستخدم [`Skeleton`](../aspose.threed.entities/skeleton/) أساسًا من قبل برامج CAD لمساعدة المصمم على تعديل تحويل الهيكل العظمي، وهو عادةً غير مفيد خارج برامج CAD. لجعل تسلسل هيكل الـ Skeleton يعمل ككائن واحد في برنامج CAD، من الضروري وضع علامة على عقدة [`Skeleton`](../aspose.threed.entities/skeleton/) العليا كجذر عن طريق ضبط [`Type`](../aspose.threed.entities/skeleton/type/) إلى Skeleton، وتعيين جميع الأطفال إلى Bone. |
| [Sphere](./sphere/) | كرة ذات معلمات. |
| [SweptAreaSolid](./sweptareasolid/) | يقوم [`SweptAreaSolid`](../aspose.threed.entities/sweptareasolid/) بإنشاء هندسة عن طريق مسح ملف تعريف على طول الخط المستقيم. |
| [Torus](./torus/) | طُرُس ذو معلمات. |
| [TransformedCurve](./transformedcurve/) | يمنح [`TransformedCurve`](../aspose.threed.entities/transformedcurve/) المنحنى موضعًا باستخدام مصفوفة تحويل. هذا يسمح بإجراء تحويل داخل [`TrimmedCurve`](../aspose.threed.entities/trimmedcurve/) أو [`CompositeCurve`](../aspose.threed.entities/compositecurve/). |
| [TriMesh](./trimesh/) | يحتوي TriMesh على بيانات خام يمكن لوحدة معالجة الرسومات (GPU) استخدامها مباشرة. هذه الفئة أداة مساعدة للمساعدة في إنشاء شبكة تحتوي فقط على بيانات لكل رأس. |
| [TriMesh&lt;T&gt;](./trimesh-1/) | نسخة عامة من [`TriMesh`](../aspose.threed.entities/trimesh/) لنوع رأس معرف ثابتًا من قبل المستخدم. |
| [TrimmedCurve](./trimmedcurve/) | منحنى محدود يتم تقليم المنحنى الأساسي عند الطرفين. |
| [VertexElement](./vertexelement/) | الفئة الأساسية لعناصر الرؤوس. يتم التعرف على نوع عنصر الرأس بواسطة VertexElementType. يصف VertexElement كيفية ربط عنصر الرأس بسطح هندسي وكيفية ترتيب معلومات الربط في الذاكرة. يحتوي VertexElement على Normals و UVs أو أي نوع آخر من المعلومات. |
| [VertexElementBinormal](./vertexelementbinormal/) | يحدد المتجهات الثنائية (binormal) للمكونات المحددة. |
| [VertexElementDoublesTemplate](./vertexelementdoublestemplate/) | فئة مساعدة لتعريف تطبيقات [`VertexElement`](../aspose.threed.entities/vertexelement/) الملموسة. |
| [VertexElementEdgeCrease](./vertexelementedgecrease/) | يحدد تجعد الحافة للمكونات المحددة. |
| [VertexElementHole](./vertexelementhole/) | يحدد ما إذا كان المضلع المحدد ثقبًا. |
| [VertexElementIntsTemplate](./vertexelementintstemplate/) | فئة مساعدة لتعريف تطبيقات [`VertexElement`](../aspose.threed.entities/vertexelement/) الملموسة. |
| [VertexElementMaterial](./vertexelementmaterial/) | يحدد فهرس المادة للمكونات المحددة. يمكن للعقدة أن تحتوي على مواد متعددة، يتم استخدام [`VertexElementMaterial`](../aspose.threed.entities/vertexelementmaterial/) لتصيير أجزاء مختلفة من الهندسة بمواد مختلفة. |
| [VertexElementNormal](./vertexelementnormal/) | يحدد المتجهات العادية للمكونات المحددة. |
| [VertexElementPolygonGroup](./vertexelementpolygongroup/) | يحدد مجموعة المضلع للمكونات المحددة لتجميع المضلع المرتبط معًا. |
| [VertexElementSmoothingGroup](./vertexelementsmoothinggroup/) | مجموعة التنعيم هي مجموعة من المضلعات في شبكة مضلعات يجب أن تظهر كسطح أملس. استخدمت بعض برامج النمذجة ثلاثية الأبعاد القديمة مثل 3D Studio Max لنظام DOS مجموعة التنعيم لتجنب تخزين المتجه العادي لكل رأس في الشبكة. |
| [VertexElementSpecular](./vertexelementspecular/) | يحدد اللون اللامع (specular) للمكونات المحددة. |
| [VertexElementTangent](./vertexelementtangent/) | يحدد المتجهات المماسية للمكونات المحددة. |
| [VertexElementTemplate&lt;T&gt;](./vertexelementtemplate-1/) | فئة مساعدة لتعريف تطبيقات [`VertexElement`](../aspose.threed.entities/vertexelement/) الملموسة. |
| [VertexElementUserData](./vertexelementuserdata/) | يحدد بيانات المستخدم المخصصة للمكونات المحددة. عادةً ما تكون بيانات خاصة بالتطبيق لأغراض خاصة. |
| [VertexElementUV](./vertexelementuv/) | يحدد إحداثيات UV للمكونات المحددة. يمكن أن تحتوي الهندسة على عناصر متعددة من [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/)، ولكل منها [`TextureMapping`](../aspose.threed.entities/texturemapping/) مختلف. |
| [VertexElementVector4](./vertexelementvector4/) | فئة مساعدة لتعريف تطبيقات [`VertexElement`](../aspose.threed.entities/vertexelement/) الملموسة. |
| [VertexElementVertexColor](./vertexelementvertexcolor/) | يحدد لون الرأس للمكونات المحددة |
| [VertexElementVertexCrease](./vertexelementvertexcrease/) | يحدد تجعد الرأس للمكونات المحددة |
| [VertexElementVisibility](./vertexelementvisibility/) | يحدد ما إذا كانت المكونات المحددة مرئية |
| [VertexElementWeight](./vertexelementweight/) | يحدد وزن الدمج للمكونات المحددة. |
## Structures

| بنية | الوصف |
| --- | --- |
| [EndPoint](./endpoint/) | نقطة النهاية لتقليم المنحنى، يمكن أن تكون قيمة معامل أو نقطة ديكارتية. |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [IIndexedVertexElement](./iindexedvertexelement/) | VertexElement مع بيانات الفهارس. |
| [IMeshConvertible](./imeshconvertible/) | الكيانات التي نفذت هذه الواجهة يمكن تحويلها إلى [`Mesh`](../aspose.threed.entities/mesh/) |
| [IOrientable](./iorientable/) | الكيانات القابلة للتوجيه يجب أن تنفذ هذه الواجهة. |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [ApertureMode](./aperturemode/) | أنماط فتحة الكاميرا. تحدد وضعية الفتحة القيم التي تتحكم بفتحة الكاميرا. إذا كانت وضعية الفتحة هي HorizAndVert أو Horizontal أو Vertical، فسيتم استخدام مجال الرؤية. إذا كانت وضعية الفتحة هي FocalLength، فسيتم استخدام البعد البؤري. |
| [BooleanOperation](./booleanoperation/) | العملية البوليانية لـ Mesh |
| [CurveDimension](./curvedimension/) | بعد المنحنيات. |
| [LightType](./lighttype/) | أنواع الإضاءة. |
| [MappingMode](./mappingmode/) | يحدد كيفية ربط العنصر بسطح. الـ [`MappingMode`](../aspose.threed.entities/mappingmode/) يحدد كيف يتم ربط الـ [`VertexElement`](../aspose.threed.entities/vertexelement/) بسطح الهندسة. |
| [NurbsType](./nurbstype/) | أنواع NURBS. |
| [PatchDirectionType](./patchdirectiontype/) | أنواع اتجاه القطع. |
| [ProjectionType](./projectiontype/) | أنواع إسقاط الكاميرا. |
| [ReferenceMode](./referencemode/) | [`ReferenceMode`](../aspose.threed.entities/referencemode/) يحدد كيفية تخزين معلومات التعيين والمرجعية بواسطة. |
| [RotationMode](./rotationmode/) | وضعية دوران الـ frustum |
| [SkeletonType](./skeletontype/) | أنواع الـ [`Skeleton`](../aspose.threed.entities/skeleton/). |
| [SplitMeshPolicy](./splitmeshpolicy/) | مشاركة بيانات vertex/control point بين sub-meshes أو أن كل sub-mesh له بيانات مضغوطة خاصة به. |
| [TextureMapping](./texturemapping/) | نوع تعيين القوام لـ [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/) يصف أي نوع من تعيين القوام يُستخدم. |
| [VertexElementType](./vertexelementtype/) | نوع الـ vertex element، يحدد كيف سيُستخدم في النمذجة. |


