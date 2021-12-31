
<img src="https://hermes.digitalinnovation.one/tracks/f00290e5-b695-4ef6-b88a-d5aae004bd66.png" width="200" height="200" /> 

## Links úteis
[Sintaxe Básica Markdown](https://markdown.net.br/sintaxe-basica/)

 
## :bulb:Comandos do Terminal:

:one: Comandos importantes do *Terminal* (também utilizado no Git):

   - **`cls(win), clear(git, linux)`** - para apagar todo o histórico de comandos do prompt;
   - **`cd(win, git, linux)`** - para se transitar entre as pastas dos diretórios, também há a variante "cd .." para retornar à pasta anterior;
   - **`dir(win), ls(git, linux)`** - para mostrar a lista de diretórios contidos na pasta em que estiver, também há a variante **`dir -a(win), ls -a(git, linux)`** para mostrar inclusive os diretórios ocultos ;
   - **`mkdir(win, git, linux)`** - para criar uma pasta no diretório;
   - **`echo(win, git, linux)`** - retorna o que for inserido, entretanto se utilizado como **"echo > nome.extensão"**, ele cria o arquivo na extensão desejada, ótimo para criar um readme bem rápido sem sair do git em?! :happy:
   -  **`start(win, git, linux)`** - inicia um arquivo executável de qualquer tipo;
   - **`TAB`** - Sim, a tecla TAB tem a incrível função de abreviar algo que você deseja escrever, extremamente útil e vai agilizar muito a sua vida!

:two: Comandos de iniciação do *Git*:

   - **`git init`** - inicia o versionamento na pasta em que estiver;
   - **`git config --global user.email "email"`** - configura o ambiente de versionamento para todos os repositórios, com essa identificação de e-mail; em caso da necessidade de alterar isso posteriormente, use *git config --global unset user.email*;
   - **`git config --global user.name "username"`** - configura o ambiente de versionamento para todos os repositórios, com essa identificação de usuário no github (é importante ressaltar que os dados aqui, devem refletir o usuário no Github); em caso da necessidade de alterar isso posteriormente, use *git config --global unset user.name*
   - **`git config --list`** - mostra todos os parâmetros da configuração atual do Git; para sair, use a tecla *q*;
   - **`git remote add nome (link)`** - direciona seu repositório local para um repositório na nuvem, o parâmetro *NOME* é apenas um apelido para que você possa referenciar o link sem tê-lo que mencionar novamente; você também pode posteriormente utilizar o comando **`git remote -v`** para consultar o repositório que está recebendo os arquivos locais.

:three: A configuração do ambient com Git/Github com *chave SSH*:

   - Use o código abaixo no *Git*, para gerar uma chave SSH;

   - ```shell
     $ ssh-keygen -t ed25519 -C "seu_email@example.com"
     ```

   - **cat (chave gerada)** - use esse comando **(git, linux)** para "ler" o conteúdo da chave, em seguida vá até a página principal no *Github>settings>SSH and GPG keys>New SSH key* em seguida insira o seu conteúdo da chave no campo "key".

   - Calma que ainda não acabou!:laughing: Agora no *Git Bash*, você precisa executar o agente para que gerencie suas chaves.

   - ```shell
     $ eval "$(ssh-agent -s)"
     ```

   - A saída do comando será *"> Agent pid (número_qualquer)"*, o agente continuará executando em segundo plano. Agora como última etapa, você deve passar a chave privada para o agent com o seguinte código:

   - ```shell
     $ ssh-add "chave privada"
     ```

   - Pronto!:handshake: Agora você pode **usar todas as funcionalidades do git sem precisar se identificar o tempo todo**.

:four: O editor de arquivos *Markdown(.md)*, muito útil para o Github:

   - **Typora** - [clique aqui para baixar o Typora](https://typora.io);
   - Lista completa de **[emoticons](https://gist.github.com/rxaviers/7360908)**:skull::smiley::collision:;

## :bookmark_tabs:Atividades

Abaixo, todas as atividades do **Bootcamp Inter Frontend Developer**:

- [x] Boas-vindas ao Bootcamp Inter Frontend Developer; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/6F53018D);
- [x] Lógica de Programação Essencial; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/1D548C65);
- [x] Aprenda o que são Estrutura de Dados e Algoritmos; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/39B6EB82);
- [x] Introdução ao Git e ao GitHub; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/0C0BA954);
- [x] Projetos ágeis com SCRUM; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/ED4C8F71);
- [x] Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso ; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/9767EF81);
- [x] Introdução a criação de websites com HTML5 e CSS3; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/74AB6DB2);
- [x] Construindo páginas para internet com Bootstrap; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/3124FEBD);
- [x] IDE Instalação e Configuração (Visual Studio Code); - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/35BC1F925);
- [x] Sintaxe Básica em JavaScript; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/0A648966);
- [x] Sintaxe e Operadores; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/96A26938);
- [x]  Variáveis e Tipos; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/BE0FF6C5);
- [x]  Funções; - :paperclip: [**[Certificado]**](https://certificates.digitalinnovation.one/C1D0847A);
- [x]  Coleções; - :paperclip: [**[Certificado]**](https://hermes.digitalinnovation.one/certificates/0B2739AC.pdf);


   
  

  



