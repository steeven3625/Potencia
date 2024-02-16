public class PotenciaSuma {
    
    public static int potenciasumas(int n, int p) {
        if (p == 0) {
            return 1;
        }
        
        int resu = n;
        
        for (int i = 1; i < p; i++) {
            resu = resu + n; 
        }
        
        return resu;
    }

    public static void main(String[] args) {
    
        int n = 3;
        int p = 4;
        
        int resultado = potenciasumas(n, p);
        
        System.out.println(n + " elevado a la potencia " + p + " es igual a " + resultado);
    }
}



Steeven Hilarion, Jaider Suarez, Kevin Jimenez
