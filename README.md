<p align="center">
  <img src="icone.png" width="96" alt="Icône de Mon Jardin">
</p>

<h1 align="center">Mon Jardin</h1>

<p align="center"><em>Un carnet de potager pour iPhone</em></p>

<p align="center">
  <a href="LIEN_APP_STORE">App Store</a> ·
  <a href="https://niferno.github.io/Mon-jardin/">Site</a> ·
  <a href="https://niferno.github.io/Mon-jardin/editeur-base.html">Éditeur de base</a> ·
  <a href="https://niferno.github.io/Mon-jardin/assistance.html">Aide</a>
</p>

---

J'ai commencé cette application pour mon propre potager, parce que mes carnets à spirale finissaient
pleins de terre et mes notes éparpillées un peu partout. Je voulais savoir, chaque matin, ce qu'il y
avait vraiment à faire : semer, arroser, protéger du gel, traiter avant le mildiou.

Ce dépôt contient la **base de connaissances** de l'app (plantes, maladies, associations, engrais) et
le petit site qui va avec. Le code de l'application n'est pas ici.

## L'application

- les tâches du jour, calculées à partir de ce que tu as semé, de la météo et de ce que tu as déjà fait ;
- l'arrosage au litre près, avec un bilan d'eau par parcelle ;
- les alertes mildiou, oïdium, pourriture grise, rouille et limaces, la veille au soir ;
- le calendrier de ta région : méditerranéen, océanique, Sud-Ouest, montagne… ;
- les rotations, les associations et les engrais conseillés ;
- le plan de chaque parcelle, les récoltes pesées, le bilan de la saison ;
- un widget, et Siri pour noter une récolte les mains sales.

Pas de compte, pas de publicité, pas de pistage, pas d'intelligence artificielle. Le carnet reste sur
l'iPhone ; seule la météo a besoin d'Internet.

**[Télécharger sur l'App Store](LIEN_APP_STORE)** — iPhone, iOS 17 ou plus récent.

## La base de connaissances

| Fichier | Contenu |
|---|---|
| [`jardin_data.json`](jardin_data.json) | 98 plantes, 32 maladies et ravageurs, les symptômes pour le diagnostic, les associations, les types d'apport |
| [`version.json`](version.json) | le numéro de version, lu par l'app pour savoir s'il y a du neuf |

L'app vérifie ces fichiers de temps en temps et télécharge la nouvelle version toute seule. Il n'y a
rien à faire de ton côté.

Le calendrier des plantes est écrit pour un climat semi-continental (l'Est de la France). L'app le
décale elle-même pour les autres régions : ne le corrige pas pour ta région dans la base officielle.

## Faire ta propre base

Tu veux ajouter tes variétés, corriger une date qui ne colle pas à ton coin, décrire une maladie
qu'on ne voit que chez toi ?

1. Dans l'app : **Réglages → Base de connaissances → Exporter la base**.
2. Ouvre le fichier dans l'**[éditeur de base](https://niferno.github.io/Mon-jardin/editeur-base.html)**,
   sur un ordinateur ou un iPad. Tout se passe dans ton navigateur, rien n'est envoyé.
3. **Vérifier et exporter**, puis dans l'app : **Importer une base personnelle**.

L'éditeur applique les mêmes règles que l'app : si l'export passe, l'app l'acceptera.

## Proposer une correction

Une date de semis fausse, une plante qui manque, une association douteuse ? Ouvre une
[issue](../../issues) en expliquant ce qui ne va pas et, si possible, d'où vient l'information
(ton expérience compte, les livres et les semenciers aussi). Tu peux aussi joindre la fiche modifiée
dans l'éditeur.

## Liens

- [Politique de confidentialité](https://niferno.github.io/Mon-jardin/confidentialite.html)
- [Aide](https://niferno.github.io/Mon-jardin/assistance.html)
- Contact : ADRESSE_A_REMPLACER
- Météo : [Open-Meteo](https://open-meteo.com/) (données sous licence CC BY 4.0)

<sub>Conçue et développée en France.</sub>
