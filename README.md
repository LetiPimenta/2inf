# 2inf
 public static void main(String args[]){
        Scanner entrada = new Scanner(System.in);
        int quant = 0;
        int valor  = 1000;
         int carros = 0;
        
        System.out.println("-----------------------------------------------------");
        System.out.println("-         informe a quantidade de carros  vendidos    -");
        System.out.println("-----------------------------------------------------");
       carros = entrada.nextInt();
   
           if (carros >= 5){
               valor = valor +(500*carros);
           }         
           else{
               valor = valor + (1000*carros);
        }  
            System.out.println("-----------------------------------------------------");
            System.out.println("-                  Valor total:"+valor+"            -");
            System.out.println("-----------------------------------------------------");
         }
