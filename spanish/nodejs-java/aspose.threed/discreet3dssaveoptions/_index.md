---
title: "Discreet3dsSaveOptions"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Opciones de guardado para archivo 3DS.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Constructor de Discreet3dsSaveOptions |

 **Result:**



---


### getExportLight{#getExportLight}

| Nombre | Descripción |
| --- | --- |
| getExportLight() | Obtiene o establece si se exportan todas las luces en la escena. |

 **Result:**



---


### setExportLight{#setExportLight}

| Nombre | Descripción |
| --- | --- |
| setExportLight(value) | Obtiene o establece si se exportan todas las luces en la escena. |

 **Result:**



---


### getExportCamera{#getExportCamera}

| Nombre | Descripción |
| --- | --- |
| getExportCamera() | Obtiene o establece si se exportan todas las cámaras en la escena. |

 **Result:**



---


### setExportCamera{#setExportCamera}

| Nombre | Descripción |
| --- | --- |
| setExportCamera(value) | Obtiene o establece si se exportan todas las cámaras en la escena. |

 **Result:**



---


### getDuplicatedNameSeparator{#getDuplicatedNameSeparator}

| Nombre | Descripción |
| --- | --- |
| getDuplicatedNameSeparator() | El separador entre el nombre del objeto y el contador duplicado, el valor predeterminado es "_". Cuando la escena contiene objetos que usan el mismo nombre, el exportador 3DS de Aspose.3D generará un nombre diferente para el objeto. Por ejemplo, hay dos nodos llamados "Box", el primer nodo tendrá el nombre "Box", y el segundo nodo obtendrá un nuevo nombre "Box_2" usando la configuración predeterminada. |

 **Result:**



---


### setDuplicatedNameSeparator{#setDuplicatedNameSeparator}

| Nombre | Descripción |
| --- | --- |
| setDuplicatedNameSeparator(value) | El separador entre el nombre del objeto y el contador duplicado, el valor predeterminado es "_". Cuando la escena contiene objetos que usan el mismo nombre, el exportador 3DS de Aspose.3D generará un nombre diferente para el objeto. Por ejemplo, hay dos nodos llamados "Box", el primer nodo tendrá el nombre "Box", y el segundo nodo obtendrá un nuevo nombre "Box_2" usando la configuración predeterminada. |

 **Result:**



---


### getDuplicatedNameCounterBase{#getDuplicatedNameCounterBase}

| Nombre | Descripción |
| --- | --- |
| getDuplicatedNameCounterBase() | El contador usado para generar un nuevo nombre para nombres duplicados, el valor predeterminado es 2. |

 **Result:**



---


### setDuplicatedNameCounterBase{#setDuplicatedNameCounterBase}

| Nombre | Descripción |
| --- | --- |
| setDuplicatedNameCounterBase(value) | El contador usado para generar un nuevo nombre para nombres duplicados, el valor predeterminado es 2. |

 **Result:**



---


### getDuplicatedNameCounterFormat{#getDuplicatedNameCounterFormat}

| Nombre | Descripción |
| --- | --- |
| getDuplicatedNameCounterFormat() | El formato del contador duplicado, el valor predeterminado es una cadena vacía. |

 **Result:**



---


### setDuplicatedNameCounterFormat{#setDuplicatedNameCounterFormat}

| Nombre | Descripción |
| --- | --- |
| setDuplicatedNameCounterFormat(value) | El formato del contador duplicado, el valor predeterminado es una cadena vacía. |

 **Result:**



---


### getMasterScale{#getMasterScale}

| Nombre | Descripción |
| --- | --- |
| getMasterScale() | Obtiene o establece la escala maestra utilizada en la exportación. |

 **Result:**



---


### setMasterScale{#setMasterScale}

| Nombre | Descripción |
| --- | --- |
| setMasterScale(value) | Obtiene o establece la escala maestra utilizada en la exportación. |

 **Result:**



---


### getGammaCorrectedColor{#getGammaCorrectedColor}

| Nombre | Descripción |
| --- | --- |
| getGammaCorrectedColor() | Un archivo 3ds puede contener color original y color corregido por gamma para el mismo atributo. Configurarlo en true hará que se use el color corregido por gamma si es posible; de lo contrario, Aspose.3D intentará usar el color original. |

 **Result:**



---


### setGammaCorrectedColor{#setGammaCorrectedColor}

| Nombre | Descripción |
| --- | --- |
| setGammaCorrectedColor(value) | Un archivo 3ds puede contener color original y color corregido por gamma para el mismo atributo. Configurarlo en true hará que se use el color corregido por gamma si es posible; de lo contrario, Aspose.3D intentará usar el color original. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Nombre | Descripción |
| --- | --- |
| getFlipCoordinateSystem() | Obtiene o establece el sistema de coordenadas invertido de los puntos de control/normal durante la importación/exportación. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Nombre | Descripción |
| --- | --- |
| setFlipCoordinateSystem(value) | Obtiene o establece el sistema de coordenadas invertido de los puntos de control/normal durante la importación/exportación. |

 **Result:**



---


### getHighPreciseColor{#getHighPreciseColor}

| Nombre | Descripción |
| --- | --- |
| getHighPreciseColor() | Si esto es true, el archivo 3ds generado usará color de alta precisión, lo que significa que cada canal de rojo/verde/azul está en punto flotante de 32 bits. De lo contrario, el archivo generado usará color de 24 bits, cada canal usa un byte de 8 bits. El valor predeterminado es false, porque no todas las aplicaciones admiten el color de alta precisión. |

 **Result:**



---


### setHighPreciseColor{#setHighPreciseColor}

| Nombre | Descripción |
| --- | --- |
| setHighPreciseColor(value) | Si esto es true, el archivo 3ds generado usará color de alta precisión, lo que significa que cada canal de rojo/verde/azul está en punto flotante de 32 bits. De lo contrario, el archivo generado usará color de 24 bits, cada canal usa un byte de 8 bits. El valor predeterminado es false, porque no todas las aplicaciones admiten el color de alta precisión. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Nombre | Descripción |
| --- | --- |
| getExportTextures() | Intenta copiar las texturas usadas en la escena al directorio de salida. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Nombre | Descripción |
| --- | --- |
| setExportTextures(value) | Intenta copiar las texturas usadas en la escena al directorio de salida. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Nombre | Descripción |
| --- | --- |
| getFileFormat() | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |

 **Result:**



---


### getEncoding{#getEncoding}

| Nombre | Descripción |
| --- | --- |
| getEncoding() | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Nombre | Descripción |
| --- | --- |
| getFileSystem() | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Nombre | Descripción |
| --- | --- |
| setFileSystem(value) | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Nombre | Descripción |
| --- | --- |
| getLookupPaths() | Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permiten que Aspose.3D busque el archivo externo para cargarlo. |

 **Result:**



---


### getFileName{#getFileName}

| Nombre | Descripción |
| --- | --- |
| getFileName() | El nombre de archivo de la escena de exportación/importación. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Nombre | Descripción |
| --- | --- |
| setFileName(value) | El nombre de archivo de la escena de exportación/importación. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |

 **Result:**



---



