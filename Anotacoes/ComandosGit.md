# Introdução ao Git/GitHub

## O Git é um *Sistema de Versionamento Distribuido (VCS)* criado em 2005 por _Linus Torvalds_

Progetado para ser um *CLI* (Command Line Interface) - ações através de "linhas de comando"



##Comandos Básicos

**git init** - inicia o git dentro de um diretório, criando uma master e o diretório invisivel .git, onde são guardados todos os metadados deste repositório

**git config** usado para criar sua configuração pessoal apenas dentro do repositório, ou global, bastando usar *git config --global user.name "**seunome**"* e o *git config --global user.email "**seu email**""*

**git add .** adiciona todos os arquivos e alterações para a área de stage do git

**git commit -m** onde você faz as declarações do que foi efetuado nos arquivos ou no repositório

**git remote add origin** linka sua máquina com o servidor cloud, geralmente o github (*git remote add origin + link repositorio remoto*)

**git push** empurra seus arquivos locais para o repositório remoto (*git push origin master/main*)

**git pull** faz o inverso do anterior, trazendo o arquivo do remoto para o local (*git pull origin master/main*)

**git clone** clona/copia repositorios do remoto para o local, com todas as configurações prontas, incluindo o diretório .git com o endereço remoto (*git clone + url/ssh*)

# O que é Sha1?

O Sha1 - Secure Hash Algorithm (Algoritmo de Has Seguro) é um conjunto de funções hash criptograficas projetadas pela NSA - Agência de Segurança Nacional EUA.


