---
title: "aspose.threed"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
keywords: "Aspose.3D for Node.js via Java, Aspose.3D, STL, OBJ, Aspose API Reference."
type: docs
weight: 10
url: /it/nodejs-java/aspose.threed/
---


## Classi

| Classe | Descrizione |
| --- | --- |
| [A3DObject](../aspose.threed/a3dobject) | La classe base di tutti gli oggetti Aspose.ThreeD, tutte le sottoclassi supporteranno proprietà dinamiche. |
| [A3dwSaveOptions](../aspose.threed/a3dwsaveoptions) | Opzioni di salvataggio per il formato A3DW. |
| [AmfSaveOptions](../aspose.threed/amfsaveoptions) | Opzioni di salvataggio per AMF |
| [AnimationChannel](../aspose.threed/animationchannel) | Un canale mappa il campo componente della proprietà a un insieme di sequenze di fotogrammi chiave  @hideconstructor |
| [AnimationClip](../aspose.threed/animationclip) | Il clip di Animazione è una raccolta di animazioni.  La scena può avere uno o più clip di animazione. |
| [AnimationNode](../aspose.threed/animationnode) | Aspose.3D supporta la gerarchia di animazione, ogni animazione può essere composta da diverse animazioni e dalla definizione dei fotogrammi chiave dell'animazione.  AnimationNode definisce la trasformazione di un valore di proprietà nel tempo, ad esempio, il nodo di animazione può essere usato per controllare la trasformazione di un nodo o altre proprietà numeriche dell'oggetto A3DObject. |
| [ArbitraryProfile](../aspose.threed/arbitraryprofile) | Questa classe consente di costruire un profilo 2D direttamente da una curva arbitraria. |
| [AssetInfo](../aspose.threed/assetinfo) | Informazioni dell'asset.  Le informazioni dell'asset possono essere allegate a una Scena.  Una Scena figlia può avere il proprio AssetInfo per sovrascrivere la definizione del genitore. |
| [BindPoint](../aspose.threed/bindpoint) | Un BindPoint viene solitamente creato su una proprietà di un oggetto, alcuni tipi di proprietà contengono più campi componenti (come un campo Vector3),  BindPoint genererà un canale per ogni campo componente e collega il campo a una o più istanze di sequenza di fotogrammi chiave attraverso i canali. |
| [Bone](../aspose.threed/bone) | Un bone definisce il sottoinsieme dei punti di controllo della geometria e il peso di fusione definito per ogni punto di controllo.  L'oggetto Bone non può essere usato direttamente, un'istanza di SkinDeformer è usata per deformare la geometria, e SkinDeformer viene fornito con un insieme di bones, ciascun bone collegato a un nodo.  NOTA: Un punto di controllo di una geometria può essere associato a più di un Bones. |
| [BonePose](../aspose.threed/bonepose) | Il BonePose contiene la matrice di trasformazione per un nodo bone |
| [BoundingBox](../aspose.threed/boundingbox) | La bounding box allineata agli assi |
| [BoundingBox2D](../aspose.threed/boundingbox2d) | La bounding box allineata agli assi per Vector2 |
| [Box](../aspose.threed/box) | Box. |
| [Camera](../aspose.threed/camera) | La telecamera descrive il punto di vista dell'osservatore che guarda la scena. |
| [Circle](../aspose.threed/circle) | Una curva Circle è composta da un insieme di punti sul bordo della forma circolare. |
| [CircleShape](../aspose.threed/circleshape) | Profilo circolare compatibile IFC, che può essere usato per costruire una mesh tramite LinearExtrusion |
| [ColladaSaveOptions](../aspose.threed/colladasaveoptions) | Opzioni di salvataggio per collada |
| [CompositeCurve](../aspose.threed/compositecurve) | Un CompositeCurve è composto da diversi segmenti di curva. |
| [CShape](../aspose.threed/cshape) | Profilo a forma di C compatibile con IFC definito da parametri. La posizione centrale del profilo è al centro della bounding box. |
| [Curve](../aspose.threed/curve) | La classe base di tutte le implementazioni di curve.  @hideconstructor |
| [CustomObject](../aspose.threed/customobject) | I metadati o gli oggetti personalizzati utilizzati nei file 3D sono gestiti da questa classe. Tutte le proprietà personalizzate sono salvate come proprietà dinamiche. |
| [Cylinder](../aspose.threed/cylinder) | Cilindro parametrizzato. Può anche essere usato per rappresentare il cono quando uno dei valori radiusTop/radiusBottom è zero. |
| [Deformer](../aspose.threed/deformer) | Classe base per SkinDeformer e MorphTargetDeformer |
| [DescriptorSetUpdater](../aspose.threed/descriptorsetupdater) | Questa classe consente di aggiornare il com.aspose.threed.IDescriptorSet in un'operazione a catena.  @hideconstructor |
| [Discreet3dsLoadOptions](../aspose.threed/discreet3dsloadoptions) | Opzioni di caricamento per file 3DS. |
| [Discreet3dsSaveOptions](../aspose.threed/discreet3dssaveoptions) | Opzioni di salvataggio per file 3DS. |
| [Dish](../aspose.threed/dish) | Piatto parametrizzato. |
| [DracoFormat](../aspose.threed/dracoformat) | Formato Google Draco  @hideconstructor |
| [DracoSaveOptions](../aspose.threed/dracosaveoptions) | Opzioni di salvataggio per file Google draco |
| [DriverException](../aspose.threed/driverexception) | L'eccezione sollevata dai driver di rendering interni.  @hideconstructor |
| [DummyFileSystem](../aspose.threed/dummyfilesystem) | Le operazioni di lettura/scrittura sono operazioni fittizie. |
| [Ellipse](../aspose.threed/ellipse) | Un'Ellisse definisce un insieme di punti che formano la forma di un'ellisse. |
| [EllipseShape](../aspose.threed/ellipseshape) | Forma ellittica compatibile con IFC definita da parametri. La posizione centrale del profilo è al centro della bounding box. |
| [EndPoint](../aspose.threed/endpoint) | Il punto finale per tagliare la curva, può essere un valore di parametro o un punto cartesiano. |
| [Entity](../aspose.threed/entity) | La classe base di tutte le entità. Un'entità rappresenta un oggetto concreto che è collegato sotto un nodo come Light/Geometry. |
| [EntityRenderer](../aspose.threed/entityrenderer) | Estendi questa classe per implementare il rendering per diversi tipi di entità. |
| [EntityRendererKey](../aspose.threed/entityrendererkey) | La chiave del renderer di entità registrato |
| [ExportException](../aspose.threed/exportexception) | Eccezioni quando Aspose.3D non riesce a esportare la scena in un file |
| [Extrapolation](../aspose.threed/extrapolation) | L'estrapolazione definisce come procedere quando il valore campionato è fuori dall'intervallo definito dal primo e dall'ultimo fotogramma chiave.  @hideconstructor |
| [FbxLoadOptions](../aspose.threed/fbxloadoptions) | Opzioni di caricamento per formato Fbx. |
| [FbxSaveOptions](../aspose.threed/fbxsaveoptions) | Opzioni di salvataggio per file Fbx. |
| [FileFormat](../aspose.threed/fileformat) | Definizione del formato file  @hideconstructor |
| [FileFormatType](../aspose.threed/fileformattype) | Tipo di formato file  @hideconstructor |
| [FileSystem](../aspose.threed/filesystem) | Incapsulamento del file system.  Aspose.3D utilizzerà questo per leggere/scrivere le dipendenze.  @hideconstructor |
| [FMatrix4](../aspose.threed/fmatrix4) | Matrice 4x4 con tutti i componenti di tipo float |
| [FontFile](../aspose.threed/fontfile) | Il file di font contiene definizioni per i glifi, viene utilizzato per creare il profilo di testo.  @hideconstructor |
| [Frustum](../aspose.threed/frustum) | La classe base di Camera e Light  @hideconstructor |
| [FVector2](../aspose.threed/fvector2) | Un vettore float con due componenti. |
| [FVector3](../aspose.threed/fvector3) | Un vettore float con tre componenti. |
| [FVector4](../aspose.threed/fvector4) | Un vettore float con quattro componenti. |
| [Geometry](../aspose.threed/geometry) | La classe base di tutti gli oggetti geometrici renderizzabili (come Mesh, NurbsSurface, Patch ecc.).  La classe base Geometry supporta:  Gestione dei punti di controllo, i punti di controllo definiscono la struttura spaziale 3D di base della geometria, i diversi tipi geometrici hanno modalità diverse per definire modelli 3D concreti. Definizione degli elementi di vertice, gli elementi di vertice applicano informazioni aggiuntive come normali/coordinate uv/colori dei vertici alla geometria, vedere VertexElement per maggiori dettagli. Deformazione dell'oggetto, Deformer può essere collegato per animare la forma della geometria. |
| [GlobalTransform](../aspose.threed/globaltransform) | La trasformazione globale è simile a Transform ma è immutabile mentre rappresenta la trasformazione finale valutata.  Viene utilizzato un sistema di coordinate destro durante la valutazione della trasformazione globale  @hideconstructor |
| [GLSLSource](../aspose.threed/glslsource) | Il codice sorgente degli shader in GLSL |
| [GltfLoadOptions](../aspose.threed/gltfloadoptions) | Opzioni di caricamento per il formato glTF |
| [GltfSaveOptions](../aspose.threed/gltfsaveoptions) | Opzioni di salvataggio per il formato glTF. |
| [HollowCircleShape](../aspose.threed/hollowcircleshape) | Profilo circolare cavo compatibile IFC. |
| [HollowRectangleShape](../aspose.threed/hollowrectangleshape) | Forma rettangolare cava compatibile IFC con angoli arrotondati interni/esterni. |
| [HShape](../aspose.threed/hshape) | L'HShape fornisce i parametri di definizione di una forma a 'H' o 'I'. |
| [Html5SaveOptions](../aspose.threed/html5saveoptions) | Opzioni di salvataggio per HTML5 |
| [ImageRenderOptions](../aspose.threed/imagerenderoptions) | Opzioni per Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) e  Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions) |
| [ImportException](../aspose.threed/importexception) | Eccezione quando Aspose.3D non è riuscito ad aprire la sorgente specificata |
| [InitializationException](../aspose.threed/initializationexception) | Eccezioni nell'inizializzazione della pipeline di rendering |
| [IOConfig](../aspose.threed/ioconfig) | Configurazione IO per serializzazione/deserializzazione.  L'utente può specificare configurazioni dettagliate come il percorso di ricerca delle dipendenze  O configurazioni correlate al formato qui  @hideconstructor |
| [IOUtils](../aspose.threed/ioutils) | Utility per scrivere matrici/vettori su un binary writer  @hideconstructor |
| [KeyFrame](../aspose.threed/keyframe) | Un key frame è principalmente definito da un tempo e un valore; per alcuni tipi di interpolazione, tangente/tensione/bias/continuità sono anche usati nel calcolo del valore campionato finale.  I valori campionati in una posizione temporale non key-frame sono interpolati dai key-frame tra il key-frame precedente e quello successivo.  I valori prima/dopo il primo/ultimo key-frame sono calcolati dalla classe Extrapolation. |
| [KeyframeSequence](../aspose.threed/keyframesequence) | La sequenza di key-frame, descrive la trasformazione di un valore campionato nel tempo. |
| [LambertMaterial](../aspose.threed/lambertmaterial) | Materiale per il modello di shading Lambert |
| [License](../aspose.threed/license) | Fornisce metodi per licenziare il componente. |
| [Light](../aspose.threed/light) | La luce illumina la scena.  La formula per calcolare l'attenuazione totale della luce è:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation) |
| [Line](../aspose.threed/line) | Una polilinea è un percorso definito da un insieme di punti con Geometry.ControlPoints e collegato da Segmenti, il che significa che può anche essere un insieme di segmenti di linea connessi.  La linea è solitamente un oggetto lineare, il che significa che non può essere usata per rappresentare una curva; per rappresentare una curva, si utilizza NurbsCurve. |
| [LinearExtrusion](../aspose.threed/linearextrusion) | L'estrusione lineare prende una forma 2D in input ed estende la forma nella terza dimensione. |
| [LoadOptions](../aspose.threed/loadoptions) | La classe base per configurare le opzioni di caricamento file per diversi tipi  @hideconstructor |
| [LocalFileSystem](../aspose.threed/localfilesystem) | Il LocalFileSystem mapperà le operazioni di lettura/scrittura alla directory locale. |
| [LShape](../aspose.threed/lshape) | Profilo a forma di L compatibile IFC definito da parametri. |
| [Material](../aspose.threed/material) | Il materiale definisce i parametri necessari per l'aspetto visivo della geometria.  Aspose.3D fornisce modelli di shading per LambertMaterial, PhongMaterial e ShaderMaterial  @hideconstructor |
| [MathUtils](../aspose.threed/mathutils) | Un insieme di utilità matematiche utili.  @hideconstructor |
| [Matrix4](../aspose.threed/matrix4) | Implementazione di matrice 4x4. |
| [MemoryFileSystem](../aspose.threed/memoryfilesystem) | Il MemoryFileSystem mapperà le operazioni di lettura/scrittura alla memoria. |
| [Mesh](../aspose.threed/mesh) | Una mesh è composta da molti poligoni a n lati. |
| [Metered](../aspose.threed/metered) | Fornisce metodi per impostare la chiave misurata. |
| [MirroredProfile](../aspose.threed/mirroredprofile) | Profilo a specchio compatibile IFC.  Questo profilo definisce un nuovo profilo specchiando il profilo base rispetto all'asse y. |
| [MorphTargetChannel](../aspose.threed/morphtargetchannel) | Un MorphTargetChannel è usato da MorphTargetDeformer per organizzare le geometrie target.  Alcuni formati di file come FBX supportano più canali in parallelo.  Il peso è compreso tra 0 e 1.0, e il peso predefinito per il target è 0.0; |
| [MorphTargetDeformer](../aspose.threed/morphtargetdeformer) | MorphTargetDeformer fornisce animazione per vertice.  MorphTargetDeformer organizza tutti i target tramite MorphTargetChannel, ogni canale può organizzare più target.  Un uso comune del deformatore di morph target è applicare espressioni facciali a un personaggio.  Maggiori dettagli sono disponibili su https://en.wikipedia.org/wiki/Morph_target_animation |
| [Node](../aspose.threed/node) | Rappresenta un elemento nel grafo della scena.  Un grafo della scena è un albero di oggetti Node. I servizi di gestione dell'albero sono contenuti in questa classe.  Nota che l'Aspose.3D SDK non verifica la validità del grafo della scena costruito. È responsabilità del chiamante assicurarsi che non vengano generati grafi ciclici nella gerarchia dei nodi.  Oltre alla gestione dell'albero, questa classe definisce tutte le proprietà necessarie per descrivere la posizione dell'oggetto nella scena. Queste informazioni includono le proprietà di base Traslazione, Rotazione e Scala e le opzioni più avanzate per pivot, limiti e attributi delle giunture IK come rigidità e smorzamento.  Quando viene creato per la prima volta, l'oggetto Node è "vuoto" (cioè è un oggetto senza alcuna rappresentazione grafica che contiene solo le informazioni di posizione). In questo stato, può essere usato per rappresentare i genitori nella struttura ad albero dei nodi ma non molto altro. L'uso normale di questo tipo di oggetti è aggiungere loro un'entità che specializzerà il nodo (vedi "Entity").  L'entità è un oggetto a sé stante ed è collegata al Node. Questo significa anche che la stessa entità può essere condivisa tra più nodi. Camera, Light, Mesh, ecc... sono tutte entità e derivano tutte dalla classe base Entity. |
| [NurbsCurve](../aspose.threed/nurbscurve) | Una curva NURBS è una curva rappresentata da NURBS (Non-uniform rational basis spline).  Una curva NURBS è definita dal suo Ordine, da un insieme di Geometry.ControlPoints ponderati e da KnotVectors.  Il componente w nel punto di controllo è usato come peso del punto di controllo, indipendentemente dal fatto che sia CurveDimension.TWO_DIMENSIONAL o CurveDimension.THREE_DIMENSIONAL. |
| [NurbsDirection](../aspose.threed/nurbsdirection) | Una NurbsSurface 3D ha due direzioni, NurbsSurface.U e NurbsSurface.V; NurbsDirection definisce i dati per ciascuna direzione.  Una direzione è in realtà una curva NURBS, il che significa che è anche definita dal suo Ordine, da KnotVectors e da un insieme di punti di controllo ponderati (definiti in NurbsSurface). |
| [NurbsSurface](../aspose.threed/nurbssurface) | NurbsSurface è una superficie rappresentata da NURBS (Non-uniform rational basis spline).  Una NurbsSurface è definita da due NurbsDirectionU e V.  Il componente w nel punto di controllo è usato come peso del punto di controllo, indipendentemente dal tipo di direzione, sia CurveDimension.TWO_DIMENSIONAL sia CurveDimension.THREE_DIMENSIONAL. |
| [ObjLoadOptions](../aspose.threed/objloadoptions) | Opzioni di caricamento per wavefront obj |
| [ObjSaveOptions](../aspose.threed/objsaveoptions) | Opzioni di salvataggio per file wavefront obj |
| [ParameterizedProfile](../aspose.threed/parameterizedprofile) | La classe base di tutti i profili parametrizzati.  @hideconstructor |
| [ParseException](../aspose.threed/parseexception) | Eccezione quando Aspose.3D non è riuscito a analizzare l'input. |
| [Patch](../aspose.threed/patch) | Un Patch è una superficie di modellazione parametrica, simile a NurbsSurface, è anche definita da due PatchDirection, l'U e la V. Ma la differenza tra Patch e NurbsSurface è che la curva PatchDirection può essere una di PatchDirectionType.BEZIER, PatchDirectionType.QUADRATIC_BEZIER, PatchDirectionType.BASIS_SPLINE, PatchDirectionType.CARDINAL_SPLINE e PatchDirectionType.LINEAR |
| [PatchDirection](../aspose.threed/patchdirection) | Direzione U e V del Patch. |
| [PbrMaterial](../aspose.threed/pbrmaterial) | Materiale per il rendering fisicamente basato su colore albedo/metallo/ruvidità |
| [PbrSpecularMaterial](../aspose.threed/pbrspecularmaterial) | Materiale per il rendering fisicamente basato su colore diffuso/speculare/brillantezza |
| [PdfFormat](../aspose.threed/pdfformat) | Formato Portable Document di Adobe  @hideconstructor |
| [PdfLoadOptions](../aspose.threed/pdfloadoptions) | Opzioni per il caricamento PDF |
| [PdfSaveOptions](../aspose.threed/pdfsaveoptions) | Le opzioni di salvataggio nell'esportazione PDF. |
| [PhongMaterial](../aspose.threed/phongmaterial) | Materiale per il modello di shading Blinn-Phong. |
| [PixelMapping](../aspose.threed/pixelmapping) | @hideconstructor |
| [Plane](../aspose.threed/plane) | Piano parametrico. |
| [PlyFormat](../aspose.threed/plyformat) | Il formato PLY.  @hideconstructor |
| [PlyLoadOptions](../aspose.threed/plyloadoptions) | Opzioni di caricamento per file PLY |
| [PlySaveOptions](../aspose.threed/plysaveoptions) | Opzioni di salvataggio per esportare la scena come file PLY. |
| [PointCloud](../aspose.threed/pointcloud) | La nuvola di punti non contiene informazioni di topologia ma solo i punti di controllo e gli elementi dei vertici. |
| [PolygonBuilder](../aspose.threed/polygonbuilder) | Una classe di supporto per costruire poligoni per Mesh |
| [PolygonModifier](../aspose.threed/polygonmodifier) | Utility per modificare i poligoni  @hideconstructor |
| [Pose](../aspose.threed/pose) | La posa è usata per memorizzare la matrice di trasformazione quando la geometria è skinned. La posa è un insieme di BonePose, ogni BonePose salva le informazioni concrete di trasformazione del nodo osso. |
| [PostProcessing](../aspose.threed/postprocessing) | Gli effetti di post-elaborazione  @hideconstructor |
| [Primitive](../aspose.threed/primitive) | Classe base per tutte le primitive |
| [Profile](../aspose.threed/profile) | Profilo 2D nel piano xy  @hideconstructor |
| [Property](../aspose.threed/property) | Classe per contenere proprietà definite dall'utente.  @hideconstructor |
| [PropertyCollection](../aspose.threed/propertycollection) | La collezione di proprietà  @hideconstructor |
| [PushConstant](../aspose.threed/pushconstant) | Una utility per fornire dati allo shader tramite push constant. |
| [Pyramid](../aspose.threed/pyramid) | Piramide parametrica. |
| [Quaternion](../aspose.threed/quaternion) | Il quaternione è solitamente usato per eseguire rotazioni nella grafica computerizzata. |
| [Rect](../aspose.threed/rect) | Una classe per rappresentare il rettangolo |
| [RectangleShape](../aspose.threed/rectangleshape) | Forma rettangolare compatibile IFC con angoli arrotondati. |
| [RectangularTorus](../aspose.threed/rectangulartorus) | Toro rettangolare parametrizzato. |
| [RelativeRectangle](../aspose.threed/relativerectangle) | Rettangolo relativo  La formula tra componente relativo e valore assoluto è:  Scala  (Larghezza di riferimento) + offset  Quindi, se vogliamo rappresentare un valore assoluto, impostare tutti i campi scala a zero e utilizzare invece i campi offset. |
| [Renderer](../aspose.threed/renderer) | Il contesto relativo al renderer.  @hideconstructor |
| [RendererVariableManager](../aspose.threed/renderervariablemanager) | Questa classe gestisce le variabili utilizzate nel rendering  @hideconstructor |
| [RenderFactory](../aspose.threed/renderfactory) | RenderFactory crea tutte le risorse rappresentate nella pipeline di rendering.  @hideconstructor |
| [RenderParameters](../aspose.threed/renderparameters) | Descrivi i parametri del render target |
| [RenderResource](../aspose.threed/renderresource) | La classe astratta di tutte le risorse di rendering  Tutte le risorse di rendering saranno rilasciate quando il renderer viene chiuso.  Classi come Mesh/Texture avranno una corrispondente RenderResource  @hideconstructor |
| [RenderState](../aspose.threed/renderstate) | Stato di rendering per la costruzione della pipeline  Le modifiche apportate allo stato di rendering non influenzeranno le istanze della pipeline create. |
| [RevolvedAreaSolid](../aspose.threed/revolvedareasolid) | Questa classe rappresenta un modello solido ruotando una sezione trasversale fornita da un profilo attorno a un asse. |
| [RvmFormat](../aspose.threed/rvmformat) | Il formato RVM  @hideconstructor |
| [RvmLoadOptions](../aspose.threed/rvmloadoptions) | Opzioni di caricamento per il file RVM di AVEVA Plant Design Management System. |
| [RvmSaveOptions](../aspose.threed/rvmsaveoptions) | Opzioni di salvataggio per il file RVM di Aveva PDMS. |
| [SaveOptions](../aspose.threed/saveoptions) | La classe base per configurare le opzioni di salvataggio file per diversi tipi  @hideconstructor |
| [Scene](../aspose.threed/scene) | Una scena è un oggetto di livello superiore che contiene nodi, geometrie, materiali, texture, animazioni, pose, sotto-scene ecc.  La scena può avere sotto-scene, funge da supporto multi-documento in file come collada/blender/fbx.  La gerarchia dei nodi è accessibile tramite RootNodeLibrary, che viene utilizzata per mantenere un riferimento agli oggetti non collegati durante la serializzazione (come metadati o oggetti personalizzati) così da poter essere usata come libreria. |
| [SceneObject](../aspose.threed/sceneobject) | La classe radice degli oggetti che saranno memorizzati all'interno di una scena. |
| [ShaderException](../aspose.threed/shaderexception) | Eccezioni relative agli shader |
| [ShaderMaterial](../aspose.threed/shadermaterial) | Un materiale shader consente di descrivere il materiale tramite un motore di rendering esterno o un linguaggio shader.  ShaderMaterial utilizza ShaderTechnique per descrivere i dettagli concreti del rendering,  e quello più adatto verrà usato in base alla piattaforma di rendering finale.  Ad esempio, la tua istanza di ShaderMaterial può avere due tecniche, una definita in HLSL e un'altra definita in GLSL.  Su piattaforme non Windows, dovrebbe essere usato GLSL invece di HLSL |
| [ShaderProgram](../aspose.threed/shaderprogram) | Il programma shader  @hideconstructor |
| [ShaderSet](../aspose.threed/shaderset) | Programmi shader per ogni tipo di materiale |
| [ShaderSource](../aspose.threed/shadersource) | Il codice sorgente dello shader  @hideconstructor |
| [ShaderTechnique](../aspose.threed/shadertechnique) | Una tecnica shader rappresenta un'implementazione concreta di rendering. |
| [ShaderVariable](../aspose.threed/shadervariable) | Variabile shader |
| [Shape](../aspose.threed/shape) | La forma descrive la deformazione su un insieme di punti di controllo, simile al cluster deformer in Maya.  Ad esempio, possiamo aggiungere una forma a una geometria creata.  La forma e la geometria hanno la stessa informazione topologica ma posizioni diverse dei punti di controllo.  Con diverse quantità di influenza, la geometria produce un effetto di deformazione. |
| [Skeleton](../aspose.threed/skeleton) | Lo Skeleton è principalmente usato dal software CAD per aiutare il progettista a manipolare la trasformazione della struttura scheletrica, è solitamente inutile al di fuori dei software CAD. Per far sì che la gerarchia dello scheletro agisca come un unico oggetto nel software CAD, è necessario contrassegnare il nodo Skeleton superiore come radice impostando Type su SkeletonType.SKELETON e tutti i figli su SkeletonType.BONE. |
| [SkinDeformer](../aspose.threed/skindeformer) | Un skin deformer contiene più ossa per funzionare, ogni osso fonde una parte della geometria in base ai pesi dei punti di controllo. |
| [Sphere](../aspose.threed/sphere) | Sfera parametrizzata. |
| [SPIRVSource](../aspose.threed/spirvsource) | Lo shader compilato in formato SPIR-V. |
| [StencilState](../aspose.threed/stencilstate) | Stati stencil per faccia.  @hideconstructor |
| [StlLoadOptions](../aspose.threed/stlloadoptions) | Opzioni di caricamento per STL |
| [StlSaveOptions](../aspose.threed/stlsaveoptions) | Opzioni di salvataggio per STL |
| [SweptAreaSolid](../aspose.threed/sweptareasolid) | Un SweptAreaSolid costruisce una geometria spazzolando un profilo lungo una direttrice. |
| [Text](../aspose.threed/text) | Profilo di testo, questo profilo descrive i contorni usando caratteri e testo. |
| [Texture](../aspose.threed/texture) | Questa classe definisce la texture da un file esterno. |
| [TextureBase](../aspose.threed/texturebase) | Classe base per tutte le texture concrete.  Texture definisce l'aspetto di una superficie geometrica. |
| [TextureCodec](../aspose.threed/texturecodec) | Classe per gestire encoder e decoder per le texture. |
| [TextureData](../aspose.threed/texturedata) | Questa classe contiene i dati grezzi e la definizione del formato di una texture. |
| [TextureSlot](../aspose.threed/textureslot) | Slot della texture in Material, può essere enumerato tramite l'istanza del materiale.  @hideconstructor |
| [Torus](../aspose.threed/torus) | Toro parametrizzato. |
| [Transform](../aspose.threed/transform) | Una trasformazione contiene informazioni che consentono l'accesso alla traslazione/scalatura/rotazione dell'oggetto o alla matrice di trasformazione a costo minimo.  Questo è usato dalla trasformazione locale.  @hideconstructor |
| [TransformBuilder](../aspose.threed/transformbuilder) | Il TransformBuilder è usato per costruire la matrice di trasformazione tramite una catena di trasformazioni. |
| [TransformedCurve](../aspose.threed/transformedcurve) | Una TransformedCurve assegna una posizione a una curva usando una matrice di trasformazione.  Questo consente di eseguire una trasformazione all'interno di una TrimmedCurve o CompositeCurve. |
| [TrapeziumShape](../aspose.threed/trapeziumshape) | Forma a Trapezio compatibile IFC definita da parametri. |
| [TrialException](../aspose.threed/trialexception) | Questo viene sollevato in Scene.Open/Scene.Save quando non sono applicate licenze.  È possibile disattivare questa eccezione impostando SuppressTrialException su true. |
| [TriMesh](../aspose.threed/trimesh) | Un TriMesh contiene dati grezzi che possono essere usati direttamente dalla GPU.  Questa classe è un'utilità per aiutare a costruire una mesh che contiene solo dati per vertice. |
| [TrimmedCurve](../aspose.threed/trimmedcurve) | Una curva limitata che taglia la curva di base a entrambe le estremità. |
| [TShape](../aspose.threed/tshape) | Forma a T compatibile IFC definita da parametri. |
| [U3dLoadOptions](../aspose.threed/u3dloadoptions) | Opzioni di caricamento per universal 3d |
| [U3dSaveOptions](../aspose.threed/u3dsaveoptions) | Opzioni di salvataggio per universal 3d |
| [UsdSaveOptions](../aspose.threed/usdsaveoptions) | Opzioni di salvataggio per i formati USD/USDZ. |
| [UShape](../aspose.threed/ushape) | Forma a U compatibile con IFC definita da parametri. |
| [Vector2](../aspose.threed/vector2) | Un vettore con due componenti. |
| [Vector3](../aspose.threed/vector3) | Un vettore con tre componenti. |
| [Vector4](../aspose.threed/vector4) | Un vettore con quattro componenti. |
| [Vertex](../aspose.threed/vertex) | Riferimento al vertice, usato per accedere al vertice grezzo in TriMesh.  @hideconstructor |
| [VertexDeclaration](../aspose.threed/vertexdeclaration) | La dichiarazione della struttura di un vertice definito personalizzato |
| [VertexElement](../aspose.threed/vertexelement) | Classe base degli elementi del vertice.  Un tipo di elemento del vertice è identificato da VertexElementType.  Un VertexElement descrive come l'elemento del vertice è mappato su una superficie geometrica e come le informazioni di mappatura sono organizzate in memoria.  Un VertexElement contiene Normali, UV o altri tipi di informazioni.  @hideconstructor |
| [VertexElementBinormal](../aspose.threed/vertexelementbinormal) | Definisce i vettori binormali per le componenti specificate. |
| [VertexElementDoublesTemplate](../aspose.threed/vertexelementdoublestemplate) | Una classe di supporto per definire implementazioni concrete di VertexElement.  @hideconstructor |
| [VertexElementEdgeCrease](../aspose.threed/vertexelementedgecrease) | Definisce la piega del bordo per le componenti specificate |
| [VertexElementHole](../aspose.threed/vertexelementhole) | Definisce se il poligono specificato è un buco |
| [VertexElementIntsTemplate](../aspose.threed/vertexelementintstemplate) | Una classe di supporto per definire implementazioni concrete di VertexElement.  @hideconstructor |
| [VertexElementMaterial](../aspose.threed/vertexelementmaterial) | Definisce l'indice del materiale per le componenti specificate.  Un nodo può avere più materiali, il VertexElementMaterial è usato per renderizzare parti diverse della geometria con materiali differenti. |
| [VertexElementNormal](../aspose.threed/vertexelementnormal) | Definisce i vettori normali per le componenti specificate. |
| [VertexElementPolygonGroup](../aspose.threed/vertexelementpolygongroup) | Definisce il gruppo di poligoni per le componenti specificate per raggruppare insieme i poligoni correlati. |
| [VertexElementSmoothingGroup](../aspose.threed/vertexelementsmoothinggroup) | Un gruppo di smussatura è un gruppo di poligoni in una mesh poligonale che dovrebbe apparire come una superficie liscia.  Alcuni primi software di modellazione 3D come 3D Studio Max per DOS usavano il gruppo di smussatura per evitare di memorizzare il vettore normale per ogni vertice della mesh. |
| [VertexElementSpecular](../aspose.threed/vertexelementspecular) | Definisce il colore speculare per le componenti specificate. |
| [VertexElementTangent](../aspose.threed/vertexelementtangent) | Definisce i vettori tangenti per le componenti specificate. |
| [VertexElementUserData](../aspose.threed/vertexelementuserdata) | Definisce dati utente personalizzati per le componenti specificate.  Di solito sono dati specifici dell'applicazione per scopi speciali. |
| [VertexElementUV](../aspose.threed/vertexelementuv) | Definisce le coordinate UV per le componenti specificate.  Una geometria può avere più elementi VertexElementUV, e ciascuno ha diverse TextureMappings. |
| [VertexElementVector4](../aspose.threed/vertexelementvector4) | Una classe di supporto per definire implementazioni concrete di VertexElement.  @hideconstructor |
| [VertexElementVertexColor](../aspose.threed/vertexelementvertexcolor) | Definisce il colore del vertice per le componenti specificate |
| [VertexElementVertexCrease](../aspose.threed/vertexelementvertexcrease) | Definisce la piega del vertice per le componenti specificate |
| [VertexElementVisibility](../aspose.threed/vertexelementvisibility) | Definisce se le componenti specificate sono visibili |
| [VertexElementWeight](../aspose.threed/vertexelementweight) | Definisce il peso di fusione per le componenti specificate. |
| [VertexField](../aspose.threed/vertexfield) | Descrizione del layout di memoria dei campi del vertice.  @hideconstructor |
| [Viewport](../aspose.threed/viewport) | Un com.aspose.threed.IRenderTarget contiene almeno una viewport per il rendering della scena.  @hideconstructor |
| [Watermark](../aspose.threed/watermark) | Utility per codificare/decodificare watermark cieco da/a una mesh.  @hideconstructor |
| [WindowHandle](../aspose.threed/windowhandle) | Handle di finestra incapsulato per diverse piattaforme.  @hideconstructor |
| [XLoadOptions](../aspose.threed/xloadoptions) | Le opzioni di caricamento per i file DirectX X. |
| [ZipArchiveFileSystem](../aspose.threed/ziparchivefilesystem) | File system per fornire l'accesso in sola lettura a un file zip specificato o a uno stream zip.  Il file system verrà eliminato dopo l'operazione di apertura/salvataggio. |
| [ZShape](../aspose.threed/zshape) | Profilo a forma Z compatibile IFC definito dai parametri. |
| [CubeFace](../aspose.threed/cubeface) | Classe di utilità contenente costanti.  Ogni faccia della texture della cubemap  @hideconstructor |
| [IndexDataType](../aspose.threed/indexdatatype) | Classe di utilità contenente costanti.  Il tipo di dati degli elementi in com.aspose.threed.IIndexBuffer  @hideconstructor |
