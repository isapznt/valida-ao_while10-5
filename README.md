📌 Validação de Números com REGEX
🧠 Objetivo

Este projeto tem como objetivo praticar o uso de expressões regulares (REGEX) em JavaScript para validar entradas de dados em um formulário web.

📄 Descrição

A aplicação consiste em uma página web simples onde o usuário pode digitar um valor em um campo de entrada e verificar se ele é um número válido.

A validação é feita utilizando uma expressão regular que aceita:

Números inteiros
Números decimais com ponto (.)
Números decimais com vírgula (,)
⚙️ Funcionalidades
Campo de entrada para o usuário digitar um valor
Botão para validar o valor digitado
Validação com REGEX em JavaScript
Exibição de mensagem:

✅ Valor válido

❌ Valor inválido

Feedback visual no campo:
🟢 Borda verde → valor válido

🔴 Borda vermelha → valor inválido

🔍 Expressão Regular Utilizada
/^\d+([.,]\d+)?$/

Explicação:
^ → início da string
\d+ → um ou mais dígitos
([.,]\d+)? → parte decimal opcional (ponto ou vírgula + números)
$ → fim da string
🧪 Exemplos

✔️ Válidos:
10
3.14
10,5
0.75
0,25

❌ Inválidos:
abc
10..2
10,,5
12.
,5

🚀 Como Executar
Baixe o arquivo index.html
Abra o arquivo em qualquer navegador
Digite um valor no campo
Clique em Validar
Veja o resultado exibido na tela

🗂️ Estrutura do Projeto
index.html

O arquivo contém:

HTML → estrutura da página
CSS → estilização
JavaScript → lógica de validação

🎯 Critérios de Avaliação

✔️ Uso correto da expressão regular

✔️ Funcionamento da validação

✔️ Organização do código

✔️ Clareza da interface

✔️ Estilização visual

💡 Possíveis Melhorias

🔄 Validação em tempo real (enquanto o usuário digita)

🧠 Mensagens de erro mais detalhadas

🔢 Conversão automática de vírgula para ponto para cálculos

👨‍💻 Autor

Projeto desenvolvido para fins educacionais.
