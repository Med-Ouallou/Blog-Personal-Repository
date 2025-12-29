---
marp: true
theme: default
paginate: true
title: Blog Solicode – Sprint 1
author: Mohamed Ouallou
style: |
  img , ma{
      width: 40%;
      height: auto;
      display: block;
      margin: auto;
   }

  .maquette {
      width: 40%;
      height: auto;
      display: block;
      margin: auto;
   }

---

# Blog Solicode
## Sprint 1 : Page Article Details

**Présenté par :** Mohamed Ouallou  
**Encadré par :** Mr. Essarraj Fouad

---

# Introduction

## Travail à faire

Créer la **Page Article Details** du **Blog Solicode**

### Labs :
- PHP Naming Conventions

---

# Livrables Attendus

À la fin de ce sprint :

1. **Code Source**  
   Dépôt Laravel bien structuré

2. **Frontend**  
   Page Article Details fonctionnelle et responsive

3. **Documentation**  
   Présentation du Sprint 1 terminée

---

# Perspective Utilisateur

<img src="Presentation-image/usecase.png" class="ma" style="width:100%;">

---

# Fonctionnalités

L'accueil repose sur quatre piliers techniques majeurs :

```mermaid
classDiagram
    direction RL
    class HomePageController {
        +getBySlug(slug)
        +getCategories()
        +getTags()
    }

```
---

# Class Diagram


<img src="Presentation-image/image.png" class="ma" style="width:100%;">

---
# Maquette


<img src="Presentation-image/Article-Details.png" class="maquette">

---

# Lab : PHP Naming Conventions
## Variables
- Utiliser le **camelCase**
```php
$userName;
$totalPrice;
```
## Fonctions
```php
function getUserName() {}
function calculateTotal() {}
```
---

## Classes
```php
class UserController {}
class ProductService {}
```
