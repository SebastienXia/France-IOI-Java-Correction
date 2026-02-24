# 5. Sisyphe

<img src="ressources/schema.png">

<img src="ressources/Punishment_sisyph.jpg">

Nous devons faire en sorte que le robot monte une pyramide de 21 cas et le redescende, faire cela avec des boucles `for` :
Nous avons à disposition comme opérations `haut()` , `bas()` , `droite` , `gauche()`.

----

```Java
import static algorea.Robot.*;

class Main {
   public static void main(String[] args) {
      for (int i = 1; i <= 21; i++) {
         haut();
         droite();
      }
      for (int i = 1; i <= 21; i++) {
         gauche();
         bas();
      }
   }

}
```
