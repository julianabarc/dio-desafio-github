## Entraves e Soluções na Caminhada

Lista pequenas dificuldades encontradas no decorrer do curso que geram perda de tempo e produtividade. 

Ao buscar soluções para cada entrave encontrado (através dos fóruns e da plataforma Discord) foi possível verificar que outras pessoas já passaram anteriormente pela mesma situação. Porém, estas informações estão dispersas em locais diferentes. 

Desta forma, este repositório tem a intenção de reunir as dificuldades que ocorrem mais regularmente com suas respectivas soluções em um único local.


| **ENTRAVE** | **SOLUÇÃO** |
| :--- | :--- |
| No códido para geração do par de chaves SSH, a letra C é maiúscula|ssh-keygen -t ed25519 -C emaildousuário |
| O editor para markdown Typora é pago após período de teste | Usar o próprio VSCode para markdown acrescentando as extensões 'Markdown Preview Github Styling' e 'GitHub Markdown Preview' (este último para inclusão de emojis e outras funcionalidades). No VSCode é possível ter a tela dividida em tela do código e tela de visualização ao lado (CTRL+K e depois solta e aperta V ou clicar no ícone no canto superior à direita que tem o símbolo de uma janela com uma lupa) |
| Nomes de pastas/arquivos que possuem espaçamento em branco dando erro em comandos do Git | Colocar o nome entre aspas. Ex: cd 'entraves e soluções'. Ou, usar o TAB para o Git completar o nome da pasta/arquivo com as barras que caracterizam o espaçamento |