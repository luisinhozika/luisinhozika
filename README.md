#include <stdio.h>

int main()
{
    int horas_trabalho, numero_funcionario, numero;
    float valor_porhora, salario_funcionario;
    
    //printf("Número do funcionário: ");
    scanf("%d", &numero_funcionario);
    
    //printf("Horas de trabalho: ");
    scanf("%d", &horas_trabalho);
    
    //printf("Digite o valor por hora: ");
    scanf("%f", &valor_porhora);
    
    numero = numero_funcionario;
    
    printf("NUMBER = %d\n", numero);
    
    salario_funcionario = horas_trabalho * valor_porhora;
    
    printf("SALARY = U$ %.2f\n", salario_funcionario);

    return 0;
}
