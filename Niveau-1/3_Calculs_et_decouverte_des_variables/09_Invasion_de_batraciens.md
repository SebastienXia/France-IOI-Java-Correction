# 9. Invasion de batraciens

Nous avons n-nombre de crapauds au mois 1, combien y'aura t - il de crapaud au mois 12 ? En utilisant une boucle : 

```Java
class Main {
    public static void main(String[] args) {
        int nombreDeCrapauds = 1337;
        for (int i = 1; i <= 12; i++) {
            nombreDeCrapauds = nombreDeCrapauds * 2;
        }
        System.out.println(nombreDeCrapauds);
    }
}
```
