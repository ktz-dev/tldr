# vim

> Vim (Vi IMproved), un éditeur de texte en ligne de commandes, fournit plusieurs modes pour différentes manipulations de texte.
> Pressez `<i>` pour passer en mode édition. `<Esc>` revient au mode normal, qui ne permet pas l insertion de code.
> Plus d'informations : <https://www.vim.org>.

- Ouvrir un fichier :

`vim {{chemin/vers/fichier}}`

- Ouvrir un fichier à une ligne spécifiée :

`vim +{{numero_ligne}} {{chemin/vers/fichier}}`

- Consulter le manuel utilisateur :

`<:>help<Enter>`

- Sauvegarder et fermer :

`{{<Esc><Z><Z>|<Esc><:>x<Enter>|<Esc><:>wq<Enter>}}`

- Annuler la dernière opération :

`<Esc><u>`

- Rechercher un motif dans un fichier (appuyez `<n>`/`<N>` pour aller à la prochaine / précédente occurrence) :

`</>{{motif_recherché}}<Entrée>`

- Effectuer une substitution par expression régulière dans tout le fichier :

`<:>%s/{{motif}}/{{remplacement}}/g<Entrée>`

- Afficher les numéros de ligne :

`<:>set nu<Entrée>`
