## CMD

dir -> verifica o diretório atual

cd pasta -> entra na pasta

cd .. -> sai da pasta

cls -> limpa o terminal

## GIT

winget install --id Git.Git -e --source winget -> instala o git

git clone https://github.com/AntonioIrineuFilho/REPOSITORIO.git -> clona o repositório para o diretório especificado

git add . -> adiciona todos os arquivos da pasta

git add arquivo.ext -> adiciona o arquivo especifico

git commit -m "mensagem" -> salva a versão

git push -> sobe a versão para o repositório no Github

git fetch origin -> verifica/atualiza o estado dos arquivos em comparação com o diretório

git pull -> atualiza o diretório local conforme o repositório 

git status -> mostra o estado dos arquivos

git stash -> guarda temporariamente em um espaço separado alterações que você não deseja commitar(útil quando você quer dar um pull mas ainda tem alterações que você não subiu no repositório local)

git stash drop -> apaga essas alterações guardadas

git stash pop -> recupera a última alteração armazenada

git stash apply -> recupera um commit especifico

git stash list -> mostra uma lista das alterações guardadas

git branch -> lista as branchs locais do repositório

git branch nome -> cria uma nova branch

git checkout nome -> troca a branch atual para a branch nome

git checkout -b nome -> cria uma nova branch e já faz a troca para ela

git merge nome -> mescla na branch atual o que tiver na branch nome

git push origin --delete nome -> exclui uma branch remota
