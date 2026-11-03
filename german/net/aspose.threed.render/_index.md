---
title: "Aspose.ThreeD.Render"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Alle renderebezogenen Klassen sind in diesem Namensraum definiert"
type: docs
weight: 80
url: /de/net/aspose.threed.render/
---
Alle renderebezogenen Klassen sind in diesem Namensraum definiert

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [DescriptorSetUpdater](./descriptorsetupdater/) | Diese Klasse ermöglicht das Aktualisieren des [`IDescriptorSet`](../aspose.threed.render/idescriptorset/) in einer Kettenoperation. |
| [DriverException](./driverexception/) | Die von internen Rendering‑Treibern ausgelöste Ausnahme. |
| [EntityRenderer](./entityrenderer/) | Erben Sie hiervon, um das Rendering für verschiedene Arten von Entitäten zu implementieren. |
| [EntityRendererKey](./entityrendererkey/) | Der Schlüssel des registrierten Entitäts‑Renderers |
| [GLSLSource](./glslsource/) | Der Quellcode von Shadern in GLSL |
| [InitializationException](./initializationexception/) | Ausnahmen bei der Initialisierung der Rendering‑Pipeline |
| [PixelMapping](./pixelmapping/) |  |
| [PostProcessing](./postprocessing/) | Die Nachbearbeitungseffekte |
| [PushConstant](./pushconstant/) | Ein Dienstprogramm, um Daten über Push-Konstanten an den Shader zu übermitteln. |
| [Renderer](./renderer/) | Der Kontext zum Renderer. |
| [RendererVariableManager](./renderervariablemanager/) | Diese Klasse verwaltet Variablen, die beim Rendern verwendet werden. |
| [RenderFactory](./renderfactory/) | RenderFactory erstellt alle Ressourcen, die in der Rendering-Pipeline dargestellt werden. |
| [RenderParameters](./renderparameters/) | Beschreibe die Parameter des Renderziels. |
| [RenderResource](./renderresource/) | Die abstrakte Klasse aller Renderressourcen Alle Renderressourcen werden freigegeben, wenn der Renderer freigegeben wird. Klassen wie [`Mesh`](../aspose.threed.entities/mesh/)/[`Texture`](../aspose.threed.shading/texture/) haben ein entsprechendes RenderResource |
| [RenderState](./renderstate/) | Renderzustand zum Aufbau der Pipeline Die Änderungen am Renderzustand wirken sich nicht auf die erstellten Pipeline-Instanzen aus. |
| [ShaderException](./shaderexception/) | Shader-bezogene Ausnahmen |
| [ShaderProgram](./shaderprogram/) | Das Shader-Programm |
| [ShaderSet](./shaderset/) | Shader-Programme für jede Art von Materialien |
| [ShaderSource](./shadersource/) | Der Quellcode des Shaders |
| [ShaderVariable](./shadervariable/) | Shader-Variable |
| [SPIRVSource](./spirvsource/) | Der kompilierte Shader im SPIR-V-Format. |
| [StencilState](./stencilstate/) | Stencil-Zustände pro Seite. |
| [TextureCodec](./texturecodec/) | Klasse zur Verwaltung von Encodern und Decodern für Texturen. |
| [TextureData](./texturedata/) | Diese Klasse enthält die Rohdaten und die Formatdefinition einer Textur. |
| [Viewport](./viewport/) | Ein [`IRenderTarget`](../aspose.threed.render/irendertarget/) enthält mindestens ein Viewport zum Rendern der Szene. |
| [WindowHandle](./windowhandle/) | Kapselter Fenster-Handle für verschiedene Plattformen. |
## Structures

| Struktur | Beschreibung |
| --- | --- |
| [CubeFaceData&lt;T&gt;](./cubefacedata-1/) | Daten für jede Seite der Cube-Map-Textur. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IBuffer](./ibuffer/) | Die Basisschnittstelle aller verwalteten Puffer, die beim Rendern verwendet werden |
| [ICommandList](./icommandlist/) | Kodiert eine Sequenz von Befehlen, die an die GPU zum Rendern gesendet werden. |
| [IDescriptorSet](./idescriptorset/) | Die Deskriptorsätze beschreiben verschiedene Ressourcen, die an die Rendering-Pipeline gebunden werden können, wie Puffer, Texturen |
| [IIndexBuffer](./iindexbuffer/) | Der Indexpuffer beschreibt die Geometrie, die in der Rendering-Pipeline verwendet wird. |
| [IPipeline](./ipipeline/) | Die vorgefertigte Sequenz von Operationen zum Zeichnen auf GPU-Seite. |
| [IRenderQueue](./irenderqueue/) | Der Entity-Renderer verwendet diese Warteschlange, um Renderaufgaben zu verwalten. |
| [IRenderTarget](./irendertarget/) | Die Basisschnittstelle des Renderziels |
| [IRenderTexture](./irendertexture/) | Die Schnittstelle der Render-Textur |
| [IRenderWindow](./irenderwindow/) | IRenderWindow stellt das vom Betriebssystem erstellte native Fenster dar, das Rendering unterstützt. |
| [ITexture1D](./itexture1d/) | 1D-Textur |
| [ITexture2D](./itexture2d/) | 2D-Textur |
| [ITextureCodec](./itexturecodec/) | Codec für Texturen |
| [ITextureCubemap](./itexturecubemap/) | Cube-Map-Textur |
| [ITextureDecoder](./itexturedecoder/) | Ein externer Texturdecoder sollte diese Schnittstelle für das Dekodieren implementieren. |
| [ITextureEncoder](./itextureencoder/) | Ein externer Texturencoder sollte diese Schnittstelle für das Kodieren implementieren. |
| [ITextureUnit](./itextureunit/) | [`ITextureUnit`](../aspose.threed.render/itextureunit/) repräsentiert eine Textur im Speicher, die zwischen GPU und CPU geteilt wird und vom Shader abgetastet werden kann, wobei [`Texture`](../aspose.threed.shading/texture/) nur einen Verweis auf eine externe Datei darstellt. Weitere Details finden Sie https://en.wikipedia.org/wiki/Texture_mapping_unit |
| [IVertexBuffer](./ivertexbuffer/) | Der Vertex-Puffer enthält die Polygon-Vertex-Daten, die an die Rendering-Pipeline gesendet werden. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [BlendFactor](./blendfactor/) | Der Blend-Faktor gibt die Pixelarithmetik an. |
| [CompareFunction](./comparefunction/) | Die Vergleichsfunktion, die beim Tiefen-/Stencil-Test verwendet wird. |
| [CubeFace](./cubeface/) | Jede Seite der Cube-Map-Textur |
| [CullFaceMode](./cullfacemode/) | Welche Seite zu verwerfen ist |
| [DrawOperation](./drawoperation/) | Die zu rendernden Primitive-Typen |
| [EntityRendererFeatures](./entityrendererfeatures/) | Die zusätzlichen Funktionen, die der Entity-Renderer bereitstellt |
| [FrontFace](./frontface/) | Definiert vorder- und rückseitige Polygone |
| [IndexDataType](./indexdatatype/) | Der Datentyp der Elemente in [`IIndexBuffer`](../aspose.threed.render/iindexbuffer/) |
| [PixelFormat](./pixelformat/) | Das Pixel-Format, das in der Textureinheit verwendet wird. |
| [PixelMapMode](./pixelmapmode/) |  |
| [PolygonMode](./polygonmode/) | Der Polygon-Rasterisierungsmodus |
| [PresetShaders](./presetshaders/) | Dies definiert die vordefinierten internen Shader, die vom Renderer verwendet werden. |
| [RenderQueueGroupId](./renderqueuegroupid/) | Die Gruppen-ID der Renderwarteschlange |
| [RenderStage](./renderstage/) | Die Renderstufe |
| [ShaderStage](./shaderstage/) | Shader-Stufe |
| [StencilAction](./stencilaction/) | Die Stencil-Testaktionen |
| [TextureType](./texturetype/) | Der Typ von [`ITextureUnit`](../aspose.threed.render/itextureunit/) |


