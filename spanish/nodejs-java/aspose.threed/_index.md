---
title: "aspose.threed"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
keywords: "Aspose.3D for Node.js via Java, Aspose.3D, STL, OBJ, Aspose API Reference."
type: docs
weight: 10
url: /es/nodejs-java/aspose.threed/
---


## Clases

| Clase | Descripción |
| --- | --- |
| [A3DObject](../aspose.threed/a3dobject) | La clase base de todos los objetos Aspose.ThreeD, todas las subclases admitirán propiedades dinámicas. |
| [A3dwSaveOptions](../aspose.threed/a3dwsaveoptions) | Opciones de guardado para el formato A3DW. |
| [AmfSaveOptions](../aspose.threed/amfsaveoptions) | Opciones de guardado para AMF |
| [AnimationChannel](../aspose.threed/animationchannel) | Un canal asigna el campo componente de una propiedad a un conjunto de secuencias de fotogramas clave  @hideconstructor |
| [AnimationClip](../aspose.threed/animationclip) | El clip de Animación es una colección de animaciones.  La escena puede tener uno o más clips de animación. |
| [AnimationNode](../aspose.threed/animationnode) | Aspose.3D admite jerarquía de animación, cada animación puede estar compuesta por varias animaciones y la definición de fotogramas clave de la animación.  AnimationNode define la transformación del valor de una propiedad a lo largo del tiempo, por ejemplo, el nodo de animación puede usarse para controlar la transformación de un nodo o otras propiedades numéricas del objeto A3DObject. |
| [ArbitraryProfile](../aspose.threed/arbitraryprofile) | Esta clase le permite construir un perfil 2D directamente a partir de una curva arbitraria. |
| [AssetInfo](../aspose.threed/assetinfo) | Información del activo.  La información del activo puede adjuntarse a una Escena.  La Escena hija puede tener su propio AssetInfo para sobrescribir la definición del padre. |
| [BindPoint](../aspose.threed/bindpoint) | Un BindPoint suele crearse en la propiedad de un objeto, algunos tipos de propiedad contienen múltiples campos componentes (como un campo Vector3),  BindPoint generará un canal para cada campo componente y conectará el campo a una o más instancias de secuencia de fotogramas clave a través de los canales. |
| [Bone](../aspose.threed/bone) | Un hueso define el subconjunto del punto de control de la geometría y el peso de mezcla definido para cada punto de control.  El objeto Bone no puede usarse directamente, se utiliza una instancia de SkinDeformer para deformar la geometría, y SkinDeformer viene con un conjunto de huesos, cada hueso vinculado a un nodo.  NOTA: Un punto de control de una geometría puede estar vinculado a más de un Bone. |
| [BonePose](../aspose.threed/bonepose) | El BonePose contiene la matriz de transformación para un nodo de hueso |
| [BoundingBox](../aspose.threed/boundingbox) | El cuadro delimitador alineado a los ejes |
| [BoundingBox2D](../aspose.threed/boundingbox2d) | El cuadro delimitador alineado a los ejes para Vector2 |
| [Box](../aspose.threed/box) | Caja. |
| [Camera](../aspose.threed/camera) | La cámara describe el punto de vista del observador que mira la escena. |
| [Circle](../aspose.threed/circle) | Una curva Círculo consiste en un conjunto de puntos en el borde de la forma circular. |
| [CircleShape](../aspose.threed/circleshape) | Perfil de círculo compatible con IFC, que puede usarse para construir una malla mediante LinearExtrusion |
| [ColladaSaveOptions](../aspose.threed/colladasaveoptions) | Opciones de guardado para collada |
| [CompositeCurve](../aspose.threed/compositecurve) | Un CompositeCurve está compuesto por varios segmentos de curva. |
| [CShape](../aspose.threed/cshape) | Perfil en forma de C compatible con IFC definido por parámetros. La posición central del perfil está en el centro del cuadro delimitador. |
| [Curve](../aspose.threed/curve) | La clase base de todas las implementaciones de curvas.  @hideconstructor |
| [CustomObject](../aspose.threed/customobject) | Los metadatos o objetos personalizados utilizados en archivos 3D son gestionados por esta clase. Todas las propiedades personalizadas se guardan como propiedades dinámicas. |
| [Cylinder](../aspose.threed/cylinder) | Cilindro parametrizado. También puede usarse para representar el cono cuando uno de radiusTop/radiusBottom es cero. |
| [Deformer](../aspose.threed/deformer) | Clase base para SkinDeformer y MorphTargetDeformer |
| [DescriptorSetUpdater](../aspose.threed/descriptorsetupdater) | Esta clase permite actualizar el com.aspose.threed.IDescriptorSet en una operación en cadena.  @hideconstructor |
| [Discreet3dsLoadOptions](../aspose.threed/discreet3dsloadoptions) | Opciones de carga para archivo 3DS. |
| [Discreet3dsSaveOptions](../aspose.threed/discreet3dssaveoptions) | Opciones de guardado para archivo 3DS. |
| [Dish](../aspose.threed/dish) | Plato parametrizado. |
| [DracoFormat](../aspose.threed/dracoformat) | Formato Google Draco  @hideconstructor |
| [DracoSaveOptions](../aspose.threed/dracosaveoptions) | Opciones de guardado para archivos Google draco |
| [DriverException](../aspose.threed/driverexception) | La excepción generada por los controladores internos de renderizado.  @hideconstructor |
| [DummyFileSystem](../aspose.threed/dummyfilesystem) | Las operaciones de lectura/escritura son operaciones ficticias. |
| [Ellipse](../aspose.threed/ellipse) | Una Elipse define un conjunto de puntos que forman la forma de una elipse. |
| [EllipseShape](../aspose.threed/ellipseshape) | Forma de elipse compatible con IFC definida por parámetros. La posición central del perfil está en el centro del cuadro delimitador. |
| [EndPoint](../aspose.threed/endpoint) | El punto final para recortar la curva, puede ser un valor de parámetro o un punto cartesiano. |
| [Entity](../aspose.threed/entity) | La clase base de todas las entidades.  Entity representa un objeto concreto que está adjunto bajo un nodo como Light/Geometry. |
| [EntityRenderer](../aspose.threed/entityrenderer) | Subclase esto para implementar renderizado para diferentes tipos de entidades. |
| [EntityRendererKey](../aspose.threed/entityrendererkey) | La clave del renderizador de entidad registrado |
| [ExportException](../aspose.threed/exportexception) | Excepciones cuando Aspose.3D no pudo exportar la escena a un archivo |
| [Extrapolation](../aspose.threed/extrapolation) | La extrapolación define qué hacer cuando el valor muestreado está fuera del rango definido por los primeros y últimos fotogramas clave.  @hideconstructor |
| [FbxLoadOptions](../aspose.threed/fbxloadoptions) | Opciones de carga para formato Fbx. |
| [FbxSaveOptions](../aspose.threed/fbxsaveoptions) | Opciones de guardado para archivo Fbx. |
| [FileFormat](../aspose.threed/fileformat) | Definición del formato de archivo  @hideconstructor |
| [FileFormatType](../aspose.threed/fileformattype) | Tipo de formato de archivo  @hideconstructor |
| [FileSystem](../aspose.threed/filesystem) | Encapsulación del sistema de archivos.  Aspose.3D usará esto para leer/escribir dependencias.  @hideconstructor |
| [FMatrix4](../aspose.threed/fmatrix4) | Matriz 4x4 con todos los componentes en tipo flotante |
| [FontFile](../aspose.threed/fontfile) | El archivo de fuente contiene definiciones de glifos, se usa para crear el perfil de texto.  @hideconstructor |
| [Frustum](../aspose.threed/frustum) | La clase base de Cámara y Luz  @hideconstructor |
| [FVector2](../aspose.threed/fvector2) | Un vector flotante con dos componentes. |
| [FVector3](../aspose.threed/fvector3) | Un vector flotante con tres componentes. |
| [FVector4](../aspose.threed/fvector4) | Un vector flotante con cuatro componentes. |
| [Geometry](../aspose.threed/geometry) | La clase base de todos los objetos geométricos renderizables (como Mesh, NurbsSurface, Patch, etc.).  La clase base Geometry admite:  Gestión de puntos de control, los puntos de control definen la estructura espacial 3D base de la geometría; los diferentes tipos geométricos tienen diferentes formas de definir modelos 3D concretos. Definición de elementos de vértice, los elementos de vértice aplican información adicional como normales, coordenadas uv o colores de vértice a la geometría; vea VertexElement para más detalles. Deformación de objetos, Deformer puede enlazarse para animar la forma de la geometría. |
| [GlobalTransform](../aspose.threed/globaltransform) | La transformación global es similar a Transform pero es inmutable mientras representa la transformación final evaluada.  Se utiliza un sistema de coordenadas de mano derecha al evaluar la transformación global  @hideconstructor |
| [GLSLSource](../aspose.threed/glslsource) | El código fuente de los shaders en GLSL |
| [GltfLoadOptions](../aspose.threed/gltfloadoptions) | Opciones de carga para el formato glTF |
| [GltfSaveOptions](../aspose.threed/gltfsaveoptions) | Opciones de guardado para el formato glTF. |
| [HollowCircleShape](../aspose.threed/hollowcircleshape) | Perfil circular hueco compatible con IFC. |
| [HollowRectangleShape](../aspose.threed/hollowrectangleshape) | Forma rectangular hueca compatible con IFC con esquinas redondeadas internas/externas. |
| [HShape](../aspose.threed/hshape) | HShape proporciona los parámetros definitorios de una forma 'H' o 'I'. |
| [Html5SaveOptions](../aspose.threed/html5saveoptions) | Opciones de guardado para HTML5 |
| [ImageRenderOptions](../aspose.threed/imagerenderoptions) | Opciones para Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) y Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions) |
| [ImportException](../aspose.threed/importexception) | Excepción cuando Aspose.3D no pudo abrir la fuente especificada |
| [InitializationException](../aspose.threed/initializationexception) | Excepciones en la inicialización del pipeline de renderizado |
| [IOConfig](../aspose.threed/ioconfig) | Configuración de E/S para serialización/deserialización.  El usuario puede especificar configuraciones detalladas como la ruta de búsqueda de dependencias  o configuraciones relacionadas con el formato aquí  @hideconstructor |
| [IOUtils](../aspose.threed/ioutils) | Utilidades para escribir matrices/vectores en un escritor binario  @hideconstructor |
| [KeyFrame](../aspose.threed/keyframe) | Un fotograma clave se define principalmente por un tiempo y un valor; para algunos tipos de interpolación, también se utilizan tangente/ tensión/ sesgo/ continuidad al calcular el valor muestreado final.  Los valores muestreados en una posición de tiempo sin fotograma clave se interpolan mediante fotogramas clave entre el fotograma clave anterior y el siguiente.  Los valores antes/después del primer/último fotograma clave se calculan con la clase Extrapolation. |
| [KeyframeSequence](../aspose.threed/keyframesequence) | La secuencia de fotogramas clave, describe la transformación de un valor muestreado a lo largo del tiempo. |
| [LambertMaterial](../aspose.threed/lambertmaterial) | Material para el modelo de sombreado Lambert |
| [License](../aspose.threed/license) | Proporciona métodos para licenciar el componente. |
| [Light](../aspose.threed/light) | La luz ilumina la escena.  La fórmula para calcular la atenuación total de la luz es:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation) |
| [Line](../aspose.threed/line) | Una polilínea es una ruta definida por un conjunto de puntos con Geometry.ControlPoints, y conectada por Segments, lo que significa que también puede ser un conjunto de segmentos de línea conectados. La línea suele ser un objeto lineal, lo que significa que no puede usarse para representar una curva; para representar una curva, se utiliza NurbsCurve. |
| [LinearExtrusion](../aspose.threed/linearextrusion) | La extrusión lineal toma una forma 2D como entrada y extiende la forma en la tercera dimensión. |
| [LoadOptions](../aspose.threed/loadoptions) | La clase base para configurar opciones en la carga de archivos para diferentes tipos  @hideconstructor |
| [LocalFileSystem](../aspose.threed/localfilesystem) | El LocalFileSystem asignará las operaciones de lectura/escritura al directorio local. |
| [LShape](../aspose.threed/lshape) | Perfil en forma de L compatible con IFC que se define mediante parámetros. |
| [Material](../aspose.threed/material) | Material define los parámetros necesarios para la apariencia visual de la geometría.  Aspose.3D proporciona modelos de sombreado para LambertMaterial, PhongMaterial y ShaderMaterial  @hideconstructor |
| [MathUtils](../aspose.threed/mathutils) | Un conjunto de utilidades matemáticas útiles.  @hideconstructor |
| [Matrix4](../aspose.threed/matrix4) | Implementación de matriz 4x4. |
| [MemoryFileSystem](../aspose.threed/memoryfilesystem) | El MemoryFileSystem asignará las operaciones de lectura/escritura a la memoria. |
| [Mesh](../aspose.threed/mesh) | Una malla está compuesta por muchos polígonos de n lados. |
| [Metered](../aspose.threed/metered) | Proporciona métodos para establecer la clave medida. |
| [MirroredProfile](../aspose.threed/mirroredprofile) | Perfil espejo compatible con IFC.  Este perfil define un nuevo perfil al reflejar el perfil base respecto al eje y. |
| [MorphTargetChannel](../aspose.threed/morphtargetchannel) | Un MorphTargetChannel es utilizado por MorphTargetDeformer para organizar las geometrías objetivo. Algunos formatos de archivo como FBX admiten múltiples canales en paralelo. El peso está entre 0 y 1.0, y el peso predeterminado para el objetivo es 0.0; |
| [MorphTargetDeformer](../aspose.threed/morphtargetdeformer) | MorphTargetDeformer proporciona animación por vértice. MorphTargetDeformer organiza todos los objetivos a través de MorphTargetChannel, cada canal puede organizar múltiples objetivos. Un uso común del deformador de objetivos de morfología es aplicar expresiones faciales a un personaje. Más detalles pueden encontrarse en https://en.wikipedia.org/wiki/Morph_target_animation |
| [Node](../aspose.threed/node) | Representa un elemento en el grafo de escena. Un grafo de escena es un árbol de objetos Node. Los servicios de gestión del árbol están contenidos en esta clase. Nota: el SDK Aspose.3D no verifica la validez del grafo de escena construido. Es responsabilidad del llamador asegurarse de que no genere grafos cíclicos en una jerarquía de nodos. Además de la gestión del árbol, esta clase define todas las propiedades necesarias para describir la posición del objeto en la escena. Esta información incluye las propiedades básicas de Translación, Rotación y Escalado, y las opciones más avanzadas para pivotes, límites y atributos de articulaciones IK como la rigidez y el amortiguamiento. Cuando se crea por primera vez, el objeto Node está "empty" (es decir, es un objeto sin representación gráfica que solo contiene la información de posición). En este estado, puede usarse para representar padres en la estructura del árbol de nodos pero no mucho más. El uso normal de este tipo de objetos es añadirles una entidad que especializará el nodo (ver "Entity"). La entidad es un objeto por sí misma y está conectada al Node. Esto también significa que la misma entidad puede compartirse entre varios nodos. Cámara, Luz, Malla, etc... son todas entidades y todas derivan de la clase base Entity. |
| [NurbsCurve](../aspose.threed/nurbscurve) | Una curva NURBS es una curva representada por NURBS (Non-uniform rational basis spline). Una curva NURBS se define por su Order, un conjunto de Geometry.ControlPoints ponderados y un KnotVectors. El componente w en el punto de control se usa como peso del punto de control, sea que sea CurveDimension.TWO_DIMENSIONAL o CurveDimension.THREE_DIMENSIONAL. |
| [NurbsDirection](../aspose.threed/nurbsdirection) | Una NurbsSurface 3D tiene dos direcciones, NurbsSurface.U y NurbsSurface.V; NurbsDirection define los datos para cada dirección. Una dirección es en realidad una curva NURBS, lo que significa que también se define por su Order, un KnotVectors y un conjunto de puntos de control ponderados (definidos en NurbsSurface). |
| [NurbsSurface](../aspose.threed/nurbssurface) | NurbsSurface es una superficie representada por NURBS (Non-uniform rational basis spline). Una NurbsSurface se define por dos NurbsDirectionU y V. El componente w en el punto de control se usa como peso del punto de control, sea que el tipo de dirección sea CurveDimension.TWO_DIMENSIONAL o CurveDimension.THREE_DIMENSIONAL. |
| [ObjLoadOptions](../aspose.threed/objloadoptions) | Opciones de carga para wavefront obj |
| [ObjSaveOptions](../aspose.threed/objsaveoptions) | Opciones de guardado para archivo wavefront obj |
| [ParameterizedProfile](../aspose.threed/parameterizedprofile) | La clase base de todos los perfiles parametrizados.  @hideconstructor |
| [ParseException](../aspose.threed/parseexception) | Excepción cuando Aspose.3D no pudo analizar la entrada. |
| [Patch](../aspose.threed/patch) | Un Patch es una superficie de modelado paramétrico, similar a NurbsSurface, también está definida por dos PatchDirection, la U y la V. Pero la diferencia entre Patch y NurbsSurface es que la curva PatchDirection puede ser una de PatchDirectionType.BEZIER, PatchDirectionType.QUADRATIC_BEZIER, PatchDirectionType.BASIS_SPLINE, PatchDirectionType.CARDINAL_SPLINE y PatchDirectionType.LINEAR |
| [PatchDirection](../aspose.threed/patchdirection) | Dirección U y V del Patch. |
| [PbrMaterial](../aspose.threed/pbrmaterial) | Material para renderizado físicamente basado en color albedo/metallic/roughness |
| [PbrSpecularMaterial](../aspose.threed/pbrspecularmaterial) | Material para renderizado físicamente basado en color difuso/specular/glossiness |
| [PdfFormat](../aspose.threed/pdfformat) | Formato de Documento Portátil de Adobe  @hideconstructor |
| [PdfLoadOptions](../aspose.threed/pdfloadoptions) | Opciones para cargar PDF |
| [PdfSaveOptions](../aspose.threed/pdfsaveoptions) | Las opciones de guardado al exportar PDF. |
| [PhongMaterial](../aspose.threed/phongmaterial) | Material para el modelo de sombreado Blinn-Phong. |
| [PixelMapping](../aspose.threed/pixelmapping) | @hideconstructor |
| [Plane](../aspose.threed/plane) | Plano parametrizado. |
| [PlyFormat](../aspose.threed/plyformat) | El formato PLY.  @hideconstructor |
| [PlyLoadOptions](../aspose.threed/plyloadoptions) | Opciones de carga para archivos PLY |
| [PlySaveOptions](../aspose.threed/plysaveoptions) | Opciones de guardado para exportar la escena como archivo PLY. |
| [PointCloud](../aspose.threed/pointcloud) | La nube de puntos no contiene información de topología, solo los puntos de control y los elementos de vértice. |
| [PolygonBuilder](../aspose.threed/polygonbuilder) | Una clase auxiliar para construir polígonos para Mesh |
| [PolygonModifier](../aspose.threed/polygonmodifier) | Utilidades para modificar polígonos  @hideconstructor |
| [Pose](../aspose.threed/pose) | La pose se usa para almacenar la matriz de transformación cuando la geometría está con skinning. La pose es un conjunto de BonePose, cada BonePose guarda la información concreta de transformación del nodo óseo. |
| [PostProcessing](../aspose.threed/postprocessing) | Los efectos de post-procesado  @hideconstructor |
| [Primitive](../aspose.threed/primitive) | Clase base para todas las primitivas |
| [Profile](../aspose.threed/profile) | Perfil 2D en el plano xy  @hideconstructor |
| [Property](../aspose.threed/property) | Clase para contener propiedades definidas por el usuario.  @hideconstructor |
| [PropertyCollection](../aspose.threed/propertycollection) | La colección de propiedades  @hideconstructor |
| [PushConstant](../aspose.threed/pushconstant) | Una utilidad para proporcionar datos al shader mediante push constant. |
| [Pyramid](../aspose.threed/pyramid) | Pirámide parametrizada. |
| [Quaternion](../aspose.threed/quaternion) | El cuaternión se usa normalmente para realizar rotaciones en gráficos por computadora. |
| [Rect](../aspose.threed/rect) | Una clase para representar el rectángulo |
| [RectangleShape](../aspose.threed/rectangleshape) | Forma rectangular compatible con IFC con esquinas redondeadas. |
| [RectangularTorus](../aspose.threed/rectangulartorus) | Toro rectangular parametrizado. |
| [RelativeRectangle](../aspose.threed/relativerectangle) | Rectángulo relativo  La fórmula entre el componente relativo y el valor absoluto es:  Escala  (Ancho de referencia) + desplazamiento  Así que si queremos que represente un valor absoluto, deje todos los campos de escala en cero y use los campos de desplazamiento en su lugar. |
| [Renderer](../aspose.threed/renderer) | El contexto sobre el renderizador.  @hideconstructor |
| [RendererVariableManager](../aspose.threed/renderervariablemanager) | Esta clase gestiona variables usadas en el renderizado  @hideconstructor |
| [RenderFactory](../aspose.threed/renderfactory) | RenderFactory crea todos los recursos que se representan en la canalización de renderizado.  @hideconstructor |
| [RenderParameters](../aspose.threed/renderparameters) | Describe los parámetros del objetivo de renderizado |
| [RenderResource](../aspose.threed/renderresource) | La clase abstracta de todos los recursos de renderizado  Todos los recursos de renderizado se dispondrán cuando se libere el renderizador.  Clases como Mesh/Texture tendrán un RenderResource correspondiente  @hideconstructor |
| [RenderState](../aspose.threed/renderstate) | Estado de renderizado para construir la canalización  Los cambios realizados en el estado de renderizado no afectarán a las instancias de la canalización creadas. |
| [RevolvedAreaSolid](../aspose.threed/revolvedareasolid) | Esta clase representa un modelo sólido al girar una sección transversal proporcionada por un perfil alrededor de un eje. |
| [RvmFormat](../aspose.threed/rvmformat) | El formato RVM  @hideconstructor |
| [RvmLoadOptions](../aspose.threed/rvmloadoptions) | Opciones de carga para el archivo RVM del Sistema de Gestión de Diseño de Plantas AVEVA. |
| [RvmSaveOptions](../aspose.threed/rvmsaveoptions) | Opciones de guardado para el archivo RVM de Aveva PDMS. |
| [SaveOptions](../aspose.threed/saveoptions) | La clase base para configurar opciones al guardar archivos para diferentes tipos  @hideconstructor |
| [Scene](../aspose.threed/scene) | Una escena es un objeto de nivel superior que contiene los nodos, geometrías, materiales, texturas, animaciones, poses, sub-escenas, etc.  La escena puede tener sub-escenas, funciona como soporte de múltiples documentos en archivos como collada/blender/fbx.  La jerarquía de nodos se puede acceder a través de RootNodeLibrary, que se utiliza para mantener una referencia de objetos no adjuntos durante la serialización (como metadatos u objetos personalizados) para que pueda usarse como una biblioteca. |
| [SceneObject](../aspose.threed/sceneobject) | La clase raíz de los objetos que se almacenarán dentro de una escena. |
| [ShaderException](../aspose.threed/shaderexception) | Excepciones relacionadas con shaders |
| [ShaderMaterial](../aspose.threed/shadermaterial) | Un material de shader permite describir el material mediante un motor de renderizado externo o un lenguaje de shader.  ShaderMaterial usa ShaderTechnique para describir los detalles concretos de renderizado, y se utilizará el más adecuado según la plataforma de renderizado final.  Por ejemplo, su instancia de ShaderMaterial puede tener dos técnicas, una definida por HLSL y otra definida por GLSL.  En plataformas sin ventana, se debe usar GLSL en lugar de HLSL. |
| [ShaderProgram](../aspose.threed/shaderprogram) | El programa de shader  @hideconstructor |
| [ShaderSet](../aspose.threed/shaderset) | Programas de shader para cada tipo de material |
| [ShaderSource](../aspose.threed/shadersource) | El código fuente del shader  @hideconstructor |
| [ShaderTechnique](../aspose.threed/shadertechnique) | Una técnica de shader representa una implementación concreta de renderizado. |
| [ShaderVariable](../aspose.threed/shadervariable) | Variable de shader |
| [Shape](../aspose.threed/shape) | La forma describe la deformación en un conjunto de puntos de control, lo cual es similar al deformador de clúster en Maya.  Por ejemplo, podemos añadir una forma a una geometría creada.  Y la forma y la geometría tienen la misma información topológica pero diferentes posiciones de los puntos de control.  Con diferentes niveles de influencia, la geometría produce un efecto de deformación. |
| [Skeleton](../aspose.threed/skeleton) | El esqueleto se usa principalmente en software CAD para ayudar al diseñador a manipular la transformación de la estructura esquelética; suele ser inútil fuera de los softwares CAD. Para que la jerarquía del esqueleto actúe como un solo objeto en el software CAD, es necesario marcar el nodo superior del Skeleton como la raíz estableciendo Type a SkeletonType.SKELETON, y todos los hijos a SkeletonType.BONE. |
| [SkinDeformer](../aspose.threed/skindeformer) | Un deformador de piel contiene múltiples huesos para trabajar, cada hueso mezcla una parte de la geometría mediante los pesos de los puntos de control. |
| [Sphere](../aspose.threed/sphere) | Esfera parametrizada. |
| [SPIRVSource](../aspose.threed/spirvsource) | El shader compilado en formato SPIR-V. |
| [StencilState](../aspose.threed/stencilstate) | Estados de stencil por cara.  @hideconstructor |
| [StlLoadOptions](../aspose.threed/stlloadoptions) | Opciones de carga para STL |
| [StlSaveOptions](../aspose.threed/stlsaveoptions) | Opciones de guardado para STL |
| [SweptAreaSolid](../aspose.threed/sweptareasolid) | Un SweptAreaSolid construye una geometría barrendo un perfil a lo largo de una directriz. |
| [Text](../aspose.threed/text) | Perfil de texto, este perfil describe contornos usando fuente y texto. |
| [Texture](../aspose.threed/texture) | Esta clase define la textura a partir de un archivo externo. |
| [TextureBase](../aspose.threed/texturebase) | Clase base para todas las texturas concretas.  Texture define el aspecto y la sensación de la superficie de una geometría. |
| [TextureCodec](../aspose.threed/texturecodec) | Clase para gestionar codificadores y decodificadores de texturas. |
| [TextureData](../aspose.threed/texturedata) | Esta clase contiene los datos sin procesar y la definición de formato de una textura. |
| [TextureSlot](../aspose.threed/textureslot) | Ranura de textura en Material, puede enumerarse a través de la instancia del material.  @hideconstructor |
| [Torus](../aspose.threed/torus) | Toro parametrizado. |
| [Transform](../aspose.threed/transform) | Una transformación contiene información que permite acceder a la traslación/escala/rotación del objeto o a la matriz de transformación con el coste mínimo.  Esto se usa en la transformación local.  @hideconstructor |
| [TransformBuilder](../aspose.threed/transformbuilder) | El TransformBuilder se usa para construir la matriz de transformación mediante una cadena de transformaciones. |
| [TransformedCurve](../aspose.threed/transformedcurve) | Una TransformedCurve asigna una posición a una curva usando una matriz de transformación.  Esto permite realizar una transformación dentro de una TrimmedCurve o CompositeCurve. |
| [TrapeziumShape](../aspose.threed/trapeziumshape) | Forma de trapecio compatible con IFC definida por parámetros. |
| [TrialException](../aspose.threed/trialexception) | Esto se genera en Scene.Open/Scene.Save cuando no se aplican licencias.  Puedes desactivar esta excepción estableciendo SuppressTrialException a true. |
| [TriMesh](../aspose.threed/trimesh) | Un TriMesh contiene datos sin procesar que pueden ser usados directamente por la GPU.  Esta clase es una utilidad para ayudar a construir una malla que solo contiene datos por vértice. |
| [TrimmedCurve](../aspose.threed/trimmedcurve) | Una curva acotada que recorta la curva base en ambos extremos. |
| [TShape](../aspose.threed/tshape) | Forma en T compatible con IFC definida por parámetros. |
| [U3dLoadOptions](../aspose.threed/u3dloadoptions) | Opciones de carga para universal 3d |
| [U3dSaveOptions](../aspose.threed/u3dsaveoptions) | Opciones de guardado para universal 3d |
| [UsdSaveOptions](../aspose.threed/usdsaveoptions) | Opciones de guardado para formatos USD/USDZ. |
| [UShape](../aspose.threed/ushape) | Forma en U compatible con IFC definida por parámetros. |
| [Vector2](../aspose.threed/vector2) | Un vector con dos componentes. |
| [Vector3](../aspose.threed/vector3) | Un vector con tres componentes. |
| [Vector4](../aspose.threed/vector4) | Un vector con cuatro componentes. |
| [Vertex](../aspose.threed/vertex) | Referencia de vértice, utilizada para acceder al vértice sin procesar en TriMesh.  @hideconstructor |
| [VertexDeclaration](../aspose.threed/vertexdeclaration) | La declaración de la estructura de un vértice definido de forma personalizada |
| [VertexElement](../aspose.threed/vertexelement) | Clase base de elementos de vértice.  Un tipo de elemento de vértice se identifica mediante VertexElementType.  Un VertexElement describe cómo el elemento de vértice se asigna a una superficie geométrica y cómo la información de asignación se organiza en memoria.  Un VertexElement contiene Normales, UVs u otro tipo de información.  @hideconstructor |
| [VertexElementBinormal](../aspose.threed/vertexelementbinormal) | Define los vectores binormales para los componentes especificados. |
| [VertexElementDoublesTemplate](../aspose.threed/vertexelementdoublestemplate) | Una clase auxiliar para definir implementaciones concretas de VertexElement.  @hideconstructor |
| [VertexElementEdgeCrease](../aspose.threed/vertexelementedgecrease) | Define el pliegue del borde para los componentes especificados |
| [VertexElementHole](../aspose.threed/vertexelementhole) | Define si el polígono especificado es un agujero |
| [VertexElementIntsTemplate](../aspose.threed/vertexelementintstemplate) | Una clase auxiliar para definir implementaciones concretas de VertexElement.  @hideconstructor |
| [VertexElementMaterial](../aspose.threed/vertexelementmaterial) | Define el índice de material para los componentes especificados.  Un nodo puede tener múltiples materiales, el VertexElementMaterial se utiliza para renderizar diferentes partes de la geometría con diferentes materiales. |
| [VertexElementNormal](../aspose.threed/vertexelementnormal) | Define los vectores normales para los componentes especificados. |
| [VertexElementPolygonGroup](../aspose.threed/vertexelementpolygongroup) | Define el grupo de polígonos para los componentes especificados para agrupar polígonos relacionados juntos. |
| [VertexElementSmoothingGroup](../aspose.threed/vertexelementsmoothinggroup) | Un grupo de suavizado es un conjunto de polígonos en una malla de polígonos que debería aparecer como una superficie lisa.  Algunos softwares de modelado 3D tempranos, como 3D Studio Max para DOS, utilizaban grupos de suavizado para evitar almacenar el vector normal para cada vértice de la malla. |
| [VertexElementSpecular](../aspose.threed/vertexelementspecular) | Define el color especular para los componentes especificados. |
| [VertexElementTangent](../aspose.threed/vertexelementtangent) | Define los vectores tangentes para los componentes especificados. |
| [VertexElementUserData](../aspose.threed/vertexelementuserdata) | Define datos de usuario personalizados para los componentes especificados.  Normalmente son datos específicos de la aplicación para un propósito especial. |
| [VertexElementUV](../aspose.threed/vertexelementuv) | Define las coordenadas UV para los componentes especificados.  Una geometría puede tener múltiples elementos VertexElementUV, y cada uno tiene diferentes TextureMappings. |
| [VertexElementVector4](../aspose.threed/vertexelementvector4) | Una clase auxiliar para definir implementaciones concretas de VertexElement.  @hideconstructor |
| [VertexElementVertexColor](../aspose.threed/vertexelementvertexcolor) | Define el color del vértice para los componentes especificados |
| [VertexElementVertexCrease](../aspose.threed/vertexelementvertexcrease) | Define el pliegue del vértice para los componentes especificados |
| [VertexElementVisibility](../aspose.threed/vertexelementvisibility) | Define si los componentes especificados son visibles |
| [VertexElementWeight](../aspose.threed/vertexelementweight) | Define el peso de mezcla para los componentes especificados. |
| [VertexField](../aspose.threed/vertexfield) | Descripción del diseño de memoria del campo del vértice.  @hideconstructor |
| [Viewport](../aspose.threed/viewport) | Un com.aspose.threed.IRenderTarget contiene al menos una ventana de visualización para renderizar la escena.  @hideconstructor |
| [Watermark](../aspose.threed/watermark) | Utilidad para codificar/decodificar marca de agua ciega a/de una malla.  @hideconstructor |
| [WindowHandle](../aspose.threed/windowhandle) | Manejador de ventana encapsulado para diferentes plataformas.  @hideconstructor |
| [XLoadOptions](../aspose.threed/xloadoptions) | Las opciones de carga para archivos DirectX X. |
| [ZipArchiveFileSystem](../aspose.threed/ziparchivefilesystem) | Sistema de archivos para proporcionar acceso de solo lectura al archivo zip especificado o al flujo zip.  El sistema de archivos se eliminará después de la operación de abrir/guardar. |
| [ZShape](../aspose.threed/zshape) | Perfil en forma de Z compatible con IFC definido por parámetros. |
| [CubeFace](../aspose.threed/cubeface) | Clase de utilidad que contiene constantes.  Cada cara de la textura del mapa cúbico  @hideconstructor |
| [IndexDataType](../aspose.threed/indexdatatype) | Clase de utilidad que contiene constantes.  El tipo de datos de los elementos en com.aspose.threed.IIndexBuffer  @hideconstructor |
