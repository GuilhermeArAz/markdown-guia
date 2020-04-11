# **LINGUAGEM MARKDOWN**

Locais em que se usa a linguagem Markdown no GitHub: 
* readme.md (ou qualquer outro arquivo .md) 
* issues
* pull requests
***
## *ESTILOS*
  * *Itálico* = `*Itálico* ou \Itálico\`
  * **Negrito** = `**negrito** ou __negrito__`
  * ~Riscado~ =  `~riscado~ ou ~~riscado~~`
  * \*XXX\* = `\iguinora marcador`
***
## *TÍTULOS*
  * # Título nv1      
     `#(espaço)Título`      
  * ## Título nv2
     `##(espaço)Título` 
  * ### Título nv3
     `###(espaço)Título`
***
## *LINHAS*
\---
--- 
    OU
***
`***`
_Sendo que `---` transforma tudo que foi escrito acima em negrito e a linha será mais fina._
***
## LISTAS
* ### Listas numeradas:
1. Teste                =====   `1.(espaço)Teste`
 
1. Teste                =====   `1.(espaço)Teste` 
   1. Teste                ==        `(espaço)(espaço)(espaço)1.(espaço)Teste`                    
   3. Teste                ==        `(espaço)(espaço)(espaço)3.(espaço)Teste`                    
55. Teste              =====    `55.(espaço)Teste`

700. Teste            =====    `700.(espaço)Teste`

* ### Listas demarcadas:
* Teste                =====     `*(espaço)Teste`
 
- Teste                =====     `-(espaço)Teste`  
   * Teste                    ==      `(espaço)(espaço)(espaço)*(espaço)Teste`                    
   - Teste                    ==      `(espaço)(espaço)(espaço)-(espaço)Teste`                    
- Teste                =====     `-(espaço)Teste`

* Teste                =====     `*(espaço)Teste`

* ### Lista de tarefas:
- [ ] abcdef ===== `-(espaço)[espaço](espaço)abcdef` 
- [x] abcdef ===== `-(espaço)[x](espaço)abcdef` 
***
## ADICIONANDO IMAGENS

*Para adicionar imagens ,jogue a imagem até a área escrita **Attach files by dragging & dropping,selecting or pasting them*** ou use a sintaxe:
`![imagem](url)`

![octocat](https://user-images.githubusercontent.com/62729789/79037617-45dca900-7ba9-11ea-9169-6647c5ed73cd.jpg)
***
## ADICIONANDO LINKS

* Para adicionar link: `[texto](url)`
EX: [github](http://www.github.com)
***
## TABELA
int | carac | real
--- | --- | ---
01 | xxx | 00,0
02 | yyy | 11,1
03 | zzz | 22,2

```
int(espaço)|(espaço)carac(espaço)|(espaço)real                      |    div vertical
---|---|---                                                         ---| div horizontal de titulo
01(espaço)|(espaço)xxx(espaço)|(espaço)00,0
02(espaço)|(espaço)yyy(espaço)|(espaço)11,1
03(espaço)|(espaço)zzz(espaço)|(espaço)22,2
```
***
## MARCAR COMANDOS
Para marcar comandos use \`\` crases por volta dos caracteres/comandos:
``(caractere/comandos)`` == \`\(caractere/comandos\)\` 
### Inserir códigos
Para inserir códigos use \`\`\`(caractere/comandos)\`\`\` por volta dos caracteres/comandos:
```
sintaxe do código

```
\`\`\`
`sintaxe do código`
\`\`\`
***
## ADICIONAR EMOJI
Para adicionar emoji no corpo de arquivos .md,issues e poll requests `:nome do emoji`.
   - Os nomes dos emoji usado para o corpo dos arquivos são encontrados no [https://github.com/ikatyang](https://github.com/ikatyang/emoji-cheat-sheet)

Para adicionar emoji nos titulos de issues e poll requests `:nome do emoji`
   - Os nomes dos emoji usado nos titulos dos arquivos são encontrados no [https://emojipedia.org/](https://emojipedia.org/)
***
## CITAR PESSOAS
Citar pessoas no texto basta colocar `@perfil da pessoa`
Ex: @pauloreis7
***
## FAZER REPLY

 Para se fazer o reply ,clique nas reticencias no canto superior direito dos comentário selecionado e nas opções escolha  `Quote reply`.
   - É possivel fazer reply utilizando a sintaxe `>comentario` 
Só é possivel  fazer um reply com comentarios da mesma Issue/poll request. 
Ex: 
> Visite o perfil @pauloreis7.






