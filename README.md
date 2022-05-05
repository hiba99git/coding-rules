## **Votre travail doit être :**

- **Réutilisable** Répondant aux contraintes et obligation de l’Open Source.
- **Standard** Ayez un code neutre pour pouvoir le réutiliser partout.
- **Compréhensible** Même sans commentaire, être explicite est toujours mieux qu'implicite.
- **Qualitatif** Le diable est dans les détails, veillez à toujours rajouter ce petit truc qui fera gagner du temps, rendra votre création parfaite, etc.
- **Testable** Vos fonctions et objets ne doivent pas être trop dépendants les uns des autres, il faut pouvoir injecter facilement des données en entrées à des fins de tests
- **Simple** La simplicité est toujours mieux que la fonctionnalité. Votre code à un objectif, réalisez le le plus simplement possible (c’est le plus difficile)

## **Coding rules**

### **YAGNI**

**You ain't gonna need it** (qui peut se traduire par « vous n'en aurez pas besoin ») est un principe d'extreme programming qui déclare que les programmeurs ne devraient pas ajouter de fonctionnalité à un logiciel tant que celle-ci n'est pas absolument nécessaire.

### **KISS**

**Keep it simple, stupid** (en français, mot à mot : « garde ça simple, bête », dans le sens de « ne complique pas les choses »), ou principe KISS, est une ligne directrice de conception qui préconise la simplicité dans la conception et que toute complexité non indispensable devrait être évitée dans toute la mesure du possible. L'idée est de **ne pas optimiser** quoi que ce soit avant de **maîtriser totalement une version simple de ce que l'on crée.** 

### **DRY**

**Don’t repeat yourself** (en français, Ne vous répétez pas) est une philosophie en programmation informatique consistant à éviter la redondance de code au travers de l’ensemble d’une application afin de faciliter la maintenance, le test, le débogage et les évolutions de cette dernière.

## **Les commandes Git de base pour tout développeur:**

### **Git pull:**

Git pull permet de récupérer tous les changements sur la branche distant.

Elle prend en paramètre la branche source et la branche ciblé.

### **Git fetch:**

Git fetch permet de rechercher et afficher les changements sur un remote passé en argument, qui ne sont pas présent en local, sans aucun transfert de fichiers.

### **Git rebase:**

Git rebase permet de transférer les changements d’une branche à une autre, elle prend en argument la branche avec laquelle nous voulons rebaser.

### **Git checkout:**

Git checkout permet de déplacer d’une branche à une autre, elle prend en argument la branche cible et aussi de supprimer les modifications qui ne sont pas ajoutées.

### **Git add:**

Git add permet d’ajouter les changements que nous avons fait dans nos fichiers sur la branche courante.

les deux arguments les plus importants de cette commande sont:

*git add .*  : permet d’ajouter tous les changements que nous avons fait. *git add -u*  : permet d’ajouter les modifications sur les fichier déjà connus par git (les nouveaux fichiers ne seront pas ajoutés).

### **Git commit:**

Git commit permet commiter les modifications que nous avons en local sur la branche courante.

### **Git reset:**

Git reset permet de supprimer tous les changements que nous avons fait sur la branche courante.

### **Git push:**

Git push permet d’envoyer les modifications sur un remote.

### **Git status:**

*git status*  : permet d’afficher toutes les modifications non commités sur la branche courante.
