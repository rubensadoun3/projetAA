# projetAA 
On va créer un moteur de recherche qui nous permet de rechercher certains mots inside nos documents présents dans le dossier Corpus.
1.	Charger le Corpus et afficher le nombre de docs
2.	Lire les docs
3.	Conserver infos dans une liste de dictionnaires 
4.	Tokeniser les mots
5.	Remove the stopwords 
6.	Stemming dans les docs
7.	Créer un vocabulaire contenant all unique processed terms 
8.	On comptes les termes et leur occurrence dans chaque doc
9.	Créer la term frequencies matrix
10.	Calculer IDF avec la formule log10(N/(1+DF))
11.	Créer la tf idf matrix en multiplliant TF par IDF
12.	Appliquer normalisation L2 to TF-IDF vectors
13.	Recevoir une recherche et appliquer le même preprocessing que les autres docs
14.	Créer et normaliser le vecteur tf-idf de la recherche
15.	Calculer la similarité cosinus entre la recherche et les docs
16.	Vérifier quels mots sont présents (de la recherche) dans chaque doc avec la tf matrix
17.	Calculer la proximité des mots et favoriser ceux qui sont proches et dans le bon ordre 
18.	Classer les docs selon leur similarité, le nombre de mots retrouvés et leur proximité
19.	Afficher le srésultats, avec score, nom du doc, 200 premiers caractères du texte original 
seulement et le nom de la recherche apparaissant dans ce résultat ( ou faire en sorte que ce résultat a un lien direct avec la recherche)
