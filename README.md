# ejercicio-4-introducci-n
Adjunto actividades de la clase 4

public class MyClass {
    public static void main(String args[]) {
      
        int numero  = 3;
        int numeroWhile = 2;
     
        if (numero < 0 ) {
            System.out.println("negativo");
        }
        if (numero > 0 ) {
            System.out.println( "positivo");
        }

        System.out.println ("comenzó el While");
        while (numeroWhile < 3) {
            System.out.println( numeroWhile );
            numeroWhile= numeroWhile + 1 ;
        }
         
        do {System.out.println (numeroWhile);
            numeroWhile++;
        }
        while (numeroWhile < 3 );
       
       System.out.println ("comenzó el For");
       for ( int numeroFor = 0; numeroFor <=3; numeroFor++)  {
       System.out.println (numeroFor );
      }
      
      
      String Estacion = "otoño";
      switch (Estacion) { 
        case "verano":
            System.out.println ( "La estación es verano "); 
            break;
        case "invierno": 
            System.out.println ( "La estacion es invierno ");
            break;
        case "primavera" :
            System.out.println ( "La estacion es primavera ");
            break;
        case "otoño":
            System.out.println ( "La estacion es otoño ");
            break;
        default:
            System.out.println ( "Estación desconocida ");
      }
    }
 }
