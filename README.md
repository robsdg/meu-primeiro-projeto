
# meu-primeiro-projeto
Esse projeto faz parte do meu primeiro desafio do DIO, desculpem ainda estou começand
#Programa em C Imposto de Renda


   float sb,ir;
    printf("Digite seu Salario Bruto:\n");
    
    scanf("%f",&sb);
    
    ir = (sb/100*90);
  
    if (sb>10000){
    printf("O salario Bruto com IR:\n%.2f, ",ir);
   }
    else (sb<10000);
    
    { ir = (sb/100*95);
    printf("O salario Bruto com IR:\n%.2f, ",ir);
           
    }
