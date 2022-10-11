## 🚀 Bootcamp - Cloud DevOps Experience - Banco Carrefour

### 📋 Infraestrutura como Código: Script de Criação de Estrutura de Usuários, Diretórios e Permissões

Desafio de projeto: Criar um script onde toda a infraestrutura de usuários, grupos de usuários, diretórios e permissões serão criadas automaticamente através de script.

#### :white_check_mark: Diretórios:

* publico, adm, ven e sec

#### :white_check_mark: Grupos:

* GRP_ADM, GRP_VEN e GRP_ADM

#### :white_check_mark: Usuários:

* carlos,maria e joao -> GRUPO: GRP_ADM

* debora, sebastiana e roberto -> GRUPO GRP_VEN

* josefina, amanda e rogerio -> GRUPO GRP_SEC

#### :white_check_mark: Definições:

* Excluir diretórios, arquivos, grupos e usuários criados anteriormente;
* Todo provisionamento deve ser feito em um arquivo do tipo Bash Script;
* O dono de todos os diretórios criados será o usuário root;
* Todos os usuários terão permissão total dentro do diretório publico;
* Os usuários de cada grupo terão permissão total dentro de seu respectivo diretório;
* Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertencem;
* Subir arquivo de script criado para a sua conta no GitHub.
