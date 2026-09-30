# Dark - Arbre Généalogique Interactif

Arbre généalogique interactif pour la série **Dark** (Netflix), conçu pour suivre les relations entre les personnages **sans spoilers**.

## Fonctionnalités

- **Progression épisode par épisode** : Sélectionnez la saison et l'épisode que vous venez de regarder
- **Sans spoilers** : Seules les informations révélées jusqu'à votre épisode actuel sont affichées
- **Filtres par époque** : Cliquez sur une année (1953, 1986, 2019, 2052...) pour filtrer l'affichage
- **4 familles principales** : Nielsen, Kahnwald, Doppler, Tiedemann
- **Révélations progressives** : Les connexions majeures apparaissent au bon moment
- **Design fidèle à la série** : Ambiance sombre, triquetra, typographie Cinzel

## Déploiement

### GitHub Pages

Le site est accessible sur : [https://doog33k.github.io/dark-family-tree/](https://doog33k.github.io/dark-family-tree/)

### Docker (Synology / Self-hosted)

```bash
docker-compose up -d
```

Le site sera accessible sur le port `8085`.

## Technologies

- HTML5 / CSS3 / JavaScript vanilla
- Police : Cinzel (Google Fonts)
- Conteneur : nginx:alpine

## Licence

Projet personnel à but non lucratif. Dark est une série Netflix créée par Baran bo Odar et Jantje Friese.

---

*"The beginning is the end, and the end is the beginning."*
