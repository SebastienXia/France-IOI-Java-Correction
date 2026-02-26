# 7. Progresser par l'erreur

Nous avons 6 exemples de code, à déterminer si Valide (V) ou bien Invalide (I) : 

### 1)
```Java
class Main {
   public static void main(String[] args) {
      int nbBillesRouges = 4;
      int nbBillesBleues = 6;
      System.out.println(nbBillesRouges + nbBillesBleues);
   }
}
```

### 2)
```Java
class Main {
   public static void main(String[] args) {
      int taille = 4;
      taille = 6;
      System.out.println(taille);
   }
}
```

### 3)
```Java
class Main {
   public static void main(String[] args) {
      int nbBillesBleues = 3;
      System.out.println(nbBillesRouges);
   }
}
```

### 4)
```Java
class Main {
   public static void main(String[] args) {
      2 = 2;
      System.out.println(2);
   }
}
```

### 5)
```Java
class Main {
   public static void main(String[] args) {
      int âge1 = 6;
      int âge2 = 4;
      âge2 = âge1;
      System.out.println(âge2);
   }
}
```

### 6)
```Java
class Main {
   public static void main(String[] args) {
      int prix = 10;
      prix - 2 = prix;
      System.out.println(prix);
   }
}
```

### 7)
```Java
class Main {
   public static void main(String[] args) {
      int prix = âge - 7;
      int âge = 12;
      System.out.println(prix);
   }
}
```

## Solution :

```Java
class Main {
    public static void main(String[] args) {
        System.out.println("V");
        System.out.println("V");
        System.out.println("I");
        System.out.println("I");
        System.out.println("V");
        System.out.println("I");
        System.out.print("I");
   }
}
```
