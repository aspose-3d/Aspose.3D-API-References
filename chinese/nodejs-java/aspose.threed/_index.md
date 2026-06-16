---
title: "aspose.threed"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
keywords: "Aspose.3D for Node.js via Java, Aspose.3D, STL, OBJ, Aspose API Reference."
type: docs
weight: 10
url: /zh/nodejs-java/aspose.threed/
---


## 类

| 类 | 描述 |
| --- | --- |
| [A3DObject](../aspose.threed/a3dobject) | 所有 Aspose.ThreeD 对象的基类，所有子类都将支持动态属性。 |
| [A3dwSaveOptions](../aspose.threed/a3dwsaveoptions) | A3DW 格式的保存选项。 |
| [AmfSaveOptions](../aspose.threed/amfsaveoptions) | AMF 的保存选项 |
| [AnimationChannel](../aspose.threed/animationchannel) | 通道将属性的组件字段映射到一组关键帧序列  @hideconstructor |
| [AnimationClip](../aspose.threed/animationclip) | Animation clip 是动画的集合。场景可以拥有一个或多个 animation clips。 |
| [AnimationNode](../aspose.threed/animationnode) | Aspose.3D 支持动画层次结构，每个动画可以由多个动画及其关键帧定义组成。AnimationNode 定义属性值随时间的变换，例如，animation node 可用于控制节点的变换或其他 A3DObject 对象的数值属性。 |
| [ArbitraryProfile](../aspose.threed/arbitraryprofile) | 此类允许您直接从任意曲线构建 2D 轮廓。 |
| [AssetInfo](../aspose.threed/assetinfo) | 资产信息。资产信息可以附加到 Scene。子 Scene 可以拥有自己的 AssetInfo 来覆盖父级的定义。 |
| [BindPoint](../aspose.threed/bindpoint) | BindPoint 通常在对象的属性上创建，某些属性类型包含多个组件字段（如 Vector3 字段），BindPoint 将为每个组件字段生成通道，并通过这些通道将字段连接到一个或多个关键帧序列实例。 |
| [Bone](../aspose.threed/bone) | bone 定义了几何体控制点的子集，并为每个控制点定义了混合权重。Bone 对象不能直接使用，需使用 SkinDeformer 实例来变形几何体，SkinDeformer 附带一组 bones，每个 bone 链接到一个节点。注意：几何体的控制点可以绑定到多个 Bones。 |
| [BonePose](../aspose.threed/bonepose) | BonePose 包含 bone 节点的变换矩阵 |
| [BoundingBox](../aspose.threed/boundingbox) | 轴对齐包围盒 |
| [BoundingBox2D](../aspose.threed/boundingbox2d) | Vector2 的轴对齐包围盒 |
| [Box](../aspose.threed/box) | 盒子。 |
| [Camera](../aspose.threed/camera) | camera 描述了观看者注视场景的眼点。 |
| [Circle](../aspose.threed/circle) | Circle 曲线由圆形边缘上的一组点组成。 |
| [CircleShape](../aspose.threed/circleshape) | IFC 兼容的圆形轮廓，可用于通过 LinearExtrusion 构建网格。 |
| [ColladaSaveOptions](../aspose.threed/colladasaveoptions) | Collada 的保存选项 |
| [CompositeCurve](../aspose.threed/compositecurve) | CompositeCurve 由多个曲线段组成。 |
| [CShape](../aspose.threed/cshape) | IFC 兼容的 C 形轮廓，由参数定义。轮廓的中心位置位于包围盒的中心。 |
| [Curve](../aspose.threed/curve) | 所有曲线实现的基类。  @hideconstructor |
| [CustomObject](../aspose.threed/customobject) | 此类管理 3D 文件中使用的元数据或自定义对象。所有自定义属性都保存为动态属性。 |
| [Cylinder](../aspose.threed/cylinder) | 参数化圆柱体。当 radiusTop/radiusBottom 为零时，它也可用于表示圆锥体。 |
| [Deformer](../aspose.threed/deformer) | SkinDeformer 和 MorphTargetDeformer 的基类 |
| [DescriptorSetUpdater](../aspose.threed/descriptorsetupdater) | 此类允许在链式操作中更新 com.aspose.threed.IDescriptorSet。  @hideconstructor |
| [Discreet3dsLoadOptions](../aspose.threed/discreet3dsloadoptions) | 3DS 文件的加载选项。 |
| [Discreet3dsSaveOptions](../aspose.threed/discreet3dssaveoptions) | 3DS 文件的保存选项。 |
| [Dish](../aspose.threed/dish) | 参数化碟形。 |
| [DracoFormat](../aspose.threed/dracoformat) | Google Draco 格式  @hideconstructor |
| [DracoSaveOptions](../aspose.threed/dracosaveoptions) | Google Draco 文件的保存选项 |
| [DriverException](../aspose.threed/driverexception) | 内部渲染驱动程序抛出的异常。  @hideconstructor |
| [DummyFileSystem](../aspose.threed/dummyfilesystem) | 读/写操作为虚拟操作。 |
| [Ellipse](../aspose.threed/ellipse) | Ellipse 定义了一组形成椭圆形状的点。 |
| [EllipseShape](../aspose.threed/ellipseshape) | IFC 兼容的椭圆形状，由参数定义。轮廓的中心位置位于包围盒的中心。 |
| [EndPoint](../aspose.threed/endpoint) | 用于修剪曲线的终点，可以是参数值或笛卡尔点。 |
| [Entity](../aspose.threed/entity) | 所有实体的基类。Entity 表示附加在 Light/Geometry 等节点下的具体对象。 |
| [EntityRenderer](../aspose.threed/entityrenderer) | 子类化此类以实现不同类型实体的渲染。 |
| [EntityRendererKey](../aspose.threed/entityrendererkey) | 已注册实体渲染器的键 |
| [ExportException](../aspose.threed/exportexception) | Aspose.3D 导出场景到文件失败时的异常 |
| [Extrapolation](../aspose.threed/extrapolation) | 外推定义了当采样值超出由首帧和尾帧定义的范围时的处理方式。  @hideconstructor |
| [FbxLoadOptions](../aspose.threed/fbxloadoptions) | Fbx 格式的加载选项。 |
| [FbxSaveOptions](../aspose.threed/fbxsaveoptions) | Fbx 文件的保存选项。 |
| [FileFormat](../aspose.threed/fileformat) | 文件格式定义  @hideconstructor |
| [FileFormatType](../aspose.threed/fileformattype) | 文件格式类型  @hideconstructor |
| [FileSystem](../aspose.threed/filesystem) | 文件系统封装。Aspose.3D 将使用它来读取/写入依赖项。  @hideconstructor |
| [FMatrix4](../aspose.threed/fmatrix4) | 矩阵 4x4，所有分量为 float 类型 |
| [FontFile](../aspose.threed/fontfile) | 字体文件包含字形定义，用于创建文本配置文件。  @hideconstructor |
| [Frustum](../aspose.threed/frustum) | Camera 和 Light 的基类  @hideconstructor |
| [FVector2](../aspose.threed/fvector2) | 一个具有两个分量的 float 向量。 |
| [FVector3](../aspose.threed/fvector3) | 一个具有三个分量的 float 向量。 |
| [FVector4](../aspose.threed/fvector4) | 一个具有四个分量的 float 向量。 |
| [Geometry](../aspose.threed/geometry) | 所有可渲染几何对象（如 Mesh、NurbsSurface、Patch 等）的基类。Geometry 基类支持：控制点管理，控制点定义几何体的基础 3D 空间结构，不同几何类型有不同的方式来定义具体的 3D 模型。顶点元素定义，顶点元素为几何体添加额外信息，如法线/uv 坐标/顶点颜色，更多细节请参见 VertexElement。对象变形，Deformer 可绑定以动画化几何体的形状。 |
| [GlobalTransform](../aspose.threed/globaltransform) | 全局变换类似于 Transform，但它是不可变的，因为它表示最终评估的变换。评估全局变换时使用右手坐标系  @hideconstructor |
| [GLSLSource](../aspose.threed/glslsource) | GLSL 中着色器的源代码 |
| [GltfLoadOptions](../aspose.threed/gltfloadoptions) | glTF 格式的加载选项 |
| [GltfSaveOptions](../aspose.threed/gltfsaveoptions) | glTF 格式的保存选项。 |
| [HollowCircleShape](../aspose.threed/hollowcircleshape) | 兼容 IFC 的空心圆形轮廓。 |
| [HollowRectangleShape](../aspose.threed/hollowrectangleshape) | 兼容 IFC 的空心矩形形状，具有内外圆角。 |
| [HShape](../aspose.threed/hshape) | HShape 提供了 'H' 或 'I' 形状的定义参数。 |
| [Html5SaveOptions](../aspose.threed/html5saveoptions) | HTML5 的保存选项 |
| [ImageRenderOptions](../aspose.threed/imagerenderoptions) | Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) 和 Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions) 的选项 |
| [ImportException](../aspose.threed/importexception) | Aspose.3D 打开指定源失败时的异常 |
| [InitializationException](../aspose.threed/initializationexception) | 渲染管线初始化中的异常 |
| [IOConfig](../aspose.threed/ioconfig) | 用于序列化/反序列化的 IO 配置。用户可以在此指定详细配置，如依赖查找路径或与格式相关的配置  @hideconstructor |
| [IOUtils](../aspose.threed/ioutils) | 将矩阵/向量写入二进制写入器的实用工具  @hideconstructor |
| [KeyFrame](../aspose.threed/keyframe) | 关键帧主要由时间和数值定义，对于某些插值类型，还会使用切线/张力/偏差/连续性来计算最终的采样值。非关键帧时间位置的采样值由前后关键帧之间的关键帧进行插值。首个/最后一个关键帧之前或之后的数值由 Extrapolation 类计算。 |
| [KeyframeSequence](../aspose.threed/keyframesequence) | 关键帧序列，描述了采样值随时间的变化。 |
| [LambertMaterial](../aspose.threed/lambertmaterial) | Lambert 着色模型的材质 |
| [License](../aspose.threed/license) | 提供对组件进行授权的方法。 |
| [Light](../aspose.threed/light) | 光照亮场景。计算光总衰减的公式为：A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation) |
| [Line](../aspose.threed/line) | 折线是由 Geometry.ControlPoints 定义的一组点构成的路径，并通过 Segments 连接，这意味着它也可以是一组相连的线段。线通常是线性对象，意味着它不能用于表示曲线，如需表示曲线，请使用 NurbsCurve。 |
| [LinearExtrusion](../aspose.threed/linearextrusion) | 线性拉伸以二维形状为输入，并在第三维度上扩展该形状。 |
| [LoadOptions](../aspose.threed/loadoptions) | 用于为不同类型配置文件加载选项的基类 @hideconstructor |
| [LocalFileSystem](../aspose.threed/localfilesystem) | LocalFileSystem 将把读写操作映射到本地目录。 |
| [LShape](../aspose.threed/lshape) | 由参数定义的符合 IFC 标准的 L 形截面。 |
| [Material](../aspose.threed/material) | 材质定义了几何体外观所需的参数。Aspose.3D 提供了 LambertMaterial、PhongMaterial 和 ShaderMaterial 的着色模型 @hideconstructor |
| [MathUtils](../aspose.threed/mathutils) | 一组有用的数学工具。 @hideconstructor |
| [Matrix4](../aspose.threed/matrix4) | 4x4 矩阵实现。 |
| [MemoryFileSystem](../aspose.threed/memoryfilesystem) | MemoryFileSystem 将把读写操作映射到内存。 |
| [Mesh](../aspose.threed/mesh) | 网格由许多 n 边多边形组成。 |
| [Metered](../aspose.threed/metered) | 提供设置计量密钥的方法。 |
| [MirroredProfile](../aspose.threed/mirroredprofile) | 符合 IFC 标准的镜像截面。该截面通过相对于 y 轴镜像基准截面来定义新的截面。 |
| [MorphTargetChannel](../aspose.threed/morphtargetchannel) | MorphTargetChannel 被 MorphTargetDeformer 用于组织目标几何体。某些文件格式如 FBX 支持并行的多个通道。权重介于 0 到 1.0 之间，目标的默认权重为 0.0； |
| [MorphTargetDeformer](../aspose.threed/morphtargetdeformer) | MorphTargetDeformer 提供每顶点动画。MorphTargetDeformer 通过 MorphTargetChannel 组织所有目标，每个通道可以组织多个目标。形变目标变形器的常见用途是为角色应用面部表情。更多细节请参阅 https://en.wikipedia.org/wiki/Morph_target_animation |
| [Node](../aspose.threed/node) | 表示场景图中的一个元素。场景图是由 Node 对象组成的树。树的管理服务封装在此类中。注意，Aspose.3D SDK 不会检查构建的场景图的有效性。调用者有责任确保在节点层次结构中不生成循环图。除了树管理外，此类还定义了描述对象在场景中位置所需的所有属性。这些信息包括基本的 Translation、Rotation 和 Scaling 属性，以及用于枢轴、限制和 IK 关节的更高级选项，如刚度和阻尼。首次创建时，Node 对象是\"empty\"（即：它是一个仅包含位置信息且没有任何图形表示的对象）。在此状态下，它可用于表示节点树结构中的父节点，但功能有限。此类对象的常规用法是为其添加一个实体以专化节点（参见\"Entity\"）。实体本身是一个对象，并连接到 Node。这也意味着同一实体可以在多个节点之间共享。Camera、Light、Mesh 等都是实体，并且它们都派生自基类 Entity。 |
| [NurbsCurve](../aspose.threed/nurbscurve) | NURBS 曲线是由 NURBS（非均匀有理基样条）表示的曲线。NURBS 曲线由其阶次、加权的 Geometry.ControlPoints 集合以及 KnotVectors 定义。控制点中的 w 分量用作控制点的权重，无论它是 CurveDimension.TWO_DIMENSIONAL 还是 CurveDimension.THREE_DIMENSIONAL。 |
| [NurbsDirection](../aspose.threed/nurbsdirection) | 3D NurbsSurface 有两个方向，NurbsSurface.U 和 NurbsSurface.V，NurbsDirection 为每个方向定义数据。方向实际上是一条 NURBS 曲线，这意味着它也由阶次、KnotVectors 和一组加权控制点（在 NurbsSurface 中定义）决定。 |
| [NurbsSurface](../aspose.threed/nurbssurface) | NurbsSurface 是由 NURBS（非均匀有理基样条）表示的曲面。NurbsSurface 由两个 NurbsDirectionU 和 V 定义。控制点中的 w 分量用作控制点的权重，无论该方向的类型是 CurveDimension.TWO_DIMENSIONAL 还是 CurveDimension.THREE_DIMENSIONAL。 |
| [ObjLoadOptions](../aspose.threed/objloadoptions) | Wavefront OBJ 的加载选项 |
| [ObjSaveOptions](../aspose.threed/objsaveoptions) | Wavefront OBJ 文件的保存选项 |
| [ParameterizedProfile](../aspose.threed/parameterizedprofile) | 所有参数化截面的基类。 @hideconstructor |
| [ParseException](../aspose.threed/parseexception) | Aspose.3D 解析输入失败时抛出的异常。 |
| [Patch](../aspose.threed/patch) | Patch 是一种参数化建模曲面，类似于 NurbsSurface，它也由两个 PatchDirection（U 和 V）定义。但 Patch 与 NurbsSurface 的区别在于 PatchDirection 曲线可以是 PatchDirectionType.BEZIER、PatchDirectionType.QUADRATIC_BEZIER、PatchDirectionType.BASIS_SPLINE、PatchDirectionType.CARDINAL_SPLINE 和 PatchDirectionType.LINEAR 中的一种。 |
| [PatchDirection](../aspose.threed/patchdirection) | Patch 的 U 和 V 方向。 |
| [PbrMaterial](../aspose.threed/pbrmaterial) | 基于 albedo 颜色/金属度/粗糙度的物理渲染材质 |
| [PbrSpecularMaterial](../aspose.threed/pbrspecularmaterial) | 基于漫反射颜色/高光/光泽度的物理渲染材质 |
| [PdfFormat](../aspose.threed/pdfformat) | Adobe 的可移植文档格式  @hideconstructor |
| [PdfLoadOptions](../aspose.threed/pdfloadoptions) | PDF 加载选项 |
| [PdfSaveOptions](../aspose.threed/pdfsaveoptions) | PDF 导出时的保存选项。 |
| [PhongMaterial](../aspose.threed/phongmaterial) | Blinn-Phong 着色模型的材质。 |
| [PixelMapping](../aspose.threed/pixelmapping) | @hideconstructor |
| [Plane](../aspose.threed/plane) | 参数化平面。 |
| [PlyFormat](../aspose.threed/plyformat) | PLY 格式。  @hideconstructor |
| [PlyLoadOptions](../aspose.threed/plyloadoptions) | PLY 文件的加载选项 |
| [PlySaveOptions](../aspose.threed/plysaveoptions) | 将场景导出为 PLY 文件的保存选项。 |
| [PointCloud](../aspose.threed/pointcloud) | 点云不包含拓扑信息，仅包含控制点和顶点元素。 |
| [PolygonBuilder](../aspose.threed/polygonbuilder) | 用于为 Mesh 构建多边形的辅助类 |
| [PolygonModifier](../aspose.threed/polygonmodifier) | 修改多边形的实用工具  @hideconstructor |
| [Pose](../aspose.threed/pose) | 姿势用于在几何体进行蒙皮时存储变换矩阵。姿势是一组 BonePose，每个 BonePose 保存骨骼节点的具体变换信息。 |
| [PostProcessing](../aspose.threed/postprocessing) | 后处理效果  @hideconstructor |
| [Primitive](../aspose.threed/primitive) | 所有基元的基类 |
| [Profile](../aspose.threed/profile) | xy 平面中的 2D 剖面  @hideconstructor |
| [Property](../aspose.threed/property) | 用于保存用户自定义属性的类。  @hideconstructor |
| [PropertyCollection](../aspose.threed/propertycollection) | 属性集合  @hideconstructor |
| [PushConstant](../aspose.threed/pushconstant) | 通过推送常量向着色器提供数据的实用工具。 |
| [Pyramid](../aspose.threed/pyramid) | 参数化金字塔。 |
| [Quaternion](../aspose.threed/quaternion) | 四元数通常用于在计算机图形学中执行旋转。 |
| [Rect](../aspose.threed/rect) | 用于表示矩形的类 |
| [RectangleShape](../aspose.threed/rectangleshape) | 兼容 IFC 的带圆角矩形形状。 |
| [RectangularTorus](../aspose.threed/rectangulartorus) | 参数化矩形环面。 |
| [RelativeRectangle](../aspose.threed/relativerectangle) | 相对矩形  相对组件到绝对值的公式为：  Scale (Reference Width) + offset  因此如果我们想让它表示绝对值，请将所有 scale 字段设为零，并改用 offset 字段。 |
| [Renderer](../aspose.threed/renderer) | 关于渲染器的上下文。  @hideconstructor |
| [RendererVariableManager](../aspose.threed/renderervariablemanager) | 此类管理渲染中使用的变量  @hideconstructor |
| [RenderFactory](../aspose.threed/renderfactory) | RenderFactory 创建渲染管线中表示的所有资源。  @hideconstructor |
| [RenderParameters](../aspose.threed/renderparameters) | 描述渲染目标的参数 |
| [RenderResource](../aspose.threed/renderresource) | 所有渲染资源的抽象类  当渲染器释放时，所有渲染资源将被处理。  类如 Mesh/Texture 将拥有相应的 RenderResource  @hideconstructor |
| [RenderState](../aspose.threed/renderstate) | 用于构建管线的渲染状态  对渲染状态所做的更改不会影响已创建的管线实例。 |
| [RevolvedAreaSolid](../aspose.threed/revolvedareasolid) | 此类通过围绕轴旋转由轮廓提供的横截面来表示实体模型。 |
| [RvmFormat](../aspose.threed/rvmformat) | RVM 格式  @hideconstructor |
| [RvmLoadOptions](../aspose.threed/rvmloadoptions) | AVEVA Plant Design Management System 的 RVM 文件的加载选项。 |
| [RvmSaveOptions](../aspose.threed/rvmsaveoptions) | Aveva PDMS RVM 文件的保存选项。 |
| [SaveOptions](../aspose.threed/saveoptions) | 用于配置不同类型文件保存选项的基类  @hideconstructor |
| [Scene](../aspose.threed/scene) | 场景是一个顶层对象，包含节点、几何体、材质、纹理、动画、姿态、子场景等。 场景可以拥有子场景，在 collada/blender/fbx 等文件中充当多文档支持。 可以通过 RootNodeLibrary 访问节点层次结构，RootNodeLibrary 用于在序列化期间保存未关联对象的引用（如元数据或自定义对象），以便将其用作库。 |
| [SceneObject](../aspose.threed/sceneobject) | 将在场景内部存储的对象的根类。 |
| [ShaderException](../aspose.threed/shaderexception) | 着色器相关异常 |
| [ShaderMaterial](../aspose.threed/shadermaterial) | 着色器材质允许通过外部渲染引擎或着色器语言来描述材质。ShaderMaterial 使用 ShaderTechnique 来描述具体的渲染细节，并且会根据最终渲染平台选择最合适的实现。例如，您的 ShaderMaterial 实例可以拥有两种 technique，一种由 HLSL 定义，另一种由 GLSL 定义。在非 Windows 平台下应使用 GLSL 而不是 HLSL。 |
| [ShaderProgram](../aspose.threed/shaderprogram) | 着色器程序  @hideconstructor |
| [ShaderSet](../aspose.threed/shaderset) | 针对每种材质的着色器程序 |
| [ShaderSource](../aspose.threed/shadersource) | 着色器的源代码  @hideconstructor |
| [ShaderTechnique](../aspose.threed/shadertechnique) | Shader technique 表示具体的渲染实现。 |
| [ShaderVariable](../aspose.threed/shadervariable) | 着色器变量 |
| [Shape](../aspose.threed/shape) | 形状描述了一组控制点上的变形，类似于 Maya 中的 cluster deformer。例如，我们可以向已创建的几何体添加一个形状。该形状与几何体拥有相同的拓扑信息，但控制点的位置不同。通过不同程度的影响，几何体产生变形效果。 |
| [Skeleton](../aspose.threed/skeleton) | Skeleton主要用于CAD软件，帮助设计师操作骨骼结构的变换，在CAD软件之外通常无用。为了使骨骼层级在CAD软件中表现为一个对象，需要通过将Type设置为SkeletonType.SKELETON将顶部Skeleton节点标记为根节点，并将所有子节点设置为SkeletonType.BONE。 |
| [SkinDeformer](../aspose.threed/skindeformer) | 皮肤变形器包含多个骨骼工作，每个骨骼通过控制点的权重混合几何体的一部分。 |
| [Sphere](../aspose.threed/sphere) | 参数化球体。 |
| [SPIRVSource](../aspose.threed/spirvsource) | 以SPIR-V格式编译的着色器。 |
| [StencilState](../aspose.threed/stencilstate) | 每个面的模板状态。  @hideconstructor |
| [StlLoadOptions](../aspose.threed/stlloadoptions) | STL的加载选项 |
| [StlSaveOptions](../aspose.threed/stlsaveoptions) | STL的保存选项 |
| [SweptAreaSolid](../aspose.threed/sweptareasolid) | SweptAreaSolid通过沿导线扫掠轮廓来构建几何体。 |
| [Text](../aspose.threed/text) | 文本轮廓，该轮廓使用字体和文字描述轮廓。 |
| [Texture](../aspose.threed/texture) | 此类定义来自外部文件的纹理。 |
| [TextureBase](../aspose.threed/texturebase) | 所有具体纹理的基类。Texture定义几何表面的外观和质感。 |
| [TextureCodec](../aspose.threed/texturecodec) | 用于管理纹理的编码器和解码器的类。 |
| [TextureData](../aspose.threed/texturedata) | 此类包含纹理的原始数据和格式定义。 |
| [TextureSlot](../aspose.threed/textureslot) | Material中的纹理槽，可通过材质实例枚举。  @hideconstructor |
| [Torus](../aspose.threed/torus) | 参数化环面。 |
| [Transform](../aspose.threed/transform) | 变换包含允许以最小开销访问对象的平移/缩放/旋转或变换矩阵的信息，这用于局部变换。  @hideconstructor |
| [TransformBuilder](../aspose.threed/transformbuilder) | TransformBuilder用于通过一系列变换构建变换矩阵。 |
| [TransformedCurve](../aspose.threed/transformedcurve) | TransformedCurve通过使用变换矩阵为曲线提供位置，这允许在TrimmedCurve或CompositeCurve内部执行变换。 |
| [TrapeziumShape](../aspose.threed/trapeziumshape) | 符合IFC的梯形形状，由参数定义。 |
| [TrialException](../aspose.threed/trialexception) | 当未应用许可证时，在Scene.Open/Scene.Save中会抛出此异常。可以通过将SuppressTrialException设置为true来关闭此异常。 |
| [TriMesh](../aspose.threed/trimesh) | TriMesh包含可直接由GPU使用的原始数据。此类是一个实用工具，帮助构建仅包含每顶点数据的网格。 |
| [TrimmedCurve](../aspose.threed/trimmedcurve) | 在两端修剪基曲线的有界曲线。 |
| [TShape](../aspose.threed/tshape) | 符合IFC的T形，由参数定义。 |
| [U3dLoadOptions](../aspose.threed/u3dloadoptions) | 通用3D的加载选项 |
| [U3dSaveOptions](../aspose.threed/u3dsaveoptions) | 通用3D的保存选项 |
| [UsdSaveOptions](../aspose.threed/usdsaveoptions) | USD/USDZ 格式的保存选项。 |
| [UShape](../aspose.threed/ushape) | 由参数定义的兼容 IFC 的 U 形。 |
| [Vector2](../aspose.threed/vector2) | 具有两个分量的向量。 |
| [Vector3](../aspose.threed/vector3) | 具有三个分量的向量。 |
| [Vector4](../aspose.threed/vector4) | 具有四个分量的向量。 |
| [Vertex](../aspose.threed/vertex) | Vertex 引用，用于访问 TriMesh 中的原始顶点。  @hideconstructor |
| [VertexDeclaration](../aspose.threed/vertexdeclaration) | 自定义顶点结构的声明 |
| [VertexElement](../aspose.threed/vertexelement) | vertex 元素的基类。  vertex 元素类型由 VertexElementType 标识。  VertexElement 描述 vertex 元素如何映射到几何表面以及映射信息在内存中的排列方式。  VertexElement 包含 Normals、UVs 或其他类型的信息。  @hideconstructor |
| [VertexElementBinormal](../aspose.threed/vertexelementbinormal) | 为指定的组件定义副法线向量。 |
| [VertexElementDoublesTemplate](../aspose.threed/vertexelementdoublestemplate) | 用于定义具体 VertexElement 实现的辅助类。  @hideconstructor |
| [VertexElementEdgeCrease](../aspose.threed/vertexelementedgecrease) | 为指定的组件定义边缘折痕。 |
| [VertexElementHole](../aspose.threed/vertexelementhole) | 定义指定多边形是否为孔洞。 |
| [VertexElementIntsTemplate](../aspose.threed/vertexelementintstemplate) | 用于定义具体 VertexElement 实现的辅助类。  @hideconstructor |
| [VertexElementMaterial](../aspose.threed/vertexelementmaterial) | 为指定的组件定义材质索引。  一个节点可以拥有多种材质，VertexElementMaterial 用于在不同材质下渲染几何体的不同部分。 |
| [VertexElementNormal](../aspose.threed/vertexelementnormal) | 为指定的组件定义法线向量。 |
| [VertexElementPolygonGroup](../aspose.threed/vertexelementpolygongroup) | 为指定的组件定义多边形组，以将相关多边形归为一组。 |
| [VertexElementSmoothingGroup](../aspose.threed/vertexelementsmoothinggroup) | 平滑组是多边形网格中的一组多边形，应该呈现出光滑的表面。一些早期的 3D 建模软件，如 DOS 版 3D studio max，使用平滑组来避免为每个网格顶点存储法线向量。 |
| [VertexElementSpecular](../aspose.threed/vertexelementspecular) | 为指定的组件定义高光颜色。 |
| [VertexElementTangent](../aspose.threed/vertexelementtangent) | 为指定的组件定义切线向量。 |
| [VertexElementUserData](../aspose.threed/vertexelementuserdata) | 为指定的组件定义自定义用户数据。 通常是针对特定应用的专用数据。 |
| [VertexElementUV](../aspose.threed/vertexelementuv) | 为指定的组件定义 UV 坐标。 一个几何体可以拥有多个 VertexElementUV 元素，每个元素都有不同的 TextureMappings。 |
| [VertexElementVector4](../aspose.threed/vertexelementvector4) | 用于定义具体 VertexElement 实现的辅助类。  @hideconstructor |
| [VertexElementVertexColor](../aspose.threed/vertexelementvertexcolor) | 为指定的组件定义顶点颜色 |
| [VertexElementVertexCrease](../aspose.threed/vertexelementvertexcrease) | 为指定的组件定义顶点折痕 |
| [VertexElementVisibility](../aspose.threed/vertexelementvisibility) | 定义指定的组件是否可见 |
| [VertexElementWeight](../aspose.threed/vertexelementweight) | 为指定的组件定义混合权重。 |
| [VertexField](../aspose.threed/vertexfield) | Vertex 字段的内存布局描述。  @hideconstructor |
| [Viewport](../aspose.threed/viewport) | 一个 com.aspose.threed.IRenderTarget 包含至少一个用于渲染场景的视口。  @hideconstructor |
| [Watermark](../aspose.threed/watermark) | 用于对盲水印进行编码/解码到/从网格的实用工具。  @hideconstructor |
| [WindowHandle](../aspose.threed/windowhandle) | 针对不同平台的封装窗口句柄。  @hideconstructor |
| [XLoadOptions](../aspose.threed/xloadoptions) | DirectX X 文件的加载选项。 |
| [ZipArchiveFileSystem](../aspose.threed/ziparchivefilesystem) | 文件系统用于提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。 |
| [ZShape](../aspose.threed/zshape) | 由参数定义的符合 IFC 标准的 Z 形截面。 |
| [CubeFace](../aspose.threed/cubeface) | 包含常量的实用类。  立方体贴图纹理的每个面  @hideconstructor |
| [IndexDataType](../aspose.threed/indexdatatype) | 包含常量的实用类。  com.aspose.threed.IIndexBuffer 中元素的数据类型  @hideconstructor |
