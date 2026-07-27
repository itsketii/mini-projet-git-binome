# MINI-PROJET GIT EN BINÔME - JOUR 1 : COLLABORATION AVEC GIT

### Description

Dans le cadre de la formation IIT Learn 25-26, ce mini-projet réalisé en binôme permet de mettre en pratique les compétences de collaboration avec Git et GitHub, en travaillant sur un site vitrine minimal en une seule page HTML.

---

### Objectifs validés

* Création et gestion d'un dépôt GitHub avec des collaborateurs
* Travail en parallèle sur des branches distinctes
* Fusion de branches (avec et sans conflit)
* Résolution de conflit sur GitHub
* Mise en place d'un fichier .gitignore
* Rédaction d'un README professionnel

---

### Travail réalisé

* [X] Créer un dépôt GitHub nommé `mini-projet-git-binome`
* [X] Inviter les collaborateurs sur le dépôt
* [X] Cloner le dépôt
* [X] Créer un fichier index.html sur la branche main
* [X] Créer une branche `feature/style` (Membre A)
* [X] Créer une branche `feature/competences` (Membre B)
* [X] Fusionner `feature/competences` dans main
* [X] Fusionner `feature/style` dans main (avec résolution de conflit)
* [ ] Ajouter un fichier .gitignore
* [ ] Mettre à jour le README.md

---

### Configuration du projet

##### 1. Clonage du projet

```bash
git clone https://github.com/[pseudo]/mini-projet-git-binome.git
cd mini-projet-git-binome
```

---

#### 2. Branches créées

* ```bash
  git branch -a
  ```

  * `main` : branche principale
  * `feature/style` : ajout du style CSS (Membre A : Kouadio Ketsia)
  * `feature/competences`: ajout des compétences (Membre B : Edéré Régina)

---

### Site vitrine

Le site est une page HTML minimaliste présentant :

Un titre avec mise en forme CSS

* Une description du projet
* Une liste de compétences

---

### Collaboration & Workflow Git

* Membres du binôme :
  * Membre A : Kouadio Ketsia Marie-Aude A. (@itsketii)
  * Membre B : Edéré Hervé Regina (@rey830873-crypto)
* Collaborateurs invités : @sedrickgael & @junmodeste
* Workflow utilisé :

1. Chaque membre a respecté les instruction et a travaillé sur sa propre branche
2. Les pull Request ont été effectuer pour fusionner dans main
3. La résolution du conflit s'est faite en équipe
4. La validation finale a été faite sur la branche principale

---

### Résolution de conflit

Un conflit est apparu lors de la fusion de la branche `feature/style` dans `main`, car les deux branches avaient modifié la balise `<h1>`, dans la branche `feature/style` avait ajouter du CCS dans le head et enfin que fichier README a été modifié dans la branche `feature/competences`. Le conflit a été résolu en discutant avec le binôme pour décider du contenu à garder.
