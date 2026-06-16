---
title: "ICommandList"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Encode une séquence de commandes qui seront envoyées au GPU pour le rendu."
type: docs
weight: 240
url: /fr/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

Encode une séquence de commandes qui seront envoyées au GPU pour le rendu.
## Méthodes

| Méthode | Description |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | Lier le jeu de descripteurs au pipeline actuel |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | Lier le tampon d'index pour le rendu |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | Lier l'instance du pipeline pour le rendu |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | Lier le tampon de sommets pour le rendu |
| [draw()](#draw--) | Dessiner sans tampon d'index |
| [draw(int start, int count)](#draw-int-int-) | Dessiner sans tampon d'index |
| [drawIndex()](#drawIndex--) | Émettre un dessin indexé dans une liste de commandes |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | Émettre un dessin indexé dans une liste de commandes |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | Pousser la constante vers le pipeline |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | Pousser la constante vers le pipeline |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


Lier le jeu de descripteurs au pipeline actuel

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


Lier le tampon d'index pour le rendu

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


Lier l'instance du pipeline pour le rendu

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


Lier le tampon de sommets pour le rendu

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


Dessiner sans tampon d'index

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


Dessiner sans tampon d'index

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| début | int |  |
| nombre | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


Émettre un dessin indexé dans une liste de commandes

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


Émettre un dessin indexé dans une liste de commandes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| début | int | Le premier indice à dessiner |
| nombre | int | Le nombre d'indices à dessiner |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


Pousser la constante vers le pipeline

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| étape | int | Quelle étape du shader consommera les données constantes |
| données | byte[] | Les données qui seront envoyées au shader |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


Pousser la constante vers le pipeline

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| étape | int | Quelle étape du shader consommera les données constantes |
| données | byte[] | Les données qui seront envoyées au shader |
| taille | int | Octets à écrire dans le pipeline |

