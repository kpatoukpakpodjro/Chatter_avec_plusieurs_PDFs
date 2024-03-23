# Chatter_avec_plusieurs_PDFs
Utilisation de LLAMA-2 et langchain pour discuter avec plusieurs PDFs

L'application suit ces étapes pour apporter des réponses à vos questions :

1.Chargement PDF : l'application lit plusieurs documents PDF et extrait leur contenu textuel.

2. Text Chunking : le texte extrait est divisé en morceaux plus petits qui peuvent être traités efficacement.

3.Modèle de langage : l'application utilise un modèle LLM pour générer des représentations vectorielles des morceaux de texte.

4. Correspondance de similarité : lorsque vous posez une question, l'application la compare avec les morceaux de texte et identifie les plus similaires sémantiquement.

5.Génération de réponse : les morceaux sélectionnés sont transmis au modèle de langage, qui génère une réponse basée sur le contenu pertinent des PDF.
