# 8. Mont Kailash

<img src="ressources/tourMont.png">

Dans cet exercice, notre robot doit faire 108 fois le tour du Mont Kailash représenté par l'image ci-dessus, -> opérations `haut();`, `bas();`, `gauche();`, `droite();` et avec l'importation de `import static algorea.Robot.*;`

> Utilisation de boucles `for` imbriquée :

```Java
import static algorea.Robot.*;

class Main {
   public static void main(String[] args) {
      for (int i = 1; i <= 108; i++) {
         for (int h = 1; h <= 13; h++) {
            haut();
         }
         for (int d = 1; d <= 13; d++) {
            droite();
         }
         for (int b = 1; b <= 13; b++) {
            bas();
         }
         for (int g = 1; g <= 13; g++) {
            gauche();
         }
      }
   }
}
```
