# Aula 03 - 23/02/2023
## Comandos iniciais do Git
* Passo 1: logar no Git:
    * Inserindo seu nome de usuário: ```git config --global user.name "seunomedeusuario"```;
    * Para verificar: ```git config --global user.name```;
    * Inserindo o e-mail: ```git config --global user.email "seu@email.com"```;
    * Para verificar: ```git config --global user.email```;
* Criando um arquivo pelo Vim no Git Bash:
    * Crie um diretório com ```mkdir <nome_diretorio>```;
    * Entre no diretório com ```cd <nome_diretorio>```;
    * Insira o comando ```vim teste.txt```;
    * Digite a tecla "i" para editar o arquivo;
    * Insira um texto no arquivo;
    * Pressione a tecla "Esc" para sair do editor;
    * Insira o comando ```:x``` para salvar e sair do arquivo;
* Para fazer o upload do arquivo:
    * Insira o comando ```git add .```;
        * Para ver o status do commit, insira o comando ```git status```;
    * Insira o comando ```git commit -m "first commit"```;
    * Insira o comando ```git status``` para ver o status novamente, para conferir se os arquivos estão preparados para serem enviados ao diretório remoto;
    * Insira o comando ```git push``` para enviar para o diretório remoto;
