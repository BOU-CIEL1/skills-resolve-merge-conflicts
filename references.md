echo "Contenu initial" > fichier.txt && git add . && git commit -m "Initial commit"
git checkout -b branche-A && echo "Modification A" > fichier.txt && git commit -am "Modif A"
git checkout main && echo "Modification B" > fichier.txt && git commit -am "Modif B"
