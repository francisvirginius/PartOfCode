# PartOfCode
Little tips I found !
----------------------------------------------------
Pour Git :
=> git status 
    pour voir le statu des commite
=> git pull 
   il fait les 2 en meme temps :
            => git fetch
            Télécharger les objets et références depuis un autre dépôt
            => git merge 
            va intégrer localement les modifications présentes sur le dépôt distant.
=> git add .
  ajoute les commit pas enregistre 
=> git commit -m "Mon nouveau commit"
    cree un nouveau commit avec les modifications. 
=> git push 
     envoie le commit
------------------------------------------------------
pour sql :

=> cree une table avec une cle concaténée
        CREATE TABLE Commande (
    	numClic int(11) ,
        numProdc int (11),
        PRIMARY KEY (numClic,numProdc),
        FOREIGN KEY (numClic) REFERENCES Client(numCli),
        FOREIGN KEY (numProdc) REFERENCES Produit(numProd)
)

    
