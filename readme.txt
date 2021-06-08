Treinamento Alura (Teste alteração na branch ----)

Git e GitHub

Chegou a hora de você pôr em prática o que foi visto na aula. Para isso, execute os passos listados abaixo.

1) Crie uma pasta nova em seu computador;
2) No terminal (ou Git Bash, no Windows) navegue até a pasta recém criada (utilize o comando cd para navegar entre pastas);
3) Execute o comando git init --bare;
4) Navegue até a pasta onde se encontra o seu projeto;
5) Execute o comando git remote add local {caminho}. Substitua {caminho} pelo caminho completo da pasta recém criada;
6) Crie uma nova pasta em seu computador, para representar o trabalho de outra pessoa;
7) No terminal (ou Git Bash, no Windows) navegue até a pasta recém criada;
8) Execute o comando git clone {caminho} projeto. Substitua {caminho} pelo caminho completo da pasta que criamos no primeiro passo;
9) Observe que o repositório clonado está vazio;
10) Acesse a pasta Projeto e execute o comando 'git remote rename origin local' para renomear o repositório local da outra pessoa de "origin" para "local";
11) Navegue até a pasta onde se encontra o seu projeto original;
12) Execute o comando git push local main para enviar as suas modificações para o seu servidor;
13) Navegue até a pasta criada no passo 6;
14) Execute o comando git pull local main para baixar as modificações;
15) Abra o seu navegador e acesse http://github.com/;
16) Crie uma conta;
17) Crie um novo repositório, clicando no símbolo de adição no canto superior direito;
18) No terminal (ou Git Bash, no Windows) adicione, ao seu projeto inicial, o repositório remoto recém criado (os comandos são mostrados pelo próprio GitHub);
19) Execute git push origin main para enviar as suas alterações para o repositório no GitHub.

Nesta aula, aprendemos:

O que são repositórios remotos;
Como criar um repositório Git sem uma cópia dos arquivos (com --bare) para ser utilizado como servidor;
Como adicionar links para os repositórios remotos, com o comando git remote add;
Como baixar um repositório pela primeira vez, clonando-o com o comando git clone;
Como enviar as nossas alterações para um repositório remoto, com git push;
Como atualizar o nosso repositório com os dados no repositório remoto, utilizando git pull;
O que é e para que serve o GitHub;
Como criar um repositório no GitHub;
Como adicionar um repositório do GitHub como repositório remoto.
