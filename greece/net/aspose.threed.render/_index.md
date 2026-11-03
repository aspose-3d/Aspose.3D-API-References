---
title: "Aspose.ThreeD.Render"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Όλες οι κλάσεις που σχετίζονται με την απόδοση ορίζονται σε αυτόν τον χώρο ονομάτων."
type: docs
weight: 80
url: /el/net/aspose.threed.render/
---
Όλες οι κλάσεις που σχετίζονται με την απόδοση ορίζονται σε αυτόν τον χώρο ονομάτων.

## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [DescriptorSetUpdater](./descriptorsetupdater/) | Αυτή η κλάση επιτρέπει την ενημέρωση του [`IDescriptorSet`](../aspose.threed.render/idescriptorset/) σε μια αλυσίδα λειτουργιών. |
| [DriverException](./driverexception/) | Η εξαίρεση που προκαλείται από εσωτερικούς οδηγούς απόδοσης. |
| [EntityRenderer](./entityrenderer/) | Κληρονομήστε αυτήν την κλάση για να υλοποιήσετε την απόδοση διαφορετικών τύπων οντοτήτων. |
| [EntityRendererKey](./entityrendererkey/) | Το κλειδί του καταχωρημένου αποτυπωτή οντοτήτων |
| [GLSLSource](./glslsource/) | Ο πηγαίος κώδικας των shaders σε GLSL |
| [InitializationException](./initializationexception/) | Εξαιρέσεις στην αρχικοποίηση της γραμμής επεξεργασίας απόδοσης |
| [PixelMapping](./pixelmapping/) |  |
| [PostProcessing](./postprocessing/) | Τα εφέ μετα-επεξεργασίας |
| [PushConstant](./pushconstant/) | Ένα εργαλείο για την παροχή δεδομένων στο shader μέσω push constant. |
| [Renderer](./renderer/) | Το πλαίσιο σχετικά με τον αποτυπωτή. |
| [RendererVariableManager](./renderervariablemanager/) | Αυτή η κλάση διαχειρίζεται τις μεταβλητές που χρησιμοποιούνται στην απόδοση |
| [RenderFactory](./renderfactory/) | Η RenderFactory δημιουργεί όλους τους πόρους που αντιπροσωπεύονται στη γραμμή επεξεργασίας απόδοσης. |
| [RenderParameters](./renderparameters/) | Περιγράψτε τις παραμέτρους του στόχου απόδοσης |
| [RenderResource](./renderresource/) | Η αφηρημένη κλάση όλων των πόρων απόδοσης Όλοι οι πόροι απόδοσης θα απελευθερωθούν όταν ο αποτυπωτής απελευθερωθεί. Κλάσεις όπως [`Mesh`](../aspose.threed.entities/mesh/)/[`Texture`](../aspose.threed.shading/texture/) θα έχουν ένα αντίστοιχο RenderResource |
| [RenderState](./renderstate/) | Κατάσταση απόδοσης για την κατασκευή της γραμμής επεξεργασίας Οι αλλαγές που γίνονται στην κατάσταση απόδοσης δεν θα επηρεάσουν τις δημιουργημένες παρουσίες της γραμμής επεξεργασίας. |
| [ShaderException](./shaderexception/) | Εξαιρέσεις σχετικές με το shader |
| [ShaderProgram](./shaderprogram/) | Το πρόγραμμα shader |
| [ShaderSet](./shaderset/) | Προγράμματα shader για κάθε είδος υλικών |
| [ShaderSource](./shadersource/) | Ο πηγαίος κώδικας του shader |
| [ShaderVariable](./shadervariable/) | Μεταβλητή shader |
| [SPIRVSource](./spirvsource/) | Ο μεταγλωττισμένος shader σε μορφή SPIR-V. |
| [StencilState](./stencilstate/) | Καταστάσεις stencil ανά πρόσωπο. |
| [TextureCodec](./texturecodec/) | Κλάση για τη διαχείριση κωδικοποιητών και αποκωδικοποιητών για υφές. |
| [TextureData](./texturedata/) | Αυτή η κλάση περιέχει τα ακατέργαστα δεδομένα και τον ορισμό μορφής μιας υφής. |
| [Viewport](./viewport/) | Ένα [`IRenderTarget`](../aspose.threed.render/irendertarget/) περιέχει τουλάχιστον ένα παράθυρο προβολής για την απόδοση της σκηνής. |
| [WindowHandle](./windowhandle/) | Ενσωματωμένο αναγνωριστικό παραθύρου για διαφορετικές πλατφόρμες. |
## Structures

| Δομή | Περιγραφή |
| --- | --- |
| [CubeFaceData&lt;T&gt;](./cubefacedata-1/) | Δεδομένα για κάθε πρόσωπο της υφής cube map. |
## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [IBuffer](./ibuffer/) | Η βασική διεπαφή όλων των διαχειριζόμενων buffers που χρησιμοποιούνται στην απόδοση. |
| [ICommandList](./icommandlist/) | Κωδικοποιεί μια ακολουθία εντολών που θα σταλούν στην GPU για απόδοση. |
| [IDescriptorSet](./idescriptorset/) | Τα σύνολα περιγραφέων περιγράφουν διαφορετικούς πόρους που μπορούν να δεσμευτούν στην pipeline απόδοσης, όπως buffers, υφές. |
| [IIndexBuffer](./iindexbuffer/) | Το buffer δεικτών περιγράφει τη γεωμετρία που χρησιμοποιείται στην pipeline απόδοσης. |
| [IPipeline](./ipipeline/) | Η προετοιμασμένη ακολουθία λειτουργιών για σχεδίαση στην πλευρά της GPU. |
| [IRenderQueue](./irenderqueue/) | Ο renderer οντοτήτων χρησιμοποιεί αυτήν την ουρά για τη διαχείριση εργασιών απόδοσης. |
| [IRenderTarget](./irendertarget/) | Η βασική διεπαφή του render target. |
| [IRenderTexture](./irendertexture/) | Η διεπαφή του render texture. |
| [IRenderWindow](./irenderwindow/) | Το IRenderWindow αντιπροσωπεύει το εγγενές παράθυρο που δημιουργείται από το λειτουργικό σύστημα και υποστηρίζει την απόδοση. |
| [ITexture1D](./itexture1d/) | Υφή 1Δ |
| [ITexture2D](./itexture2d/) | Υφή 2Δ |
| [ITextureCodec](./itexturecodec/) | Codec για υφές. |
| [ITextureCubemap](./itexturecubemap/) | Υφή cube map. |
| [ITextureDecoder](./itexturedecoder/) | Ο εξωτερικός αποκωδικοποιητής υφών πρέπει να υλοποιεί αυτή τη διεπαφή για αποκωδικοποίηση. |
| [ITextureEncoder](./itextureencoder/) | Ο εξωτερικός κωδικοποιητής υφών πρέπει να υλοποιεί αυτή τη διεπαφή για κωδικοποίηση. |
| [ITextureUnit](./itextureunit/) | [`ITextureUnit`](../aspose.threed.render/itextureunit/) αντιπροσωπεύει μια υφή στη μνήμη που μοιράζεται μεταξύ GPU και CPU και μπορεί να δειγματοληπτεί από το shader, όπου το [`Texture`](../aspose.threed.shading/texture/) αντιπροσωπεύει μόνο μια αναφορά σε εξωτερικό αρχείο. Περισσότερες λεπτομέρειες μπορούν να βρεθούν https://en.wikipedia.org/wiki/Texture_mapping_unit |
| [IVertexBuffer](./ivertexbuffer/) | Το buffer κορυφών περιέχει τα δεδομένα κορυφών του πολύγωνου που θα σταλούν στην pipeline απόδοσης. |
## Απαρίθμηση

| Απαρίθμηση | Περιγραφή |
| --- | --- |
| [BlendFactor](./blendfactor/) | Ο συντελεστής ανάμειξης καθορίζει την αριθμητική των pixel. |
| [CompareFunction](./comparefunction/) | Η συνάρτηση σύγκρισης που χρησιμοποιείται σε δοκιμές βάθους/στίλας. |
| [CubeFace](./cubeface/) | Κάθε πλευρά του υφής χάρτη κύβου |
| [CullFaceMode](./cullfacemode/) | Ποια πλευρά να απορριφθεί |
| [DrawOperation](./drawoperation/) | Οι πρωτόγονοι τύποι προς απόδοση |
| [EntityRendererFeatures](./entityrendererfeatures/) | Τα επιπλέον χαρακτηριστικά που θα παρέχει ο αποδίτης οντοτήτων |
| [FrontFace](./frontface/) | Ορίστε πολύγωνα που βλέπουν προς τα εμπρός και προς τα πίσω |
| [IndexDataType](./indexdatatype/) | Ο τύπος δεδομένων των στοιχείων στο [`IIndexBuffer`](../aspose.threed.render/iindexbuffer/) |
| [PixelFormat](./pixelformat/) | Η μορφή του pixel που χρησιμοποιείται στη μονάδα υφής. |
| [PixelMapMode](./pixelmapmode/) |  |
| [PolygonMode](./polygonmode/) | Η λειτουργία rasterization του πολύγωνου |
| [PresetShaders](./presetshaders/) | Αυτό ορίζει τους προρυθμισμένους εσωτερικούς shaders που χρησιμοποιεί ο αποδίτης. |
| [RenderQueueGroupId](./renderqueuegroupid/) | Το αναγνωριστικό ομάδας της ουράς απόδοσης |
| [RenderStage](./renderstage/) | Το στάδιο απόδοσης |
| [ShaderStage](./shaderstage/) | Στάδιο shader |
| [StencilAction](./stencilaction/) | Οι ενέργειες δοκιμής στίλας |
| [TextureType](./texturetype/) | Ο τύπος του [`ITextureUnit`](../aspose.threed.render/itextureunit/) |


