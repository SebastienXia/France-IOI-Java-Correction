# Empilement de cylindres | TOurs de Hanoï

Un exercice de réflection sur comment le programme va éxécuter ligne par ligne celui-ci, nous disposons d'une fonction `deplacer(zoneSource, zoneDestination);` avec l'importation de `import static algorea.Robot.*;` : 

```Java
import static algorea.Robot.*;
 
class Main {
   public static void main(String[] args) {
      deplacer(1, 2);
      deplacer(1, 3);
      deplacer(2, 3);
      deplacer(1, 2);
      deplacer(3, 1);
      deplacer(3, 2);
      deplacer(1, 2);
      deplacer(1, 3);
      deplacer(2, 3);
      deplacer(2, 1);
      deplacer(3, 1);
      deplacer(2, 3);
      deplacer(1, 2);
      deplacer(1, 3);
      deplacer(2, 3);
   }
}
```

## Visualisation 
<img src="ressources/Tower_of_Hanoi_4.gif">
