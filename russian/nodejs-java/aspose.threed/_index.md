---
title: "aspose.threed"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
keywords: "Aspose.3D for Node.js via Java, Aspose.3D, STL, OBJ, Aspose API Reference."
type: docs
weight: 10
url: /ru/nodejs-java/aspose.threed/
---


## Классы

| Класс | Описание |
| --- | --- |
| [A3DObject](../aspose.threed/a3dobject) | Базовый класс всех объектов Aspose.ThreeD, все подклассы будут поддерживать динамические свойства. |
| [A3dwSaveOptions](../aspose.threed/a3dwsaveoptions) | Параметры сохранения для формата A3DW. |
| [AmfSaveOptions](../aspose.threed/amfsaveoptions) | Параметры сохранения для AMF |
| [AnimationChannel](../aspose.threed/animationchannel) | Канал сопоставляет компонентное поле свойства с набором последовательностей ключевых кадров  @hideconstructor |
| [AnimationClip](../aspose.threed/animationclip) | Клип анимации представляет собой набор анимаций. Сцена может содержать один или несколько клипов анимации. |
| [AnimationNode](../aspose.threed/animationnode) | Aspose.3D поддерживает иерархию анимации, каждая анимация может состоять из нескольких анимаций и определения ключевых кадров. AnimationNode определяет преобразование значения свойства во времени, например, узел анимации может использоваться для управления преобразованием узла или другими числовыми свойствами объекта A3DObject. |
| [ArbitraryProfile](../aspose.threed/arbitraryprofile) | Этот класс позволяет создавать 2D профиль напрямую из произвольной кривой. |
| [AssetInfo](../aspose.threed/assetinfo) | Информация об активе. Информация об активе может быть прикреплена к сцене. Дочерняя сцена может иметь собственный AssetInfo, переопределяющий определение родителя. |
| [BindPoint](../aspose.threed/bindpoint) | BindPoint обычно создаётся на свойстве объекта, некоторые типы свойств содержат несколько компонентных полей (например, поле Vector3), BindPoint генерирует канал для каждого компонентного поля и соединяет поле с одним или несколькими экземплярами последовательностей ключевых кадров через каналы. |
| [Bone](../aspose.threed/bone) | Кость определяет подмножество контрольных точек геометрии и задаёт вес смешивания для каждой контрольной точки. Объект Bone нельзя использовать напрямую, для деформации геометрии используется экземпляр SkinDeformer, который поставляется с набором костей, каждая кость привязана к узлу. ПРИМЕЧАНИЕ: Контрольная точка геометрии может быть привязана к более чем одной кости. |
| [BonePose](../aspose.threed/bonepose) | BonePose содержит матрицу преобразования для узла кости. |
| [BoundingBox](../aspose.threed/boundingbox) | Осиально-выравненный ограничивающий параллелепипед |
| [BoundingBox2D](../aspose.threed/boundingbox2d) | Осиально-выравненный ограничивающий параллелепипед для Vector2 |
| [Box](../aspose.threed/box) | Коробка. |
| [Camera](../aspose.threed/camera) | Камера описывает точку глаза наблюдателя, смотрящего на сцену. |
| [Circle](../aspose.threed/circle) | Кривая круга состоит из набора точек на границе круглой формы. |
| [CircleShape](../aspose.threed/circleshape) | Совместимый с IFC профиль круга, который можно использовать для построения сетки через LinearExtrusion |
| [ColladaSaveOptions](../aspose.threed/colladasaveoptions) | Параметры сохранения для collada |
| [CompositeCurve](../aspose.threed/compositecurve) | CompositeCurve состоит из нескольких сегментов кривой. |
| [CShape](../aspose.threed/cshape) | Совместимый с IFC профиль C-образной формы, определяемый параметрами. Центр профиля находится в центре ограничивающего бокса. |
| [Curve](../aspose.threed/curve) | Базовый класс всех реализаций кривых.  @hideconstructor |
| [CustomObject](../aspose.threed/customobject) | Метаданные или пользовательские объекты, используемые в 3D‑файлах, управляются этим классом.  Все пользовательские свойства сохраняются как динамические свойства. |
| [Cylinder](../aspose.threed/cylinder) | Параметрический цилиндр. Его также можно использовать для представления конуса, когда один из параметров radiusTop/radiusBottom равен нулю. |
| [Deformer](../aspose.threed/deformer) | Базовый класс для SkinDeformer и MorphTargetDeformer |
| [DescriptorSetUpdater](../aspose.threed/descriptorsetupdater) | Этот класс позволяет обновлять com.aspose.threed.IDescriptorSet в цепочечной операции.  @hideconstructor |
| [Discreet3dsLoadOptions](../aspose.threed/discreet3dsloadoptions) | Параметры загрузки для файла 3DS. |
| [Discreet3dsSaveOptions](../aspose.threed/discreet3dssaveoptions) | Параметры сохранения для файла 3DS. |
| [Dish](../aspose.threed/dish) | Параметрическая тарелка. |
| [DracoFormat](../aspose.threed/dracoformat) | Формат Google Draco  @hideconstructor |
| [DracoSaveOptions](../aspose.threed/dracosaveoptions) | Параметры сохранения для файлов Google Draco |
| [DriverException](../aspose.threed/driverexception) | Исключение, вызываемое внутренними драйверами рендеринга.  @hideconstructor |
| [DummyFileSystem](../aspose.threed/dummyfilesystem) | Операции чтения/записи являются фиктивными. |
| [Ellipse](../aspose.threed/ellipse) | Эллипс определяет набор точек, образующих форму эллипса. |
| [EllipseShape](../aspose.threed/ellipseshape) | Совместимая с IFC форма эллипса, определяемая параметрами. Центр профиля находится в центре ограничивающего бокса. |
| [EndPoint](../aspose.threed/endpoint) | Конечная точка для обрезки кривой, может быть значением параметра или декартовой точкой. |
| [Entity](../aspose.threed/entity) | Базовый класс всех сущностей. Entity представляет конкретный объект, прикреплённый к узлу, например Light/Geometry. |
| [EntityRenderer](../aspose.threed/entityrenderer) | Создайте подкласс, чтобы реализовать рендеринг для различных типов сущностей. |
| [EntityRendererKey](../aspose.threed/entityrendererkey) | Ключ зарегистрированного рендерера сущностей |
| [ExportException](../aspose.threed/exportexception) | Исключения, возникающие когда Aspose.3D не удалось экспортировать сцену в файл |
| [Extrapolation](../aspose.threed/extrapolation) | Экстраполяция определяет, как действовать, когда измеренное значение выходит за диапазон, определённый первым и последним ключевыми кадрами.  @hideconstructor |
| [FbxLoadOptions](../aspose.threed/fbxloadoptions) | Параметры загрузки для формата Fbx. |
| [FbxSaveOptions](../aspose.threed/fbxsaveoptions) | Параметры сохранения для файла Fbx. |
| [FileFormat](../aspose.threed/fileformat) | Определение формата файла  @hideconstructor |
| [FileFormatType](../aspose.threed/fileformattype) | Тип формата файла  @hideconstructor |
| [FileSystem](../aspose.threed/filesystem) | Инкапсуляция файловой системы.  Aspose.3D будет использовать это для чтения/записи зависимостей.  @hideconstructor |
| [FMatrix4](../aspose.threed/fmatrix4) | Матрица 4x4, все компоненты в типе float |
| [FontFile](../aspose.threed/fontfile) | Файл шрифта содержит определения глифов, он используется для создания текстового профиля.  @hideconstructor |
| [Frustum](../aspose.threed/frustum) | Базовый класс для Camera и Light  @hideconstructor |
| [FVector2](../aspose.threed/fvector2) | Вектор float с двумя компонентами. |
| [FVector3](../aspose.threed/fvector3) | Вектор float с тремя компонентами. |
| [FVector4](../aspose.threed/fvector4) | Вектор float с четырьмя компонентами. |
| [Geometry](../aspose.threed/geometry) | Базовый класс всех отрисовываемых геометрических объектов (например Mesh, NurbsSurface, Patch и т.д.).  Базовый класс Geometry поддерживает:  Управление контрольными точками, контрольные точки определяют базовую 3D пространственную структуру геометрии, разные типы геометрии имеют разные способы определения конкретных 3D моделей. Определение элементов вершин, элементы вершин добавляют дополнительную информацию, такую как нормали/UV‑координаты/цвета вершин, к геометрии, см. VertexElement для более подробной информации. Деформация объектов, Deformer может быть привязан для анимации формы геометрии. |
| [GlobalTransform](../aspose.threed/globaltransform) | Глобальное преобразование аналогично Transform, но является неизменяемым, поскольку представляет окончательное вычисленное преобразование.  При вычислении глобального преобразования используется правосторонняя система координат  @hideconstructor |
| [GLSLSource](../aspose.threed/glslsource) | Исходный код шейдеров на GLSL |
| [GltfLoadOptions](../aspose.threed/gltfloadoptions) | Параметры загрузки для формата glTF |
| [GltfSaveOptions](../aspose.threed/gltfsaveoptions) | Параметры сохранения для формата glTF. |
| [HollowCircleShape](../aspose.threed/hollowcircleshape) | Профиль полого круга, совместимый с IFC. |
| [HollowRectangleShape](../aspose.threed/hollowrectangleshape) | Полый прямоугольный профиль, совместимый с IFC, с закруглёнными внутренними и внешними углами. |
| [HShape](../aspose.threed/hshape) | HShape предоставляет определяющие параметры формы 'H' или 'I'. |
| [Html5SaveOptions](../aspose.threed/html5saveoptions) | Параметры сохранения для HTML5 |
| [ImageRenderOptions](../aspose.threed/imagerenderoptions) | Параметры для Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) и  Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions) |
| [ImportException](../aspose.threed/importexception) | Исключение, когда Aspose.3D не удалось открыть указанный источник |
| [InitializationException](../aspose.threed/initializationexception) | Исключения при инициализации конвейера рендеринга |
| [IOConfig](../aspose.threed/ioconfig) | Конфигурация ввода-вывода для сериализации/десериализации.  Пользователь может указать детальные настройки, такие как путь поиска зависимостей, или настройки, связанные с форматом, здесь  @hideconstructor |
| [IOUtils](../aspose.threed/ioutils) | Утилиты для записи матрицы/вектора в бинарный writer  @hideconstructor |
| [KeyFrame](../aspose.threed/keyframe) | Ключевой кадр в основном определяется временем и значением, для некоторых типов интерполяции также используются тангенс/натяжение/смещение/непрерывность при расчёте окончательного выбранного значения.  Выбранные значения в позиции времени без ключевого кадра интерполируются ключевыми кадрами между предыдущим и следующим ключевыми кадрами.  Значения до/после первого/последнего ключевого кадра вычисляются классом Extrapolation. |
| [KeyframeSequence](../aspose.threed/keyframesequence) | Последовательность ключевых кадров, описывающая преобразование выбранного значения во времени. |
| [LambertMaterial](../aspose.threed/lambertmaterial) | Материал для ламбертовой модели затенения |
| [License](../aspose.threed/license) | Предоставляет методы лицензирования компонента. |
| [Light](../aspose.threed/light) | Свет освещает сцену.  Формула для расчёта общей затухания света выглядит так:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation) |
| [Line](../aspose.threed/line) | Полилиния — это путь, определённый набором точек с Geometry.ControlPoints и соединённый сегментами (Segments), что означает, что она также может быть набором соединённых отрезков. Линия обычно является линейным объектом, поэтому её нельзя использовать для представления кривой; для представления кривой используется NurbsCurve. |
| [LinearExtrusion](../aspose.threed/linearextrusion) | Линейная экструзия принимает 2D-форму в качестве входных данных и расширяет её в третьем измерении. |
| [LoadOptions](../aspose.threed/loadoptions) | Базовый класс для настройки параметров загрузки файлов разных типов  @hideconstructor |
| [LocalFileSystem](../aspose.threed/localfilesystem) | LocalFileSystem будет сопоставлять операции чтения/записи с локальной директорией. |
| [LShape](../aspose.threed/lshape) | Совместимый с IFC профиль L-образной формы, определяемый параметрами. |
| [Material](../aspose.threed/material) | Material определяет параметры, необходимые для визуального отображения геометрии. Aspose.3D предоставляет модели затенения для LambertMaterial, PhongMaterial и ShaderMaterial  @hideconstructor |
| [MathUtils](../aspose.threed/mathutils) | Набор полезных математических утилит.  @hideconstructor |
| [Matrix4](../aspose.threed/matrix4) | Реализация 4x4 матрицы. |
| [MemoryFileSystem](../aspose.threed/memoryfilesystem) | MemoryFileSystem будет сопоставлять операции чтения/записи с памятью. |
| [Mesh](../aspose.threed/mesh) | Сетка состоит из множества n-угольных полигонов. |
| [Metered](../aspose.threed/metered) | Предоставляет методы установки измеряемого ключа. |
| [MirroredProfile](../aspose.threed/mirroredprofile) | Совместимый с IFC профиль зеркального отражения. Этот профиль определяет новый профиль, отражая базовый профиль относительно оси y. |
| [MorphTargetChannel](../aspose.threed/morphtargetchannel) | MorphTargetChannel используется MorphTargetDeformer для организации целевых геометрий. Некоторые форматы файлов, такие как FBX, поддерживают несколько каналов одновременно. Вес находится в диапазоне от 0 до 1.0, а вес по умолчанию для цели равен 0.0; |
| [MorphTargetDeformer](../aspose.threed/morphtargetdeformer) | MorphTargetDeformer предоставляет анимацию на уровне вершин. MorphTargetDeformer организует все цели через MorphTargetChannel, каждый канал может содержать несколько целей. Распространённое применение morph target deformer — применение мимики к персонажу. Подробнее можно узнать по ссылке https://en.wikipedia.org/wiki/Morph_target_animation |
| [Node](../aspose.threed/node) | Представляет элемент в графе сцены. Граф сцены — это дерево объектов Node. Службы управления деревом инкапсулированы в этом классе. Обратите внимание, что Aspose.3D SDK не проверяет корректность построенного графа сцены. Ответственность за то, чтобы не создавать циклические графы в иерархии узлов, лежит на вызывающем. Помимо управления деревом, этот класс определяет все свойства, необходимые для описания положения объекта в сцене. Эта информация включает базовые свойства Translation, Rotation и Scaling, а также более продвинутые параметры для точек вращения, ограничений и атрибутов IK‑соединений, таких как жёсткость и демпфирование. При первом создании объект Node является \"empty\" (т.е. это объект без графического представления, содержащий только информацию о позиции). В этом состоянии его можно использовать для представления родительских узлов в структуре дерева, но не более. Обычное использование таких объектов — добавить к ним сущность, которая специализирует узел (см. \"Entity\"). Сущность является отдельным объектом и соединена с Node. Это также означает, что одна и та же сущность может быть общей для нескольких узлов. Camera, Light, Mesh и т.д. являются всеми сущностями и все они наследуются от базового класса Entity. |
| [NurbsCurve](../aspose.threed/nurbscurve) | Кривая NURBS — это кривая, представляемая NURBS (Non-uniform rational basis spline). Кривая NURBS определяется её порядком (Order), набором взвешенных Geometry.ControlPoints и KnotVectors. Компонент w в контрольной точке используется как вес контрольной точки, независимо от того, является ли она CurveDimension.TWO_DIMENSIONAL или CurveDimension.THREE_DIMENSIONAL. |
| [NurbsDirection](../aspose.threed/nurbsdirection) | 3D NurbsSurface имеет два направления: NurbsSurface.U и NurbsSurface.V; NurbsDirection определяет данные для каждого направления. Направление фактически является кривой NURBS, то есть оно также определяется своим порядком (Order), KnotVectors и набором взвешенных контрольных точек (определённых в NurbsSurface). |
| [NurbsSurface](../aspose.threed/nurbssurface) | NurbsSurface — это поверхность, представляемая NURBS (Non-uniform rational basis spline). NurbsSurface определяется двумя направлениями NurbsDirectionU и V. Компонент w в контрольной точке используется как вес контрольной точки, независимо от того, является ли тип направления CurveDimension.TWO_DIMENSIONAL или CurveDimension.THREE_DIMENSIONAL. |
| [ObjLoadOptions](../aspose.threed/objloadoptions) | Параметры загрузки для wavefront obj |
| [ObjSaveOptions](../aspose.threed/objsaveoptions) | Параметры сохранения для файла wavefront obj |
| [ParameterizedProfile](../aspose.threed/parameterizedprofile) | Базовый класс всех параметризованных профилей.  @hideconstructor |
| [ParseException](../aspose.threed/parseexception) | Исключение, когда Aspose.3D не удалось разобрать входные данные. |
| [Patch](../aspose.threed/patch) | Patch — это параметрическая модельная поверхность, похожая на NurbsSurface, она также определяется двумя направлениями PatchDirection, U и V. Но различие между Patch и NurbsSurface заключается в том, что кривая PatchDirection может быть одной из PatchDirectionType.BEZIER, PatchDirectionType.QUADRATIC_BEZIER, PatchDirectionType.BASIS_SPLINE, PatchDirectionType.CARDINAL_SPLINE и PatchDirectionType.LINEAR. |
| [PatchDirection](../aspose.threed/patchdirection) | Направления U и V Patch. |
| [PbrMaterial](../aspose.threed/pbrmaterial) | Материал для физически основанного рендеринга, основанный на альбедо‑цвете/металличности/шероховатости. |
| [PbrSpecularMaterial](../aspose.threed/pbrspecularmaterial) | Материал для физически основанного рендеринга, основанный на диффузном цвете/спекуляре/глянце. |
| [PdfFormat](../aspose.threed/pdfformat) | Portable Document Format от Adobe  @hideconstructor |
| [PdfLoadOptions](../aspose.threed/pdfloadoptions) | Параметры загрузки PDF |
| [PdfSaveOptions](../aspose.threed/pdfsaveoptions) | Параметры сохранения при экспорте PDF. |
| [PhongMaterial](../aspose.threed/phongmaterial) | Материал для модели освещения Blinn-Phong. |
| [PixelMapping](../aspose.threed/pixelmapping) | @hideconstructor |
| [Plane](../aspose.threed/plane) | Параметризованная плоскость. |
| [PlyFormat](../aspose.threed/plyformat) | Формат PLY.  @hideconstructor |
| [PlyLoadOptions](../aspose.threed/plyloadoptions) | Параметры загрузки файлов PLY |
| [PlySaveOptions](../aspose.threed/plysaveoptions) | Параметры сохранения при экспорте сцены в файл PLY. |
| [PointCloud](../aspose.threed/pointcloud) | Облако точек не содержит информации о топологии, а только контрольные точки и элементы вершин. |
| [PolygonBuilder](../aspose.threed/polygonbuilder) | Вспомогательный класс для построения полигонов для Mesh. |
| [PolygonModifier](../aspose.threed/polygonmodifier) | Утилиты для модификации полигонов  @hideconstructor |
| [Pose](../aspose.threed/pose) | Позa используется для хранения матрицы преобразования, когда геометрия скинится. Позa представляет собой набор BonePose, каждый BonePose сохраняет конкретную информацию о преобразовании узла кости. |
| [PostProcessing](../aspose.threed/postprocessing) | Эффекты постобработки  @hideconstructor |
| [Primitive](../aspose.threed/primitive) | Базовый класс для всех примитивов |
| [Profile](../aspose.threed/profile) | 2D профиль в плоскости xy  @hideconstructor |
| [Property](../aspose.threed/property) | Класс для хранения пользовательских свойств.  @hideconstructor |
| [PropertyCollection](../aspose.threed/propertycollection) | Коллекция свойств  @hideconstructor |
| [PushConstant](../aspose.threed/pushconstant) | Утилита для передачи данных в шейдер через push‑constant. |
| [Pyramid](../aspose.threed/pyramid) | Параметризованная пирамида. |
| [Quaternion](../aspose.threed/quaternion) | Кватернион обычно используется для выполнения вращения в компьютерной графике. |
| [Rect](../aspose.threed/rect) | Класс для представления прямоугольника |
| [RectangleShape](../aspose.threed/rectangleshape) | Прямоугольная форма, совместимая с IFC, со скруглёнными углами. |
| [RectangularTorus](../aspose.threed/rectangulartorus) | Параметризованный прямоугольный тор. |
| [RelativeRectangle](../aspose.threed/relativerectangle) | Относительный прямоугольник  Формула между относительным компонентом и абсолютным значением выглядит так:  Scale  (Reference Width) + offset  Поэтому, если мы хотим представить абсолютное значение, оставьте все поля масштабирования нулевыми и вместо этого используйте поля смещения. |
| [Renderer](../aspose.threed/renderer) | Контекст о рендерере.  @hideconstructor |
| [RendererVariableManager](../aspose.threed/renderervariablemanager) | Этот класс управляет переменными, используемыми при рендеринге  @hideconstructor |
| [RenderFactory](../aspose.threed/renderfactory) | RenderFactory создаёт все ресурсы, представленные в конвейере рендеринга.  @hideconstructor |
| [RenderParameters](../aspose.threed/renderparameters) | Опишите параметры целевого рендеринга |
| [RenderResource](../aspose.threed/renderresource) | Абстрактный класс всех ресурсов рендеринга  Все ресурсы рендеринга будут освобождены при освобождении рендера.  Классы вроде Mesh/Texture будут иметь соответствующий RenderResource  @hideconstructor |
| [RenderState](../aspose.threed/renderstate) | Состояние рендеринга для построения конвейера  Изменения, внесённые в состояние рендеринга, не повлияют на созданные экземпляры конвейера. |
| [RevolvedAreaSolid](../aspose.threed/revolvedareasolid) | Этот класс представляет твёрдое тело, вращая поперечное сечение, заданное профилем, вокруг оси. |
| [RvmFormat](../aspose.threed/rvmformat) | Формат RVM  @hideconstructor |
| [RvmLoadOptions](../aspose.threed/rvmloadoptions) | Параметры загрузки RVM‑файла системы AVEVA Plant Design Management System. |
| [RvmSaveOptions](../aspose.threed/rvmsaveoptions) | Параметры сохранения RVM‑файла Aveva PDMS. |
| [SaveOptions](../aspose.threed/saveoptions) | Базовый класс для настройки параметров сохранения файлов разных типов  @hideconstructor |
| [Scene](../aspose.threed/scene) | Сцена — это объект верхнего уровня, содержащий узлы, геометрию, материалы, текстуры, анимацию, позы, подп сцены и т.д.  Сцена может иметь подп сцены, обеспечивая поддержку нескольких документов в файлах вроде collada/blender/fbx.  Иерархию узлов можно получить через RootNodeLibrary, который используется для хранения ссылок на несвязанные объекты во время сериализации (например, метаданные или пользовательские объекты), чтобы их можно было использовать как библиотеку. |
| [SceneObject](../aspose.threed/sceneobject) | Корневой класс объектов, которые будут храниться внутри сцены. |
| [ShaderException](../aspose.threed/shaderexception) | Исключения, связанные с шейдерами |
| [ShaderMaterial](../aspose.threed/shadermaterial) | Шейдерный материал позволяет описать материал с помощью внешнего движка рендеринга или языка шейдеров.  ShaderMaterial использует ShaderTechnique для описания конкретных деталей рендеринга, и наиболее подходящий будет выбран в зависимости от конечной платформы рендеринга.  Например, ваш экземпляр ShaderMaterial может иметь две техники: одна определена в HLSL, другая — в GLSL.  На платформах без окна следует использовать GLSL вместо HLSL. |
| [ShaderProgram](../aspose.threed/shaderprogram) | Шейдерная программа  @hideconstructor |
| [ShaderSet](../aspose.threed/shaderset) | Шейдерные программы для каждого типа материалов |
| [ShaderSource](../aspose.threed/shadersource) | Исходный код шейдера  @hideconstructor |
| [ShaderTechnique](../aspose.threed/shadertechnique) | Шейдерная техника представляет конкретную реализацию рендеринга. |
| [ShaderVariable](../aspose.threed/shadervariable) | Шейдерная переменная |
| [Shape](../aspose.threed/shape) | Форма описывает деформацию набора контрольных точек, что аналогично кластерному деформеру в Maya.  Например, мы можем добавить форму к уже созданной геометрии.  При этом форма и геометрия имеют одинаковую топологическую информацию, но различаются положением контрольных точек.  При различном уровне влияния геометрия осуществляет эффект деформации. |
| [Skeleton](../aspose.threed/skeleton) | The Skeleton в основном используется CAD‑программами, чтобы помочь дизайнеру управлять преобразованием скелетной структуры; обычно он бесполезен вне CAD‑программ. Чтобы иерархия скелета вела себя как один объект в CAD‑программе, необходимо пометить верхний узел Skeleton как корневой, установив Type в SkeletonType.SKELETON, а все дочерние — в SkeletonType.BONE |
| [SkinDeformer](../aspose.threed/skindeformer) | Skin deformer содержит несколько костей, каждая кость смешивает часть геометрии по весам контрольных точек. |
| [Sphere](../aspose.threed/sphere) | Параметрическая сфера. |
| [SPIRVSource](../aspose.threed/spirvsource) | Скомпилированный шейдер в формате SPIR-V. |
| [StencilState](../aspose.threed/stencilstate) | Состояния трафарета для каждой грани.  @hideconstructor |
| [StlLoadOptions](../aspose.threed/stlloadoptions) | Параметры загрузки для STL |
| [StlSaveOptions](../aspose.threed/stlsaveoptions) | Параметры сохранения для STL |
| [SweptAreaSolid](../aspose.threed/sweptareasolid) | SweptAreaSolid создает геометрию, вытягивая профиль вдоль директиксы. |
| [Text](../aspose.threed/text) | Текстовый профиль, этот профиль описывает контуры с использованием шрифта и текста. |
| [Texture](../aspose.threed/texture) | Этот класс определяет текстуру из внешнего файла. |
| [TextureBase](../aspose.threed/texturebase) | Базовый класс для всех конкретных текстур.  Texture определяет внешний вид и ощущение поверхности геометрии. |
| [TextureCodec](../aspose.threed/texturecodec) | Класс для управления кодировщиками и декодировщиками текстур. |
| [TextureData](../aspose.threed/texturedata) | Этот класс содержит необработанные данные и определение формата текстуры. |
| [TextureSlot](../aspose.threed/textureslot) | Слот текстуры в Material, может быть перечислен через экземпляр материала.  @hideconstructor |
| [Torus](../aspose.threed/torus) | Параметрический тор. |
| [Transform](../aspose.threed/transform) | Трансформ содержит информацию, позволяющую получить доступ к перемещению/масштабированию/вращению объекта или матрице преобразования с минимальными затратами.  Это используется локальным трансформом.  @hideconstructor |
| [TransformBuilder](../aspose.threed/transformbuilder) | TransformBuilder используется для построения матрицы преобразования цепочкой трансформаций. |
| [TransformedCurve](../aspose.threed/transformedcurve) | TransformedCurve размещает кривую, используя матрицу преобразования.  Это позволяет выполнить преобразование внутри TrimmedCurve или CompositeCurve. |
| [TrapeziumShape](../aspose.threed/trapeziumshape) | IFC‑совместимая трапециевидная форма, определяемая параметрами. |
| [TrialException](../aspose.threed/trialexception) | Это исключение возникает в Scene.Open/Scene.Save, когда лицензии не применены.  Вы можете отключить это исключение, установив SuppressTrialException в true. |
| [TriMesh](../aspose.threed/trimesh) | TriMesh содержит необработанные данные, которые могут использоваться GPU напрямую.  Этот класс — утилита, помогающая построить сетку, содержащую только данные по вершинам. |
| [TrimmedCurve](../aspose.threed/trimmedcurve) | Ограниченная кривая, обрезающая базовую кривую с обеих сторон. |
| [TShape](../aspose.threed/tshape) | IFC‑совместимая T‑форма, определяемая параметрами. |
| [U3dLoadOptions](../aspose.threed/u3dloadoptions) | Параметры загрузки для universal 3d |
| [U3dSaveOptions](../aspose.threed/u3dsaveoptions) | Параметры сохранения для universal 3d |
| [UsdSaveOptions](../aspose.threed/usdsaveoptions) | Сохранить параметры для форматов USD/USDZ. |
| [UShape](../aspose.threed/ushape) | Совместимая с IFC U-образная форма, определённая параметрами. |
| [Vector2](../aspose.threed/vector2) | Вектор с двумя компонентами. |
| [Vector3](../aspose.threed/vector3) | Вектор с тремя компонентами. |
| [Vector4](../aspose.threed/vector4) | Вектор с четырьмя компонентами. |
| [Vertex](../aspose.threed/vertex) | Ссылка на вершину, используемая для доступа к необработанной вершине в TriMesh.  @hideconstructor |
| [VertexDeclaration](../aspose.threed/vertexdeclaration) | Объявление структуры пользовательской вершины |
| [VertexElement](../aspose.threed/vertexelement) | Базовый класс элементов вершины. Тип элемента вершины определяется VertexElementType. VertexElement описывает, как элемент вершины отображается на поверхность геометрии и как информация о отображении размещается в памяти. VertexElement содержит нормали, UV или другую информацию.  @hideconstructor |
| [VertexElementBinormal](../aspose.threed/vertexelementbinormal) | Определяет бинормальные векторы для указанных компонентов. |
| [VertexElementDoublesTemplate](../aspose.threed/vertexelementdoublestemplate) | Вспомогательный класс для определения конкретных реализаций VertexElement.  @hideconstructor |
| [VertexElementEdgeCrease](../aspose.threed/vertexelementedgecrease) | Определяет сгиб ребра для указанных компонентов |
| [VertexElementHole](../aspose.threed/vertexelementhole) | Определяет, является ли указанный полигон отверстием |
| [VertexElementIntsTemplate](../aspose.threed/vertexelementintstemplate) | Вспомогательный класс для определения конкретных реализаций VertexElement.  @hideconstructor |
| [VertexElementMaterial](../aspose.threed/vertexelementmaterial) | Определяет индекс материала для указанных компонентов. Узел может иметь несколько материалов, VertexElementMaterial используется для рендеринга разных частей геометрии разными материалами. |
| [VertexElementNormal](../aspose.threed/vertexelementnormal) | Определяет нормальные векторы для указанных компонентов. |
| [VertexElementPolygonGroup](../aspose.threed/vertexelementpolygongroup) | Определяет группу полигонов для указанных компонентов, чтобы объединять связанные полигоны вместе. |
| [VertexElementSmoothingGroup](../aspose.threed/vertexelementsmoothinggroup) | Группа сглаживания — это набор полигонов в полигональной сетке, которые должны выглядеть как гладкая поверхность. Некоторые ранние 3D‑моделирующие программы, такие как 3D Studio Max для DOS, использовали группы сглаживания, чтобы избежать хранения нормального вектора для каждой вершины сетки. |
| [VertexElementSpecular](../aspose.threed/vertexelementspecular) | Определяет зеркальный цвет для указанных компонентов. |
| [VertexElementTangent](../aspose.threed/vertexelementtangent) | Определяет касательные векторы для указанных компонентов. |
| [VertexElementUserData](../aspose.threed/vertexelementuserdata) | Определяет пользовательские данные для указанных компонентов. Обычно это данные, специфичные для приложения, для специального назначения. |
| [VertexElementUV](../aspose.threed/vertexelementuv) | Определяет UV‑координаты для указанных компонентов. Геометрия может иметь несколько элементов VertexElementUV, каждый из которых имеет разные TextureMappings. |
| [VertexElementVector4](../aspose.threed/vertexelementvector4) | Вспомогательный класс для определения конкретных реализаций VertexElement.  @hideconstructor |
| [VertexElementVertexColor](../aspose.threed/vertexelementvertexcolor) | Определяет цвет вершины для указанных компонентов |
| [VertexElementVertexCrease](../aspose.threed/vertexelementvertexcrease) | Определяет сгиб вершины для указанных компонентов |
| [VertexElementVisibility](../aspose.threed/vertexelementvisibility) | Определяет, видимы ли указанные компоненты |
| [VertexElementWeight](../aspose.threed/vertexelementweight) | Определяет вес смешивания для указанных компонентов. |
| [VertexField](../aspose.threed/vertexfield) | Описание расположения полей вершины в памяти.  @hideconstructor |
| [Viewport](../aspose.threed/viewport) | Объект com.aspose.threed.IRenderTarget содержит как минимум один видовой порт для рендеринга сцены.  @hideconstructor |
| [Watermark](../aspose.threed/watermark) | Утилита для кодирования/декодирования слепой водяной метки в/из сетки.  @hideconstructor |
| [WindowHandle](../aspose.threed/windowhandle) | Инкапсулированный дескриптор окна для разных платформ.  @hideconstructor |
| [XLoadOptions](../aspose.threed/xloadoptions) | Параметры загрузки для файлов DirectX X. |
| [ZipArchiveFileSystem](../aspose.threed/ziparchivefilesystem) | Файловая система, предоставляющая только чтение к указанному zip‑файлу или zip‑потоку.  Файловая система будет освобождена после операции открытия/сохранения. |
| [ZShape](../aspose.threed/zshape) | Профиль Z‑формы, совместимый с IFC, определённый параметрами. |
| [CubeFace](../aspose.threed/cubeface) | Утилитный класс, содержащий константы.  Каждая грань кубической карты текстур  @hideconstructor |
| [IndexDataType](../aspose.threed/indexdatatype) | Утилитный класс, содержащий константы.  Тип данных элементов в com.aspose.threed.IIndexBuffer  @hideconstructor |
