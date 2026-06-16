---
title: "RenderFactory"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

Το RenderFactory δημιουργεί όλους τους πόρους που αναπαριστώνται στην αλυσίδα απόδοσης.  @hideconstructor


## Μέθοδοι

### createRenderTexture{#createRenderTexture}

| Όνομα | Περιγραφή |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | Δημιουργήστε έναν στόχο απόδοσης που αποδίδει στην υφή |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| παράμετροι | RenderParameters | Παράμετροι απόδοσης για τη δημιουργία της υφής απόδοσης |
| στόχοι | Αριθμός | Πόσοι στόχοι εξόδου χρώματος |
| πλάτος | Αριθμός | Το πλάτος της υφής απόδοσης |
| height | Αριθμός | Το ύψος της υφής απόδοσης |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Όνομα | Περιγραφή |
| --- | --- |
| createRenderTexture(parameters, width, height) | Δημιουργήστε έναν στόχο απόδοσης που περιέχει 1 στόχο και αποδίδει στην υφή |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| παράμετροι | RenderParameters | Παράμετροι απόδοσης για τη δημιουργία της υφής απόδοσης |
| πλάτος | Αριθμός | Το πλάτος της υφής απόδοσης |
| height | Αριθμός | Το ύψος της υφής απόδοσης |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Όνομα | Περιγραφή |
| --- | --- |
| createDescriptorSet(shader) | Δημιουργήστε το σύνολο περιγραφέων για το καθορισμένο πρόγραμμα σκίασης. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shader | ShaderProgram | Το πρόγραμμα σκίασης |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Όνομα | Περιγραφή |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | Δημιουργήστε έναν στόχο απόδοσης που περιέχει 1 κυβική υφή |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| παράμετροι | RenderParameters | Παράμετροι απόδοσης για τη δημιουργία της υφής απόδοσης |
| πλάτος | Αριθμός | Το πλάτος της υφής απόδοσης |
| height | Αριθμός | Το ύψος της υφής απόδοσης |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Όνομα | Περιγραφή |
| --- | --- |
| createRenderWindow(parameters, handle) | Δημιουργήστε έναν στόχο απόδοσης που αποδίδει στο εγγενές παράθυρο. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| παράμετροι | RenderParameters | Παράμετροι απόδοσης για τη δημιουργία του παραθύρου απόδοσης |
| αναγνωριστικό | WindowHandle | Το αναγνωριστικό του παραθύρου για απόδοση |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| Όνομα | Περιγραφή |
| --- | --- |
| createVertexBuffer(declaration) | Δημιουργήστε ένα αντικείμενο com.aspose.threed.IVertexBuffer για την αποθήκευση των πληροφοριών κορυφής του πολύγωνου. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| Όνομα | Περιγραφή |
| --- | --- |
| createIndexBuffer() | Δημιουργήστε ένα αντικείμενο com.aspose.threed.IIndexBuffer για την αποθήκευση των πληροφοριών προσώπων του πολύγωνου. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| createTextureUnit(textureType) | Δημιουργήστε μια μονάδα υφής που μπορεί να προσπελαστεί από το shader. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| Όνομα | Περιγραφή |
| --- | --- |
| createTextureUnit() | Δημιουργήστε μια 2Δ μονάδα υφής που μπορεί να προσπελαστεί από το shader. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| Όνομα | Περιγραφή |
| --- | --- |
| createShaderProgram(shaderSource) | Δημιουργήστε ένα αντικείμενο ShaderProgram |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shaderSource | ShaderSource | Ο κώδικας πηγής του shader |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| Όνομα | Περιγραφή |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Δημιουργήστε μια προρυθμισμένη γραφική pipeline με προρυθμισμένο shader/renderState/vertexDeclaration και drawOperation. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shader | ShaderProgram | Το shader που χρησιμοποιείται στην απόδοση |
| renderState | RenderState | Η renderState που χρησιμοποιείται στην απόδοση |
| vertexDeclaration | VertexDeclaration | Η vertexDeclaration των εισερχόμενων δεδομένων κορυφής |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Όνομα | Περιγραφή |
| --- | --- |
| createUniformBuffer(size) | Δημιουργήστε ένα νέο uniform buffer στην πλευρά του GPU με προ‑καθορισμένο μέγεθος. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| μέγεθος | Αριθμός | Το μέγεθος του uniform buffer |

 **Result:**
IBuffer


---



