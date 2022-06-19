## Anotações Relevantes de Aprendizado

- Git é um sistema de controle de versão distribuído seguro

- GitHub é um serviço baseado na web para controle de versão, que usa o Git como base para seu funcionamento

- Pode-se proteger o GitHub de alterações de terceiros (branch protection rule)

- Pull Request (PR) serve para notificar o propritério do projeto para implementar as alterações solicitadas

- SHA (Secure Hash Algorithm) é uma encriptação que gera um conjunto de caracteres de 40 dígitos. A cada nova alteração no conteúdo do arquivo, irá gerar um novo SHA1. Se retornar o conteúdo ao estado anterior, volta a ter o mesmo SHA1 anterior.

- Blobs, Trees e Commits são objetos internos do Git, que funcionam por "trás do palco". Blobs armazena metadados do Git (tipo do objeto, tamanho da string, tamanho do arquivo, etc). Trees armazenam Blobs e são responsáveis por montar toda a estrutura dos arquivos, podendo apontar tanto para Blobs quando para outras Trees. E os Commits juntam tudo

- Chaves SSH e Tokens são formas de fazer conexão segura. Token não é recomendado deixar na máquina. É mais seguro usar Chave SSH. Chave SSH tem um par de chaves - 1 pública e 1 privada, sendo necessário:
    1. Gerar a chave no Git
    2. Inserir a chave no GitHub
    3. Validar para o SSH Agent no Git

- Pastas que iniciam com . são pastas ocultas

- Tracked são os arquivos que o Git já rastreia e se divide em três estágios: unmodified, modified e staged. Untracked são os arquivos que o Git ainda não tem ciência deles. Stage são os arquivos que estão se preparando para fazer parte de um outro tipo de agrupamento para posterior commit