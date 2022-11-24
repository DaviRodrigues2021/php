# php
 Introdução ao básico do PHP


# PHP (Hypertext Preprocessor)

Uma liguagem server-side, rolada ao lado do servidor. È uma lingugagem de programação back-end, pois ela realiza a comunicação com banco de dados. Ele é um processador no servidor e o resultado do processamento é enviado ao cliente(quem requisitou).

Ex: Arquivo PHP: 2+2
Cliente: 4
Todo arquivo php usa uma extensão: nome.php

Requisitor para funcionar:

Xampp(servidor)
https://www.apachefriends.org/pt_br/index.html

# onde gravado os arquivos:

`c:\xampp\htdocs`

Exemplo

`c:\xampp\htdocs\site\index.php`

# Acesso ao site`

`http://localhost/`

host - máquina - PC - Computador

Exemplo:

`http://localhots/site/index.php`

# Variáveis:

Exemplo:

`http://localhost/site/index.php`

# Variáveis:

- Variável pe um espaço na memória que damos um nome para armazenar algum valor.
- O PHP é case-sensitive, significa que ele diferencia maiúscula, ou seja, Nome é diferente de nome.
- O nome de uma variável deve ser significativo de acordo com o valor. EX: para uma variável que vai armazenar a idade de uma pessoa eu coloco o nome da variável de $idade.
- No PHP toda variável incia com $
Não utilize caracteres especiais, espaços ou acentos para o nome das variáveis. Alguns deles até funcionam, porém é recomendável escrever nomes de variáveis de forma simples.

EX:

$endereço ---- errado
$endereço ---- correto
$Endereco ---- errado
$EndeReco ---- errado
$endereco_do_CLiente --- errado
$end895676 -- errado
$endChico -- errado
$chocolate -- errado
$1 - errado


## Tipos de dados:

- os valores em php podem ser divididas entre os tipos:
- string : todos os valores que estiver entre aspas é uma string, ou seja, um texto. EX:
'Vagner
- integer: todo número inteiro EX: 41
- float ou double: todo número decimal .  EX: 1.75
- Boolean: valor verdadeiro (true) ou falso (false)

# operadores aritiméticos:

+ : adição
- : subtração
* : multiplicação
/ :divisão
** : exponenciação
% : resto da divisão, operador de módulo