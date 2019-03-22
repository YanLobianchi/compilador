# COMPILADOR                                                                 

## Compilador feito com as bibliotecas FLEX e BISON da linguagem C.

### Para dar build no projeto tenha o LEX ou o FLEX e o YACC ou o BISON instalados.
### Os comandos são os seguintes (entre na pasta `src`): 
- (*Windows*)
`win_bison -d compilador.y`
`win_flex compilador.l`
`gcc lex.yy.c compilador.tab.c -o compilador`
- (*Linux*)
`bison -d compilador.y`
`flex compilador.l`
`gcc lex.yy.c compilador.tab.c -o compilador`
### Para rodar o comando é: `.\compilador.exe` ou `.\compilador`.
- Se for rodar com arquivo o comando é o seguinte: `type arquivo.txt | .\compilador.exe`

## Tipos de dados: `number` e `text`
## Comando de print: `print <var | op_aritmetica | literal>;`
## Parser reconhece:
- if
- else
- for
- while
- declaração e manuseio de variáveis
- declaração de funções
- operações aritméticas
