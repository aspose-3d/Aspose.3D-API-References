---
title: "Discreet3dsSaveOptions"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Opzioni di salvataggio per file 3DS.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Costruttore di Discreet3dsSaveOptions |

 **Result:**



---


### getExportLight{#getExportLight}

| Nome | Descrizione |
| --- | --- |
| getExportLight() | Ottiene o imposta se esportare tutte le luci nella scena. |

 **Result:**



---


### setExportLight{#setExportLight}

| Nome | Descrizione |
| --- | --- |
| setExportLight(value) | Ottiene o imposta se esportare tutte le luci nella scena. |

 **Result:**



---


### getExportCamera{#getExportCamera}

| Nome | Descrizione |
| --- | --- |
| getExportCamera() | Ottiene o imposta se esportare tutte le telecamere nella scena. |

 **Result:**



---


### setExportCamera{#setExportCamera}

| Nome | Descrizione |
| --- | --- |
| setExportCamera(value) | Ottiene o imposta se esportare tutte le telecamere nella scena. |

 **Result:**



---


### getDuplicatedNameSeparator{#getDuplicatedNameSeparator}

| Nome | Descrizione |
| --- | --- |
| getDuplicatedNameSeparator() | Il separatore tra il nome dell'oggetto e il contatore dei duplicati, il valore predefinito è "_". Quando la scena contiene oggetti che utilizzano lo stesso nome, l'esportatore 3DS di Aspose.3D genererà un nome diverso per l'oggetto. Ad esempio, ci sono due nodi chiamati "Box", il primo nodo avrà il nome "Box", e il secondo otterrà un nuovo nome "Box_2" usando la configurazione predefinita. |

 **Result:**



---


### setDuplicatedNameSeparator{#setDuplicatedNameSeparator}

| Nome | Descrizione |
| --- | --- |
| setDuplicatedNameSeparator(value) | Il separatore tra il nome dell'oggetto e il contatore dei duplicati, il valore predefinito è "_". Quando la scena contiene oggetti che utilizzano lo stesso nome, l'esportatore 3DS di Aspose.3D genererà un nome diverso per l'oggetto. Ad esempio, ci sono due nodi chiamati "Box", il primo nodo avrà il nome "Box", e il secondo otterrà un nuovo nome "Box_2" usando la configurazione predefinita. |

 **Result:**



---


### getDuplicatedNameCounterBase{#getDuplicatedNameCounterBase}

| Nome | Descrizione |
| --- | --- |
| getDuplicatedNameCounterBase() | Il contatore usato per generare un nuovo nome per i nomi duplicati, il valore predefinito è 2. |

 **Result:**



---


### setDuplicatedNameCounterBase{#setDuplicatedNameCounterBase}

| Nome | Descrizione |
| --- | --- |
| setDuplicatedNameCounterBase(value) | Il contatore usato per generare un nuovo nome per i nomi duplicati, il valore predefinito è 2. |

 **Result:**



---


### getDuplicatedNameCounterFormat{#getDuplicatedNameCounterFormat}

| Nome | Descrizione |
| --- | --- |
| getDuplicatedNameCounterFormat() | Il formato del contatore dei duplicati, il valore predefinito è una stringa vuota. |

 **Result:**



---


### setDuplicatedNameCounterFormat{#setDuplicatedNameCounterFormat}

| Nome | Descrizione |
| --- | --- |
| setDuplicatedNameCounterFormat(value) | Il formato del contatore dei duplicati, il valore predefinito è una stringa vuota. |

 **Result:**



---


### getMasterScale{#getMasterScale}

| Nome | Descrizione |
| --- | --- |
| getMasterScale() | Ottiene o imposta la scala principale usata nell'esportazione. |

 **Result:**



---


### setMasterScale{#setMasterScale}

| Nome | Descrizione |
| --- | --- |
| setMasterScale(value) | Ottiene o imposta la scala principale usata nell'esportazione. |

 **Result:**



---


### getGammaCorrectedColor{#getGammaCorrectedColor}

| Nome | Descrizione |
| --- | --- |
| getGammaCorrectedColor() | Un file 3ds può contenere il colore originale e il colore corretto gamma per lo stesso attributo; impostando questo su true verrà usato il colore corretto gamma se possibile, altrimenti Aspose.3D proverà a utilizzare il colore originale. |

 **Result:**



---


### setGammaCorrectedColor{#setGammaCorrectedColor}

| Nome | Descrizione |
| --- | --- |
| setGammaCorrectedColor(value) | Un file 3ds può contenere il colore originale e il colore corretto gamma per lo stesso attributo; impostando questo su true verrà usato il colore corretto gamma se possibile, altrimenti Aspose.3D proverà a utilizzare il colore originale. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Nome | Descrizione |
| --- | --- |
| getFlipCoordinateSystem() | Ottiene o imposta il sistema di coordinate invertito dei punti di controllo/normali durante l'importazione/esportazione. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Nome | Descrizione |
| --- | --- |
| setFlipCoordinateSystem(value) | Ottiene o imposta il sistema di coordinate invertito dei punti di controllo/normali durante l'importazione/esportazione. |

 **Result:**



---


### getHighPreciseColor{#getHighPreciseColor}

| Nome | Descrizione |
| --- | --- |
| getHighPreciseColor() | Se questo è true, il file 3ds generato utilizzerà colori ad alta precisione, il che significa che ogni canale rosso/verde/blu è in float a 32 bit. Altrimenti il file generato utilizzerà colori a 24 bit, ogni canale usa un byte a 8 bit. Il valore predefinito è false, perché non tutte le applicazioni supportano il colore ad alta precisione. |

 **Result:**



---


### setHighPreciseColor{#setHighPreciseColor}

| Nome | Descrizione |
| --- | --- |
| setHighPreciseColor(value) | Se questo è true, il file 3ds generato utilizzerà colori ad alta precisione, il che significa che ogni canale rosso/verde/blu è in float a 32 bit. Altrimenti il file generato utilizzerà colori a 24 bit, ogni canale usa un byte a 8 bit. Il valore predefinito è false, perché non tutte le applicazioni supportano il colore ad alta precisione. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Nome | Descrizione |
| --- | --- |
| getExportTextures() | Prova a copiare le texture utilizzate nella scena nella directory di output. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Nome | Descrizione |
| --- | --- |
| setExportTextures(value) | Prova a copiare le texture utilizzate nella scena nella directory di output. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Nome | Descrizione |
| --- | --- |
| getFileFormat() | Ottiene il formato file specificato nell'opzione Salva/Carica corrente. |

 **Result:**



---


### getEncoding{#getEncoding}

| Nome | Descrizione |
| --- | --- |
| getEncoding() | Ottiene o imposta la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Nome | Descrizione |
| --- | --- |
| getFileSystem() | Consente all'utente di gestire come amministrare le dipendenze esterne durante il caricamento/salvataggio. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Nome | Descrizione |
| --- | --- |
| setFileSystem(value) | Consente all'utente di gestire come amministrare le dipendenze esterne durante il caricamento/salvataggio. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Nome | Descrizione |
| --- | --- |
| getLookupPaths() | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare i file esterni da caricare. |

 **Result:**



---


### getFileName{#getFileName}

| Nome | Descrizione |
| --- | --- |
| getFileName() | Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Nome | Descrizione |
| --- | --- |
| setFileName(value) | Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ. |

 **Result:**



---



