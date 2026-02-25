# 2. Mathématiques de base
Correction du code suivant :

```Java
class Main {
   public static void main(String[] args) {
      for (int loop = 1 loop < 13; loop = loop + 1) {
         System.out.println("9 * 8 = 72);
      }
   }
}
```

Solution : (il y avait trois erreurs sur la ligne du for : un `;` manquant et un `<` au lieu d'un `<=`, de plus une `"` dans le `System.out.println()`) :

```Java
class Main {
   public static void main(String[] args) {
      for (int loop = 1; loop <= 13; loop++) {
         System.out.println("9 * 8 = 72");
      }
   }
}
```

