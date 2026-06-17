---
title: "Transform"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/transform/
---
## Transform class

Una transformación contiene información que permite acceder a la traslación/escala/rotación del objeto o a la matriz de transformación con el coste mínimo.  Esto se usa en la transformación local.  @hideconstructor


## Métodos

### getGeometricTranslation{#getGeometricTranslation}

| Nombre | Descripción |
| --- | --- |
| getGeometricTranslation() | Obtiene o establece la traslación geométrica. La transformación geométrica solo afecta a las entidades adjuntas y deja sin efecto a los nodos hijos. Se combinará como transformación local cuando exporte la transformación geométrica a tipos de archivo que no la soportan. |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| Nombre | Descripción |
| --- | --- |
| setGeometricTranslation(value) | Obtiene o establece la traslación geométrica. La transformación geométrica solo afecta a las entidades adjuntas y deja sin efecto a los nodos hijos. Se combinará como transformación local cuando exporte la transformación geométrica a tipos de archivo que no la soportan. |

 **Result:**



---


### getGeometricScaling{#getGeometricScaling}

| Nombre | Descripción |
| --- | --- |
| getGeometricScaling() | Obtiene o establece el escalado geométrico. La transformación geométrica solo afecta a las entidades adjuntas y deja sin efecto a los nodos hijos. Se combinará como transformación local cuando exporte la transformación geométrica a tipos de archivo que no la soportan. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Nombre | Descripción |
| --- | --- |
| setGeometricScaling(value) | Obtiene o establece el escalado geométrico. La transformación geométrica solo afecta a las entidades adjuntas y deja sin efecto a los nodos hijos. Se combinará como transformación local cuando exporte la transformación geométrica a tipos de archivo que no la soportan. |

 **Result:**



---


### getGeometricRotation{#getGeometricRotation}

| Nombre | Descripción |
| --- | --- |
| getGeometricRotation() | Obtiene o establece la rotación Euler geométrica (medida en grados). La transformación geométrica solo afecta a las entidades adjuntas y deja sin efecto a los nodos hijos. Se combinará como transformación local cuando exporte la transformación geométrica a tipos de archivo que no la soportan. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Nombre | Descripción |
| --- | --- |
| setGeometricRotation(value) | Obtiene o establece la rotación Euler geométrica (medida en grados). La transformación geométrica solo afecta a las entidades adjuntas y deja sin efecto a los nodos hijos. Se combinará como transformación local cuando exporte la transformación geométrica a tipos de archivo que no la soportan. |

 **Result:**



---


### getTranslation{#getTranslation}

| Nombre | Descripción |
| --- | --- |
| getTranslation() | Obtiene o establece la traslación |

 **Result:**



---


### setTranslation{#setTranslation}

| Nombre | Descripción |
| --- | --- |
| setTranslation(value) | Obtiene o establece la traslación |

 **Result:**



---


### getScale{#getScale}

| Nombre | Descripción |
| --- | --- |
| getScale() | Obtiene o establece la escala |

 **Result:**



---


### setScale{#setScale}

| Nombre | Descripción |
| --- | --- |
| setScale(value) | Obtiene o establece la escala |

 **Result:**



---


### getPreRotation{#getPreRotation}

| Nombre | Descripción |
| --- | --- |
| getPreRotation() | Obtiene o establece la pre-rotación representada en grados |

 **Result:**



---


### setPreRotation{#setPreRotation}

| Nombre | Descripción |
| --- | --- |
| setPreRotation(value) | Obtiene o establece la pre-rotación representada en grados |

 **Result:**



---


### getPostRotation{#getPostRotation}

| Nombre | Descripción |
| --- | --- |
| getPostRotation() | Obtiene o establece la post-rotación representada en grados |

 **Result:**



---


### setPostRotation{#setPostRotation}

| Nombre | Descripción |
| --- | --- |
| setPostRotation(value) | Obtiene o establece la post-rotación representada en grados |

 **Result:**



---


### getEulerAngles{#getEulerAngles}

| Nombre | Descripción |
| --- | --- |
| getEulerAngles() | Obtiene o establece la rotación representada en ángulos de Euler, medida en grados |

 **Result:**



---


### setEulerAngles{#setEulerAngles}

| Nombre | Descripción |
| --- | --- |
| setEulerAngles(value) | Obtiene o establece la rotación representada en ángulos de Euler, medida en grados |

 **Result:**



---


### getRotation{#getRotation}

| Nombre | Descripción |
| --- | --- |
| getRotation() | Obtiene o establece la rotación representada en cuaternión. |

 **Result:**



---


### setRotation{#setRotation}

| Nombre | Descripción |
| --- | --- |
| setRotation(value) | Obtiene o establece la rotación representada en cuaternión. |

 **Result:**



---


### getTransformMatrix{#getTransformMatrix}

| Nombre | Descripción |
| --- | --- |
| getTransformMatrix() | Obtiene o establece la matriz de transformación. Asignar a esto restablecerá la Translation, Scale y Rotation, la GeometricRotation, GeometricScaling y GeometricTranslation no se verán afectadas. |

 **Result:**



---


### setTransformMatrix{#setTransformMatrix}

| Nombre | Descripción |
| --- | --- |
| setTransformMatrix(value) | Obtiene o establece la matriz de transformación. Asignar a esto restablecerá la Translation, Scale y Rotation, la GeometricRotation, GeometricScaling y GeometricTranslation no se verán afectadas. |

 **Result:**



---


### getName{#getName}

| Nombre | Descripción |
| --- | --- |
| getName() | Obtiene o establece el nombre. El nombre. |

 **Result:**



---


### setName{#setName}

| Nombre | Descripción |
| --- | --- |
| setName(value) | Obtiene o establece el nombre. El nombre. |

 **Result:**



---


### getProperties{#getProperties}

| Nombre | Descripción |
| --- | --- |
| getProperties() | Obtiene la colección de todas las propiedades. |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| Nombre | Descripción |
| --- | --- |
| setGeometricTranslation(x, y, z) | Establece la traducción geométrica. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no la soporten. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Nombre | Descripción |
| --- | --- |
| setGeometricScaling(sx, sy, sz) | Establece el escalado geométrico. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no la soporten. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Nombre | Descripción |
| --- | --- |
| setGeometricRotation(rx, ry, rz) | Establece la rotación geométrica de Euler (medida en grados). La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no la soporten. |

 **Result:**



---


### setTranslation{#setTranslation}

| Nombre | Descripción |
| --- | --- |
| setTranslation(tx, ty, tz) | Establece la traslación de la transformación actual. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| t | Número | null |
| t | Número | null |
| t | Número | null |

 **Result:**
Transform


---


### setScale{#setScale}

| Nombre | Descripción |
| --- | --- |
| setScale(sx, sy, sz) | Establece la escala de la transformación actual. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| s | Número | null |
| s | Número | null |
| s | Número | null |

 **Result:**
Transform


---


### setEulerAngles{#setEulerAngles}

| Nombre | Descripción |
| --- | --- |
| setEulerAngles(rx, ry, rz) | Establece los ángulos de Euler en grados de la transformación actual. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| r | Número | null |
| r | Número | null |
| r | Número | null |

 **Result:**
Transform


---


### setRotation{#setRotation}

| Nombre | Descripción |
| --- | --- |
| setRotation(rw, rx, ry, rz) | Establece la rotación (como componentes del cuaternión) de la transformación actual. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| r | Número | null |
| r | Número | null |
| r | Número | null |
| r | Número | null |

 **Result:**
Transform


---


### setPreRotation{#setPreRotation}

| Nombre | Descripción |
| --- | --- |
| setPreRotation(rx, ry, rz) | Establece la pre-rotación representada en grados |

 **Result:**
Transform


---


### setPostRotation{#setPostRotation}

| Nombre | Descripción |
| --- | --- |
| setPostRotation(rx, ry, rz) | Establece la post-rotación representada en grados |

 **Result:**
Transform


---


### removeProperty{#removeProperty}

| Nombre | Descripción |
| --- | --- |
| removeProperty(property) | Elimina una propiedad dinámica. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Property | Qué propiedad eliminar |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nombre | Descripción |
| --- | --- |
| removeProperty(property) | Eliminar la propiedad especificada identificada por nombre |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| propert | Cadena | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nombre | Descripción |
| --- | --- |
| getProperty(property) | Obtener el valor de la propiedad especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Cadena | Nombre de la propiedad |

 **Result:**
Objeto


---


### setProperty{#setProperty}

| Nombre | Descripción |
| --- | --- |
| setProperty(property, value) | Establece el valor de la propiedad especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Cadena | Nombre de la propiedad |
| valor | Objeto | El valor de la propiedad |

 **Result:**
Objeto


---


### findProperty{#findProperty}

| Nombre | Descripción |
| --- | --- |
| findProperty(propertyName) | Busca la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| propertyName | Cadena | Nombre de la propiedad. |

 **Result:**
Property


---



