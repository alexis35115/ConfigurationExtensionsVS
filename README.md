# Configuration des extensions dans Visual Studio

Pour configurer les extensions, il faut ouvrir le menu qui se trouve sous : "Outils -> Options"

## Productivity Power Tools

Dans le menu de Productivity Power Tools, aller dans le menu "PowerCommands" et s'assurer que les options "Format document on save" et "Remove and Sort Usings on save".

## Indent Guides

Dans le menu de Indent Guides, sous menu "Apparance" s'assurer que toutes les options (Default, Unaligned, #0, ...) soient à "Visible true".

Dans le sous-menu "Page Width Markers", créer deux lignes, une à 80 et une à 120. 80 est souvent un standard dans lequel les commentaires ne devraient pas dépasser cette limite et le 120 est pour une ligne de code! Il est portant de mettre l'attribut "Visible true"! Si les lignes ne s'affichent pas, allez dans le menu "Édition -> Avancé" et cliquez sur "View Indent Guides".

## Contrôle de code source

Dans le menu "Contrôle de code source", veuillez sélectionner "Git" comme contrôleur de code source.

## Éditeur de texte

Allez sous "Étidteur de texte -> C# -> Avancé", décochez "Insérer \* au début des nouvelles lignes pour l'écriture de commentaires /**/"

## SpellChecker

Dans le menu d'accès rapide (Ctrl+Q), saisir "spell" et choisir dans le menu "Edit Global Configuration". Dans l'onglet "Dictionary Settings", ajoutez le dictionnaire Français et supprimez les autres si nécessaire. Pour sauvegarder les modifications, il suffit de faire "Ctrl+S".
