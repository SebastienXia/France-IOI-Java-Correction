# 9. Vendanges

<img src="ressources/vendanges.png">

Notre robot doit faire des aller-retour entre les raisins et le chariot en faisant `ramasser();` pour ramasser un raison puis `deposer();` pour déposer un raisin cela 20 fois :

```Java
import static algorea.Robot.*;

class Main {
   public static void main(String[] args) {
      for (int i = 1; i <= 20; i++) {
         ramasser();
         for (int x = 1; x <= 15; x++) {
            droite();
         }
         deposer();
         for (int y = 1; y <= 15; y++) {
            gauche();
         }
      }
   }
}
```
