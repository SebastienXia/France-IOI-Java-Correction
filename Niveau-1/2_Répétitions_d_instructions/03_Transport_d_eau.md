# 3. Transport d'eau

<img src="ressources/rue.png">

Nous avons à disposition plusieurs opérations ` gauche() ` , `droite()`, `ramasser()`, `deposer()` et avec l'importation du `import static algorea.Robot.*;`
Nous devons faire en sorte que le robot va rammaser le bac d'eau en disant avant de le ramasser `"Bonjour, laissez-moi vous aider"` puis aller jusqu'à sa maison qui se situe à 32 cases à partir de l'endroit où il a ramassé le bac d'eau,
sans toucher les murs au extrémité de l'image.

----

> Condition à respecter :  Votre programme ne doit pas faire plus d'une vingtaine de lignes. 

```Java
import static algorea.Robot.*;

class Main {
   public static void main(String[] args) {
      gauche();
      gauche();
      System.out.println("Bonjour, laissez-moi vous aider");
      ramasser();
      for (int loop = 1; loop <= 32; loop = loop + 1) {
         droite();
      }
      deposer();
   }
}
```
