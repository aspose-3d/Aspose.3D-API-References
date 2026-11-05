---
title: "Trasformazione"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/transform/
---
## Transform class

Una trasformazione contiene informazioni che consentono l'accesso alla traslazione/scalatura/rotazione dell'oggetto o alla matrice di trasformazione al costo minimo  Questo è usato dalla trasformazione locale.  @hideconstructor


## Metodi

### getGeometricTranslation{#getGeometricTranslation}

| Nome | Descrizione |
| --- | --- |
| getGeometricTranslation() | Ottiene o imposta la traslazione geometrica. La trasformazione geometrica influisce solo sulle entità collegate e lascia inalterati i nodi figli. Verrà unita come trasformazione locale quando si esporta la trasformazione geometrica in tipi di file che non la supportano. |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| Nome | Descrizione |
| --- | --- |
| setGeometricTranslation(value) | Ottiene o imposta la traslazione geometrica. La trasformazione geometrica influisce solo sulle entità collegate e lascia inalterati i nodi figli. Verrà unita come trasformazione locale quando si esporta la trasformazione geometrica in tipi di file che non la supportano. |

 **Result:**



---


### getGeometricScaling{#getGeometricScaling}

| Nome | Descrizione |
| --- | --- |
| getGeometricScaling() | Ottiene o imposta la scala geometrica. La trasformazione geometrica influisce solo sulle entità collegate e lascia i nodi figli inalterati. Verrà unita come trasformazione locale quando esporti la trasformazione geometrica in tipi di file che non la supportano. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Nome | Descrizione |
| --- | --- |
| setGeometricScaling(value) | Ottiene o imposta la scala geometrica. La trasformazione geometrica influisce solo sulle entità collegate e lascia i nodi figli inalterati. Verrà unita come trasformazione locale quando esporti la trasformazione geometrica in tipi di file che non la supportano. |

 **Result:**



---


### getGeometricRotation{#getGeometricRotation}

| Nome | Descrizione |
| --- | --- |
| getGeometricRotation() | Ottiene o imposta la rotazione Euler geometrica (misurata in gradi). La trasformazione geometrica influisce solo sulle entità collegate e lascia i nodi figli inalterati. Verrà unita come trasformazione locale quando esporti la trasformazione geometrica in tipi di file che non la supportano. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Nome | Descrizione |
| --- | --- |
| setGeometricRotation(value) | Ottiene o imposta la rotazione Euler geometrica (misurata in gradi). La trasformazione geometrica influisce solo sulle entità collegate e lascia i nodi figli inalterati. Verrà unita come trasformazione locale quando esporti la trasformazione geometrica in tipi di file che non la supportano. |

 **Result:**



---


### getTranslation{#getTranslation}

| Nome | Descrizione |
| --- | --- |
| getTranslation() | Ottiene o imposta la traslazione |

 **Result:**



---


### setTranslation{#setTranslation}

| Nome | Descrizione |
| --- | --- |
| setTranslation(value) | Ottiene o imposta la traslazione |

 **Result:**



---


### getScale{#getScale}

| Nome | Descrizione |
| --- | --- |
| getScale() | Ottiene o imposta la scala |

 **Result:**



---


### setScale{#setScale}

| Nome | Descrizione |
| --- | --- |
| setScale(value) | Ottiene o imposta la scala |

 **Result:**



---


### getPreRotation{#getPreRotation}

| Nome | Descrizione |
| --- | --- |
| getPreRotation() | Ottiene o imposta la pre-rotazione rappresentata in gradi |

 **Result:**



---


### setPreRotation{#setPreRotation}

| Nome | Descrizione |
| --- | --- |
| setPreRotation(value) | Ottiene o imposta la pre-rotazione rappresentata in gradi |

 **Result:**



---


### getPostRotation{#getPostRotation}

| Nome | Descrizione |
| --- | --- |
| getPostRotation() | Ottiene o imposta la post-rotazione rappresentata in gradi |

 **Result:**



---


### setPostRotation{#setPostRotation}

| Nome | Descrizione |
| --- | --- |
| setPostRotation(value) | Ottiene o imposta la post-rotazione rappresentata in gradi |

 **Result:**



---


### getEulerAngles{#getEulerAngles}

| Nome | Descrizione |
| --- | --- |
| getEulerAngles() | Ottiene o imposta la rotazione rappresentata in angoli Euler, misurata in gradi |

 **Result:**



---


### setEulerAngles{#setEulerAngles}

| Nome | Descrizione |
| --- | --- |
| setEulerAngles(value) | Ottiene o imposta la rotazione rappresentata in angoli Euler, misurata in gradi |

 **Result:**



---


### getRotation{#getRotation}

| Nome | Descrizione |
| --- | --- |
| getRotation() | Ottiene o imposta la rotazione rappresentata in quaternione. |

 **Result:**



---


### setRotation{#setRotation}

| Nome | Descrizione |
| --- | --- |
| setRotation(value) | Ottiene o imposta la rotazione rappresentata in quaternione. |

 **Result:**



---


### getTransformMatrix{#getTransformMatrix}

| Nome | Descrizione |
| --- | --- |
| getTransformMatrix() | Ottiene o imposta la matrice di trasformazione. Assegnare questo resetterà la Traslazione, la Scala e la Rotazione, mentre la GeometricRotation, la GeometricScaling e la GeometricTranslation non saranno influenzate. |

 **Result:**



---


### setTransformMatrix{#setTransformMatrix}

| Nome | Descrizione |
| --- | --- |
| setTransformMatrix(value) | Ottiene o imposta la matrice di trasformazione. Assegnare questo resetterà la Traslazione, la Scala e la Rotazione, mentre la GeometricRotation, la GeometricScaling e la GeometricTranslation non saranno influenzate. |

 **Result:**



---


### getName{#getName}

| Nome | Descrizione |
| --- | --- |
| getName() | Ottiene o imposta il nome. Il nome. |

 **Result:**



---


### setName{#setName}

| Nome | Descrizione |
| --- | --- |
| setName(value) | Ottiene o imposta il nome. Il nome. |

 **Result:**



---


### getProperties{#getProperties}

| Nome | Descrizione |
| --- | --- |
| getProperties() | Ottiene la collezione di tutte le proprietà. |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| Nome | Descrizione |
| --- | --- |
| setGeometricTranslation(x, y, z) | Imposta la traslazione geometrica. La trasformazione geometrica influisce solo sulle entità collegate e lascia i nodi figli inalterati. Verrà unita come trasformazione locale quando esporti la trasformazione geometrica in tipi di file che non la supportano. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Nome | Descrizione |
| --- | --- |
| setGeometricScaling(sx, sy, sz) | Imposta la scala geometrica. La trasformazione geometrica influisce solo sulle entità collegate e lascia i nodi figli inalterati. Verrà unita come trasformazione locale quando esporti la trasformazione geometrica in tipi di file che non la supportano. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Nome | Descrizione |
| --- | --- |
| setGeometricRotation(rx, ry, rz) | Imposta la rotazione Euler geometrica (misurata in gradi). La trasformazione geometrica influisce solo sulle entità collegate e lascia inalterati i nodi figlio. Verrà unita come trasformazione locale quando esporti la trasformazione geometrica in formati di file che non la supportano. |

 **Result:**



---


### setTranslation{#setTranslation}

| Nome | Descrizione |
| --- | --- |
| setTranslation(tx, ty, tz) | Imposta la traslazione della trasformazione corrente. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| t | Numero | null |
| t | Numero | null |
| t | Numero | null |

 **Result:**
Trasformazione


---


### setScale{#setScale}

| Nome | Descrizione |
| --- | --- |
| setScale(sx, sy, sz) | Imposta la scala della trasformazione corrente. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| s | Numero | null |
| s | Numero | null |
| s | Numero | null |

 **Result:**
Trasformazione


---


### setEulerAngles{#setEulerAngles}

| Nome | Descrizione |
| --- | --- |
| setEulerAngles(rx, ry, rz) | Imposta gli angoli Euler in gradi della trasformazione corrente. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| r | Numero | null |
| r | Numero | null |
| r | Numero | null |

 **Result:**
Trasformazione


---


### setRotation{#setRotation}

| Nome | Descrizione |
| --- | --- |
| setRotation(rw, rx, ry, rz) | Imposta la rotazione (come componenti quaternion) della trasformazione corrente. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| r | Numero | null |
| r | Numero | null |
| r | Numero | null |
| r | Numero | null |

 **Result:**
Trasformazione


---


### setPreRotation{#setPreRotation}

| Nome | Descrizione |
| --- | --- |
| setPreRotation(rx, ry, rz) | Imposta la pre-rotazione rappresentata in gradi |

 **Result:**
Trasformazione


---


### setPostRotation{#setPostRotation}

| Nome | Descrizione |
| --- | --- |
| setPostRotation(rx, ry, rz) | Imposta la post-rotazione rappresentata in gradi |

 **Result:**
Trasformazione


---


### removeProperty{#removeProperty}

| Nome | Descrizione |
| --- | --- |
| removeProperty(property) | Rimuove una proprietà dinamica. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | Proprietà | Quale proprietà rimuovere |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nome | Descrizione |
| --- | --- |
| removeProperty(property) | Rimuovi la proprietà specificata identificata per nome |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nome | Descrizione |
| --- | --- |
| getProperty(property) | Ottieni il valore della proprietà specificata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | String | Nome della proprietà |

 **Result:**
Object


---


### setProperty{#setProperty}

| Nome | Descrizione |
| --- | --- |
| setProperty(property, value) | Imposta il valore della proprietà specificata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | String | Nome della proprietà |
| valore | Object | Il valore della proprietà |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nome | Descrizione |
| --- | --- |
| findProperty(propertyName) | Trova la proprietà. Può essere una proprietà dinamica (Creata da CreateDynamicProperty/SetProperty) o una proprietà nativa (Identificata per il suo nome) |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | String | Nome della proprietà. |

 **Result:**
Proprietà


---



