---
title: "Aspose.ThreeD.Render"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Toutes les classes liées au rendu sont définies dans cet espace de noms"
type: docs
weight: 80
url: /fr/net/aspose.threed.render/
---
Toutes les classes liées au rendu sont définies dans cet espace de noms

## Classes

| Classe | Description |
| --- | --- |
| [DescriptorSetUpdater](./descriptorsetupdater/) | Cette classe permet de mettre à jour le [`IDescriptorSet`](../aspose.threed.render/idescriptorset/) dans une opération en chaîne. |
| [DriverException](./driverexception/) | L'exception levée par les pilotes de rendu internes. |
| [EntityRenderer](./entityrenderer/) | Sous‑classez ceci pour implémenter le rendu pour différents types d'entités. |
| [EntityRendererKey](./entityrendererkey/) | La clé du rendu d'entité enregistré |
| [GLSLSource](./glslsource/) | Le code source des shaders en GLSL |
| [InitializationException](./initializationexception/) | Exceptions lors de l'initialisation du pipeline de rendu |
| [PixelMapping](./pixelmapping/) |  |
| [PostProcessing](./postprocessing/) | Les effets de post‑traitement |
| [PushConstant](./pushconstant/) | Un utilitaire pour fournir des données au shader via une constante push. |
| [Renderer](./renderer/) | Le contexte du rendu. |
| [RendererVariableManager](./renderervariablemanager/) | Cette classe gère les variables utilisées lors du rendu |
| [RenderFactory](./renderfactory/) | RenderFactory crée toutes les ressources représentées dans le pipeline de rendu. |
| [RenderParameters](./renderparameters/) | Décrivez les paramètres de la cible de rendu |
| [RenderResource](./renderresource/) | La classe abstraite de toutes les ressources de rendu Toutes les ressources de rendu seront libérées lorsque le rendu sera relâché. Les classes comme [`Mesh`](../aspose.threed.entities/mesh/)/[`Texture`](../aspose.threed.shading/texture/) auront une ressource de rendu correspondante. |
| [RenderState](./renderstate/) | État de rendu pour la construction du pipeline Les modifications apportées à l'état de rendu n'affecteront pas les instances de pipeline créées. |
| [ShaderException](./shaderexception/) | Exceptions liées aux shaders |
| [ShaderProgram](./shaderprogram/) | Le programme shader |
| [ShaderSet](./shaderset/) | Programmes shader pour chaque type de matériau |
| [ShaderSource](./shadersource/) | Le code source du shader |
| [ShaderVariable](./shadervariable/) | Variable shader |
| [SPIRVSource](./spirvsource/) | Le shader compilé au format SPIR-V. |
| [StencilState](./stencilstate/) | États de stencil par face. |
| [TextureCodec](./texturecodec/) | Classe pour gérer les encodeurs et décodeurs de textures. |
| [TextureData](./texturedata/) | Cette classe contient les données brutes et la définition du format d'une texture. |
| [Viewport](./viewport/) | Un [`IRenderTarget`](../aspose.threed.render/irendertarget/) contient au moins une fenêtre d'affichage pour le rendu de la scène. |
| [WindowHandle](./windowhandle/) | Gestionnaire de fenêtre encapsulé pour différentes plateformes. |
## Structures

| Structure | Description |
| --- | --- |
| [CubeFaceData&lt;T&gt;](./cubefacedata-1/) | Données pour chaque face de la texture cube map. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IBuffer](./ibuffer/) | L'interface de base de tous les tampons gérés utilisés dans le rendu |
| [ICommandList](./icommandlist/) | Encode une séquence de commandes qui seront envoyées au GPU pour le rendu. |
| [IDescriptorSet](./idescriptorset/) | Les ensembles de descripteurs décrivent différentes ressources qui peuvent être liées au pipeline de rendu, comme les tampons, les textures |
| [IIndexBuffer](./iindexbuffer/) | Le tampon d'indices décrit la géométrie utilisée dans le pipeline de rendu. |
| [IPipeline](./ipipeline/) | La séquence pré‑cuisinée d'opérations à dessiner côté GPU. |
| [IRenderQueue](./irenderqueue/) | Le moteur de rendu d'entités utilise cette file d'attente pour gérer les tâches de rendu. |
| [IRenderTarget](./irendertarget/) | L'interface de base de la cible de rendu |
| [IRenderTexture](./irendertexture/) | L'interface de la texture de rendu |
| [IRenderWindow](./irenderwindow/) | IRenderWindow représente la fenêtre native créée par le système d'exploitation qui prend en charge le rendu. |
| [ITexture1D](./itexture1d/) | Texture 1D |
| [ITexture2D](./itexture2d/) | Texture 2D |
| [ITextureCodec](./itexturecodec/) | Codec pour les textures |
| [ITextureCubemap](./itexturecubemap/) | Texture cube map |
| [ITextureDecoder](./itexturedecoder/) | Le décodeur de texture externe doit implémenter cette interface pour le décodage. |
| [ITextureEncoder](./itextureencoder/) | L'encodeur de texture externe doit implémenter cette interface pour l'encodage. |
| [ITextureUnit](./itextureunit/) | [`ITextureUnit`](../aspose.threed.render/itextureunit/) représente une texture en mémoire partagée entre le GPU et le CPU et pouvant être échantillonnée par le shader, où le [`Texture`](../aspose.threed.shading/texture/) ne représente qu'une référence à un fichier externe. Plus de détails peuvent être trouvés https://en.wikipedia.org/wiki/Texture_mapping_unit |
| [IVertexBuffer](./ivertexbuffer/) | Le tampon de sommets contient les données de sommets des polygones qui seront envoyées au pipeline de rendu |
## Énumération

| Énumération | Description |
| --- | --- |
| [BlendFactor](./blendfactor/) | Le facteur de mélange spécifie l'arithmétique des pixels. |
| [CompareFunction](./comparefunction/) | La fonction de comparaison utilisée dans les tests de profondeur/stencil. |
| [CubeFace](./cubeface/) | Chaque face de la texture cube map. |
| [CullFaceMode](./cullfacemode/) | Quelle face à éliminer. |
| [DrawOperation](./drawoperation/) | Les types primitifs à rendre. |
| [EntityRendererFeatures](./entityrendererfeatures/) | Les fonctionnalités supplémentaires que le rendu d'entité fournira. |
| [FrontFace](./frontface/) | Définir les polygones orientés vers l'avant et l'arrière. |
| [IndexDataType](./indexdatatype/) | Le type de données des éléments dans [`IIndexBuffer`](../aspose.threed.render/iindexbuffer/). |
| [PixelFormat](./pixelformat/) | Le format du pixel utilisé dans l'unité de texture. |
| [PixelMapMode](./pixelmapmode/) |  |
| [PolygonMode](./polygonmode/) | Le mode de rastérisation des polygones. |
| [PresetShaders](./presetshaders/) | Cela définit les shaders internes prédéfinis utilisés par le moteur de rendu. |
| [RenderQueueGroupId](./renderqueuegroupid/) | L'identifiant de groupe de la file d'attente de rendu. |
| [RenderStage](./renderstage/) | L'étape de rendu. |
| [ShaderStage](./shaderstage/) | Étape du shader. |
| [StencilAction](./stencilaction/) | Les actions du test stencil. |
| [TextureType](./texturetype/) | Le type du [`ITextureUnit`](../aspose.threed.render/itextureunit/). |


