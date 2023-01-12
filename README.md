# Python-OrientadoAObjeto

Crie uma classe com os seguintes atributos:

nome
salario
numero_dependentes
salario_liquido
imposto
inss

a classe deve ter os seguintes métodos:

construtor - solicita o nome, o salário e o número de dependentes para criar o objeto.
      repr - retorna " Nome do funcionário: " + nome + "\n Salário" + salario +  " Dependentes: " + numero_dependentes

calcula_imposto
     calcula imposto retorna o valor do imposto, de acordo com a formula:

      imposto = (salario - (200 * numero_dependentes)) * 0,25

calcula_inss
 calcula o inss do funcionario pela formula:

     se salario < 2000 --> inss = salario * 0,1
     senão --> inss = salario * 0,14

calcula_liquido
     retorna salario liquido = salario - inss - imposto
