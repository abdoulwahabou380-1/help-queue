Q2: 404 Not Found

Q3: route /a/b n'existe pas

Q4 : Pour la deuxième adresse, le navigateur affiche `Bob` et non les balises HTML. On en déduit que `{{ }}` dans Blade permet d'afficher une variable tout en échappant automatiquement le HTML pour éviter l'exécution de code malveillant (protection XSS). 

Q5 : La table contient **5 colonnes** : `id`, `nom`, `pays`, `stade`, `created_at` et `updated_at` — soit 6 colonnes au total.

Les colonnes générées automatiquement sont :

- `id` : créée par `$table->id();`
- `created_at` et `updated_at` : créées par `$table->timestamps();`