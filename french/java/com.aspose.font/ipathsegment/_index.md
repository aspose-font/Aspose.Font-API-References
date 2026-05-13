---
title: "IPathSegment"
second_title: "Référence API d'Aspose.Font pour Java"
description: "Représente l'interface de tout segment de chemin."
type: docs
weight: 131
url: /fr/java/com.aspose.font/ipathsegment/
---
**All Implemented Interfaces:**
java.lang.Cloneable
```
public interface IPathSegment extends Cloneable
```

Représente l'interface de tout segment de chemin.
## Méthodes

| Méthode | Description |
| --- | --- |
| [copy()](#copy--) | Crée une copie de l'objet segment. |
| [shift(double dx, double dy)](#shift-double-double-) | Effectue un décalage selon les coordonnées x et y. |
| [transform(TransformationMatrix matrix)](#transform-com.aspose.font.TransformationMatrix-) | Transforme les coordonnées avec la matrice de transformation. |
### copy() {#copy--}
```
public abstract IPathSegment copy()
```


Crée une copie de l'objet segment.

**Returns:**
[IPathSegment](../../com.aspose.font/ipathsegment) - Copy of the segment object.
### shift(double dx, double dy) {#shift-double-double-}
```
public abstract void shift(double dx, double dy)
```


Effectue un décalage selon les coordonnées x et y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | double | Valeur dx. |
| dy | double | Valeur dy. |

### transform(TransformationMatrix matrix) {#transform-com.aspose.font.TransformationMatrix-}
```
public abstract void transform(TransformationMatrix matrix)
```


Transforme les coordonnées avec la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [TransformationMatrix](../../com.aspose.font/transformationmatrix) | Matrice de transformation. |

