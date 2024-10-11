### Portugol💻

## Vetores
* **Exemplo:**
programa
{
Função inicio()
{
inteiro vetor[10] // Declaração do vetor com 10 elementos
inteiro i // Variável de controle do loop
// Leitura dos 10 elementos
para (i = 0; i < 10; i++)
{
escreva("Digite o elemento ", i + 1, ": ")
leia(vetor[i])
}
// Apresentação dos valores lidos
escreva("\nValores lidos:\n")
para (i = 0; i < 10; i++)
{
escreva("Elemento ", i + 1, ": ", vetor[i], "\n")
}
}
}

## Estruturas de Repetição
Utilizado quando se deseja que um determinado conjunto de
instruções, sejam executados por mais de uma vez, podendo ser um
número definido ou indefinido de vezes.
• Existem 3 estruturas de repetição:
• Para
• Enquanto
• Faça...enquanto

## Estruturas de Controle Condicional
* **Exemplo:**
programa {
funcao inicio() {
inteiro ano, anoatual, idade
cadeia nome
escreva("Informe seu nome")
leia(nome)
escreva(nome , " informe o ano do seu nascimento")
leia(ano)
escreva("Informe o ano atual ")
leia(anoatual)
idade = anoatual - ano
se(idade >= 16){
escreva(nome, " você já tem ", idade, "\nVocê votará ")
}senao{
escreva(nome, "você tem apenas ",
idade, " anos\n Você não poderá votar")
}

