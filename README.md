# TP XML / XSLT - Promotion 2026-2027

Projet : Affichage des étudiants avec XML, XSLT et CSS.

## Fichiers
- `etudiant.xml` : Données des étudiants
- `tableau.xsl` : Transformation principale (Etapes 7, 8, 9)
- `liste.xsl` : Autre transformation
- `style.css` : Thème du site

## Etape 7 - Tableau trié
Tableau avec rang, nom, prénom, email, moyenne et badge Admis / À revoir.
Tri par moyenne décroissante.

## Etape 8 - Un tableau par classe
Un tableau par classe (L1-A, L1-B) avec `xsl:key` et `generate-id()`.
Le titre indique le nombre d'étudiants de la classe.
Le rang recommence à 1 dans chaque classe.

## Etape 9 (bonus) - Major et thème
- Classe `major` ajoutée à la première ligne de chaque tableau avec `xsl:attribute`
- Thème avec variables `--bleu` et `--vert` dans `style.css`
- Style `.major td` pour mettre en évidence le major

## Pour tester
Ouvrir `etudiant.xml` avec Live Server dans VS Code.
