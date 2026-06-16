---
title: "TriMesh"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un TriMesh contient des données brutes pouvant être utilisées directement par le GPU."
type: docs
weight: 194
url: /fr/java/com.aspose.threed/trimesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
java.lang.Iterable
```
public class TriMesh extends Entity implements Iterable<Vertex>
```

Un TriMesh contient des données brutes qui peuvent être utilisées directement par le GPU. Cette classe est un utilitaire pour aider à construire un maillage qui ne contient que des données par sommet. **Example:** Le code suivant montre comment créer un TriMesh avec une disposition mémoire personnalisée, et l'exporter vers un fichier.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TriMesh(String name, VertexDeclaration declaration)](#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-) | Initialiser une instance de [TriMesh](../../com.aspose.threed/trimesh) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addTriangle(int a, int b, int c)](#addTriangle-int-int-int-) | Ajouter un nouveau triangle |
| [beginVertex()](#beginVertex--) | Commencer l'ajout de vertex |
| [copyFrom(TriMesh input, VertexDeclaration vd)](#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-) | Copier le [TriMesh](../../com.aspose.threed/trimesh) depuis l'entrée avec une nouvelle disposition de vertex |
| [endVertex()](#endVertex--) | Terminer l'ajout de vertex |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [fromMesh(Mesh mesh)](#fromMesh-com.aspose.threed.Mesh-) | Créer un TriMesh à partir d'un objet maillage donné, la déclaration de vertex étant basée sur la structure du maillage d'entrée. |
| [fromMesh(Mesh mesh, boolean useFloat)](#fromMesh-com.aspose.threed.Mesh-boolean-) | Créer un TriMesh à partir d'un objet maillage donné, la déclaration de vertex étant basée sur la structure du maillage d'entrée. |
| [fromMesh(VertexDeclaration declaration, Mesh mesh)](#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-) | Créer un TriMesh à partir d'un objet maillage donné avec la disposition de vertex spécifiée. |
| [fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)](#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-) | Créer un TriMesh à partir de données brutes |
| [getBoundingBox()](#getBoundingBox--) | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |
| [getCapacity()](#getCapacity--) | La capacité des vertex pré-alloués. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |
| [getExcluded()](#getExcluded--) | Obtient si l'entité doit être exclue lors de l'exportation. |
| [getIndicesCount()](#getIndicesCount--) | Le nombre d'indices dans ce [TriMesh](../../com.aspose.threed/trimesh) |
| [getIntIndices()](#getIntIndices--) | Convertir les indices en tableau d'entiers 32 bits |
| [getName()](#getName--) | Obtient le nom. |
| [getParentNode()](#getParentNode--) | Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [getParentNodes()](#getParentNodes--) | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getScene()](#getScene--) | Obtient la scène à laquelle cet objet appartient |
| [getShortIndices()](#getShortIndices--) | Convertir les indices en tableau d'entiers 16 bits |
| [getUnmergedVerticesCount()](#getUnmergedVerticesCount--) | Le nombre de vertex non fusionnés fournis par [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) et [endVertex](../../com.aspose.threed/trimesh\#endVertex). |
| [getVertexDeclaration()](#getVertexDeclaration--) | La disposition des vertex du [TriMesh](../../com.aspose.threed/trimesh). |
| [getVerticesCount()](#getVerticesCount--) | Le nombre de vertex dans ce [TriMesh](../../com.aspose.threed/trimesh) |
| [getVerticesSizeInBytes()](#getVerticesSizeInBytes--) | La taille totale de tous les vertex en octets |
| [hashCode()](#hashCode--) |  |
| [indicesToArray(int[][] result)](#indicesToArray-int-----) | Convertir les indices en tableau d'entiers 32 bits |
| [indicesToArray(short[][] result)](#indicesToArray-short-----) | Convertir les indices en tableau d'entiers 16 bits |
| [iterator()](#iterator--) | Obtenir l'énumérateur pour énumérer les [Vertex](../../com.aspose.threed/vertex) |
| [loadVerticesFromBytes(byte[] verticesInBytes)](#loadVerticesFromBytes-byte---) | Charger les vertex à partir d'octets, la longueur des octets doit être un multiple entier de la taille d'un vertex. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(int idx, VertexField field)](#readDouble-int-com.aspose.threed.VertexField-) | Lire le champ double |
| [readFVector2(int idx, VertexField field)](#readFVector2-int-com.aspose.threed.VertexField-) | Lire le champ vector2 |
| [readFVector3(int idx, VertexField field)](#readFVector3-int-com.aspose.threed.VertexField-) | Lire le champ vector3 |
| [readFVector4(int idx, VertexField field)](#readFVector4-int-com.aspose.threed.VertexField-) | Lire le champ vector4 |
| [readFloat(int idx, VertexField field)](#readFloat-int-com.aspose.threed.VertexField-) | Lire le champ float |
| [readVector2(int idx, VertexField field)](#readVector2-int-com.aspose.threed.VertexField-) | Lire le champ vector2 |
| [readVector3(int idx, VertexField field)](#readVector3-int-com.aspose.threed.VertexField-) | Lire le champ vector3 |
| [readVector4(int idx, VertexField field)](#readVector4-int-com.aspose.threed.VertexField-) | Lire le champ vector4 |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Définit si l'entité doit être exclue lors de l'exportation. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [toString()](#toString--) | Obtient la représentation sous forme de chaîne de [TriMesh](../../com.aspose.threed/trimesh) |
| [verticesToArray()](#verticesToArray--) | Convertir les données des sommets en tableau d'octets |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write16bIndicesTo(Stream stream)](#write16bIndicesTo-com.aspose.threed.Stream-) | Écrire les données d'indices en entier 16 bits vers le flux **Example:** |
| [write16bIndicesTo(OutputStream stream)](#write16bIndicesTo-java.io.OutputStream-) | Écrire les données d'indices en entier 16 bits vers le flux |
| [write32bIndicesTo(Stream stream)](#write32bIndicesTo-com.aspose.threed.Stream-) | Écrire les données d'indices en entier 32 bits vers le flux **Example:** |
| [write32bIndicesTo(OutputStream stream)](#write32bIndicesTo-java.io.OutputStream-) | Écrire les données d'indices en entier 32 bits vers le flux |
| [writeVerticesTo(Stream stream)](#writeVerticesTo-com.aspose.threed.Stream-) | Écrire les données des sommets vers le flux spécifié |
| [writeVerticesTo(OutputStream stream)](#writeVerticesTo-java.io.OutputStream-) | Écrire les données des sommets vers le flux spécifié |
### TriMesh(String name, VertexDeclaration declaration) {#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-}
```
public TriMesh(String name, VertexDeclaration declaration)
```


Initialiser une instance de [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom de ce TriMesh |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | La déclaration du sommet |

### addTriangle(int a, int b, int c) {#addTriangle-int-int-int-}
```
public void addTriangle(int a, int b, int c)
```


Ajouter un nouveau triangle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | int | L'index du premier sommet |
| b | int | L'index du deuxième sommet |
| c | int | L'index du troisième sommet |

### beginVertex() {#beginVertex--}
```
public Vertex beginVertex()
```


Commencer l'ajout de vertex

**Returns:**
[Vertex](../../com.aspose.threed/vertex) - The reference of internal vertex object in type [Vertex](../../com.aspose.threed/vertex)
### copyFrom(TriMesh input, VertexDeclaration vd) {#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-}
```
public static TriMesh copyFrom(TriMesh input, VertexDeclaration vd)
```


Copier le [TriMesh](../../com.aspose.threed/trimesh) depuis l'entrée avec une nouvelle disposition de vertex

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [TriMesh](../../com.aspose.threed/trimesh) | Le TriMesh d'entrée pour la copie |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | La nouvelle déclaration du sommet du TriMesh de sortie |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - A new TriMesh instance with new vertex declaration. **Example:**

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
  vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
  //convert a mesh to TriMesh, the layout is automatically inferred from input mesh
  var oldTriMesh = TriMesh.fromMesh((new Sphere()).toMesh());
  //now create a new TriMesh from old TriMesh, using explicit memory layout defined by vd
  var newTriMesh = TriMesh.copyFrom(oldTriMesh, vd);
```
### endVertex() {#endVertex--}
```
public int endVertex()
```


Terminer l'ajout de vertex

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | Nom de la propriété. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromMesh(Mesh mesh) {#fromMesh-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(Mesh mesh)
```


Créer un TriMesh à partir d'un objet maillage donné, la déclaration de vertex étant basée sur la structure du maillage d'entrée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(Mesh mesh, boolean useFloat) {#fromMesh-com.aspose.threed.Mesh-boolean-}
```
public static TriMesh fromMesh(Mesh mesh, boolean useFloat)
```


Créer un TriMesh à partir d'un objet maillage donné, la déclaration de vertex étant basée sur la structure du maillage d'entrée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| useFloat | boolean | Utilisez le type float au lieu du type double pour chaque composant d'élément de sommet. |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(VertexDeclaration declaration, Mesh mesh) {#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(VertexDeclaration declaration, Mesh mesh)
```


Créer un TriMesh à partir d'un objet maillage donné avec la disposition de vertex spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Définition du type du sommet, ou disposition mémoire |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Maillage source |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - Instance of TriMesh converted from input mesh with specified vertex's memory layout **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping) {#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-}
```
public static TriMesh fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)
```


Créer un TriMesh à partir de données brutes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Déclaration du sommet, doit contenir au moins un champ. |
| vertices | byte[] | Les données d'entrée des sommets, la longueur minimale des sommets doit être supérieure ou égale à la taille de la déclaration de sommet. |
| indices | int[] | Les indices du triangle |
| generateVertexMapping | boolean | Générer [Vertex](../../com.aspose.threed/vertex) pour chaque sommet, ce qui n'est pas nécessaire uniquement pour la sérialisation/désérialisation. |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) instance that encapsulated the input byte array. **Remarks:** The returned TriMesh will not copy the input byte array for performance, external changes on the array will be reflected to this instance. **Example:** The following code shows how to construct a TriMesh from raw bytes, this is useful when build your own 3D format

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0The string representation,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getCapacity() {#getCapacity--}
```
public int getCapacity()
```


La capacité des vertex pré-alloués.

**Returns:**
int - La capacité des sommets pré‑alloués.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Obtient la clé du rendu d'entité enregistré dans le moteur de rendu

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Obtient si l'entité doit être exclue lors de l'exportation.

**Returns:**
booléen - indique si l'entité doit être exclue lors de l'exportation.
### getIndicesCount() {#getIndicesCount--}
```
public int getIndicesCount()
```


Le nombre d'indices dans ce [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
int - Le nombre d'indices dans ce [TriMesh](../../com.aspose.threed/trimesh)
### getIntIndices() {#getIntIndices--}
```
public int[] getIntIndices()
```


Convertir les indices en tableau d'entiers 32 bits

**Returns:**
int[]
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Obtient le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtient la collection de toutes les propriétés.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtenir la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |

**Returns:**
java.lang.Object - La valeur de la propriété trouvée
### getScene() {#getScene--}
```
public Scene getScene()
```


Obtient la scène à laquelle cet objet appartient

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShortIndices() {#getShortIndices--}
```
public short[] getShortIndices()
```


Convertir les indices en tableau d'entiers 16 bits

**Returns:**
short[]
### getUnmergedVerticesCount() {#getUnmergedVerticesCount--}
```
public int getUnmergedVerticesCount()
```


Le nombre de vertex non fusionnés fournis par [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) et [endVertex](../../com.aspose.threed/trimesh\#endVertex).

**Returns:**
int - Le nombre de sommets non fusionnés qui ont été fournis par [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) et [endVertex](../../com.aspose.threed/trimesh\#endVertex).
### getVertexDeclaration() {#getVertexDeclaration--}
```
public VertexDeclaration getVertexDeclaration()
```


La disposition des vertex du [TriMesh](../../com.aspose.threed/trimesh).

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - The vertex layout of the [TriMesh](../../com.aspose.threed/trimesh).
### getVerticesCount() {#getVerticesCount--}
```
public int getVerticesCount()
```


Le nombre de vertex dans ce [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
int - Le nombre de sommets dans ce [TriMesh](../../com.aspose.threed/trimesh)
### getVerticesSizeInBytes() {#getVerticesSizeInBytes--}
```
public int getVerticesSizeInBytes()
```


La taille totale de tous les vertex en octets

**Returns:**
int - La taille totale de tous les sommets en octets
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicesToArray(int[][] result) {#indicesToArray-int-----}
```
public void indicesToArray(int[][] result)
```


Convertir les indices en tableau d'entiers 32 bits

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| résultat | int[][] |  |

### indicesToArray(short[][] result) {#indicesToArray-short-----}
```
public void indicesToArray(short[][] result)
```


Convertir les indices en tableau d'entiers 16 bits

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| résultat | short[][] |  |

### iterator() {#iterator--}
```
public Iterator<Vertex> iterator()
```


Obtenir l'énumérateur pour énumérer les [Vertex](../../com.aspose.threed/vertex)

**Returns:**
java.util.Iterator<com.aspose.threed.Vertex>
### loadVerticesFromBytes(byte[] verticesInBytes) {#loadVerticesFromBytes-byte---}
```
public void loadVerticesFromBytes(byte[] verticesInBytes)
```


Charger les sommets à partir d'octets, la longueur des octets doit être un multiple entier de la taille du sommet. **Exemple:** Le code suivant montre comment créer un TriMesh vide et charger manuellement les sommets à partir d'octets bruts.

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.LoadVerticesFromBytes(vertices);
  triMesh.AddTriangle(0, 1, 2);
```

```
int[] indices = new int[] { 0,  1,  2 };
  byte[] vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.loadVerticesFromBytes(vertices);
  triMesh.addTriangle(0, 1, 2);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| verticesInBytes | byte[] |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readDouble(int idx, VertexField field) {#readDouble-int-com.aspose.threed.VertexField-}
```
public double readDouble(int idx, VertexField field)
```


Lire le champ double

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int | L'index du sommet à lire |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Le champ avec un type de données compatible float/double |

**Returns:**
double - Valeur double du champ du sommet spécifié
### readFVector2(int idx, VertexField field) {#readFVector2-int-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(int idx, VertexField field)
```


Lire le champ vector2

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int | L'index du sommet à lire |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Le champ avec un type de données Vector2/FVector2 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - FVector2 of specified vertex's field
### readFVector3(int idx, VertexField field) {#readFVector3-int-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(int idx, VertexField field)
```


Lire le champ vector3

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int | L'index du sommet à lire |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Le champ avec un type de données Vector3/FVector3 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(int idx, VertexField field) {#readFVector4-int-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(int idx, VertexField field)
```


Lire le champ vector4

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int | L'index du sommet à lire |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Le champ avec un type de données Vector4/FVector4 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(int idx, VertexField field) {#readFloat-int-com.aspose.threed.VertexField-}
```
public float readFloat(int idx, VertexField field)
```


Lire le champ float

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int | L'index du sommet à lire |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Le champ avec un type de données compatible float/double |

**Returns:**
float - Valeur float du champ du sommet spécifié
### readVector2(int idx, VertexField field) {#readVector2-int-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(int idx, VertexField field)
```


Lire le champ vector2

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int | L'index du sommet à lire |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Le champ avec un type de données Vector2/FVector2 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Vector2 of specified vertex's field
### readVector3(int idx, VertexField field) {#readVector3-int-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(int idx, VertexField field)
```


Lire le champ vector3

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int | L'index du sommet à lire |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Le champ avec un type de données Vector3/FVector3 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(int idx, VertexField field) {#readVector4-int-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(int idx, VertexField field)
```


Lire le champ vector4

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int | L'index du sommet à lire |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Le champ avec un type de données Vector4/FVector4 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Supprime une propriété dynamique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Supprime la propriété spécifiée identifiée par son nom

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Définit si l'entité doit être exclue lors de l'exportation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nouvelle valeur |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Définit la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |
| valeur | java.lang.Object | La valeur de la propriété |

### toString() {#toString--}
```
public String toString()
```


Obtient la représentation sous forme de chaîne de [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
java.lang.String - La représentation sous forme de chaîne
### verticesToArray() {#verticesToArray--}
```
public byte[] verticesToArray()
```


Convertir les données des sommets en tableau d'octets

**Returns:**
byte[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write16bIndicesTo(Stream stream) {#write16bIndicesTo-com.aspose.threed.Stream-}
```
public void write16bIndicesTo(Stream stream)
```


Écrire les données d'indices en entier 16 bits vers le flux **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write16bIndicesTo(OutputStream stream) {#write16bIndicesTo-java.io.OutputStream-}
```
public void write16bIndicesTo(OutputStream stream)
```


Écrire les données d'indices en entier 16 bits vers le flux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | flux | java.io.OutputStream | **Exemple:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
     var mesh = (new Sphere()).toMesh();    
     var triMesh = TriMesh.fromMesh(mesh);    
     //save it to a stream, 115 vertices * 32bytes per vertex    
     var stream = new ByteArrayOutputStream();    
     triMesh.writeVerticesTo(stream);    
     //save indices as ushort to stream, 504 indices * 2 bytes per index    
     triMesh.write16bIndicesTo(stream);
``` |

### write32bIndicesTo(Stream stream) {#write32bIndicesTo-com.aspose.threed.Stream-}
```
public void write32bIndicesTo(Stream stream)
```


Écrire les données d'indices en entier 32 bits vers le flux **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write32bIndicesTo(s);
      }
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write32bIndicesTo(OutputStream stream) {#write32bIndicesTo-java.io.OutputStream-}
```
public void write32bIndicesTo(OutputStream stream)
```


Écrire les données d'indices en entier 32 bits vers le flux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | flux | java.io.OutputStream | **Exemple:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write32bIndicesTo(stream);
``` |

### writeVerticesTo(Stream stream) {#writeVerticesTo-com.aspose.threed.Stream-}
```
public void writeVerticesTo(Stream stream)
```


Écrire les données des sommets vers le flux spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | [Stream](../../com.aspose.threed/stream) | Le flux auquel les données des sommets seront écrites **Exemple:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
``` |

### writeVerticesTo(OutputStream stream) {#writeVerticesTo-java.io.OutputStream-}
```
public void writeVerticesTo(OutputStream stream)
```


Écrire les données des sommets vers le flux spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | flux | java.io.OutputStream | Le flux auquel les données des sommets seront écrites **Exemple:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write16bIndicesTo(stream);
``` |

