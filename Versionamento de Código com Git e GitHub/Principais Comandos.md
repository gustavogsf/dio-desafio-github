# Principais Comandos das Aulas

Comando   | Ação
--------- | ------
GIT INIT | Transforma um diretório local em um repositório
GIT CLONE (URL) (nome da pasta) | Clona um repositório remoto
GIT CLONE (URL) --BRANCH (nome da branch) --SINGLE-BRANCH | Clona uma branch específica
GIT REMOTE -V | Mostra os repositórios remotos na qual está conectado
GIT REMOTE ADD (repositório) (URL repo no GitHub) | Copia um repositório para pasta acessada
MKDIR (nome da pasta) | Cria um novo diretório (pasta local)
TOUCH (nome da pasta ou nome arquivo.tipo) (repete) | Cria arquivos dentro de uma pasta
ECHO (conteúdo) (nome do arquivo.tipo) | Adiciona um conteúdo no arquivo especificado
CD (nome da pasta) | Acessa o pasta indicada
LS | Lista todos os itens que se encontram dentro do arquivo acessado
CAT (nome do arquivo) | Acessa as informações de um arquivo
RM -RF (nome do arquivo) | Remove um item do repositório
GIT COMMIT --AMEND -M"texto alterado" | Altera a descrição do último commit realizado
GIT COMMIT --AMEND | Abre o editor padrão para realizarmos a edição do texto
GIT RESET --SOFT (hash do commit) | Restaura a versão do commit, apagando as alterações posteriores
GIT RESET --MIXED (hash do commit) | Restaura o commit e deixa as alterações posteriores em espera, para que possam ser commitadas de novo
GIT RESET --HARD (hash do commit) | Restaura o commit e apaga todas as alterações posteriores
GIT RESTORE (nome do arquivo) | Restaura o arquivo para a última versão salva
GIT STATUS | Mostra o status dos arquivos (gerados, modificados e excluídos) que não foram commitados
GIT LOG | Mostra o histórico dos commits realizados
GIT PULL | Baixa as últimas alterações dos arquivos editados no repositório remoto, para o repositório local
GIT PUSH | Sobe as últimas alterações dos arquivos editados no repositório local, para o repositório remoto

