# CALCULO_SALARIO_LIQ
Construa um algoritmo que peça o salário bruto mensal e o nome de um funcionário, calcule e apresente os valores

Var
// Seção de Declarações das variáveis 
nome: caracter
sal_bruto,sal_liq,desc_ir,desc_inss,desc_sind,total_desc : Real

Inicio
// Seção de Comandos, procedimento, funções, operadores, etc... 
escreval("CALCULO DO SALARIO LIQUIDO DE UM FUNCIONARIO")
escreval (" ")
escreva ("Digite o nome do(a) funcionario(a):")
leia (nome)
escreva ("Digite o salario bruto do(a) funcionario (a):")
leia(sal_bruto)
desc_ir <- sal_bruto * 0.15
desc_inss <-sal_bruto * 0.11
desc_sind <-sal_bruto * 0.03
total_desc <- desc_ir + desc_inss +desc_sind
sal_liq <- sal_bruto - total_desc
escreval (" ")
escreval("Funcionário : ", nome)
escreval("Salário Bruto : ", sal_bruto)
escreval (" ")
escreval (" (-) IR (15%):R$", desc_ir)
escreval (" (-) INSS(11%):R$", desc_inss)
escreval(" (-) Sindicato (3%):R$", desc_sind)
escreval (" ")
escreval("Salário Liquido :R$ ", sal_liQ)

Fimalgoritmo
