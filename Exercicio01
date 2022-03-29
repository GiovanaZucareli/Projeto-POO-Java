public class exercicio01{
        public static void main(String args[]){
                               int dados = args.length/3;
        int fX =0, mX=0, x=0;
        double iX=0, fmenor=0, menoridade=0, idoso=0, porcentomenor, porcentomulher, porcentohomem, mediaf, mediam;
       
        for (int cont = 0; cont <= dados-1; cont++){

            int nascimento = Integer.parseInt (args[x]);
            int idade = 2022-nascimento;
            if (idade < 21){
                menoridade++;
            }
            if (idade > 60){
                idoso++;
            }

            int sexo = Integer.parseInt (args[x+1]);
            if (sexo == 1){
                mX++;
            }
            if (sexo == 2){
                fX++;
                if(idade<21){
                    fmenor++;
                }
            }

            int procedencia = Integer.parseInt (args[x+2]);
            if (procedencia == 1){
                iX++;
            }
            x+=3;
        }
 
            porcentomenor = (menoridade *100) /dados;
            porcentomulher = (fX * 100) /dados;
            porcentohomem = (mX * 100) /dados;
            mediaf = dados - (fX/dados);
            mediam = dados - (mX/dados);
       
           /* System.out.printf("Porcentagem de motoristas com menos de 21 anos: %2.2f \n", porcentomenor);*/
            System.out.printf("Total de mulheres com menos de 21 anos: %2.2f \n", fmenor);
            System.out.printf("Total de habitantes no interior: %2.2f \n", iX);
            if (idoso>0){
                System.out.println("Existem maiores de 60 anos");
            }
            if (idoso == 0){
                System.out.println("Não existem maiores de 60 anos");
            }
            System.out.printf("A média de mulheres é %2.2f e a média de homens é %2.2f \n", mediaf, mediam);
            System.out.printf("A porcentagem de mulheres é %2.2f e a porcentagem de homens é %2.2f \n", porcentomulher, porcentohomem);
        }
}
