# Introdução ao Git e Github

## Git e Github

O Git (Command line interface) é um sistema de controle de versão de arquivos, onde é possível que diversas pessoas editem e (ou) criem novos arquivos, sem que as alterações sejam sobrescritas.

**Benefícios :** trabalho em equipe, dados mais seguros, armazenamento em nuvem, gestão de mudanças.

Já Github é um repositório remoto, ou seja, ele faz a hospedagem de repositórios do Git de forma online.

### Funcionamento do Git

* SHA1
* Obejtos fundamentais
* Sistema distribuido
* Segurança

#### SHA1

O **Secure Hash Algorithm** é um algorítimo de encriptação, que gera um conjunto **único** de caracteres identificadores de 40 dígitos.

#### Objetos fundamentais

-**BLOBS:** armazena metadados do Git, como o tipo do objeto, o tamanho e o conteúdo.
-**TREES**: armazenam blobs, armazena o nome do arquivo, podem apontar tanto para blobs quanto para outras árvores.
-**COMMIT**: armazena qualquer tipo de informação e garante a segurança se o arquivo não foi alterado (ou há mudança no SHA1)

#### Comandos básicos do terminal (Windows)

* **cd** = navegar entre as pastas do sistema
* **dir** = listar diretórios
* **mkdir** = criar pasta
* **rmdir** = deleta um diretório
* **TAB** = completa o nome
* **cd ..** = volta um repositório
* **cls** = limpar o terminal
* **del "arquivo/pasta"** = deleta todos os arquivos da pasta
* **pwd** = mostra o diretório completo
* **ls** = lista o conteúdo

#### Comandos com o Git

* **git init -** iniciar o git
* **git config --global user.name** - adicionar o user (de preferência o mesmo usado no github)
* **git config --global user.email** - adicionar o e-mail (de preferência o mesmo usado no github)
* **git add** - inicia versionamento/move arquivo
* **git commit** - cria um commit
* **git status** - verifica o status dos arquivos
* **git push origin master** - "empurra" os arquivos para o github
* **git pull origin master -** traz os arquivos do github para nossa máquina
* **git clone "link repertório"** - clona o repositório do github para o git
