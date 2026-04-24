---
title: ICommandList
second_title: Aspose.3D for Java API Reference
description: Κωδικοποιεί μια ακολουθία εντολών που θα σταλούν στην GPU για απόδοση.
type: docs
weight: 240
url: /el/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

Κωδικοποιεί μια ακολουθία εντολών που θα σταλούν στην GPU για απόδοση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | Bind the descriptor set to current pipeline |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | Δέσμευση του buffer δεικτών για απόδοση |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | Δέσμευση του αντικειμένου pipeline για απόδοση |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | Δέσμευση του buffer κορυφών για απόδοση |
| [draw()](#draw--) | Σχεδίαση χωρίς buffer δεικτών |
| [draw(int start, int count)](#draw-int-int-) | Σχεδίαση χωρίς buffer δεικτών |
| [drawIndex()](#drawIndex--) | Δημιουργία εντολής σχεδίασης με δείκτες σε λίστα εντολών |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | Δημιουργία εντολής σχεδίασης με δείκτες σε λίστα εντολών |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | Προώθηση της σταθεράς στο pipeline |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | Προώθηση της σταθεράς στο pipeline |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


Bind the descriptor set to current pipeline

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


Δέσμευση του buffer δεικτών για απόδοση

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


Δέσμευση του αντικειμένου pipeline για απόδοση

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


Δέσμευση του buffer κορυφών για απόδοση

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


Σχεδίαση χωρίς buffer δεικτών

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


Σχεδίαση χωρίς buffer δεικτών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έναρξη | int |  |
| πλήθος | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


Δημιουργία εντολής σχεδίασης με δείκτες σε λίστα εντολών

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


Δημιουργία εντολής σχεδίασης με δείκτες σε λίστα εντολών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έναρξη | int | Ο πρώτος δείκτης για σχεδίαση |
| πλήθος | int | Ο αριθμός των δεικτών για σχεδίαση |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


Προώθηση της σταθεράς στο pipeline

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| στάδιο | int | Ποιο στάδιο του shader θα καταναλώσει τα σταθερά δεδομένα |
| δεδομένα | byte[] | Τα δεδομένα που θα σταλούν στο shader |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


Προώθηση της σταθεράς στο pipeline

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| στάδιο | int | Ποιο στάδιο του shader θα καταναλώσει τα σταθερά δεδομένα |
| δεδομένα | byte[] | Τα δεδομένα που θα σταλούν στο shader |
| μέγεθος | int | Bytes προς εγγραφή στο pipeline |

