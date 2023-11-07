# Resumo Introdutório ao Git e GitHub

Aqui encontra-se todo o resumo feito por mim, para acompanhar e estudar o contepudo aplicado nas aulas de Versionamento de Código com Git e GitHub

<br>

## O que são os Sistemas de Controle de Versão (VCS)

São os sistemas que realizam o controle de versões dos arquivos de projetos ao longo do tempo de trabalho.

### Possuem como principais funçôes: 

* Registrar o histórico de atualizações dos arquivos;
* Gerenciar quais foram as alterações, quando e quem atualizou, etc;
* Organizar, controlar e garantir a segurança do projeto, principalmente quando trabalhado por equipes.

<br>

## Quais são os tipos de Sistemas de Controle de Versão

### VCS Centralizado (CVCS) - CVS, Subversion
* Neste tipo, todos os arquivos ficam centralizados em um único servidor central e caso o servidor não esteja disponível, todos os usuários que precisam trabalhar com os arquivos, não terão mais acesso para salvar, recuperar, etc.

### VCS Distribuído (DVCS) - Git- Mercurial
* Neste outro tipo, os bancos de versões são duplicados localmente para cada usuário, permitindo que todos tenham cópias que não ficaram fora do ar caso o servidor caia, dessa forma, permanecem com o acesso aos arquivos.

> 💡 Os clones servem como backups da aplicação, possibilitando o fluxo de trabalho flexível e sem a necessidade da conexão à rede.

<br>

## Mas afinal, o que é Git?
O Git é o Sistema de Controle de Versão Distribuído (DVCS) mais amplamente adotado em todo o mundo, sendo uma ferramenta de código aberto e gratuita. Ele possibilita a criação de ramificações (branches) para o desenvolvimento de código de maneira eficiente, além de facilitar a fusão (merging) de alterações, o que resulta em um processo de trabalho mais ágil e eficaz.

> [Clique aqui](https://git-scm.com/downloads) para instalar o Git<br>
> [Clique aqui](https://git-scm.com/doc) para acessar a documentação

### Fluxo Básico do Git
* **git clone** - Clona um repositório existente para um novo diretório (pasta) local;
* **git commit** - Grava alterações no repositório (local);
* **git pull** - “Puxa” as alterações do repositório remoto (servidor) para o local (busca e mescla);
* **git push** - “Empurra” as alterações do repositório local para o remoto (servidor).

<br>

## O que é GitHub? 
O GitHub é uma plataforma de hospedagem de código que integra o Git, permitindo o controle de versão e a colaboração entre usuários. Essa plataforma possui uma comunidade ativa, é amplamente utilizada em todo o mundo e é conhecida pelo seu mascote, chamado "Octocat".

<br>

## Primeiro Passo para o Versionamento
Há várias formas de começar um novo projeto versionado com Git e com o GitHub, primeiramente para obter-se um repositório podemos tanto criar um novo quanto clonar um já exitente.
1. Para transformar um diretório local (pasta no computador que ainda não está sob controle de versão) em um repositório Git, basta acessar a pasta, e abrir ela com o **Git Bash** e em seguida aplicar o comando **Git Init**, deste modo já acessaria o repositório em Git no seu computador.
2. Clonar um repositório remoto já existente, dentro do GitHub, ao acessar um repositório podemos clicar em **<> code** e copiar o HTTPS ou o SSH caso tenha, voltando na pasta em que deseja clonar o repositório, acesse o **Git Bash** e add **git clone (url do repositório remoto)**.

### Trabalhando com Git
Assim que conseguir um repositório, é possível utilizar os vários comandos do Git no terminal git bash e para isso, passei em um outro arquivo com os [principais comandos](https://github.com/gustavogsf/dio-desafio-github/blob/main/Versionamento%20de%20C%C3%B3digo%20com%20Git%20e%20GitHub/Principais%20Comandos.md) utilizados nas aulas do curso de Versionamento de Códigos, ou se preferir acesse a [documentação completa](https://git-scm.com/doc) do site do Git.
