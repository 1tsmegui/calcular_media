<h1>Documentação do Projeto</h1>
<h1>Calculadora de média </h1>

<h2>Objetivo:</h2>

<h3>Este projeto implementa uma calculadora de média simples utilizando HTML, CSS e JavaScript.
O usuário pode inserir duas notas e calcular sua média, além de visualizar se foi aprovado ou reprovado com base na média obtida.</h3>

<h2>Estrutura HTML:</h2>

<h3>Campos de Entrada: Dois campos <input> do tipo number são fornecidos para que o usuário insira suas notas.
Botão de Cálculo: Um botão "Calcular Média" que, ao ser clicado, invoca a função JavaScript calcularMediaInput().
Exibição de Resultados: Após o cálculo, são exibidos dois <span>s: um para mostrar a média calculada e outro para indicar se o aluno foi aprovado ou reprovado.</h3>

<h2>Estilos CSS:</h2>

<h3>A página utiliza estilos simples para centralizar o conteúdo (text-align: center) e estilizar os elementos.
As classes .aprovado e .reprovado definem as cores do texto para indicar visualmente a situação do aluno.</h3>

<h2>Funcionalidade JavaScript:</h2>

<h3>Função calcularMediaInput():
Obtém os valores das notas dos campos de entrada.
Verifica se os valores inseridos são números válidos.</h3>

<h2>Calcula a média das notas.</h2>

<h3>Exibe a média com uma casa decimal no elemento <span id="mediaInput"></span>.
Determina a situação do aluno (aprovado ou reprovado) com base na média calculada e atualiza o texto no <span id="situacaoInput"></span>. 
Validações:

O código inclui uma verificação para garantir que apenas valores numéricos sejam aceitos como entrada, exibindo um alerta caso contrário.
Utilização: </h3

<h2>Passos do Usuário:</h2>
<h3>Insira as notas nos campos indicados.
Clique no botão "Calcular Média".
Observe a média calculada e a situação de aprovação ou reprovação exibida na página.
Este projeto oferece uma forma interativa e visualmente clara para os usuários calcularem suas médias escolares e compreenderem rapidamente sua situação acadêmica com base nos critérios definidos.</h3>
