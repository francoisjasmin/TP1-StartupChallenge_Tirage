# Startup Challenge — Tirage des contraintes

Application autonome HTML/CSS/JavaScript pour le TP1.

## Utilisation
1. Ouvrir `index.html` dans Chrome, Edge ou Firefox.
2. Inscrire le nom de la classe et, si désiré, renommer les 6 équipes.
3. Cliquer sur **Tirer pour les 6 équipes**.
4. Révéler les résultats une équipe à la fois ou avec **Tout révéler**.
5. Cliquer sur **Rapport imprimable** pour imprimer ou enregistrer en PDF.

## Fonctionnement
- 2 cartes Architecture par équipe.
- 1 événement de faisabilité par équipe.
- Aucune carte Architecture ni aucun événement ne se répète dans une même classe.
- Le tirage est conservé dans le navigateur avec `localStorage` jusqu'à réinitialisation.
- Aucun serveur ni connexion Internet n'est requis.

## Modification
Les listes `ARCH_CARDS` et `EVENTS` se trouvent directement dans `index.html`.
Vous pouvez ajouter, retirer ou modifier des cartes facilement.
