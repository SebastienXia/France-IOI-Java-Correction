# 4. Le secret du Goma

<img src="ressources/grille_bouses.png">

Nous avons à disposition plusieurs opérations ` gauche() ` , `droite()`, `ramasser()`, `deposer()` et avec l'importation du `import static algorea.Robot.*;`
Nous devons faire en sorte que notre robot ramasse tous les bouses et déposer cela à la case la plus à droite.

----

> Condition à respecter :  Votre programme ne doit pas faire plus d'une dizaine de lignes.

```Java
import static algorea.Robot.*;
 
class Main {
   public static void main(String[] args) {
      for (int i = 1; i <= 15; i++) {
         droite();
         ramasser();
      }
      droite();
      deposer();
   }
}
```
