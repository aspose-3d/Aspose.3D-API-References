---
title: aspose.threed
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
keywords: "Aspose.3D for Node.js via Java, Aspose.3D, STL, OBJ, Aspose API Reference."
type: docs
weight: 10
url: /fr/nodejs-java/aspose.threed/
---


## Classes

| Classe | Description |
| --- | --- |
| [A3DObject](../aspose.threed/a3dobject) | La classe de base de tous les objets Aspose.ThreeD, toutes les sous‑classes prendront en charge les propriétés dynamiques. |
| [A3dwSaveOptions](../aspose.threed/a3dwsaveoptions) | Options d'enregistrement pour le format A3DW. |
| [AmfSaveOptions](../aspose.threed/amfsaveoptions) | Options d'enregistrement pour AMF |
| [AnimationChannel](../aspose.threed/animationchannel) | Un canal mappe le champ de composant d'une propriété à un ensemble de séquences d'images clés  @hideconstructor |
| [AnimationClip](../aspose.threed/animationclip) | Le clip d'animation est une collection d'animations.  La scène peut contenir un ou plusieurs clips d'animation. |
| [AnimationNode](../aspose.threed/animationnode) | Aspose.3D prend en charge la hiérarchie d'animation, chaque animation pouvant être composée de plusieurs animations et de la définition des images clés d'animation.  AnimationNode définit la transformation d'une valeur de propriété au fil du temps, par exemple, le nœud d'animation peut être utilisé pour contrôler la transformation d'un nœud ou d'autres propriétés numériques d'un objet A3DObject. |
| [ArbitraryProfile](../aspose.threed/arbitraryprofile) | Cette classe vous permet de construire un profil 2D directement à partir d'une courbe arbitraire. |
| [AssetInfo](../aspose.threed/assetinfo) | Informations sur l'actif.  Les informations d'actif peuvent être attachées à une scène.  Une scène enfant peut avoir son propre AssetInfo pour remplacer la définition du parent. |
| [BindPoint](../aspose.threed/bindpoint) | Un BindPoint est généralement créé sur la propriété d'un objet, certains types de propriétés contiennent plusieurs champs de composant (comme un champ Vector3),  BindPoint générera un canal pour chaque champ de composant et connectera le champ à une ou plusieurs instances de séquence d'images clés via les canaux. |
| [Bone](../aspose.threed/bone) | Un os définit le sous-ensemble des points de contrôle de la géométrie et définit le poids de mélange pour chaque point de contrôle.  L'objet Bone ne peut pas être utilisé directement, une instance de SkinDeformer est utilisée pour déformer la géométrie, et SkinDeformer est fourni avec un ensemble d'os, chaque os étant lié à un nœud.  NOTE : Un point de contrôle d'une géométrie peut être lié à plusieurs os. |
| [BonePose](../aspose.threed/bonepose) | Le BonePose contient la matrice de transformation d'un nœud os. |
| [BoundingBox](../aspose.threed/boundingbox) | La boîte englobante alignée sur les axes |
| [BoundingBox2D](../aspose.threed/boundingbox2d) | La boîte englobante alignée sur les axes pour Vector2 |
| [Box](../aspose.threed/box) | Boîte. |
| [Camera](../aspose.threed/camera) | La caméra décrit le point de vue de l'observateur regardant la scène. |
| [Circle](../aspose.threed/circle) | Une courbe circulaire se compose d'un ensemble de points sur le bord de la forme circulaire. |
| [CircleShape](../aspose.threed/circleshape) | Profil circulaire compatible IFC, qui peut être utilisé pour construire un maillage via LinearExtrusion |
| [ColladaSaveOptions](../aspose.threed/colladasaveoptions) | Options d'enregistrement pour collada |
| [CompositeCurve](../aspose.threed/compositecurve) | Une CompositeCurve est constituée de plusieurs segments de courbe. |
| [CShape](../aspose.threed/cshape) | Profil en forme de C compatible IFC défini par des paramètres.  La position centrale du profil se trouve au centre de la boîte englobante. |
| [Curve](../aspose.threed/curve) | La classe de base de toutes les implémentations de courbes.  @hideconstructor |
| [CustomObject](../aspose.threed/customobject) | Les métadonnées ou objets personnalisés utilisés dans les fichiers 3D sont gérés par cette classe.  Toutes les propriétés personnalisées sont enregistrées en tant que propriétés dynamiques. |
| [Cylinder](../aspose.threed/cylinder) | Cylindre paramétré.  Il peut également être utilisé pour représenter le cône lorsqu'un des rayons radiusTop/radiusBottom est nul. |
| [Deformer](../aspose.threed/deformer) | Classe de base pour SkinDeformer et MorphTargetDeformer |
| [DescriptorSetUpdater](../aspose.threed/descriptorsetupdater) | Cette classe permet de mettre à jour le com.aspose.threed.IDescriptorSet dans une opération en chaîne.  @hideconstructor |
| [Discreet3dsLoadOptions](../aspose.threed/discreet3dsloadoptions) | Options de chargement pour le fichier 3DS. |
| [Discreet3dsSaveOptions](../aspose.threed/discreet3dssaveoptions) | Options d'enregistrement pour le fichier 3DS. |
| [Dish](../aspose.threed/dish) | Plat paramétré. |
| [DracoFormat](../aspose.threed/dracoformat) | Format Google Draco  @hideconstructor |
| [DracoSaveOptions](../aspose.threed/dracosaveoptions) | Options d'enregistrement pour les fichiers Google draco |
| [DriverException](../aspose.threed/driverexception) | L'exception levée par les pilotes de rendu internes.  @hideconstructor |
| [DummyFileSystem](../aspose.threed/dummyfilesystem) | Les opérations de lecture/écriture sont des opérations factices. |
| [Ellipse](../aspose.threed/ellipse) | Une ellipse définit un ensemble de points qui forment la forme d'une ellipse. |
| [EllipseShape](../aspose.threed/ellipseshape) | Forme d'ellipse compatible IFC définie par des paramètres. La position centrale du profil se trouve au centre de la boîte englobante. |
| [EndPoint](../aspose.threed/endpoint) | Le point final pour tronquer la courbe, peut être une valeur de paramètre ou un point cartésien. |
| [Entity](../aspose.threed/entity) | La classe de base de toutes les entités. Entity représente un objet concret qui est attaché sous un nœud tel que Light/Geometry. |
| [EntityRenderer](../aspose.threed/entityrenderer) | Sous-classez ceci pour implémenter le rendu pour différents types d'entités. |
| [EntityRendererKey](../aspose.threed/entityrendererkey) | La clé du rendu d'entité enregistré |
| [ExportException](../aspose.threed/exportexception) | Exceptions lorsque Aspose.3D n'a pas pu exporter la scène vers le fichier |
| [Extrapolation](../aspose.threed/extrapolation) | Extrapolation définit comment procéder lorsque la valeur échantillonnée est hors de la plage définie par les première et dernière images clés.  @hideconstructor |
| [FbxLoadOptions](../aspose.threed/fbxloadoptions) | Options de chargement pour le format Fbx. |
| [FbxSaveOptions](../aspose.threed/fbxsaveoptions) | Options d'enregistrement pour le fichier Fbx. |
| [FileFormat](../aspose.threed/fileformat) | Définition du format de fichier  @hideconstructor |
| [FileFormatType](../aspose.threed/fileformattype) | Type de format de fichier  @hideconstructor |
| [FileSystem](../aspose.threed/filesystem) | Encapsulation du système de fichiers. Aspose.3D utilisera cela pour lire/écrire les dépendances.  @hideconstructor |
| [FMatrix4](../aspose.threed/fmatrix4) | Matrice 4x4 avec tous les composants de type flottant |
| [FontFile](../aspose.threed/fontfile) | Le fichier de police contient les définitions des glyphes, il est utilisé pour créer le profil de texte.  @hideconstructor |
| [Frustum](../aspose.threed/frustum) | La classe de base de Camera et Light  @hideconstructor |
| [FVector2](../aspose.threed/fvector2) | Un vecteur flottant à deux composants. |
| [FVector3](../aspose.threed/fvector3) | Un vecteur flottant à trois composants. |
| [FVector4](../aspose.threed/fvector4) | Un vecteur flottant à quatre composants. |
| [Geometry](../aspose.threed/geometry) | La classe de base de tous les objets géométriques rendables (comme Mesh, NurbsSurface, Patch, etc.). La classe de base Geometry prend en charge : la gestion des points de contrôle, les points de contrôle définissent la structure spatiale 3D de base de la géométrie, les différents types géométriques ont des manières différentes de définir des modèles 3D concrets. La définition des éléments de sommet, les éléments de sommet appliquent des informations supplémentaires telles que les normales, les coordonnées UV ou les couleurs de sommet à la géométrie, voir VertexElement pour plus de détails. Déformation d'objet, le Deformer peut être lié pour animer la forme de la géométrie. |
| [GlobalTransform](../aspose.threed/globaltransform) | La transformation globale est similaire à Transform mais elle est immutable tout en représentant la transformation finale évaluée. Un système de coordonnées droit est utilisé lors de l'évaluation de la transformation globale  @hideconstructor |
| [GLSLSource](../aspose.threed/glslsource) | Le code source des shaders en GLSL |
| [GltfLoadOptions](../aspose.threed/gltfloadoptions) | Options de chargement pour le format glTF |
| [GltfSaveOptions](../aspose.threed/gltfsaveoptions) | Options d'enregistrement pour le format glTF. |
| [HollowCircleShape](../aspose.threed/hollowcircleshape) | Profil circulaire creux compatible IFC. |
| [HollowRectangleShape](../aspose.threed/hollowrectangleshape) | Forme rectangulaire creuse compatible IFC avec des coins arrondis intérieurs/extérieurs. |
| [HShape](../aspose.threed/hshape) | Le HShape fournit les paramètres définissant une forme en 'H' ou en 'I'. |
| [Html5SaveOptions](../aspose.threed/html5saveoptions) | Options d'enregistrement pour HTML5 |
| [ImageRenderOptions](../aspose.threed/imagerenderoptions) | Options pour Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) et Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions) |
| [ImportException](../aspose.threed/importexception) | Exception lorsque Aspose.3D n'a pas pu ouvrir la source spécifiée |
| [InitializationException](../aspose.threed/initializationexception) | Exceptions lors de l'initialisation du pipeline de rendu |
| [IOConfig](../aspose.threed/ioconfig) | Configuration d'E/S pour la sérialisation/désérialisation. L'utilisateur peut spécifier des configurations détaillées comme le chemin de recherche des dépendances ou les configurations liées au format ici  @hideconstructor |
| [IOUtils](../aspose.threed/ioutils) | Utilitaires pour écrire une matrice/vec­teur dans un écrivain binaire  @hideconstructor |
| [KeyFrame](../aspose.threed/keyframe) | Une image clé est principalement définie par un temps et une valeur ; pour certains types d'interpolation, la tangente, la tension, le biais et la continuité sont également utilisés pour calculer la valeur échantillonnée finale. Les valeurs échantillonnées à un moment qui n'est pas une image clé sont interpolées par les images clés situées entre l'image clé précédente et suivante. Les valeurs avant/après la première/dernière image clé sont calculées par la classe Extrapolation. |
| [KeyframeSequence](../aspose.threed/keyframesequence) | La séquence d'images clés décrit la transformation d'une valeur échantillonnée au fil du temps. |
| [LambertMaterial](../aspose.threed/lambertmaterial) | Matériau pour le modèle d'éclairage Lambert |
| [License](../aspose.threed/license) | Fournit des méthodes pour licencier le composant. |
| [Light](../aspose.threed/light) | La lumière éclaire la scène. La formule pour calculer l'atténuation totale de la lumière est : A = ConstantAttenuation + (Dist × LinearAttenuation) + ((Dist^2) × QuadraticAttenuation) |
| [Line](../aspose.threed/line) | Une polyligne est un chemin défini par un ensemble de points avec Geometry.ControlPoints, et reliés par des Segments, ce qui signifie qu'elle peut également être un ensemble de segments de ligne connectés. La ligne est généralement un objet linéaire, ce qui signifie qu'elle ne peut pas être utilisée pour représenter une courbe ; pour représenter une courbe, utilisez NurbsCurve. |
| [LinearExtrusion](../aspose.threed/linearextrusion) | L'extrusion linéaire prend une forme 2D en entrée et étend la forme dans la troisième dimension. |
| [LoadOptions](../aspose.threed/loadoptions) | La classe de base pour configurer les options de chargement de fichiers selon différents types  @hideconstructor |
| [LocalFileSystem](../aspose.threed/localfilesystem) | Le LocalFileSystem mappe les opérations de lecture/écriture vers le répertoire local. |
| [LShape](../aspose.threed/lshape) | Profil en forme de L compatible IFC défini par des paramètres. |
| [Material](../aspose.threed/material) | Material définit les paramètres nécessaires à l'apparence visuelle de la géométrie. Aspose.3D fournit des modèles d'ombrage pour LambertMaterial, PhongMaterial et ShaderMaterial  @hideconstructor |
| [MathUtils](../aspose.threed/mathutils) | Un ensemble d'utilitaires mathématiques utiles.  @hideconstructor |
| [Matrix4](../aspose.threed/matrix4) | Implémentation de matrice 4x4. |
| [MemoryFileSystem](../aspose.threed/memoryfilesystem) | Le MemoryFileSystem mappe les opérations de lecture/écriture vers la mémoire. |
| [Mesh](../aspose.threed/mesh) | Un maillage est composé de nombreux polygones à n côtés. |
| [Metered](../aspose.threed/metered) | Fournit des méthodes pour définir la clé mesurée. |
| [MirroredProfile](../aspose.threed/mirroredprofile) | Profil miroir compatible IFC. Ce profil définit un nouveau profil en reflétant le profil de base par rapport à l'axe y. |
| [MorphTargetChannel](../aspose.threed/morphtargetchannel) | Un MorphTargetChannel est utilisé par MorphTargetDeformer pour organiser les géométries cibles. Certains formats de fichier comme FBX prennent en charge plusieurs canaux en parallèle. Le poids est compris entre 0 et 1,0, et le poids par défaut pour la cible est 0,0 ; |
| [MorphTargetDeformer](../aspose.threed/morphtargetdeformer) | MorphTargetDeformer fournit une animation par sommet. MorphTargetDeformer organise toutes les cibles via MorphTargetChannel, chaque canal pouvant organiser plusieurs cibles. Une utilisation courante du déformeur de cibles morphologiques est d'appliquer des expressions faciales à un personnage. Plus de détails sont disponibles sur https://en.wikipedia.org/wiki/Morph_target_animation |
| [Node](../aspose.threed/node) | Représente un élément du graphe de scène. Un graphe de scène est un arbre d'objets Node. Les services de gestion d'arbre sont autonomes dans cette classe. Notez que le SDK Aspose.3D ne teste pas la validité du graphe de scène construit. Il incombe à l'appelant de s'assurer qu'il ne génère pas de graphes cycliques dans une hiérarchie de nœuds. En plus de la gestion d'arbre, cette classe définit toutes les propriétés nécessaires pour décrire la position de l'objet dans la scène. Ces informations incluent les propriétés de base Translation, Rotation et Scaling ainsi que les options avancées pour les pivots, limites et les attributs des articulations IK tels que la rigidité et l'amortissement. Lorsqu'il est créé pour la première fois, l'objet Node est "vide" (c.-à-d. il s'agit d'un objet sans représentation graphique qui ne contient que les informations de position). Dans cet état, il peut être utilisé pour représenter des parents dans la structure d'arbre de nœuds mais pas bien plus. L'utilisation normale de ce type d'objets consiste à leur ajouter une entité qui spécialisera le nœud (voir "Entity"). L'entité est un objet à part entière et est connectée au Node. Cela signifie également que la même entité peut être partagée entre plusieurs nœuds. Camera, Light, Mesh, etc. sont toutes des entités et toutes dérivent de la classe de base Entity. |
| [NurbsCurve](../aspose.threed/nurbscurve) | La courbe NURBS est une courbe représentée par NURBS (Non-uniform rational basis spline). Une courbe NURBS est définie par son Order, un ensemble de Geometry.ControlPoints pondérés et des KnotVectors. Le composant w du point de contrôle est utilisé comme poids du point de contrôle, que ce soit un CurveDimension.TWO_DIMENSIONAL ou CurveDimension.THREE_DIMENSIONAL. |
| [NurbsDirection](../aspose.threed/nurbsdirection) | Une NurbsSurface 3D possède deux directions, NurbsSurface.U et NurbsSurface.V ; le NurbsDirection définit les données pour chaque direction. Une direction est en fait une courbe NURBS, ce qui signifie qu'elle est également définie par son Order, des KnotVectors et un ensemble de points de contrôle pondérés (définis dans NurbsSurface). |
| [NurbsSurface](../aspose.threed/nurbssurface) | NurbsSurface est une surface représentée par NURBS (Non-uniform rational basis spline). Une NurbsSurface est définie par deux NurbsDirectionU et V. Le composant w du point de contrôle est utilisé comme poids du point de contrôle, quel que soit le type de la direction, CurveDimension.TWO_DIMENSIONAL ou CurveDimension.THREE_DIMENSIONAL. |
| [ObjLoadOptions](../aspose.threed/objloadoptions) | Options de chargement pour wavefront obj |
| [ObjSaveOptions](../aspose.threed/objsaveoptions) | Options d'enregistrement pour le fichier wavefront obj |
| [ParameterizedProfile](../aspose.threed/parameterizedprofile) | La classe de base de tous les profils paramétrés.  @hideconstructor |
| [ParseException](../aspose.threed/parseexception) | Exception lorsque Aspose.3D n'a pas pu analyser l'entrée. |
| [Patch](../aspose.threed/patch) | Un Patch est une surface de modélisation paramétrique, similaire à NurbsSurface, elle est également définie par deux PatchDirection, le U et le V. Mais la différence entre Patch et NurbsSurface est que la courbe PatchDirection peut être l'un des types PatchDirectionType.BEZIER, PatchDirectionType.QUADRATIC_BEZIER, PatchDirectionType.BASIS_SPLINE, PatchDirectionType.CARDINAL_SPLINE ou PatchDirectionType.LINEAR. |
| [PatchDirection](../aspose.threed/patchdirection) | Direction U et V du Patch. |
| [PbrMaterial](../aspose.threed/pbrmaterial) | Matériau pour le rendu physiquement basé sur la couleur d'albédo/métallique/rugosité |
| [PbrSpecularMaterial](../aspose.threed/pbrspecularmaterial) | Matériau pour le rendu physiquement basé sur la couleur diffuse/speculaire/brillance |
| [PdfFormat](../aspose.threed/pdfformat) | Format de document portable d'Adobe  @hideconstructor |
| [PdfLoadOptions](../aspose.threed/pdfloadoptions) | Options de chargement PDF |
| [PdfSaveOptions](../aspose.threed/pdfsaveoptions) | Les options d'enregistrement lors de l'exportation PDF. |
| [PhongMaterial](../aspose.threed/phongmaterial) | Matériau pour le modèle d'éclairage Blinn-Phong. |
| [PixelMapping](../aspose.threed/pixelmapping) | @hideconstructor |
| [Plane](../aspose.threed/plane) | Plan paramétré. |
| [PlyFormat](../aspose.threed/plyformat) | Le format PLY.  @hideconstructor |
| [PlyLoadOptions](../aspose.threed/plyloadoptions) | Options de chargement pour les fichiers PLY |
| [PlySaveOptions](../aspose.threed/plysaveoptions) | Options d'enregistrement pour exporter la scène au format PLY. |
| [PointCloud](../aspose.threed/pointcloud) | Le nuage de points ne contient aucune information de topologie, seulement les points de contrôle et les éléments de sommet. |
| [PolygonBuilder](../aspose.threed/polygonbuilder) | Une classe d'aide pour construire des polygones pour Mesh |
| [PolygonModifier](../aspose.threed/polygonmodifier) | Utilitaires pour modifier les polygones  @hideconstructor |
| [Pose](../aspose.threed/pose) | La pose est utilisée pour stocker la matrice de transformation lorsque la géométrie est skinnée. La pose est un ensemble de BonePose, chaque BonePose enregistre les informations concrètes de transformation du nœud os. |
| [PostProcessing](../aspose.threed/postprocessing) | Les effets de post-traitement  @hideconstructor |
| [Primitive](../aspose.threed/primitive) | Classe de base pour toutes les primitives |
| [Profile](../aspose.threed/profile) | Profil 2D dans le plan xy  @hideconstructor |
| [Property](../aspose.threed/property) | Classe pour contenir des propriétés définies par l'utilisateur.  @hideconstructor |
| [PropertyCollection](../aspose.threed/propertycollection) | La collection de propriétés  @hideconstructor |
| [PushConstant](../aspose.threed/pushconstant) | Un utilitaire pour fournir des données au shader via une constante push. |
| [Pyramid](../aspose.threed/pyramid) | Pyramide paramétrée. |
| [Quaternion](../aspose.threed/quaternion) | Le quaternion est généralement utilisé pour effectuer des rotations en infographie. |
| [Rect](../aspose.threed/rect) | Une classe pour représenter le rectangle |
| [RectangleShape](../aspose.threed/rectangleshape) | Forme rectangulaire compatible IFC avec des coins arrondis. |
| [RectangularTorus](../aspose.threed/rectangulartorus) | Tore rectangulaire paramétré. |
| [RelativeRectangle](../aspose.threed/relativerectangle) | Rectangle relatif  La formule entre le composant relatif et la valeur absolue est :  Échelle  (Largeur de référence) + décalage  Ainsi, si l'on veut qu'il représente une valeur absolue, laissez tous les champs d'échelle à zéro et utilisez les champs de décalage à la place. |
| [Renderer](../aspose.threed/renderer) | Le contexte du rendu.  @hideconstructor |
| [RendererVariableManager](../aspose.threed/renderervariablemanager) | Cette classe gère les variables utilisées dans le rendu  @hideconstructor |
| [RenderFactory](../aspose.threed/renderfactory) | RenderFactory crée toutes les ressources représentées dans le pipeline de rendu.  @hideconstructor |
| [RenderParameters](../aspose.threed/renderparameters) | Décrivez les paramètres de la cible de rendu |
| [RenderResource](../aspose.threed/renderresource) | La classe abstraite de toutes les ressources de rendu. Toutes les ressources de rendu seront libérées lorsque le moteur de rendu sera relâché. Des classes comme Mesh/Texture auront une RenderResource correspondante  @hideconstructor |
| [RenderState](../aspose.threed/renderstate) | État de rendu pour la construction du pipeline. Les modifications apportées à l'état de rendu n'affecteront pas les instances de pipeline créées. |
| [RevolvedAreaSolid](../aspose.threed/revolvedareasolid) | Cette classe représente un modèle solide en faisant tourner une section transversale fournie par un profil autour d'un axe. |
| [RvmFormat](../aspose.threed/rvmformat) | Le format RVM  @hideconstructor |
| [RvmLoadOptions](../aspose.threed/rvmloadoptions) | Options de chargement pour le fichier RVM du système de gestion de conception d'usine AVEVA. |
| [RvmSaveOptions](../aspose.threed/rvmsaveoptions) | Options d'enregistrement pour le fichier RVM Aveva PDMS. |
| [SaveOptions](../aspose.threed/saveoptions) | La classe de base pour configurer les options d'enregistrement de fichiers pour différents types  @hideconstructor |
| [Scene](../aspose.threed/scene) | Une scène est un objet de niveau supérieur qui contient les nœuds, géométries, matériaux, textures, animations, poses, sous‑scènes, etc. Une scène peut avoir des sous‑scènes, servant de prise en charge multi‑document dans des fichiers tels que collada/blender/fbx. La hiérarchie des nœuds peut être accédée via RootNodeLibrary, qui est utilisé pour conserver une référence des objets détachés pendant la sérialisation (comme les métadonnées ou objets personnalisés) afin de pouvoir les utiliser comme bibliothèque. |
| [SceneObject](../aspose.threed/sceneobject) | La classe racine des objets qui seront stockés dans une scène. |
| [ShaderException](../aspose.threed/shaderexception) | Exceptions liées aux shaders |
| [ShaderMaterial](../aspose.threed/shadermaterial) | Un matériau de shader permet de décrire le matériau via un moteur de rendu externe ou un langage de shader. ShaderMaterial utilise ShaderTechnique pour décrire les détails concrets du rendu, et la technique la plus adaptée sera utilisée en fonction de la plateforme de rendu finale. Par exemple, votre instance de ShaderMaterial peut avoir deux techniques, l'une définie par HLSL et l'autre définie par GLSL. Sur les plateformes non Windows, le GLSL doit être utilisé à la place du HLSL. |
| [ShaderProgram](../aspose.threed/shaderprogram) | Le programme de shader  @hideconstructor |
| [ShaderSet](../aspose.threed/shaderset) | Programmes de shader pour chaque type de matériau |
| [ShaderSource](../aspose.threed/shadersource) | Le code source du shader  @hideconstructor |
| [ShaderTechnique](../aspose.threed/shadertechnique) | Une technique de shader représente une implémentation de rendu concrète. |
| [ShaderVariable](../aspose.threed/shadervariable) | Variable de shader |
| [Shape](../aspose.threed/shape) | La forme décrit la déformation d'un ensemble de points de contrôle, ce qui est similaire au déformateur de cluster dans Maya.  Par exemple, nous pouvons ajouter une forme à une géométrie créée.  Et la forme et la géométrie possèdent les mêmes informations topologiques mais des positions différentes des points de contrôle.  Avec des quantités d'influence variables, la géométrie produit un effet de déformation. |
| [Skeleton](../aspose.threed/skeleton) | Le squelette est principalement utilisé par les logiciels CAD pour aider le concepteur à manipuler la transformation de la structure squelettique, il est généralement inutile en dehors des logiciels CAD.  Pour que la hiérarchie du squelette agisse comme un seul objet dans le logiciel CAD, il est nécessaire de marquer le nœud squelette supérieur comme racine en définissant le Type sur SkeletonType.SKELETON,  et tous les enfants sur SkeletonType.BONE. |
| [SkinDeformer](../aspose.threed/skindeformer) | Un déformateur de peau contient plusieurs os pour fonctionner, chaque os mélange une partie de la géométrie selon les poids des points de contrôle. |
| [Sphere](../aspose.threed/sphere) | Sphère paramétrée. |
| [SPIRVSource](../aspose.threed/spirvsource) | Le shader compilé au format SPIR‑V. |
| [StencilState](../aspose.threed/stencilstate) | États de pochoir par face.  @hideconstructor |
| [StlLoadOptions](../aspose.threed/stlloadoptions) | Options de chargement pour STL |
| [StlSaveOptions](../aspose.threed/stlsaveoptions) | Options d'enregistrement pour STL |
| [SweptAreaSolid](../aspose.threed/sweptareasolid) | Un SweptAreaSolid construit une géométrie en balayant un profil le long d'une directrice. |
| [Text](../aspose.threed/text) | Profil texte, ce profil décrit les contours en utilisant la police et le texte. |
| [Texture](../aspose.threed/texture) | Cette classe définit la texture à partir d’un fichier externe. |
| [TextureBase](../aspose.threed/texturebase) | Classe de base pour toutes les textures concrètes.  Texture définit l'apparence et la sensation d'une surface de géométrie. |
| [TextureCodec](../aspose.threed/texturecodec) | Classe pour gérer les encodeurs et décodeurs de textures. |
| [TextureData](../aspose.threed/texturedata) | Cette classe contient les données brutes et la définition du format d’une texture. |
| [TextureSlot](../aspose.threed/textureslot) | Emplacement de texture dans Material, peut être énuméré via l'instance de matériau.  @hideconstructor |
| [Torus](../aspose.threed/torus) | Tore paramétré. |
| [Transform](../aspose.threed/transform) | Une transformation contient des informations qui permettent d'accéder à la translation/échelle/rotation de l'objet ou à la matrice de transformation avec un coût minimal.  Ceci est utilisé par la transformation locale.  @hideconstructor |
| [TransformBuilder](../aspose.threed/transformbuilder) | Le TransformBuilder est utilisé pour construire une matrice de transformation à l'aide d'une chaîne de transformations. |
| [TransformedCurve](../aspose.threed/transformedcurve) | Une TransformedCurve place une courbe en utilisant une matrice de transformation.  Cela permet d'effectuer une transformation à l'intérieur d'une TrimmedCurve ou d'une CompositeCurve. |
| [TrapeziumShape](../aspose.threed/trapeziumshape) | Forme trapézoïdale compatible IFC définie par des paramètres. |
| [TrialException](../aspose.threed/trialexception) | Cela est levé dans Scene.Open/Scene.Save lorsqu'aucune licence n'est appliquée.  Vous pouvez désactiver cette exception en définissant SuppressTrialException sur true. |
| [TriMesh](../aspose.threed/trimesh) | Un TriMesh contient des données brutes qui peuvent être utilisées directement par le GPU.  Cette classe est un utilitaire pour aider à construire un maillage ne contenant que des données par sommet. |
| [TrimmedCurve](../aspose.threed/trimmedcurve) | Une courbe bornée qui coupe la courbe de base aux deux extrémités. |
| [TShape](../aspose.threed/tshape) | Forme en T compatible IFC définie par des paramètres. |
| [U3dLoadOptions](../aspose.threed/u3dloadoptions) | Options de chargement pour le 3D universel |
| [U3dSaveOptions](../aspose.threed/u3dsaveoptions) | Options d’enregistrement pour le 3D universel |
| [UsdSaveOptions](../aspose.threed/usdsaveoptions) | Options d’enregistrement pour les formats USD/USDZ. |
| [UShape](../aspose.threed/ushape) | Forme en U compatible IFC définie par des paramètres. |
| [Vector2](../aspose.threed/vector2) | Un vecteur à deux composantes. |
| [Vector3](../aspose.threed/vector3) | Un vecteur à trois composantes. |
| [Vector4](../aspose.threed/vector4) | Un vecteur à quatre composantes. |
| [Vertex](../aspose.threed/vertex) | Référence de sommet, utilisée pour accéder au sommet brut dans TriMesh.  @hideconstructor |
| [VertexDeclaration](../aspose.threed/vertexdeclaration) | La déclaration de la structure d'un sommet défini sur mesure |
| [VertexElement](../aspose.threed/vertexelement) | Classe de base des éléments de sommet.  Un type d'élément de sommet est identifié par VertexElementType.  Un VertexElement décrit comment l'élément de sommet est mappé sur une surface de géométrie et comment les informations de mappage sont organisées en mémoire.  Un VertexElement contient des normales, des UV ou d'autres types d'informations.  @hideconstructor |
| [VertexElementBinormal](../aspose.threed/vertexelementbinormal) | Définit les vecteurs binormaux pour les composants spécifiés. |
| [VertexElementDoublesTemplate](../aspose.threed/vertexelementdoublestemplate) | Une classe d'aide pour définir des implémentations concrètes de VertexElement.  @hideconstructor |
| [VertexElementEdgeCrease](../aspose.threed/vertexelementedgecrease) | Définit le pli de bord pour les composants spécifiés |
| [VertexElementHole](../aspose.threed/vertexelementhole) | Définit si le polygone spécifié est un trou |
| [VertexElementIntsTemplate](../aspose.threed/vertexelementintstemplate) | Une classe d'aide pour définir des implémentations concrètes de VertexElement.  @hideconstructor |
| [VertexElementMaterial](../aspose.threed/vertexelementmaterial) | Définit l'index du matériau pour les composants spécifiés.  Un nœud peut avoir plusieurs matériaux, le VertexElementMaterial est utilisé pour rendre différentes parties de la géométrie avec différents matériaux. |
| [VertexElementNormal](../aspose.threed/vertexelementnormal) | Définit les vecteurs normaux pour les composants spécifiés. |
| [VertexElementPolygonGroup](../aspose.threed/vertexelementpolygongroup) | Définit le groupe de polygones pour les composants spécifiés afin de regrouper les polygones associés. |
| [VertexElementSmoothingGroup](../aspose.threed/vertexelementsmoothinggroup) | Un groupe de lissage est un groupe de polygones dans un maillage polygonal qui doit apparaître comme une surface lisse.  Certains logiciels de modélisation 3D anciens comme 3D Studio Max pour DOS utilisaient le groupe de lissage pour éviter de stocker le vecteur normal pour chaque sommet du maillage. |
| [VertexElementSpecular](../aspose.threed/vertexelementspecular) | Définit la couleur spéculaire pour les composants spécifiés. |
| [VertexElementTangent](../aspose.threed/vertexelementtangent) | Définit les vecteurs tangents pour les composants spécifiés. |
| [VertexElementUserData](../aspose.threed/vertexelementuserdata) | Définit des données utilisateur personnalisées pour les composants spécifiés.  Généralement, il s'agit de données spécifiques à l'application pour un usage spécial. |
| [VertexElementUV](../aspose.threed/vertexelementuv) | Définit les coordonnées UV pour les composants spécifiés.  Une géométrie peut avoir plusieurs éléments VertexElementUV, et chacun possède des TextureMappings différents. |
| [VertexElementVector4](../aspose.threed/vertexelementvector4) | Une classe d'aide pour définir des implémentations concrètes de VertexElement.  @hideconstructor |
| [VertexElementVertexColor](../aspose.threed/vertexelementvertexcolor) | Définit la couleur du sommet pour les composants spécifiés |
| [VertexElementVertexCrease](../aspose.threed/vertexelementvertexcrease) | Définit le pli du sommet pour les composants spécifiés |
| [VertexElementVisibility](../aspose.threed/vertexelementvisibility) | Définit si les composants spécifiés sont visibles |
| [VertexElementWeight](../aspose.threed/vertexelementweight) | Définit le poids de mélange pour les composants spécifiés. |
| [VertexField](../aspose.threed/vertexfield) | Description de la disposition mémoire du champ du sommet.  @hideconstructor |
| [Viewport](../aspose.threed/viewport) | Un com.aspose.threed.IRenderTarget contient au moins une fenêtre d'affichage pour le rendu de la scène.  @hideconstructor |
| [Watermark](../aspose.threed/watermark) | Utilitaire pour encoder/décoder un filigrane invisible vers/à partir d'un maillage.  @hideconstructor |
| [WindowHandle](../aspose.threed/windowhandle) | Gestionnaire de fenêtre encapsulé pour différentes plateformes.  @hideconstructor |
| [XLoadOptions](../aspose.threed/xloadoptions) | Les options de chargement pour les fichiers DirectX X. |
| [ZipArchiveFileSystem](../aspose.threed/ziparchivefilesystem) | Système de fichiers fournissant un accès en lecture seule au fichier zip ou au flux zip spécifié.  Le système de fichiers sera libéré après l'opération d'ouverture/enregistrement. |
| [ZShape](../aspose.threed/zshape) | Profil en forme de Z compatible IFC défini par des paramètres. |
| [CubeFace](../aspose.threed/cubeface) | Classe utilitaire contenant des constantes.  Chaque face de la texture de la carte cubique  @hideconstructor |
| [IndexDataType](../aspose.threed/indexdatatype) | Classe utilitaire contenant des constantes.  Le type de données des éléments dans com.aspose.threed.IIndexBuffer  @hideconstructor |
