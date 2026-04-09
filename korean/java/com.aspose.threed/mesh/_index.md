---
title: Mesh
second_title: Aspose.3D for Java API 레퍼런스
description: 메시는 많은 n각형으로 구성됩니다.
type: docs
weight: 102
url: /ko/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

A mesh is made of many n-sided polygons. **Example:** To add a polygon in mesh:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Travel through all polygons in mesh:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Mesh()](#Mesh--) | Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class. |
| [Mesh(String name)](#Mesh-java.lang.String-) | Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Gets all deformers with specified deformer types |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Add a new control point to the mesh, this is more efficient. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Add a new control point to the mesh, this is more efficient. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Adds an existing vertex element to current geometry |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Creates a vertex element with specified type and add it to the geometry. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Creates a vertex element with specified type and add it to the geometry. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | 주어진 텍스처 매핑 유형으로 [VertexElementUV](../../com.aspose.threed/vertexelementuv)를 생성합니다. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | 주어진 텍스처 매핑 유형으로 [VertexElementUV](../../com.aspose.threed/vertexelementuv)를 생성합니다. |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | 3개의 정점(삼각형)으로 폴리곤을 생성합니다. |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | 4개의 정점(사각형)으로 폴리곤을 생성합니다. |
| [createPolygon(int[] indices)](#createPolygon-int---) | `indices`에 정의된 모든 정점으로 새로운 폴리곤을 생성합니다. |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | `indices`에 정의된 모든 정점으로 새로운 폴리곤을 생성합니다. |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | 두 메쉬의 차이를 계산합니다. |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | 두 메쉬에 대해 불리언 연산을 수행합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getBoundingBox()](#getBoundingBox--) | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |
| [getCastShadows()](#getCastShadows--) | 이 기하학이 그림자를 드리울 수 있는지 여부를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | 모든 제어점을 가져옵니다. |
| [getDeformers()](#getDeformers--) | 이 기하학과 연결된 모든 디포머를 가져옵니다. |
| [getEdges()](#getEdges--) | 메시의 엣지를 가져옵니다. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | 지정된 유형의 정점 요소를 가져옵니다. |
| [getEntityRendererKey()](#getEntityRendererKey--) | 렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다. |
| [getExcluded()](#getExcluded--) | 내보내기 중에 이 엔터티를 제외할지 여부를 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getParentNode()](#getParentNode--) | 첫 번째 상위 노드를 가져옵니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [getParentNodes()](#getParentNodes--) | 모든 상위 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 상위 노드에 연결될 수 있습니다. |
| [getPolygonCount()](#getPolygonCount--) | 폴리곤 수를 가져옵니다. |
| [getPolygonSize(int index)](#getPolygonSize-int-) | 지정된 폴리곤의 정점 수를 가져옵니다. |
| [getPolygons()](#getPolygons--) | 메시의 폴리곤 정의를 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getReceiveShadows()](#getReceiveShadows--) | 이 기하학이 그림자를 받을 수 있는지 여부를 가져옵니다. |
| [getScene()](#getScene--) | 이 객체가 속한 씬을 가져옵니다. |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | 주어진 텍스처 매핑 유형으로 [VertexElementUV](../../com.aspose.threed/vertexelementuv) 인스턴스를 가져옵니다. |
| [getVertexElements()](#getVertexElements--) | 모든 정점 요소를 가져옵니다. |
| [getVisible()](#getVisible--) | 기하학이 보이는지 여부를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | 두 메쉬의 교차점을 계산합니다. |
| [isManifold()](#isManifold--) | 현재 메쉬가 매니폴드 메쉬인지 확인합니다. |
| [iterator()](#iterator--) | 각 내부 폴리곤에 대한 열거자를 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | 중복된 제어점을 제거하여 메쉬의 메모리 사용량을 최적화합니다. |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | 중복된 제어점을 제거하여 메쉬의 메모리 사용량을 최적화합니다. |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | 중복된 제어점을 제거하여 메쉬의 메모리 사용량을 최적화합니다. |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | 중복된 제어점을 제거하여 메쉬의 메모리 사용량을 최적화합니다. |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | 중복된 제어점을 제거하여 메쉬의 메모리 사용량을 최적화합니다. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | 이 기하학이 그림자를 드리울 수 있는지 여부를 설정합니다. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 내보내기 중에 이 엔터티를 제외할지 여부를 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 첫 번째 상위 노드를 설정합니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | 이 기하학이 그림자를 받을 수 있는지 여부를 설정합니다. |
| [setVisible(boolean value)](#setVisible-boolean-) | 기하학이 보이는지 여부를 설정합니다. |
| [toMesh()](#toMesh--) | 현재 엔터티에서 Mesh 인스턴스를 가져옵니다. |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | 삼각형 메시를 반환합니다. |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | 두 메시의 합집합을 계산합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class.

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Gets all deformers with specified deformer types

**Returns:**
java.util.Collection<T> - Deformer 컬렉션
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Add a new control point to the mesh, this is more efficient.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | double | 제어점의 x 구성 요소 |
| y | double | 제어점의 y 구성 요소 |
| z | double | 제어점의 z 구성 요소 |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Add a new control point to the mesh, this is more efficient.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | double | 제어점의 x 구성 요소 |
| y | double | 제어점의 y 구성 요소 |
| z | double | 제어점의 z 구성 요소 |
| w | double | 제어점의 w 구성 요소 |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Adds an existing vertex element to current geometry

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | 추가할 정점 요소 |

### clone() {#clone--}
```
public Mesh clone()
```




**Returns:**
[Mesh](../../com.aspose.threed/mesh)
### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


Creates a vertex element with specified type and add it to the geometry.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | 정점 요소 유형 |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Creates a vertex element with specified type and add it to the geometry.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | 정점 요소 유형 |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | 기본 매핑 모드 |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | 기본 참조 모드 |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


주어진 텍스처 매핑 유형으로 [VertexElementUV](../../com.aspose.threed/vertexelementuv)를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | 생성할 텍스처 매핑 유형 |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


주어진 텍스처 매핑 유형으로 [VertexElementUV](../../com.aspose.threed/vertexelementuv)를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | 생성할 텍스처 매핑 유형 |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | 기본 매핑 모드 |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | 기본 참조 모드 |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


3개의 정점(삼각형)으로 폴리곤을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v1 | int | 첫 번째 정점의 인덱스 |
| v2 | int | 두 번째 정점의 인덱스 |
|  | v3 | int | 세 번째 정점의 인덱스 **예시:** 다음 코드는 제어점 인덱스로 새 폴리곤을 만드는 방법을 보여줍니다. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


4개의 정점(사각형)으로 폴리곤을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v1 | int | 첫 번째 정점의 인덱스 |
| v2 | int | 두 번째 정점의 인덱스 |
| v3 | int | 세 번째 정점의 인덱스 |
|  | v4 | int | 네 번째 정점의 인덱스 **예시:** 다음 코드는 제어점 인덱스로 새 폴리곤을 만드는 방법을 보여줍니다. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


`indices`에 정의된 모든 정점으로 새 폴리곤을 생성합니다. 폴리곤을 정점별로 생성하려면 [PolygonBuilder](../../com.aspose.threed/polygonbuilder)를 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 인덱스 | int[] | 다각형 인덱스 배열이며, 각 인덱스는 다각형을 형성하는 제어점을 가리킵니다. **Example:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


`indices`에 정의된 모든 정점으로 새 폴리곤을 생성합니다. 폴리곤을 정점별로 생성하려면 [PolygonBuilder](../../com.aspose.threed/polygonbuilder)를 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int[] | 다각형 인덱스 배열이며, 각 인덱스는 다각형을 형성하는 제어점을 가리킵니다. |
| 오프셋 | int | 첫 번째 다각형 인덱스의 오프셋 |
|  | 길이 | int | 인덱스의 길이 **Example:** 다음 코드는 제어점 인덱스로 새 다각형을 만드는 방법을 보여줍니다. |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


두 메쉬의 차이를 계산합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | 첫 번째 메시 |
| b | [Mesh](../../com.aspose.threed/mesh) | 두 번째 메시 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


두 메쉬에 대해 불리언 연산을 수행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | 불리언 연산 유형. |
| a | [Mesh](../../com.aspose.threed/mesh) | 작업할 첫 번째 메시. |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | 첫 번째 메시의 변환 행렬 |
| b | [Mesh](../../com.aspose.threed/mesh) | 작업할 두 번째 메시 |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | 두 번째 메시의 변환 행렬 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


속성을 찾습니다. 동적 속성 (Created by CreateDynamicProperty/SetProperty) 또는 네이티브 속성 (Identified by its name)일 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyName | java.lang.String | 속성 이름. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


이 기하학이 그림자를 드리울 수 있는지 여부를 가져옵니다.

**Returns:**
boolean - 이 기하학이 그림자를 드리울 수 있는지 여부
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


모든 제어점을 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.Vector4> - 모든 제어점
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


이 기하학과 연결된 모든 디포머를 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - 이 기하학과 연관된 모든 디포머.
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


메시의 에지를 가져옵니다. 에지는 메시에서 선택 사항이므로 비어 있을 수 있습니다.

**Returns:**
java.util.List<java.lang.Integer> - 메시의 에지. 에지는 메시에서 선택 사항이므로 비어 있을 수 있습니다.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


지정된 유형의 정점 요소를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | 찾을 정점 요소 유형 |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


내보내기 중에 이 엔터티를 제외할지 여부를 가져옵니다.

**Returns:**
boolean - 내보내기 중에 이 엔터티를 제외할지 여부.
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


첫 번째 상위 노드를 가져옵니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


모든 상위 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 상위 노드에 연결될 수 있습니다.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - 모든 부모 노드, 엔터티는 기하학 인스턴싱을 위해 여러 부모 노드에 연결될 수 있습니다
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


폴리곤 수를 가져옵니다.

**Returns:**
int - 다각형의 개수 **Example:** 다음 코드는 메시의 다각형 수를 가져오는 방법을 보여줍니다.

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


지정된 폴리곤의 정점 수를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 인덱스. |

**Returns:**
int - 다각형 크기.
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


메시의 폴리곤 정의를 가져옵니다.

**Returns:**
java.util.List<int[]> - 메쉬의 폴리곤 정의
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


모든 속성의 컬렉션을 가져옵니다.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


지정된 속성의 값을 가져옵니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |

**Returns:**
java.lang.Object - 찾은 속성의 값
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


이 기하학이 그림자를 받을 수 있는지 여부를 가져옵니다.

**Returns:**
boolean - 이 기하학이 그림자를 받을 수 있는지 여부.
### getScene() {#getScene--}
```
public Scene getScene()
```


이 객체가 속한 씬을 가져옵니다.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


주어진 텍스처 매핑 유형으로 [VertexElementUV](../../com.aspose.threed/vertexelementuv) 인스턴스를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


모든 정점 요소를 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - 모든 정점 요소
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


기하학이 보이는지 여부를 가져옵니다.

**Returns:**
boolean - 기하학이 보이는지 여부
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(Mesh a, Mesh b) {#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh intersect(Mesh a, Mesh b)
```


두 메쉬의 교차점을 계산합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | 첫 번째 메시 |
| b | [Mesh](../../com.aspose.threed/mesh) | 두 번째 메시 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


현재 메쉬가 매니폴드 메쉬인지 확인합니다. 이 함수는 매니폴드 계산 결과를 캐시하지 않습니다.

**Returns:**
boolean - 메쉬가 매니폴드 메쉬인 경우 true.
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


각 내부 폴리곤에 대한 열거자를 가져옵니다.

**Returns:**
java.util.Iterator<int[]> - 열거자.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### optimize(boolean vertexElements) {#optimize-boolean-}
```
public Mesh optimize(boolean vertexElements)
```


중복된 제어점을 제거하여 메쉬의 메모리 사용량을 최적화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vertexElements | boolean | 중복된 정점 요소 데이터를 최적화합니다 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage **Example:** The following code shows how to eliminate duplicated control points from an unoptimized mesh:

```
//Sphere.ToMesh generates 117 control points
  Mesh mesh = (new Sphere()).toMesh();
  //After optimized, there're only 86 control points, polygon indices are also remapped.
  Mesh optimized = mesh.optimize(true);
```
### optimize(boolean vertexElements, float toleranceControlPoint) {#optimize-boolean-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint)
```


중복된 제어점을 제거하여 메쉬의 메모리 사용량을 최적화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vertexElements | boolean | 중복된 정점 요소 데이터를 최적화합니다 |
| toleranceControlPoint | float | 제어점에 대한 허용오차, 기본값은 1e-9입니다 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


중복된 제어점을 제거하여 메쉬의 메모리 사용량을 최적화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vertexElements | boolean | 중복된 정점 요소 데이터를 최적화합니다 |
| toleranceControlPoint | float | 제어점에 대한 허용오차, 기본값은 1e-9입니다 |
| toleranceNormal | float | 노멀/탄젠트/바이노멀에 대한 허용오차, 기본값은 1e-9입니다 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


중복된 제어점을 제거하여 메쉬의 메모리 사용량을 최적화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vertexElements | boolean | 중복된 정점 요소 데이터를 최적화합니다 |
| toleranceControlPoint | float | 제어점에 대한 허용오차, 기본값은 1e-9입니다 |
| toleranceNormal | float | 노멀/탄젠트/바이노멀에 대한 허용오차, 기본값은 1e-9입니다 |
| toleranceUV | float | UV에 대한 허용오차, 기본값은 1e-9입니다 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


중복된 제어점을 제거하여 메쉬의 메모리 사용량을 최적화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vertexElements | boolean | 중복된 정점 요소 데이터를 최적화합니다 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


동적 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


이름으로 식별되는 지정된 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


이 기하학이 그림자를 드리울 수 있는지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


내보내기 중에 이 엔터티를 제외할지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


첫 번째 상위 노드를 설정합니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 새 값 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


지정된 속성의 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |
| 값 | java.lang.Object | 속성의 값 |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


이 기하학이 그림자를 받을 수 있는지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


기하학이 보이는지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


현재 엔터티에서 Mesh 인스턴스를 가져옵니다.

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Returns current instance.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangulate() {#triangulate--}
```
public Mesh triangulate()
```


삼각형 메시를 반환합니다.

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Current mesh if current mesh is already triangulated, otherwise a new triangulated mesh will be calculated and returned **Example:** The following code shows how to triangulate a mesh:

```
//The plane mesh has only one polygon with 4 control points
  var mesh = (new Plane()).ToMesh();
  //After triangulated, the new mesh's rectangle will become 2 triangles.
  var triangulated = mesh.Triangulate();
```
### union(Mesh a, Mesh b) {#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh union(Mesh a, Mesh b)
```


두 메시의 합집합을 계산합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | 첫 번째 메시 |
| b | [Mesh](../../com.aspose.threed/mesh) | 두 번째 메시 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to union two meshes into one mesh:
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

