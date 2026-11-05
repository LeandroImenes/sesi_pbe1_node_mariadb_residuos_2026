# Gestão de resíduos sólidos
Projeto realizado para a matéria Programação Back-End 1 do curso de Desenvolvimento de Sistemas do SENAI

## Diagrama de classes
<img src="docs/der_residuos.png">
<img src="docs/der.png">

<br>

|Tecnologias utilizadas|Para que foi utilizada|
|-|-|
|VS code|Programação dos códigos|
|Draw.io|Desenho do MER DER|
|Node.js|Rodar o javascript|
|GitHub|Armazenar o projeto|
|Insomnia|Teste do CRUD|
|XAMPP|Utilizar o banco de dados MySQL|

<br>

## Passo a passo para testar
- Clone este repositório em seu pc
- Abra a pasta com um compilador (geralmente VS code)
- Rode o servidor no cmd utilizando o comando <kbd>npm run dev</kbd>
- Abra o Insomnia e teste as HTTP requests seguindo o CRUD (Create, Read, Update, Delete), adicionando também o resumo, login e o patch (substitui o PUT no ocorrências)

<br>

## Prints dos testes no Insomnia
- Usuários
<img src="docs/usuario/getusu.png">
<img src="docs/usuario/postusu.png">
<img src="docs/usuario/putusu.png">
<img src="docs/usuario/deleteusu.png">
<img src="docs/usuario/loginerrado.png">
<img src="docs/usuario/logincerto.png">
- Ocorrências
<img src="docs/ocorrencia/getoco.png">
<img src="docs/ocorrencia/postoco.png">
<img src="docs/ocorrencia/patchoco.png">
<img src="docs/ocorrencia/deleteoco.png">
<img src="docs/ocorrencia/resumooco.png">