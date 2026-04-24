---
title: NodeVisitor
second_title: Aspose.3D for Java API 레퍼런스
description: 전체 노드 계층 구조를 순회하는 콜백입니다.
type: docs
weight: 261
url: /ko/java/com.aspose.threed/nodevisitor/
---
```
public interface NodeVisitor
```

전체 노드 계층 구조를 순회하는 콜백입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [call(Node node)](#call-com.aspose.threed.Node-) | 전체 노드 계층 구조를 순회하는 콜백입니다. |
### call(Node node) {#call-com.aspose.threed.Node-}
```
public abstract boolean call(Node node)
```


전체 노드 계층 구조를 순회하는 콜백입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 방문 중인 노드 |

**Returns:**
boolean - 이동을 중지하려면 false를 반환합니다.
