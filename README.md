# BOOK — Portfolio PDF

Ce dépôt héberge un portfolio au format PDF via **GitHub Pages**.

---

## 🔒 Accessibilité du PDF — À lire avant d'uploader

> **Question fréquente : « Si j'uploade mon PDF, sera-t-il accessible à n'importe qui ? »**

**Oui, si le dépôt est public.**

Voici comment fonctionne la visibilité :

| Configuration du dépôt | Accès au PDF |
|---|---|
| Dépôt **public** + GitHub Pages activé | ✅ Accessible à **tout le monde** (sans connexion) |
| Dépôt **privé** + GitHub Pages activé | 🔐 Accessible uniquement aux personnes autorisées (nécessite GitHub Pro/Team/Enterprise) |
| Dépôt **privé** sans GitHub Pages | 🔐 Accessible uniquement aux collaborateurs du dépôt |

### Ce que cela signifie concrètement

- Si ton dépôt est **public**, n'importe qui peut voir et télécharger le PDF depuis l'URL GitHub Pages **sans avoir besoin d'un compte GitHub**.
- Le PDF est également indexable par les moteurs de recherche.
- **Un portfolio est généralement conçu pour être public** — c'est son but.

### Comment restreindre l'accès (si nécessaire)

Si tu ne veux **pas** que ton PDF soit accessible à tout le monde :

1. **Rends le dépôt privé** :  
   *Settings → Danger Zone → Change repository visibility → Make private*  
   ⚠️ GitHub Pages pour les dépôts privés nécessite un abonnement **GitHub Pro**, **Team** ou **Enterprise**.

2. **Désactive GitHub Pages** :  
   *Settings → Pages → Source → None*  
   Le fichier reste dans le dépôt mais ne sera plus accessible via l'URL publique.

3. **N'uploade pas le PDF dans ce dépôt** si tu veux le garder strictement privé.

---

## 🔗 Lien à partager (dépôt public)

```
https://pasr0.github.io/BOOK/
```

## 📄 Lien direct vers le PDF

```
https://pasr0.github.io/BOOK/portfolio.pdf
```

---

## ✏️ Comment mettre à jour le portfolio

1. Renomme ton nouveau fichier `portfolio.pdf`.
2. Remplace le fichier `portfolio.pdf` existant dans ce dépôt (commit & push).
3. Le lien reste identique — la nouvelle version est automatiquement disponible.

---

## ⚙️ Activer GitHub Pages (à faire une seule fois)

1. Va dans **Settings → Pages** de ce dépôt.
2. Source : **Deploy from a branch**.
3. Branch : `main` / `(root)`.
4. Clique sur **Save**.

GitHub Pages sera accessible à `https://pasr0.github.io/BOOK/` dans quelques minutes.