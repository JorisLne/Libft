<p align="center">
  <img src="https://img.shields.io/badge/42%20School-Libft-black?style=for-the-badge&logo=42" alt="Projet 42 Libft" />
</p>

<p align="center">
  <img src="https://github.com/JorisLne/42-project-badges/blob/main/badges/libftm.png?raw=true" alt="Badge Libft">
</p>

<p align="center">
  <img 
    src="https://github.com/JorisLne/42-project-badges/blob/main/covers/cover-libft.png?raw=true" 
    alt="Bannière de présentation du projet Libft" 
    width="80%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Score-125%2F100-brightgreen?style=flat-square" alt="Score du projet 125/100" />
  <img src="https://img.shields.io/badge/Testeur-Tripouille-blue?style=flat-square" alt="Testé avec Francinette" />
  <img src="https://img.shields.io/badge/Langage-C-blue.svg?style=flat-square&logo=c" alt="Langage C" />
</p>

</p>

---

## ✨ Fonctionnalités Clés

* 🔧 **Implémentation Personnalisée** : Offre une compréhension approfondie du fonctionnement interne des fonctions C.
* 📦 **Bonus Inclus**
* 🧪 **Testé Rigoureusement** : Validé à l'aide du testeur `Francinette` pour assurer la robustesse.
* 🔄 **Code Réutilisable** : Conçu comme une bibliothèque statique (`.a`) pour une intégration facile dans tous vos futurs projets C.

---

## 🚀 Démarrage

### Prérequis

* `gcc`
* `make`

### Installation

1.  **Clonez le dépôt :**
    ```bash
    git clone [https://github.com/JorisLne/Libft.git](https://github.com/JorisLne/Libft.git)
    cd Libft
    ```

2.  **Compilez la bibliothèque :**
    ```bash
    make
    ```
    Cette commande va créer le fichier de bibliothèque statique `libft.a`.

### Utilisation dans votre projet

1.  **Copiez** `libft.a` et `libft.h` dans le répertoire de votre projet.

2.  **Incluez l'en-tête** dans vos fichiers source `.c` :
    ```c
    #include "libft.h"
    ```

3.  **Linkez la bibliothèque** lors de la compilation de votre exécutable :
    ```bash
    # Exemple de compilation
    gcc your_code.c -L. -lft -o your_executable
    ```
    * `-L.` indique au compilateur de chercher les bibliothèques dans le répertoire courant.
    * `-lft` linke spécifiquement la bibliothèque `libft.a` (le préfixe `lib` et le suffixe `.a` sont sous-entendus).

---
