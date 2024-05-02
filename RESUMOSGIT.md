
# DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do curso de versionamento de Código com Git e GitHub
[Link do curso a aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/santander-2024-backend-com-java&tab=undefined&moduleId=undefined)

##📚Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

##✔Comandos:
```
Configurar Git:
```
- **git config -** Retorna variáveis de configuração;
- **git config --global user.name** "Nome"  **-** Define seu nome;
- **git config --global user.email** "Email"  **-** Define seu email;
- **git config init.defaultBranch -** Retorna nome da branch padrão;
- **git config --global init.defaultBranch** _"Nome"_ **-** Muda o nome da branch padrão;
- **git config --global --list -** Retorna todas as Alteraçãoes globais feitas;

```
Comandos Úteis e Atalhos:
```
- **Ctrl + L -** Limpa o terminal;
- **Seta Para Cima -** Copia o que Digitou anteriormente;
- **cd** _Nome da Pasta_**/ -** Vai para o diretório selecionado;
- **cd ..** - Volta uma página;
- **cd .git** - Muda para (GIT_DIR!);
- **ls** - Lista o que tem no diretório;
- **clear** - Limpa a prompt;
- **cat config** - Exibe os conteúdos resposaveis pela configuração do diretório;
- **git status** - Retorna status da ârea de preparação e status dos arquivos;

```
Criar e Clonar Repositórios:
```
- **mkdir** _Nome da Pasta_ **-** Cria um novo diretório;
- **git init -** inicializa o diretório tranformando em um repositório git;
- **git clone** _url do repositório github_ **-** Clona um repositório, adicione um _Nome após url e o repositório ira ficar com esse nome;
- **git remote -v -** Retorna repositórios que estamos vinculados;
- **git remote add** _Nome do repositório remoto URl_ **-** conecta um repositório local a um remoto;

```
Salvar Alterações Repositório Local:
```
- **touch** _NOME.md_ **-** Retorna status da ârea de preparação e status dos arquivos;
- **git status** - Retorna status da ârea de preparação e status dos arquivos;
- **git add** _Nome do Arquivo_ **-** Adciona arquivo a ârea de preparação;
- **git add . -** Adcionar todos os arquivos a ârea de preparação;
- **git commit -m"**_Mensagem_**" -** Salva e insere no Commit uma mensagem;
- **git log -** Retorna o Commit que fizemos;
- **echo** _Diretório/_ **> .gitignore -** Coloca o diretório que não tem nenhum arquivo em um arquivo que o gir ignora ao salvar;
- **echo > gitignore -** Tira o diretório do gitignore;
- **touch** _Nome da Diretório_ **/.gitkeep -** para o git reconhecer um diretório vazio;

```
Desfazer Alterações no Repositório Local:
```
- **rm -rf -** Remove diretório .git e todo seu conteudo, "tira a branch (main)";
- **git restore** _Nome do arquivo.md_ **-** Retorna para o último estado que havia salvo, cuidado...descarta tudo que fez;
- **git commit --amend -n** _"Nova Mensagem"_ **-** Altera o nome do ultimo Commit;
- **git commit --amend -** Outra forma de mudar o commit, abre o editor, para sair **ESC + : + w + q**;
- **git reset --** _opção_ **hash -** Tem 3 opções, **--soft, --mixed, --hard**;
- **git reset** _Diretório/arquivo.md_ **-** Remove o arquivo;
