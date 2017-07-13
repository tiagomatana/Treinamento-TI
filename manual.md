#CONFIGURAR
git config user.name "nome"
git config user.email "email@email.com"
#conectar o ssh
eval "$(ssh-agent -s)"
ssh-add fileSSH
#CRIAR E ABRIR A PASTA
mkdir pasta
cd pasta
#INICIAR REPOSITORIO LOCAL
git init
git status
#criar arquivo no terminal
vim README.md
#passar o arquivo para staged
git add README.md
#commitar arquivos do staged
git commit -m "message for log"
#consultar commits 
git log
#conectar com repositorio remoto
git remote add origin git@github.com:tiagomatana/Treinamento-TI.git
#enviar os arquivos do repositorio local para o remoto 
git push -u origin master
