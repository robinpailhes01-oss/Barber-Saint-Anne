# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Hommes de Montpellier centre (Écusson) qui cherchent un coiffeur-barbier proche, souvent depuis leur téléphone, entre deux rues. Ils veulent savoir vite : où c'est, combien ça coûte, si c'est ouvert, et réserver sans appeler. Beaucoup arrivent depuis Google Maps, Instagram ou la fiche Planity.

## Product Purpose

Site vitrine d'une page pour Sainte-Anne Barber, coiffeur et barbier au 10 rue Ranchin, 34000 Montpellier, ouvert depuis le 1er novembre 2025. Le site doit rassurer (le lieu, les deux barbiers, les avis), afficher la carte et envoyer vers la réservation Planity. Succès : un visiteur mobile comprend en quelques secondes ce qu'est le salon, voit un prix et clique « Réserver ».

## Positioning

Deux barbiers, Tony et Loïc, qui regardent d'abord et coupent ensuite, dans un salon de l'Écusson à l'ombre du Carré Sainte-Anne. Les clients le disent eux-mêmes : « il a su mettre une coupe là où je ne trouvais pas les mots ». Ni salon franchisé, ni barbier Instagram : un lieu où l'on s'assoit.

## Operating Context

- Réservation exclusivement via Planity : https://www.planity.com/sainte-anne-barber-34000-montpellier (intouchable, confirmé par Robin le 11 sept. 2026).
- Sans rendez-vous accepté quand un fauteuil se libère.
- Horaires : lundi à samedi 9h à 19h, fermé le dimanche. Téléphone 07 68 06 64 36. Instagram @sainte_anne_barber.
- Déploiement statique sur Vercel (barber-saint-anne.vercel.app), un seul `index.html`, pas de framework ni de build.

## Capabilities and Constraints

- Tarifs affichés (intouchables, confirmés) : Coupe 25 €, Coupe étudiant 20 €, Coupe enfant (moins de 15 ans) 18 €, Barbe 15 €, Barbe et soin 20 €, Coupe et barbe 35 €, Coupe et barbe étudiant 30 €, Coupe, barbe et soin visage 45 €, Coupe et soin visage 40 €, Barbe et soin visage 30 €, Boisson healthy 3 €. Cire nez/oreilles sur demande.
- Carte cadeau au salon ou par téléphone.
- Aucune vidéo disponible : `assets/reel.mp4` n'existe pas, la page doit tenir sans.
- Ouvert / fermé calculé en direct sur l'heure de Paris.
- Non décidé : ajouter des photos supplémentaires du salon (à demander à Tony / Loïc) ; vidéo verticale d'un dégradé.

## Brand Commitments

- Nom : Sainte-Anne Barber. Logo existant peint (flèche de l'église, ciseaux et peigne croisés, « Coupe · Barbe · Soins ») : `assets/logo.png` et `assets/logo-black.png`. Il reste tel quel, jamais redessiné.
- Ambiance validée par Robin : « black premium comme leur salon ». Le vrai salon : brique rouge, cuir noir, lampes à filament, enseigne rétroéclairée, poteau de barbier lumineux, néon bleu-vert à la porte, horloge murale.
- Ton : vouvoiement, phrases courtes, aucun point d'exclamation. Mots bannis : passion, expérience unique, tendance, moderne, premium (dans le texte), grooming, n'hésitez pas, convivial, prestations, offre.
- Typographie en place : Archivo (variable, largeur) et Instrument Serif italique, fichiers locaux dans `assets/fonts/`.
- Voir `brand/brand.md` pour la référence complète.

## Evidence on Hand

- Notes : Google 5,0 / 5 (plus de 50 avis), Planity 4,9 / 5 (36 avis).
- Verbatims réels (Google / Planity) : « propre à l'écoute et coupe nickel », « a su mettre une coupe là où je ne trouvais pas les mots », « ambiance feutrée et accueil chaleureux », « très accueillant et efficace, je recommande les yeux fermés », « super accueil, ambiance chaleureuse et coupe parfaite ».
- 18 photos réelles du salon récupérées sur Planity, en webp desktop et mobile dans `assets/` (enseigne, rue Ranchin, intérieur, fauteuil, serviette brodée, ciseaux, outils, barbiers au travail).
- Absences à ne pas inventer : aucun chiffre de clientèle, aucune vidéo, aucun portrait posé de Tony et Loïc, aucun avis au-delà de ceux cités.

## Product Principles

1. Le vrai salon avant l'effet : la page ressemble au 10 rue Ranchin, pas à un template de barbier.
2. Le mobile décide : la première vue sur téléphone doit dire le lieu, un prix, l'état d'ouverture et « Réserver ».
3. On ne dit que ce qu'on peut prouver : avis cités tels quels, tarifs exacts, aucune statistique inventée.
4. Réserver passe par Planity, toujours à un geste.
5. Sobre et net : ce qui bouge le fait pour une raison, et le contenu reste lisible sans mouvement.

## Historique de décision

- 11 sept. 2026, Robin : « Corriger et finir la v6 » plutôt que repartir de zéro. Défauts nommés : rendu « site généré par IA », hero et ouverture mobile, pas assez proche du vrai salon.
