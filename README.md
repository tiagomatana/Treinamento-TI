#CONFIGURAR</br>
==========
git config user.name "nome"</br>
git config user.email "email@email.com"</br>

#conectar o ssh</br>
===============
eval "$(ssh-agent -s)"</br>
ssh-add fileSSH</br>

#CRIAR E ABRIR A PASTA</br>
======================
mkdir pasta</br>
cd pasta</br>

#INICIAR REPOSITORIO LOCAL</br>
==========================
git init</br>
git status</br>

#criar arquivo no terminal</br>
==========================
vim README.md</br>

#passar o arquivo para staged</br>
=============================
git add README.md</br>

#commitar arquivos do staged</br>
============================
git commit -am "message for log"</br>

#consultar commits</br>
==================
git log</br>

#conectar com repositorio remoto</br>
================================
git remote add origin git@github.com:tiagomatana/Treinamento-TI.git</br>

#enviar os arquivos do repositorio local para o remoto</br>
======================================================
git push -u origin master</br>

##DESFAZER</br>
----------
git diff

###untracked</br>
------------
git checkout README.md</br>

###staged</br>
---------
git reset HEAD README.md</br>

###MATAR COMMITS</br>
----------------
git reset --soft --mixed --hard</br>

Example:</br>
git reset --soft adeda0d78ae97d8a </br>

#BRANCH</br>
=======
git checkout -b teste</br>
