# 🎨 Universal Artistic Style Transfer (VGG16)

Ce projet applique le **style artistique d'une image** (par exemple une œuvre de Van Gogh, Monet, Picasso, etc.) sur **une image cible** donnée.  
Il utilise le réseau **VGG16** pré-entraîné sur ImageNet pour extraire les caractéristiques de style et de contenu, et réalise un **neural style transfer** complet.

---

## 🧠 Principe du projet

L’algorithme sépare :
- **le contenu** d’une image (structure, formes principales),
- **le style** d’une autre image (textures, coups de pinceau, palette de couleurs).

Il optimise une image générée afin de **minimiser simultanément** la perte de contenu et la perte de style, à l’aide de **VGG16** comme extracteur de caractéristiques.

---


