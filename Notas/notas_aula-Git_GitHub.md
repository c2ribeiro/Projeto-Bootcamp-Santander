# Comandos Básicos Windows- Git - DIO. :man_technologist:

## Essa pequena lista de comandos tem o intuito de ajudar com uma descrição simplista de cada comando afim de facilitar o aprendizado com a repetição dos comandos.

- Comando **cd** - Move entre pastas - Ex. de uso (cd workspace).

- Comando **dir/ls** - Lista pastas existentes. 

- Comando **mkdir** - Cria pastas - Ex. de uso (mkdir projeto).

- Comando **rmdir** - Deleta pasta - Ex. de uso (rmdir projeto).

- Comando **rm *nome_arquivo*** - Remove arquivo desejado.

- Comando **ssh-keygen -t ed25519 -C email_usuário** - Cria sua chave SSH. 

- Comando **cat ed25519.pub** - Exibe sua chave SSH publica.

- Comando **eval $(ssh-agent -s)** - Ativa o agente SSH. 

- Comando **ssh-add id_ed25519** - Ativa o agente SSH.

- Comando **git clone + endereço** - Clona repositório (Caso tenha ativado a chave SSH, copiar o link SSH).

- Comando **git config --global user.email *email_usuário*** - Configura um usuário e atrela ao commit.

- Comando **git config --global user.name *nome_usuário*** - Configura o nickname e atrela ao commit.

- Comando **git add** - Adiciona para ser commitado.

- Comando **git add * ** - Adiciona ao commit as mudanças feitas no repositório.

- Comando ***git commit *nome do arquivo*** - Commita arquivo específico.

- Comando **git commit -m *"commit_name"*** - Commita repositório com mensagem. 

- Comando **git status** - Monitora o status. 

- Comando **mv *nome_arquivo* ./*nome_pasta*** - Move arquivo para pasta desejada.

- Comando **git remote add origin *link_repositório*** - Direciona para o link desejado.

- Comando **git remote -v** - Lista os repositórios remotos.

- Comando **git push origin *master_ou_main*** - Empurra o arquivo commitado.

- Comando **git pull origin *master_ou_main*** - Puxa arquivo.

  ***Master ou main depederá da sua branch***

  