---
title: "Aspose.ThreeD.Entities"
second_title: "مرجع Aspose.3D for .NET API"
description: "جميع الهندسة والكيانات معرفة في هذه المساحة."
type: docs
weight: 40
url: /ar/net/aspose.threed.entities/
---
جميع الهندسة والكيانات معرفة في هذه المساحة.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [BooleanOperand](./booleanoperand/) | هذه الفئة تُغلف الشبكة المُحوّلة كمعامل لعملية Boolean. |
| [BooleanOperator](./booleanoperator/) | المعامل البولياني يتيح لك تطبيق عملية Boolean على مثيلين من [`IMeshConvertible`](../aspose.threed.entities/imeshconvertible/). |
| [Box](./box/) | صندوق. |
| [Camera](./camera/) | الكاميرا تصف نقطة عين المشاهد التي تنظر إلى المشهد. |
| [Circle](./circle/) | منحنى [`Circle`](../aspose.threed.entities/circle/) يتكوّن من مجموعة من النقاط على حافة شكل الدائرة. |
| [CompositeCurve](./compositecurve/) | `[`CompositeCurve`](../aspose.threed.entities/compositecurve/)` يتكوّن من عدة مقاطع منحنى. |
| [Curve](./curve/) | الفئة الأساسية لجميع تطبيقات المنحنيات. |
| [Cylinder](./cylinder/) | أسطوانة معلمة. يمكن استخدامها أيضًا لتمثيل المخروط عندما يكون أحد القيم radiusTop/radiusBottom صفرًا. |
| [Dish](./dish/) | طبق معلم. |
| [Ellipse](./ellipse/) | `[`Ellipse`](../aspose.threed.entities/ellipse/)` يحدد مجموعة من النقاط التي تشكل شكل القطع الناقص. |
| [Frustum](./frustum/) | الفئة الأساسية لـ [`Camera`](../aspose.threed.entities/camera/) و [`Light`](../aspose.threed.entities/light/) |
| [Geometry](./geometry/) | الفئة الأساسية لجميع الكائنات الهندسية القابلة للتصوير (مثل [`Mesh`](../aspose.threed.entities/mesh/)، [`NurbsSurface`](../aspose.threed.entities/nurbssurface/)، [`Patch`](../aspose.threed.entities/patch/) وغيرها). |
| [HalfSpace](./halfspace/) | `[`HalfSpace`](../aspose.threed.entities/halfspace/)` يمثل فضاءً لا نهائيًا يتم تقسيمه بواسطة سطح، ويمكن استخدامه مع [`BooleanOperator`](../aspose.threed.entities/booleanoperator/) |
| [Light](./light/) | الضوء يضيء المشهد. |
| [Line](./line/) | الخط المتعدد هو مسار يُعرَّف بمجموعة من النقاط باستخدام [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/)، ومتصلة بواسطة [`Segments`](../aspose.threed.entities/line/segments/)، مما يعني أنه يمكن أن يكون أيضًا مجموعة من القطاعات الخطية المتصلة. عادةً ما يكون الخط كائنًا خطيًا، مما يعني أنه لا يمكن استخدامه لتمثيل منحنى؛ لتمثيل منحنى، يُستخدم [`NurbsCurve`](../aspose.threed.entities/nurbscurve/). |
| [LinearExtrusion](./linearextrusion/) | الإسقاط الخطي يأخذ شكلًا ثنائي الأبعاد كمدخل ويُمد الشكل في البُعد الثالث. |
| [Mesh](./mesh/) | الشبكة تتكون من العديد من المضلع ذات n أضلاع. |
| [NurbsCurve](./nurbscurve/) | [NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) هو منحنى يُمثَّل بواسطة NURBS (منحنى أساس غير منتظم نسبي)، يُعرَّف منحنى NURBS بــ[`Order`](../aspose.threed.entities/nurbscurve/order/)، ومجموعة من [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/) ذات وزن، و[`KnotVectors`](../aspose.threed.entities/nurbscurve/knotvectors/). يُستخدم المكوّن w في نقطة التحكم كوزن لنقطة التحكم، سواء كان ذلك في بعد ثنائي أو ثلاثي الأبعاد. |
| [NurbsDirection](./nurbsdirection/) | سطح 3D [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) له اتجاهان، الـ[`U`](../aspose.threed.entities/nurbssurface/u/) والـ[`V`](../aspose.threed.entities/nurbssurface/v/)، الـ[`NurbsDirection`](../aspose.threed.entities/nurbsdirection/) يحدد البيانات لكل اتجاه. الاتجاه في الواقع هو منحنى NURBS، مما يعني أنه يُعرَّف أيضًا بـ[`Order`](../aspose.threed.entities/nurbsdirection/order/)، و[`KnotVectors`](../aspose.threed.entities/nurbsdirection/knotvectors/)، ومجموعة من نقاط التحكم ذات الوزن (المعرَّفة في [`NurbsSurface`](../aspose.threed.entities/nurbssurface/)). |
| [NurbsSurface](./nurbssurface/) | [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) هو سطح يُمثَّل بـ[NURBS(Non-uniform rational basis spline)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline)، يُعرَّف [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) باثنين من الـ[`NurbsDirection`](../aspose.threed.entities/nurbsdirection/)[`U`](../aspose.threed.entities/nurbssurface/u/) و[`V`](../aspose.threed.entities/nurbssurface/v/). يُستخدم المكوّن w في نقطة التحكم كوزن لنقطة التحكم بغض النظر عن ما إذا كان نوع الاتجاه ثنائي أو ثلاثي الأبعاد. |
| [Patch](./patch/) | `[`Patch`](../aspose.threed.entities/patch/) هو سطح نمذجة باراميتري، مشابه لـ[`NurbsSurface`](../aspose.threed.entities/nurbssurface/)، يُعرَّف أيضًا باثنين من الـ[`PatchDirection`](../aspose.threed.entities/patchdirection/)، الـ[`U`](../aspose.threed.entities/patch/u/) والـ[`V`](../aspose.threed.entities/patch/v/). لكن الفرق بين [`Patch`](../aspose.threed.entities/patch/) و[`NurbsSurface`](../aspose.threed.entities/nurbssurface/) هو أن منحنى الـ[`PatchDirection`](../aspose.threed.entities/patchdirection/) يمكن أن يكون أحد: Bezier، QuadraticBezier، BasisSpline، CardinalSpline أو Linear. |
| [PatchDirection](./patchdirection/) | اتجاه الـU والـV للـPatch. |
| [Plane](./plane/) | سطح باراميتري. |
| [PointCloud](./pointcloud/) | سحابة النقاط لا تحتوي على معلومات طوبولوجية بل فقط نقاط التحكم وعناصر الرؤوس. |
| [PolygonBuilder](./polygonbuilder/) | فئة مساعدة لبناء مضلع لـ[`Mesh`](../aspose.threed.entities/mesh/) |
| [PolygonModifier](./polygonmodifier/) | أدوات لتعديل المضلعات. |
| [Primitive](./primitive/) | الفئة الأساسية لجميع الكائنات الأولية. |
| [Pyramid](./pyramid/) | هرم باراميتري. |
| [RectangularTorus](./rectangulartorus/) | طوق مستطيل باراميتري. |
| [RevolvedAreaSolid](./revolvedareasolid/) | هذه الفئة تمثل نموذجًا صلبًا عن طريق تدوير مقطع عرضي مُقدَّم بواسطة ملف حول محور. |
| [Shape](./shape/) | الشكل يصف التشوه على مجموعة من نقاط التحكم، وهو مشابه لمُشَكِّل التجمع (cluster deformer) في Maya. على سبيل المثال، يمكننا إضافة شكل إلى هندسة مُنشأة. ويتشارك الشكل والهندسة نفس المعلومات الطوبولوجية لكن بمواقع مختلفة لنقاط التحكم. مع اختلاف مستويات التأثير، تُنفّذ الهندسة تأثير التشوه. |
| [Skeleton](./skeleton/) | الـ[`Skeleton`](../aspose.threed.entities/skeleton/) يُستخدم أساسًا في برامج CAD لمساعدة المصمم على تعديل تحويلات الهيكل العظمي، وعادةً ما يكون غير مفيد خارج برامج CAD. لجعل تسلسل هيكل العظام يتصرف ككائن واحد في برنامج CAD، من الضروري تعيين عقدة الـ[`Skeleton`](../aspose.threed.entities/skeleton/) العليا كجذر عن طريق ضبط [`Type`](../aspose.threed.entities/skeleton/type/) إلى Skeleton، وتعيين جميع الفروع إلى Bone. |
| [Sphere](./sphere/) | كرة باراميتري. |
| [SweptAreaSolid](./sweptareasolid/) | `[`SweptAreaSolid`](../aspose.threed.entities/sweptareasolid/) يُنشئ هندسة عن طريق مسح ملف على طول خط مباشر. |
| [Torus](./torus/) | طوق باراميتري. |
| [TransformedCurve](./transformedcurve/) | `[`TransformedCurve`](../aspose.threed.entities/transformedcurve/) يضع منحنى في موضع باستخدام مصفوفة تحويل. هذا يسمح بأداء تحويل داخل [`TrimmedCurve`](../aspose.threed.entities/trimmedcurve/) أو [`CompositeCurve`](../aspose.threed.entities/compositecurve/). |
| [TriMesh](./trimesh/) | TriMesh يحتوي على بيانات خام يمكن لوحدة معالجة الرسوميات (GPU) استخدامها مباشرة. هذه الفئة أداة للمساعدة في إنشاء شبكة تحتوي فقط على بيانات لكل رأس. |
| [TriMesh&lt;T&gt;](./trimesh-1/) | نسخة عامة من [`TriMesh`](../aspose.threed.entities/trimesh/) لنوع رأس معرف ثابتًا من قبل المستخدم. |
| [TrimmedCurve](./trimmedcurve/) | منحنى محدود يقطع المنحنى الأساسي عند الطرفين. |
| [VertexElement](./vertexelement/) | الفئة الأساسية لعناصر الرؤوس. يتم التعرف على نوع عنصر الرؤوس بواسطة VertexElementType. يصف VertexElement كيف يتم تعيين عنصر الرؤوس إلى سطح هندسي وكيف يتم ترتيب معلومات التعيين في الذاكرة. يحتوي VertexElement على Normals و UVs أو أي نوع آخر من المعلومات. |
| [VertexElementBinormal](./vertexelementbinormal/) | يحدد المتجهات الثنائية للمكونات المحددة. |
| [VertexElementDoublesTemplate](./vertexelementdoublestemplate/) | فئة مساعدة لتعريف تطبيقات [`VertexElement`](../aspose.threed.entities/vertexelement/) الملموسة. |
| [VertexElementEdgeCrease](./vertexelementedgecrease/) | يحدد تجعد الحافة للمكونات المحددة. |
| [VertexElementHole](./vertexelementhole/) | يحدد ما إذا كان المضلع المحدد ثقبًا. |
| [VertexElementIntsTemplate](./vertexelementintstemplate/) | فئة مساعدة لتعريف تطبيقات [`VertexElement`](../aspose.threed.entities/vertexelement/) الملموسة. |
| [VertexElementMaterial](./vertexelementmaterial/) | يحدد فهرس المادة للمكونات المحددة. يمكن للعقدة أن تحتوي على مواد متعددة، يتم استخدام [`VertexElementMaterial`](../aspose.threed.entities/vertexelementmaterial/) لتصيير أجزاء مختلفة من الهندسة بمواد مختلفة. |
| [VertexElementNormal](./vertexelementnormal/) | يحدد المتجهات العادية للمكونات المحددة. |
| [VertexElementPolygonGroup](./vertexelementpolygongroup/) | يحدد مجموعة المضلع للمكونات المحددة لتجميع المضلع المرتبطة معًا. |
| [VertexElementSmoothingGroup](./vertexelementsmoothinggroup/) | مجموعة التنعيم هي مجموعة من المضلعات في شبكة مضلعات يجب أن تبدو كأنها تشكل سطحًا أملسًا. استخدم بعض برامج النمذجة ثلاثية الأبعاد المبكرة مثل 3D Studio Max لنظام DOS مجموعة التنعيم لتجنب تخزين المتجه العادي لكل رأس في الشبكة. |
| [VertexElementSpecular](./vertexelementspecular/) | يحدد اللون اللامع للمكونات المحددة. |
| [VertexElementTangent](./vertexelementtangent/) | يحدد المتجهات المماسية للمكونات المحددة. |
| [VertexElementTemplate&lt;T&gt;](./vertexelementtemplate-1/) | فئة مساعدة لتعريف تطبيقات [`VertexElement`](../aspose.threed.entities/vertexelement/) الملموسة. |
| [VertexElementUserData](./vertexelementuserdata/) | يحدد بيانات المستخدم المخصصة للمكونات المحددة. عادةً ما تكون بيانات خاصة بالتطبيق لأغراض خاصة. |
| [VertexElementUV](./vertexelementuv/) | يحدد إحداثيات UV للمكونات المحددة. يمكن أن تحتوي الهندسة على عناصر متعددة من [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/)، ولكل منها [`TextureMapping`](../aspose.threed.entities/texturemapping/) مختلفة. |
| [VertexElementVector4](./vertexelementvector4/) | فئة مساعدة لتعريف تطبيقات [`VertexElement`](../aspose.threed.entities/vertexelement/) الملموسة. |
| [VertexElementVertexColor](./vertexelementvertexcolor/) | يحدد لون الرأس للمكونات المحددة. |
| [VertexElementVertexCrease](./vertexelementvertexcrease/) | يحدد تجعد الرأس للمكونات المحددة. |
| [VertexElementVisibility](./vertexelementvisibility/) | يحدد ما إذا كانت المكونات المحددة مرئية. |
| [VertexElementWeight](./vertexelementweight/) | يحدد وزن الدمج للمكونات المحددة. |
## Structures

| الهيكل | الوصف |
| --- | --- |
| [EndPoint](./endpoint/) | نقطة النهاية لقطع المنحنى، يمكن أن تكون قيمة معامل أو نقطة إحداثية. |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [IIndexedVertexElement](./iindexedvertexelement/) | VertexElement مع بيانات الفهارس. |
| [IMeshConvertible](./imeshconvertible/) | الكيانات التي نفذت هذه الواجهة يمكن تحويلها إلى [`Mesh`](../aspose.threed.entities/mesh/) |
| [IOrientable](./iorientable/) | يجب على الكيانات القابلة للتوجيه تنفيذ هذه الواجهة. |
## التعداد

| التعداد | الوصف |
| --- | --- |
| [ApertureMode](./aperturemode/) | أنماط فتحة الكاميرا. تحدد وضعية الفتحة القيم التي تتحكم في فتحة الكاميرا. إذا كانت وضعية الفتحة هي HorizAndVert أو Horizontal أو Vertical، يتم استخدام مجال الرؤية. إذا كانت وضعية الفتحة هي FocalLength، يتم استخدام البعد البؤري. |
| [BooleanOperation](./booleanoperation/) | عملية بوليانية لـ Mesh. |
| [CurveDimension](./curvedimension/) | بعد المنحنيات. |
| [LightType](./lighttype/) | أنواع الإضاءة. |
| [MappingMode](./mappingmode/) | يحدد كيفية ربط العنصر بسطح. الـ[`MappingMode`](../aspose.threed.entities/mappingmode/) يحدد كيفية ربط الـ[`VertexElement`](../aspose.threed.entities/vertexelement/) بسطح الهندسة. |
| [NurbsType](./nurbstype/) | أنواع NURBS. |
| [PatchDirectionType](./patchdirectiontype/) | أنواع اتجاه الرقعة. |
| [ProjectionType](./projectiontype/) | أنواع إسقاط الكاميرا. |
| [ReferenceMode](./referencemode/) | [`ReferenceMode`](../aspose.threed.entities/referencemode/) يحدد كيفية تخزين معلومات التعيين والمرجعية بواسطة. |
| [RotationMode](./rotationmode/) | وضع دوران المخروط العرضي |
| [SkeletonType](./skeletontype/) | أنواع الـ[`Skeleton`](../aspose.threed.entities/skeleton/). |
| [SplitMeshPolicy](./splitmeshpolicy/) | شارك بيانات الرؤوس/نقاط التحكم بين الشبكات الفرعية أو كل شبكة فرعية لها بيانات مضغوطة خاصة بها. |
| [TextureMapping](./texturemapping/) | نوع تعيين القوام لـ[`VertexElementUV`](../aspose.threed.entities/vertexelementuv/) يصف أي نوع من تعيين القوام يُستخدم. |
| [VertexElementType](./vertexelementtype/) | نوع عنصر الرؤوس، يحدد كيفية استخدامه في النمذجة. |


