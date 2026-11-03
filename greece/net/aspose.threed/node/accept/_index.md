---
title: "Node.Accept"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Node. Διασχίζει όλους τους απογόνους κόμβους, συμπεριλαμβανομένου του τρέχοντος κόμβου, και καλεί τον επισκέπτη με τον κόμβο. Ο επισκέπτης μπορεί να διακόψει τη διαδρομή επιστρέφοντας false"
type: docs
weight: 140
url: /el/net/aspose.threed/node/accept/
---
## Node.Accept method

Περπατάει μέσω όλων των απογόνων κόμβων (συμπεριλαμβανομένου του τρέχοντος κόμβου) και καλεί τον επισκέπτη με τον κόμβο. Ο επισκέπτης μπορεί να διακόψει την περιήγηση επιστρέφοντας false

```csharp
public bool Accept(NodeVisitor visitor)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| επισκέπτης | NodeVisitor | Αναδρομική κλήση Visitor για την επίσκεψη του κόμβου |

### Τιμή επιστροφής

true σημαίνει ότι ο επισκέπτης διέκοψε τη διαδρομή.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να λάβετε όλα τα πλέγματα από μια σκηνή

```csharp
Scene scene = Scene.FromFile("input.fbx");
List<Mesh> meshes = new List<Mesh>();
scene.RootNode.Accept((node) =>
{
    if(node.Entity is Mesh)
        meshes.Add((Mesh)node.Entity);
    //συνεχίστε την αναζήτηση
    return true;
});
```

### Δείτε επίσης

* delegate [NodeVisitor](../../nodevisitor/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


