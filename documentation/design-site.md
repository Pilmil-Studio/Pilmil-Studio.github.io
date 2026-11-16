# Diagnostic design du site (novembre 2026)

1. Hiérarchie : la page presse reprend les composants de l'accueil (liste de principes, texte brut) sans les adapter. Elle fait une dizaine de sections sans sommaire ni séparation visible.
2. Densité : les fiches d'applis sont des listes à puces de quatre paragraphes collés, avec des liens séparés par des points médians. Les blocs « Visuels » et « Questions fréquentes » sont des murs de texte.
3. Texte à citer : même style que le reste, impossible à repérer ou à copier d'un geste.
4. Cohérence : styles en ligne répétés (logo d'en-tête, note de l'accueil, couleurs des pastilles), aucune échelle d'espacement ni de typographie, rayons et espacements en valeurs libres.
5. Accueil : les cartes ont un fond teinté fort, et le texte coloré des étiquettes passe sous 4,5:1 en thème clair (Fredonne 2,4:1, Respire 3,1:1). Les liens Site / Code / APK sont répartis sur deux niveaux de style différents.
6. Mobile : zones tactiles sous 44 px (pastilles, liens du pied de page, bouton de langue). Le dégradé de fond réduit le contraste du texte secondaire.
7. Images : les icônes sont déclarées en 44x44 alors que les fichiers font 512x512. Pas de déformation (carrées), mais les attributs ne reflètent pas le fichier et rien n'est chargé en différé.
8. Presse : le tableau de chiffres est une liste de principes, les chemins d'images ne sont que du texte, aucune icône n'est montrée.
9. Pied de page : séparateurs typographiques, liens trop serrés, avertissement peu distinct.
10. Accessibilité : `aria-labelledby` pointant vers un identifiant décalé sur la page presse, pas de lien d'évitement, pas de règle d'impression.
