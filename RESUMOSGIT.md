
# DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do curso de versionamento de Código com Git e GitHub
[Link do curso a aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/santander-2024-backend-com-java&tab=undefined&moduleId=undefined)


## 📚Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

## ✔Comandos:

- **Configurar Git:**

Retorna variáveis de configuração:
    ```
    git config
    ```
    .
    
Define seu nome globalmente:
    ```
    git config --global user.name NOME
    ```
    .

Define seu email globalmente:
    ```
    git config --global user.email EMAIL
    ```
    .

Retorna nome da branch padrão:
    ```
    git config init.defaultBranch
    ```
    .

Muda o nome da branch padrão:
    ```
    git config --global init.defaultBranch NOME
    ```
    .

Retorna todas as alteraçãoes globais feitas:
    ```
    git config --global --list
    ```
    .


- **Comandos Úteis e Atalhos:**

Vai para o diretório selecionado:
    ```
    cd NOME-DIRETÓRIO
    ```
    .

Volta uma página:
    ```
    cd ..
    ```
    .

Muda para (GIT_DIR!):
    ```
    cd .git
    ```
    .

Lista o que tem no diretório:
    ```
    ls
    ```
    .

Limpa a prompt:
    ```
    clear
    ```
    .

Exibe os conteúdos resposaveis pela configuração do diretório:
    ```
    cat config
    ```
    .

Retorna status da ârea de preparação e status dos arquivos:
    ```
    git status
    ```
    .




- **Criar e Clonar Repositórios:**

Cria um novo diretório:
    ```
    mkdir NOME-DIRETÓRIO
    ```
    .

Inicializa o diretório tranformando em um repositório git:
    ```
    git init
    ```
    .

Clona um repositório. Adicione um nome após a url e o repositório terá esse nome:
    ```
    git clone URL-REPOSITÓRIO-GITHUB
    ```
    .
    
Retorna repositórios que estamos vinculados:
    ```
    git remote -v    
    ```
    .
    
conecta um repositório local a um remoto:
    ```
    git remote add NOME-REPOSITÓRIO-REMOTO-URL
    ```
    .



-**Salvar Alterações Repositório Local:**

Comando touch + nome  cria arquivos vazios:
    ```
    touch README.md
    ```
    .

Retorna status da ârea de preparação e status dos arquivos:
    ```
    git status
    ```
    .

Adciona arquivo a ârea de preparação:
    ```
    git add NOME-DIRETÓRIO
    ```
    .

Adciona todos os arquivos a ârea de preparação:
    ```
    git add .
    ```
    .

Salva e insere no Commit uma mensagem:
    ```
    git commit -m"MENSAGEM"
    ```
    .

Retorna o Commit que fizemos:
    ```
    git log
    ```
    .

Coloca o diretório que não tem nenhum arquivo em um arquivo que o git ignora ao salvar:
    ```
    echo NOME-DIRETÓRIO/> .gitignore
    ```
    .

Tira o diretório do gitignore:
    ```
    echo > gitignore
    ```
    .

Faz com que o git reconheça um diretório vazio:
    ```
    touch NOME-DIRETÓRIO/.gitkeep
    ```
    .


- **Desfazer Alterações no Repositório Local:**

Remove diretório .git e todo seu conteudo, "sai da branch (main)":
    ```
    rm -rf
    ```
    .

Retorna para o último estado que havia salvo, cuidado...descarta tudo que fez:
    ```
    git restore NOME-ARQUIVO.MD
    ```
    .

Altera o nome do último Commit:
    ```
    git commit --amend -n "NOVA-MENSAGEM"
    ```
    .

Outra forma de mudar o commit, abre o editor:
    ```
    git commit --amend
    ```
    .  Para sair, pressione as teclas **ESC + : + w + q**.

Limpa os Diretórios em diferentes níveis:
    ```
    git reset --OPÇÃO hash
    ```
    . Tem 3 opções, **--soft, --mixed, --hard**.

Remove o arquivo selecionado:
    ```
    git reset NOME-DIRETÓRIO/NOME-ARQUIVO.MD
    ```
    .

- **branches: Criar, Mesclar, deletar, e tratar conflitos**



