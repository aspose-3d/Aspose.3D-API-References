---
title: "PolygonModifier"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

Βοηθήματα για την τροποποίηση πολυγώνων  @hideconstructor


## Μέθοδοι

### triangulate{#triangulate}

| Όνομα | Περιγραφή |
| --- | --- |
| triangulate(scene) | Μετατρέπει όλα τα πλέγματα βασισμένα σε πολύγωνα σε πλήρες τριγωνικό πλέγμα |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| scene | Scene | Η σκηνή προς επεξεργασία |

 **Result:**



---


### triangulate{#triangulate}

| Όνομα | Περιγραφή |
| --- | --- |
| triangulate(mesh) | Μετατρέπει ένα πλέγμα βασισμένο σε πολύγωνα σε πλήρες τριγωνικό πλέγμα |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | Πλέγμα | Το αρχικό μη τριγωνικό πλέγμα |

 **Result:**
Πλέγμα


---


### mergeMesh{#mergeMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| mergeMesh(scene) | Μετατρέπει ολόκληρη τη σκηνή σε ένα ενιαίο μετασχηματισμένο πλέγμα. Τα στοιχεία Vertex όπως κανονικές/συντεταγμένες υφής δεν υποστηρίζονται ακόμη. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| scene | Scene | Η σκηνή προς συγχώνευση |

 **Result:**
Πλέγμα


---


### mergeMesh{#mergeMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| mergeMesh(node) | Μετατρέπει ολόκληρο τον κόμβο σε ένα ενιαίο μετασχηματισμένο πλέγμα. Τα στοιχεία Vertex όπως κανονικές/συντεταγμένες υφής δεν υποστηρίζονται ακόμη. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόμβος | Κόμβος | Ο κόμβος προς συγχώνευση |

 **Result:**
Πλέγμα


---


### scale{#scale}

| Όνομα | Περιγραφή |
| --- | --- |
| scale(scene, scale) | Κλιμακώνει όλα τα γεωμετρικά σχήματα (Κλιμακώνει τα σημεία ελέγχου, όχι τον πίνακα μετασχηματισμού) σε αυτή τη σκηνή |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| scene | Scene | Η σκηνή προς κλιμάκωση |
| κλίμακα | Vector3 | Ο συντελεστής κλιμάκωσης |

 **Result:**
Πλέγμα


---


### scale{#scale}

| Όνομα | Περιγραφή |
| --- | --- |
| scale(node, scale) | Κλιμακώνει όλα τα γεωμετρικά σχήματα (Κλιμακώνει τα σημεία ελέγχου, όχι τον πίνακα μετασχηματισμού) σε αυτόν τον κόμβο |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόμβος | Κόμβος | Ο κόμβος προς κλιμάκωση |
| κλίμακα | Vector3 | Ο συντελεστής κλιμάκωσης |

 **Result:**
Πλέγμα


---


### generateNormal{#generateNormal}

| Όνομα | Περιγραφή |
| --- | --- |
| generateNormal(mesh) | Δημιουργήστε δεδομένα κανονικών από τον ορισμό του Mesh |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Όνομα | Περιγραφή |
| --- | --- |
| generateUV(mesh, normals) | Δημιουργήστε δεδομένα UV από το δεδομένο εισαγόμενο mesh και τα καθορισμένα δεδομένα κανονικών. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | Πλέγμα | Το εισαγόμενο mesh |
| normals | VertexElementNormal | Τα δεδομένα κανονικών |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Όνομα | Περιγραφή |
| --- | --- |
| generateUV(mesh) | Δημιουργήστε δεδομένα UV από το δεδομένο εισαγόμενο mesh |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | Πλέγμα | Το εισαγόμενο mesh |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Διαιρέστε το mesh σε υπο-πλέγματα με βάση το VertexElementMaterial. Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε τη διάσπαση του mesh σε έναν κόμβο |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| nod | Κόμβος | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Δημιουργήστε παιδικούς κόμβους για κάθε υπο-πλέγμα. |
| removeOldMesh | boolean | Αφαιρέστε το παλιό mesh μετά τη διάσπαση, εάν αυτή η παράμετρος είναι ψευδής, τα παλιά και τα νέα mesh θα συνυπάρχουν. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Διαιρέστε το mesh σε υπο-πλέγματα με βάση το VertexElementMaterial. Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε τη διάσπαση του mesh σε όλους τους κόμβους της σκηνής. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| scen | Scene | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| splitMesh(mesh, policy) | Διαιρέστε το mesh σε υπο-πλέγματα με βάση το VertexElementMaterial. Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Το αρχικό mesh δεν θα τροποποιηθεί. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Όνομα | Περιγραφή |
| --- | --- |
| buildTangentBinormal(scene) | Αυτό θα δημιουργήσει tangent και binormal σε όλα τα mesh της σκηνής. Απαιτείται το Normal, εάν το normal δεν υπάρχει στο mesh, θα δημιουργήσει επίσης τα δεδομένα normal από τη θέση. Απαιτείται επίσης το UV, το mesh θα αγνοηθεί εάν δεν οριστεί UV. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Όνομα | Περιγραφή |
| --- | --- |
| buildTangentBinormal(mesh) | Αυτό θα δημιουργήσει tangent και binormal στο mesh. Normal απαιτείται· εάν το normal δεν υπάρχει στο mesh, θα δημιουργήσει επίσης τα δεδομένα normal από τη θέση. UV επίσης απαιτείται· θα προκληθεί εξαίρεση εάν δεν βρεθεί UV. |

 **Result:**
Mesh[]


---



